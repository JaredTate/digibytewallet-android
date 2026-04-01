# ARCHITECTURE.md

## Executive Summary

`digibytewallet-android` is a DigiByte-adapted fork of Breadwallet Android with a hybrid architecture:

- **Android app layer (Java)** for UI, app lifecycle, secure storage, DB persistence, networking to DigiByte services, and orchestration.
- **Native wallet/network core (C via JNI)** from `digibytewallet-core` for deterministic key derivation, address handling, transaction creation/signing, SPV verification, and peer syncing.
- **Bridge layer (`app/src/main/jni/transition`)** exposing native C functionality as JNI methods consumed by Java managers (`BRWalletManager`, `BRPeerManager`).

DigiByte-specific chain parameters are embedded in native core, including:

- **Legacy pubkey hash prefix = 30** (`D...` addresses) in `BRAddress.h`
- **Mainnet port = 12024** in `BRChainParams.h`
- DigiByte PoW/crypto support in core crypto code and chain params

---

## High-Level Architecture

```text
+--------------------------------------------------------------------------------+
|                              Android App (Java)                                |
|                                                                                |
|  io.digibyte.DigiByte (Application)                                            |
|   - app lifecycle, native lib load, periodic sync scheduling                  |
|                                                                                |
|  Presenter/UI layer                                                            |
|   - activities, fragments, adapters, entities                                 |
|                                                                                |
|  Manager/Service layer                                                         |
|   - BRWalletManager (wallet orchestration)                                    |
|   - BRPeerManager (peer sync orchestration)                                   |
|   - SyncManager, BRApiManager, notifications, prefs, security                 |
|                                                                                |
|  Storage                                                                        |
|   - SQLite data sources (tx/peers/blocks/currency)                            |
|   - SharedPrefs + Android Keystore wrappers                                   |
+-----------------------------------+--------------------------------------------+
                                    | JNI (core-lib)
+-----------------------------------v--------------------------------------------+
|                         JNI Transition Layer (C)                                |
|  app/src/main/jni/transition                                                   |
|   - wallet.c  <-> io.digibyte.wallet.BRWalletManager                          |
|   - PeerManager.c <-> io.digibyte.wallet.BRPeerManager                        |
|   - JNIBase58/JNIBIP32Sequence/JNIKey/core helpers                            |
+-----------------------------------+--------------------------------------------+
                                    | direct C calls
+-----------------------------------v--------------------------------------------+
|                     digibytewallet-core (C SPV Wallet Core)                    |
|  BRWallet, BRTransaction, BRPeerManager, BRMerkleBlock, BRAddress, BRKey      |
|  BRChainParams (network/checkpoints/ports), crypto & hashing implementations   |
+-----------------------------------+--------------------------------------------+
                                    |
                                    v
                         DigiByte P2P Network + API endpoints
```

---

## Directory Structure (functional)

- `app/src/main/java/io/digibyte/`
  - **Application/bootstrap**: `DigiByte.java`
  - **Wallet/peer orchestration**: `wallet/BRWalletManager.java`, `wallet/BRPeerManager.java`
  - **Managers/utilities**: `tools/manager/*`, `tools/security/*`, `tools/sqlite/*`, `tools/util/*`
  - **Presentation**: `presenter/activities`, `presenter/fragments`, `presenter/entities`, custom views
- `app/src/main/jni/digibytewallet-core/`
  - Native SPV core (`BRWallet*`, `BRPeerManager*`, `BRTransaction*`, `BRAddress*`, `BRChainParams.h`, crypto)
- `app/src/main/jni/transition/`
  - JNI bridges from Java to core C logic
- `app/src/main/secp/`
  - secp256k1 crypto sources/headers used by native build
- `app/src/main/res/`
  - Android resources (layouts, drawables, strings, styles)
- Build/config root:
  - `app/CMakeLists.txt` (native build wiring)
  - `app/build.gradle`, root `build.gradle`, `settings.gradle`, wrapper files

---

## Key Components

### 1. App Bootstrap & Runtime
- **`io.digibyte.DigiByte`**
  - Extends `MultiDexApplication`
  - Loads native library (`System.loadLibrary("core-lib")`)
  - Registers lifecycle callbacks
  - Sets defaults (e.g., fee prefs)
  - Schedules background blockchain sync jobs

### 2. Wallet Domain Orchestration (Java)
- **`BRWalletManager.java`**
  - Wallet creation/recovery orchestration
  - Seed phrase and key-handling flows via keystore wrappers
  - Transaction preparation/sign/publish calls into JNI
  - Balance/address refresh and UI callback dispatch
  - Coordinates DB persistence and network-dependent operations

### 3. Peer Sync Orchestration (Java)
- **`BRPeerManager.java`**
  - Native peer manager lifecycle: create/connect/rescan/free
  - Receives sync callbacks from C and updates app state
  - Persists peers/blocks into SQLite data sources
  - Supports fixed trusted peer setting (`setFixedPeer`)

### 4. Sync/External Service Managers
- **`SyncManager`**: sync progress polling and listener notifications
- **`BRApiManager`**: rates/block info requests (HTTP via `APIClient`), secure-time updates
- SharedPrefs/security/sqlite managers: local state, persistence, and wallet metadata

### 5. JNI Transition Layer
- **`transition/wallet.c`**
  - Implements JNI methods for `BRWalletManager`
  - Manages native `BRWallet*` lifecycle and tx array hydration
  - Handles callbacks to Java for balance and transaction events
- **`transition/PeerManager.c`**
  - Implements JNI methods for `BRPeerManager`
  - Manages native `BRPeerManager*`, peers/blocks hydration, and sync callbacks
- Additional wrappers for key/base58/bip32 functions

### 6. Native Core (digibytewallet-core)
- `BRWallet.*`: UTXO/accounting/fee and transaction composition
- `BRTransaction.*`: parse/serialize/sign/validation structures
- `BRPeerManager.*` + `BRPeer.*`: SPV peer networking and sync
- `BRMerkleBlock.*`: headers and proof validation path
- **`BRAddress.h`**: DigiByte address/version constants (including `DIGIBYTE_PUBKEY_LEGACY 30`)
- **`BRChainParams.h`**: DigiByte network parameters and checkpoints (`standardPort 12024`)
- crypto folder: hash and PoW-related cryptographic functions

---

## Data Flow

### Wallet Initialization & Sync
1. App starts (`DigiByte`) and loads native `core-lib`.
2. `BRWalletManager.init()` orchestrates seed/pubkey retrieval and wallet setup.
3. Existing transactions/blocks/peers are loaded from SQLite by Java managers.
4. Java calls JNI `createTxArrayWithCount`/`putTransaction`, `createBlockArrayWithCount`/`putBlock`, etc.
5. JNI transition initializes native `BRWallet` and `BRPeerManager` with hydrated state.
6. Peer manager connects to DigiByte network and sync begins.
7. Native callbacks push updates to Java (sync status, tx updates, balances).
8. Java persists updates and refreshes UI/listeners.

### Send Transaction
1. UI collects destination + amount.
2. `BRWalletManager` requests fee estimation and unsigned tx creation via JNI.
3. Native wallet builds/signs tx (seed-derived keys via BIP32/39 path).
4. `BRPeerManagerPublishTx` broadcasts to peers.
5. Publish callback returns status and tx hash to Java for user feedback.

---

## Configuration / Build & Deployment

- **Gradle Android build**: `app/build.gradle` with Java + external native build integration.
- **Native build**: `app/CMakeLists.txt` builds shared lib `core-lib` from:
  - `jni/digibytewallet-core/*`
  - `jni/transition/*`
  - includes secp256k1 directories.
- **Runtime linkage**: Java loads `core-lib` through `BRConstants.NATIVE_LIB_NAME`.
- **Network/runtime params** are mostly native (`BRChainParams`, address/encoding constants).

---

## Design Patterns & Architectural Style

- **Layered architecture**: UI/presenter -> manager/service -> JNI bridge -> native core.
- **Singleton managers**: `BRWalletManager`, `BRPeerManager`, `SyncManager`, `BRApiManager`.
- **Bridge pattern (JNI)**: Java abstraction over C core types/functions.
- **Observer/listener pattern**: sync and balance listeners for UI updates.
- **Repository-like persistence**: SQLite data source classes for tx/peer/block/currency entities.
- **Callback-driven native integration**: C callbacks invoke static Java handlers through cached class refs.

---

## Notes for DigiByte-specific Behavior

- Address encoding and validation are customized in native core (`BRAddress*`) for DigiByte prefixes.
- Chain params and checkpoints are DigiByte-specific (`BR_CHAIN_PARAMS` from `BRChainParams.h`).
- P2P mainnet uses **port 12024**.
- Project is breadwallet-derived, but chain/network/address logic and some crypto support are adapted for DigiByte.