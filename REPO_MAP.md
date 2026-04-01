# REPO_MAP.md

Auto-generated source map of DigiByte Wallet Android repository.

### .idea/codeStyles/Project.xml
- XML elements: `<component>`, `<code_scheme>`, `<option>`, `<JavaCodeStyleSettings>`, `<value>`, `<package>`, `<emptyLine>`, `<Objective-C-extensions>`, `<file>`, `<class>` …

### .idea/codeStyles/codeStyleConfig.xml
- XML elements: `<component>`, `<state>`, `<option>`

### .idea/dictionaries/Mihail.xml
- XML elements: `<component>`, `<dictionary>`, `<words>`, `<w>`

### .idea/inspectionProfiles/Project_Default.xml
- XML elements: `<component>`, `<profile>`, `<option>`, `<inspection_tool>`

### .idea/inspectionProfiles/profiles_settings.xml
- XML elements: `<component>`, `<settings>`, `<option>`, `<version>`

### .idea/jarRepositories.xml
- XML elements: `<project>`, `<component>`, `<remote-repository>`, `<option>`

### .idea/markdown-navigator.xml
- XML elements: `<project>`, `<component>`, `<PreviewSettings>`, `<PanelProvider>`, `<provider>`, `<ParserSettings>`, `<PegdownExtensions>`, `<option>`, `<ParserOptions>`, `<HtmlSettings>` …

### .phraseapp.yml
- Contents: `phraseapp:`; `access_token: 8f2bc5ff5146811b6c737542f05fcab60f3feb60fce918c2d0199e8fe2744375`; `project_id: b801c7449dd0fbff52b08e3f47793aa9`

### README.md
- Contents: `<h1 margin="0 auto">DigiByte for Android</h1>`; `<a href="https://play.google.com/store/apps/details?id=io.digibyte">`; `<img alt="Get it on Google Play"`

### app/CMakeLists.txt
- Contents: `# Sets the minimum version of CMake required to build your native library.`; `# This ensures that a certain set of CMake features is available to`; `# your build.`

### app/build.gradle
- Gradle config blocks: `android`, `dependencies`, `defaultConfig`, `buildTypes`, `externalNativeBuild`, `compileSdkVersion`

### app/proguard-rules.pro
- Key entries: `-dontobfuscate`; `-dontoptimize`; `-dontshrink`; `-dontusemixedcaseclassnames`; `-dontskipnonpubliclibraryclasses`

### app/src/main/AndroidManifest.xml
- XML elements: `<manifest>`, `<uses-permission>`, `<uses-feature>`, `<application>`, `<meta-data>`, `<activity>`, `<intent-filter>`, `<action>`, `<category>`, `<data>` …

### app/src/main/assets/loading.json
- Contents: `{`; `"v": "4.7.0",`; `"fr": 30,`

### app/src/main/assets/words/en-BIP39Words.txt
- Contents: `abandon`; `ability`; `able`

### app/src/main/assets/words/es-BIP39Words.txt
- Contents: `ábaco`; `abdomen`; `abeja`

### app/src/main/assets/words/fr-BIP39Words.txt
- Contents: `﻿abaisser`; `abandon`; `abdiquer`

### app/src/main/assets/words/ja-BIP39Words.txt
- Contents: `あいこくしん`; `あいさつ`; `あいだ`

### app/src/main/assets/words/zh-BIP39Words.txt
- Contents: `的`; `一`; `是`

### app/src/main/java/com/jniwrappers/BRBIP32Sequence.java
- Package: `com.jniwrappers`
- Class: `BRBIP32Sequence`
- Methods: `files()`, `getInstance()`, `bip32BitIDKey()`

### app/src/main/java/com/jniwrappers/BRBase58.java
- Package: `com.jniwrappers`
- Class: `BRBase58`
- Methods: `files()`, `getInstance()`, `base58Encode()`

### app/src/main/java/com/jniwrappers/BRKey.java
- Package: `com.jniwrappers`
- Class: `BRKey`
- Methods: `files()`, `setPrivKey()`, `setSecret()`, `compactSign()`, `encryptNative()`, `decryptNative()`, `address()`

### app/src/main/java/com/platform/APIClient.java
- Package: `com.platform`
- Class: `APIClient`
- Methods: `files()`, `getInstance()`, `feePerKb()`, `sendRequest()`

### app/src/main/java/com/platform/entities/TxMetaData.java
- Package: `com.platform.entities`
- Class: `TxMetaData`
- Methods: `files()`, `equals()`, `hashCode()`, `describeContents()`, `writeToParcel()`, `createFromParcel()`, `newArray()`

### app/src/main/java/com/platform/entities/WalletInfo.java
- Package: `com.platform.entities`
- Class: `WalletInfo`
- Methods: `files()`

### app/src/main/java/com/platform/interfaces/KVStoreAdaptor.java
- Package: `com.platform.interfaces`
- Interface: `KVStoreAdaptor`
- Methods: `files()`, `ver()`, `put()`, `del()`, `get()`, `keys()`

### app/src/main/java/com/platform/kvstore/CompletionObject.java
- Package: `com.platform.kvstore`
- Class: `CompletionObject`
- Enum: `RemoteKVStoreError`
- Methods: `files()`

### app/src/main/java/com/platform/kvstore/ReplicatedKVStore.java
- Package: `com.platform.kvstore`
- Class: `ReplicatedKVStore`
- Methods: `files()`, `getInstance()`, `getNonce()`, `encrypt()`, `decrypt()`, `seconds()`, `retrieveAuthKey()`, `run()`, `getWritable()`, `getReadable()`, `true()`, `set()`, `insert()`, `version()`, `get()` …

### app/src/main/java/com/platform/sqlite/KVItem.java
- Package: `com.platform.sqlite`
- Class: `KVItem`
- Methods: `files()`

### app/src/main/java/com/platform/sqlite/PlatformSqliteHelper.java
- Package: `com.platform.sqlite`
- Class: `PlatformSqliteHelper`
- Methods: `files()`, `getInstance()`, `onCreate()`, `onUpgrade()`

### app/src/main/java/com/platform/tools/BRBitId.java
- Package: `com.platform.tools`
- Class: `BRBitId`
- Methods: `files()`, `isBitId()`, `digiIDAuthPrompt()`, `digiIDSignAndRespond()`, `signMessage()`, `formatMessageForBitcoinSigning()`, `putVarInt()`, `varIntSize()`

### app/src/main/java/com/platform/tools/KVStoreManager.java
- Package: `com.platform.tools`
- Class: `KVStoreManager`
- Methods: `files()`, `getInstance()`, `getWalletInfo()`, `putWalletInfo()`, `getTxMetaData()`, `valueToMetaData()`, `getAllTxMD()`, `putTxMetaData()`, `getFinalValue()`, `txKey()`

### app/src/main/java/io/digibyte/DigiByte.java
- Package: `io.digibyte`
- Class: `DigiByte`
- Class: `SyncBlockchainJobCreator`
- Class: `SyncBlockchainJob`
- Methods: `files()`, `getContext()`, `isSuspended()`, `getActivity()`, `onCreate()`, `onActivityCreated()`, `onActivityStarted()`, `onActivityResumed()`, `onActivityStopped()`, `onActivityDestroyed()`, `onActivityPaused()`, `onActivitySaveInstanceState()`, `create()`, `onRunJob()`, `scheduleJob()`

### app/src/main/java/io/digibyte/exceptions/BRKeystoreErrorException.java
- Package: `io.digibyte.exceptions`
- Class: `BRKeystoreErrorException`
- Methods: `files()`

### app/src/main/java/io/digibyte/exceptions/CertificateChainNotFound.java
- Package: `io.digibyte.exceptions`
- Class: `CertificateChainNotFound`
- Methods: `files()`

### app/src/main/java/io/digibyte/exceptions/PaymentRequestExpiredException.java
- Package: `io.digibyte.exceptions`
- Class: `PaymentRequestExpiredException`
- Methods: `files()`

### app/src/main/java/io/digibyte/presenter/activities/BasePinActivity.java
- Package: `io.digibyte.presenter.activities`
- Class: `BasePinActivity`
- Methods: `onPinConfirmed()`, `onCreate()`, `onResume()`, `onSaveInstanceState()`, `onRestoreInstanceState()`, `setPreviousPin()`, `pinsMatch()`, `handleClick()`, `handleDigitClick()`, `handleDeleteClick()`, `updateDots()`, `clearDots()`

### app/src/main/java/io/digibyte/presenter/activities/BreadActivity.java
- Package: `io.digibyte.presenter.activities`
- Class: `BreadActivity`
- Enum: `Adapter`
- Methods: `files()`, `onCreate()`, `run()`, `onSyncManagerStarted()`, `onSyncManagerUpdate()`, `onSyncManagerFinished()`, `onSyncFailed()`, `updateSyncText()`, `onTxManagerUpdate()`, `convertNewTransactionsForAdapter()`, `getNewTransactionsData()`, `removeAllExistingEntries()`, `updateAmounts()`, `onStatusUpdate()`, `onIsoChanged()` …

### app/src/main/java/io/digibyte/presenter/activities/DisabledActivity.java
- Package: `io.digibyte.presenter.activities`
- Class: `DisabledActivity`
- Methods: `onCreate()`, `refresh()`, `onResume()`, `onTick()`, `onFinish()`, `onPause()`, `onBackPressed()`

### app/src/main/java/io/digibyte/presenter/activities/InputWordsActivity.java
- Package: `io.digibyte.presenter.activities`
- Class: `InputWordsActivity`
- Enum: `Type`
- Class: `FocusListener`
- Methods: `getString()`, `open()`, `onCreate()`, `getType()`, `getPhrase()`, `w()`, `clearWords()`, `onFocusChange()`, `validateWord()`, `onEditorAction()`

### app/src/main/java/io/digibyte/presenter/activities/LoginActivity.java
- Package: `io.digibyte.presenter.activities`
- Class: `LoginActivity`
- Methods: `onCreate()`, `getClass()`, `onNewIntent()`, `onResume()`, `onPause()`, `processDeepLink()`, `processNFC()`, `handleClick()`, `showFingerprintDialog()`, `handleDigitClick()`, `handleDeleteClick()`, `unlockWallet()`, `showFailedToUnlock()`, `updateDots()`, `onComplete()` …

### app/src/main/java/io/digibyte/presenter/activities/PaperKeyActivity.java
- Package: `io.digibyte.presenter.activities`
- Class: `PaperKeyActivity`
- Class: `WordPagerAdapter`
- Methods: `onNextButtonClick()`, `onPreviousButtonClick()`, `show()`, `onCreate()`, `onPageScrollStateChanged()`, `onPageScrolled()`, `onPageSelected()`, `getString()`, `getPhrase()`, `getIntent()`, `updateWordView()`, `setButtonEnabled()`, `updateItemIndexText()`, `setWords()`, `getItem()` …

### app/src/main/java/io/digibyte/presenter/activities/PaperKeyProveActivity.java
- Package: `io.digibyte.presenter.activities`
- Class: `PaperKeyProveActivity`
- Class: `BRTextWatcher`
- Methods: `onSubmitClick()`, `getString()`, `show()`, `onCreate()`, `getCleanPhrase()`, `getIntent()`, `randomWordsSetUp()`, `onEditorAction()`, `beforeTextChanged()`, `onTextChanged()`, `afterTextChanged()`, `validateWord()`, `isWordCorrect()`

### app/src/main/java/io/digibyte/presenter/activities/QRCodeActivity.java
- Package: `io.digibyte.presenter.activities`
- Class: `QRCodeActivity`
- Methods: `show()`, `onCreate()`, `populateQRImage()`, `getIntent()`

### app/src/main/java/io/digibyte/presenter/activities/SettingsCallback.java
- Package: `io.digibyte.presenter.activities`
- Interface: `SettingsCallback`
- Methods: `onTitleClick()`

### app/src/main/java/io/digibyte/presenter/activities/UpdatePinActivity.java
- Package: `io.digibyte.presenter.activities`
- Class: `UpdatePinActivity`
- Enum: `Mode`
- Methods: `open()`, `onPinConfirmed()`, `getString()`, `onCreate()`, `getMode()`, `setMode()`

### app/src/main/java/io/digibyte/presenter/activities/adapters/TxAdapter.java
- Package: `io.digibyte.presenter.activities.adapters`
- Class: `TxAdapter`
- Methods: `getAllRecycler()`, `getAllAdapter()`, `getSentRecycler()`, `getSentAdapter()`, `getReceivedRecycler()`, `getReceivedAdapter()`, `instantiateItem()`, `destroyItem()`, `getCount()`, `isViewFromObject()`, `getPageTitle()`

### app/src/main/java/io/digibyte/presenter/activities/callbacks/ActivityInputWordsCallback.java
- Package: `io.digibyte.presenter.activities.callbacks`
- Interface: `ActivityInputWordsCallback`
- Methods: `onNextButtonClick()`

### app/src/main/java/io/digibyte/presenter/activities/callbacks/ActivityPaperKeyCallback.java
- Package: `io.digibyte.presenter.activities.callbacks`
- Interface: `ActivityPaperKeyCallback`
- Methods: `onNextButtonClick()`, `onPreviousButtonClick()`

### app/src/main/java/io/digibyte/presenter/activities/callbacks/ActivityPaperKeyProveCallback.java
- Package: `io.digibyte.presenter.activities.callbacks`
- Interface: `ActivityPaperKeyProveCallback`
- Methods: `onSubmitClick()`

### app/src/main/java/io/digibyte/presenter/activities/callbacks/ActivityQRCodeCallback.java
- Package: `io.digibyte.presenter.activities.callbacks`
- Interface: `ActivityQRCodeCallback`
- Methods: `onCloseClick()`

### app/src/main/java/io/digibyte/presenter/activities/callbacks/ActivityRecoverCallback.java
- Package: `io.digibyte.presenter.activities.callbacks`
- Interface: `ActivityRecoverCallback`
- Methods: `onNextClick()`

### app/src/main/java/io/digibyte/presenter/activities/callbacks/ActivitySyncCallback.java
- Package: `io.digibyte.presenter.activities.callbacks`
- Interface: `ActivitySyncCallback`
- Methods: `onScanButtonClick()`

### app/src/main/java/io/digibyte/presenter/activities/callbacks/ActivityWipeCallback.java
- Package: `io.digibyte.presenter.activities.callbacks`
- Interface: `ActivityWipeCallback`
- Methods: `onNextButtonClick()`

### app/src/main/java/io/digibyte/presenter/activities/callbacks/ActivityWriteDownCallback.java
- Package: `io.digibyte.presenter.activities.callbacks`
- Interface: `ActivityWriteDownCallback`
- Methods: `onWriteDownButtonClick()`

### app/src/main/java/io/digibyte/presenter/activities/callbacks/IntroActivityCallback.java
- Package: `io.digibyte.presenter.activities.callbacks`
- Interface: `IntroActivityCallback`
- Methods: `onNewWalletClick()`, `onRestoreClick()`, `onNewDigiIDClick()`

### app/src/main/java/io/digibyte/presenter/activities/callbacks/LoginActivityCallback.java
- Package: `io.digibyte.presenter.activities.callbacks`
- Interface: `LoginActivityCallback`
- Methods: `onFingerprintClick()`

### app/src/main/java/io/digibyte/presenter/activities/intro/IntroActivity.java
- Package: `io.digibyte.presenter.activities.intro`
- Class: `IntroActivity`
- Methods: `files()`, `onNewWalletClick()`, `onRestoreClick()`, `onNewDigiIDClick()`, `open()`, `onCreate()`, `onResume()`, `cleanup()`

### app/src/main/java/io/digibyte/presenter/activities/intro/LauncherActivity.java
- Package: `io.digibyte.presenter.activities.intro`
- Class: `LauncherActivity`
- Methods: `onCreate()`, `finish()`

### app/src/main/java/io/digibyte/presenter/activities/intro/RecoverActivity.java
- Package: `io.digibyte.presenter.activities.intro`
- Class: `RecoverActivity`
- Methods: `onCreate()`

### app/src/main/java/io/digibyte/presenter/activities/intro/WriteDownActivity.java
- Package: `io.digibyte.presenter.activities.intro`
- Class: `WriteDownActivity`
- Methods: `open()`, `getString()`, `onCreate()`, `onOptionsItemSelected()`, `onBackPressed()`, `onComplete()`, `onCancel()`

### app/src/main/java/io/digibyte/presenter/activities/models/InputWordsViewModel.java
- Package: `io.digibyte.presenter.activities.models`
- Class: `InputWordsViewModel`
- Methods: `getWord1()`, `setWord1()`, `getWord2()`, `setWord2()`, `getWord3()`, `setWord3()`, `getWord4()`, `setWord4()`, `getWord5()`, `setWord5()`, `getWord6()`, `setWord6()`, `getWord7()`, `setWord7()`, `getWord8()` …

### app/src/main/java/io/digibyte/presenter/activities/models/PinActivityModel.java
- Package: `io.digibyte.presenter.activities.models`
- Class: `PinActivityModel`
- Methods: `getKeyboardTextColor()`

### app/src/main/java/io/digibyte/presenter/activities/settings/AboutActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `AboutActivity`
- Methods: `onCreate()`

### app/src/main/java/io/digibyte/presenter/activities/settings/AdvancedActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `AdvancedActivity`
- Class: `SettingsListAdapter`
- Methods: `onCreate()`, `getView()`, `getCount()`, `getItemViewType()`, `onBackPressed()`, `populateItems()`, `onClick()`

### app/src/main/java/io/digibyte/presenter/activities/settings/DisplayCurrencyActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `DisplayCurrencyActivity`
- Class: `CurrencyListAdapter`
- Methods: `show()`, `onCreate()`, `updateExchangeRate()`, `onBackPressed()`, `getView()`, `getCount()`, `getItemViewType()`

### app/src/main/java/io/digibyte/presenter/activities/settings/FingerprintActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `FingerprintActivity`
- Methods: `onCreate()`, `getString()`, `onClick()`, `updateDrawState()`, `space()`, `getLimitText()`, `onComplete()`, `onCancel()`

### app/src/main/java/io/digibyte/presenter/activities/settings/ImportActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `ImportActivity`
- Methods: `onCreate()`, `onBackPressed()`, `onRequestPermissionsResult()`

### app/src/main/java/io/digibyte/presenter/activities/settings/NodesActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `NodesActivity`
- Methods: `run()`, `onSaveInstanceState()`, `onCreate()`, `updateButtonText()`, `getString()`, `createDialog()`, `onResume()`, `onPause()`, `startRepeatingTask()`, `stopRepeatingTask()`, `onBackPressed()`

### app/src/main/java/io/digibyte/presenter/activities/settings/NotificationActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `NotificationActivity`
- Methods: `getApp()`, `onSaveInstanceState()`, `onCreate()`, `onCheckedChanged()`, `onResume()`, `onPause()`, `onBackPressed()`

### app/src/main/java/io/digibyte/presenter/activities/settings/SecurityCenterActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `SecurityCenterActivity`
- Class: `SecurityCenterListAdapter`
- Methods: `onCreate()`, `onResume()`, `getView()`, `getCount()`, `updateList()`

### app/src/main/java/io/digibyte/presenter/activities/settings/SettingsActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `SettingsActivity`
- Class: `SettingsListAdapter`
- Class: `ViewHolder`
- Methods: `onTitleClick()`, `onCreate()`, `onResume()`, `onComplete()`, `onCancel()`, `getItemCount()`, `onCreateViewHolder()`, `getItemViewType()`, `onBindViewHolder()`, `populateItems()`, `getString()`

### app/src/main/java/io/digibyte/presenter/activities/settings/ShareDataActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `ShareDataActivity`
- Methods: `getApp()`, `onCreate()`, `onCheckedChanged()`, `onResume()`, `onPause()`, `onBackPressed()`, `onSaveInstanceState()`

### app/src/main/java/io/digibyte/presenter/activities/settings/SpendLimitActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `SpendLimitActivity`
- Class: `LimitHolder`
- Class: `LimitAdaptor`
- Methods: `show()`, `onCreate()`, `getAmountByStep()`, `onCreateViewHolder()`, `onBindViewHolder()`, `getString()`, `getItemCount()`

### app/src/main/java/io/digibyte/presenter/activities/settings/SyncBlockchainActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `SyncBlockchainActivity`
- Methods: `getString()`, `onCreate()`

### app/src/main/java/io/digibyte/presenter/activities/settings/TestActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `TestActivity`
- Methods: `onSaveInstanceState()`, `onCreate()`, `onResume()`, `onPause()`

### app/src/main/java/io/digibyte/presenter/activities/settings/WipeActivity.java
- Package: `io.digibyte.presenter.activities.settings`
- Class: `WipeActivity`
- Methods: `show()`, `onCreate()`

### app/src/main/java/io/digibyte/presenter/activities/util/ActivityUTILS.java
- Package: `io.digibyte.presenter.activities.util`
- Class: `ActivityUTILS`
- Methods: `files()`, `isAppSafe()`, `showWalletDisabled()`, `isMainThread()`, `updateDigibyteDollarValues()`, `getIntervals()`, `getCurrentAmount()`, `showJailbrokenDialog()`, `isvm()`, `getDecimalSeparator()`, `getCurrentLocale()`

### app/src/main/java/io/digibyte/presenter/activities/util/BRActivity.java
- Package: `io.digibyte.presenter.activities.util`
- Class: `BRActivity`
- Methods: `files()`, `onCreate()`, `setupToolbar()`, `setToolbarTitle()`, `onResume()`, `onActivityResult()`, `onRequestPermissionsResult()`, `onBackPressed()`, `onBackStackChanged()`, `getSupportFragmentManager()`, `onOptionsItemSelected()`, `onComplete()`, `onCancel()`

### app/src/main/java/io/digibyte/presenter/customviews/AutoResizeTextView.java
- Package: `io.digibyte.presenter.customviews`
- Class: `AutoResizeTextView`
- Interface: `OnTextResizeListener`
- Methods: `onTextResize()`, `onTextChanged()`, `resetTextSize()`, `onSizeChanged()`, `setOnResizeListener()`, `setTextSize()`, `setLineSpacing()`, `setMaxTextSize()`, `getMaxTextSize()`, `setMinTextSize()`, `getMinTextSize()`, `setAddEllipsis()`, `getAddEllipsis()`, `onLayout()`, `resizeText()` …

### app/src/main/java/io/digibyte/presenter/customviews/BRButton.java
- Package: `io.digibyte.presenter.customviews`
- Class: `BRButton`
- Methods: `files()`, `init()`, `getResources()`, `exists()`, `onGlobalLayout()`, `onTouchEvent()`, `onSizeChanged()`, `correctTextSizeIfNeeded()`, `correctTextBalance()`, `getText()`, `onDraw()`, `setType()`, `press()`, `onAnimationUpdate()`, `unPress()`

### app/src/main/java/io/digibyte/presenter/customviews/BRDialogView.java
- Package: `io.digibyte.presenter.customviews`
- Class: `BRDialogView`
- Interface: `BROnClickListener`
- Methods: `files()`, `onCreateDialog()`, `onDestroyView()`, `onDismiss()`, `setTitle()`, `setMessage()`, `setSpan()`, `setPosButton()`, `setNegButton()`, `setPosListener()`, `setNegListener()`, `setDismissListener()`, `onClick()`, `dismissWithAnimation()`

### app/src/main/java/io/digibyte/presenter/customviews/BREdit.java
- Package: `io.digibyte.presenter.customviews`
- Class: `BREdit`
- Methods: `files()`, `init()`

### app/src/main/java/io/digibyte/presenter/customviews/BRKeyboard.java
- Package: `io.digibyte.presenter.customviews`
- Class: `BRKeyboard`
- Interface: `OnInsertListener`
- Methods: `files()`, `init()`, `getText()`, `onSizeChanged()`, `addOnInsertListener()`, `onClick()`, `setBRKeyboardColor()`, `setBRButtonTextColor()`, `setBRButtonBackgroundResId()`, `setShowDot()`, `setBreadground()`, `button()`, `setCustomButtonBackgroundDrawable()`, `setCustomButtonBackgroundColor()`, `setDeleteImage()`

### app/src/main/java/io/digibyte/presenter/customviews/BRLinearLayout.java
- Package: `io.digibyte.presenter.customviews`
- Class: `BRLinearLayout`
- Methods: `files()`, `setYFraction()`, `getYFraction()`, `setXFraction()`, `getXFraction()`, `onMeasure()`, `setTranslationX()`

### app/src/main/java/io/digibyte/presenter/customviews/BRLockScreenConstraintLayout.java
- Package: `io.digibyte.presenter.customviews`
- Class: `BRLockScreenConstraintLayout`
- Methods: `files()`, `init()`, `onSizeChanged()`, `createTriangles()`, `setYFraction()`, `getYFraction()`, `setXFraction()`, `getXFraction()`, `onMeasure()`, `setTranslationX()`, `onDraw()`

### app/src/main/java/io/digibyte/presenter/customviews/BRNotificationBar.java
- Package: `io.digibyte.presenter.customviews`
- Class: `BRNotificationBar`
- Methods: `files()`, `init()`

### app/src/main/java/io/digibyte/presenter/customviews/BRRelativeLayout.java
- Package: `io.digibyte.presenter.customviews`
- Class: `BRRelativeLayout`
- Methods: `files()`, `setYFraction()`, `getYFraction()`, `setXFraction()`, `getXFraction()`, `onMeasure()`, `setTranslationX()`

### app/src/main/java/io/digibyte/presenter/customviews/BRScrollView.java
- Package: `io.digibyte.presenter.customviews`
- Class: `BRScrollView`
- Methods: `files()`, `setYFraction()`, `getYFraction()`, `setXFraction()`, `getXFraction()`, `onMeasure()`, `setTranslationX()`

### app/src/main/java/io/digibyte/presenter/customviews/BRTabLayout.java
- Package: `io.digibyte.presenter.customviews`
- Class: `BRTabLayout`
- Methods: `files()`, `setYFraction()`, `getYFraction()`, `setXFraction()`, `getXFraction()`, `onMeasure()`, `setTranslationX()`

### app/src/main/java/io/digibyte/presenter/customviews/BRText.java
- Package: `io.digibyte.presenter.customviews`
- Class: `BRText`
- Methods: `files()`, `init()`

### app/src/main/java/io/digibyte/presenter/customviews/BRToast.java
- Package: `io.digibyte.presenter.customviews`
- Class: `BRToast`
- Methods: `files()`, `showCustomToast()`, `run()`, `cancelToast()`, `isToastShown()`

### app/src/main/java/io/digibyte/presenter/entities/BRMenuItem.java
- Package: `io.digibyte.presenter.entities`
- Class: `BRMenuItem`
- Methods: `files()`

### app/src/main/java/io/digibyte/presenter/entities/BRMerkleBlockEntity.java
- Package: `io.digibyte.presenter.entities`
- Class: `BRMerkleBlockEntity`
- Methods: `files()`, `getId()`, `setId()`, `getBuff()`, `getBlockHeight()`, `setBlockHeight()`

### app/src/main/java/io/digibyte/presenter/entities/BRPeerEntity.java
- Package: `io.digibyte.presenter.entities`
- Class: `BRPeerEntity`
- Methods: `files()`, `getId()`, `setId()`, `getPort()`, `getTimeStamp()`, `getAddress()`

### app/src/main/java/io/digibyte/presenter/entities/BRSecurityCenterItem.java
- Package: `io.digibyte.presenter.entities`
- Class: `BRSecurityCenterItem`
- Methods: `files()`

### app/src/main/java/io/digibyte/presenter/entities/BRSettingsItem.java
- Package: `io.digibyte.presenter.entities`
- Class: `BRSettingsItem`
- Enum: `Type`
- Methods: `files()`

### app/src/main/java/io/digibyte/presenter/entities/BRTransactionEntity.java
- Package: `io.digibyte.presenter.entities`
- Class: `BRTransactionEntity`
- Methods: `files()`, `getBlockheight()`, `setBlockheight()`, `getTimestamp()`, `setTimestamp()`, `getTxHash()`, `setTxHash()`, `getBuff()`

### app/src/main/java/io/digibyte/presenter/entities/BlockEntity.java
- Package: `io.digibyte.presenter.entities`
- Class: `BlockEntity`
- Methods: `files()`, `getBlockBytes()`, `getBlockHeight()`

### app/src/main/java/io/digibyte/presenter/entities/CurrencyEntity.java
- Package: `io.digibyte.presenter.entities`
- Class: `CurrencyEntity`
- Class: `private`
- Methods: `files()`

### app/src/main/java/io/digibyte/presenter/entities/ImportPrivKeyEntity.java
- Package: `io.digibyte.presenter.entities`
- Class: `ImportPrivKeyEntity`
- Methods: `files()`, `getTx()`, `getAmount()`, `getFee()`

### app/src/main/java/io/digibyte/presenter/entities/PaymentItem.java
- Package: `io.digibyte.presenter.entities`
- Class: `PaymentItem`
- Methods: `files()`

### app/src/main/java/io/digibyte/presenter/entities/PaymentRequestWrapper.java
- Package: `io.digibyte.presenter.entities`
- Class: `PaymentRequestWrapper`
- Methods: `files()`, `byteSignature()`, `pkiData()`, `merchantData()`, `payment()`, `serializedTx()`

### app/src/main/java/io/digibyte/presenter/entities/PeerEntity.java
- Package: `io.digibyte.presenter.entities`
- Class: `PeerEntity`
- Methods: `files()`, `getPeerAddress()`, `getPeerPort()`, `getPeerTimeStamp()`

### app/src/main/java/io/digibyte/presenter/entities/RequestObject.java
- Package: `io.digibyte.presenter.entities`
- Class: `RequestObject`
- Methods: `files()`

### app/src/main/java/io/digibyte/presenter/entities/TxItem.java
- Package: `io.digibyte.presenter.entities`
- Class: `TxItem`
- Methods: `files()`, `getBlockHeight()`, `setBlockHeight()`, `getFee()`, `getTxSize()`, `getFrom()`, `getTxHash()`, `getTxHashHexReversed()`, `getReceived()`, `getSent()`, `getTAG()`, `getTimeStamp()`, `getTo()`, `getBalanceAfterTx()`, `getOutAmounts()` …

### app/src/main/java/io/digibyte/presenter/entities/VerticalSpaceItemDecoration.java
- Package: `io.digibyte.presenter.entities`
- Class: `VerticalSpaceItemDecoration`
- Methods: `getItemOffsets()`

### app/src/main/java/io/digibyte/presenter/fragments/FragmentFingerprint.java
- Package: `io.digibyte.presenter.fragments`
- Class: `FragmentFingerprint`
- Methods: `onCancelClick()`, `onSecondButtonClick()`, `show()`, `onAttach()`, `onCreateView()`, `getContext()`, `onActivityCreated()`, `onResume()`, `onPause()`, `backup()`, `goToBackup()`, `onAuthenticated()`, `getType()`, `fadeOutRemove()`, `remove()` …

### app/src/main/java/io/digibyte/presenter/fragments/FragmentGreetings.java
- Package: `io.digibyte.presenter.fragments`
- Class: `FragmentGreetings`
- Methods: `files()`, `onCreateView()`, `onClick()`, `onViewCreated()`, `onGlobalLayout()`, `onStop()`, `onAnimationEnd()`, `onResume()`, `onPause()`

### app/src/main/java/io/digibyte/presenter/fragments/FragmentMenu.java
- Package: `io.digibyte.presenter.fragments`
- Class: `FragmentMenu`
- Enum: `FragmentType`
- Class: `MenuListAdapter`
- Methods: `files()`, `show()`, `onCreateView()`, `onActivityCreated()`, `onCreateViewHolder()`, `onBindViewHolder()`, `getItemCount()`, `fadeOutRemove()`, `remove()`, `onBackPressed()`

### app/src/main/java/io/digibyte/presenter/fragments/FragmentPhraseWord.java
- Package: `io.digibyte.presenter.fragments`
- Class: `FragmentPhraseWord`
- Methods: `files()`, `onCreateView()`, `newInstance()`

### app/src/main/java/io/digibyte/presenter/fragments/FragmentPin.java
- Package: `io.digibyte.presenter.fragments`
- Class: `FragmentPin`
- Methods: `files()`, `onClick()`, `onCancelClick()`, `show()`, `onAttach()`, `onCreateView()`, `onActivityCreated()`, `onResume()`, `handleClick()`, `handleDigitClick()`, `handleDeleteClick()`, `updateDots()`, `getType()`, `fadeOutRemove()`, `onAnimationEnd()` …

### app/src/main/java/io/digibyte/presenter/fragments/FragmentReceive.java
- Package: `io.digibyte.presenter.fragments`
- Class: `FragmentReceive`
- Methods: `files()`, `shareEmailClick()`, `shareTextClick()`, `shareButtonClick()`, `shareCopyClick()`, `addressClick()`, `requestButtonClick()`, `backgroundClick()`, `qrImageClick()`, `closeClick()`, `onAmountEditClick()`, `onClick()`, `onIsoButtonClick()`, `onKeyboardClick()`, `onShareEmail()` …

### app/src/main/java/io/digibyte/presenter/fragments/FragmentRequestAmount.java
- Package: `io.digibyte.presenter.fragments`
- Class: `FragmentRequestAmount`
- Methods: `files()`, `show()`, `onCreateView()`, `setTitle()`, `updateQRImage()`, `onAmountEditClick()`, `onKeyboardClick()`, `onIsoButtonClick()`, `onShareEmail()`, `onShareSMS()`, `onShareCopy()`, `handleClick()`, `handleDigitClick()`, `handleSeparatorClick()`, `handleDeleteClick()` …

### app/src/main/java/io/digibyte/presenter/fragments/FragmentSend.java
- Package: `io.digibyte.presenter.fragments`
- Class: `FragmentSend`
- Methods: `files()`, `onAmountClickListener()`, `onPasteClickListener()`, `onKey()`, `onIsoButtonClickListener()`, `onScanClickListener()`, `onSendClickListener()`, `onClick()`, `onCloseClickListener()`, `onEditorAction()`, `onMaxSendButtonClickListener()`, `show()`, `onCreateView()`, `onActivityCreated()`, `onSaveInstanceState()` …

### app/src/main/java/io/digibyte/presenter/fragments/FragmentSignal.java
- Package: `io.digibyte.presenter.fragments`
- Class: `FragmentSignal`
- Methods: `files()`, `onCreateView()`, `onActivityCreated()`, `setCompletion()`, `onResume()`, `fadeOutRemove()`, `remove()`, `onPause()`, `onBackPressed()`

### app/src/main/java/io/digibyte/presenter/fragments/FragmentTransactionDetails.java
- Package: `io.digibyte.presenter.fragments`
- Class: `FragmentTransactionDetails`
- Methods: `files()`, `show()`, `onCreateView()`, `onPageScrolled()`, `onPageSelected()`, `onPageScrollStateChanged()`, `onActivityCreated()`, `fadeOutRemove()`, `onAnimationEnd()`, `onBackPressed()`

### app/src/main/java/io/digibyte/presenter/fragments/FragmentTransactionItem.java
- Package: `io.digibyte.presenter.fragments`
- Class: `FragmentTransactionItem`
- Methods: `files()`, `onBackgroundClick()`, `onAddressClick()`, `onTransactionIDClick()`, `newInstance()`, `onCreateView()`

### app/src/main/java/io/digibyte/presenter/fragments/interfaces/FingerprintFragmentCallback.java
- Package: `io.digibyte.presenter.fragments.interfaces`
- Interface: `FingerprintFragmentCallback`
- Methods: `onCancelClick()`, `onSecondButtonClick()`

### app/src/main/java/io/digibyte/presenter/fragments/interfaces/FragmentReceiveCallbacks.java
- Package: `io.digibyte.presenter.fragments.interfaces`
- Interface: `FragmentReceiveCallbacks`
- Methods: `shareEmailClick()`, `shareTextClick()`, `shareCopyClick()`, `shareButtonClick()`, `addressClick()`, `requestButtonClick()`, `backgroundClick()`, `qrImageClick()`, `closeClick()`, `onAmountEditClick()`, `onIsoButtonClick()`

### app/src/main/java/io/digibyte/presenter/fragments/interfaces/FragmentSendCallbacks.java
- Package: `io.digibyte.presenter.fragments.interfaces`
- Interface: `FragmentSendCallbacks`
- Methods: `onAmountClickListener()`, `onPasteClickListener()`, `onIsoButtonClickListener()`, `onScanClickListener()`, `onSendClickListener()`, `onCloseClickListener()`, `onMaxSendButtonClickListener()`

### app/src/main/java/io/digibyte/presenter/fragments/interfaces/MenuDialogCallback.java
- Package: `io.digibyte.presenter.fragments.interfaces`
- Interface: `MenuDialogCallback`
- Methods: `onCancelClick()`

### app/src/main/java/io/digibyte/presenter/fragments/interfaces/OnBackPressListener.java
- Package: `io.digibyte.presenter.fragments.interfaces`
- Interface: `OnBackPressListener`
- Methods: `onBackPressed()`, `getTag()`

### app/src/main/java/io/digibyte/presenter/fragments/interfaces/PinFragmentCallback.java
- Package: `io.digibyte.presenter.fragments.interfaces`
- Interface: `PinFragmentCallback`
- Methods: `onCancelClick()`

### app/src/main/java/io/digibyte/presenter/fragments/interfaces/TransactionDetailsCallback.java
- Package: `io.digibyte.presenter.fragments.interfaces`
- Interface: `TransactionDetailsCallback`
- Methods: `onBackgroundClick()`, `onAddressClick()`, `onTransactionIDClick()`

### app/src/main/java/io/digibyte/presenter/fragments/models/FingerprintFragmentViewModel.java
- Package: `io.digibyte.presenter.fragments.models`
- Class: `FingerprintFragmentViewModel`
- Methods: `setMessage()`, `getMessage()`, `setTitle()`, `getTitle()`, `setCancelButtonLabel()`, `getCancelButtonLabel()`, `setSecondaryButtonLabel()`, `getSecondaryButtonLabel()`

### app/src/main/java/io/digibyte/presenter/fragments/models/FragmentSignalViewModel.java
- Package: `io.digibyte.presenter.fragments.models`
- Class: `FragmentSignalViewModel`
- Methods: `setTitle()`, `setDescription()`, `setIcon()`, `getTitle()`, `getDescription()`, `getIcon()`

### app/src/main/java/io/digibyte/presenter/fragments/models/PinFragmentViewModel.java
- Package: `io.digibyte.presenter.fragments.models`
- Class: `PinFragmentViewModel`
- Methods: `setTitle()`, `getTitle()`, `setMessage()`, `getMessage()`, `getKeyboardTextColor()`

### app/src/main/java/io/digibyte/presenter/fragments/models/ReceiveFragmentModel.java
- Package: `io.digibyte.presenter.fragments.models`
- Class: `ReceiveFragmentModel`
- Methods: `isShareVisibility()`, `setShareVisibility()`, `isRequestButtonVisibility()`, `setRequestButtonVisibility()`, `getTitle()`, `setTitle()`, `getAddress()`, `setAddress()`, `isShowKeyboard()`, `setShowKeyboard()`, `getAmount()`, `setAmount()`, `getDisplayAmount()`, `getIsoText()`, `setIsoText()` …

### app/src/main/java/io/digibyte/presenter/fragments/models/SendFragmentModel.java
- Package: `io.digibyte.presenter.fragments.models`
- Class: `SendFragmentModel`
- Methods: `getBRKeyboardColor()`, `getIsoText()`, `getIsoButtonText()`, `getAddress()`, `setAddress()`, `getBalanceTextColor()`, `getFeeTextColor()`, `getAmountEditTextColor()`, `getISOTextColor()`, `getBalanceText()`, `getFeeText()`, `getAmount()`, `getDisplayAmount()`, `getMemo()`, `getShowSendWaiting()` …

### app/src/main/java/io/digibyte/presenter/fragments/models/TransactionDetailsViewModel.java
- Package: `io.digibyte.presenter.fragments.models`
- Class: `TransactionDetailsViewModel`
- Methods: `getCryptoAmount()`, `getRawFiatAmount()`, `getFiatAmount()`, `getOriginalFiatAmount()`, `currentFiatAmountEqualsOriginalFiatAmount()`, `getToFrom()`, `getSent()`, `getAddress()`, `getSentReceivedIcon()`, `getDate()`, `getFormattedDate()`, `getTime()`, `getFormattedTime()`, `getCompleted()`, `getFee()` …

### app/src/main/java/io/digibyte/presenter/interfaces/BRAuthCompletion.java
- Package: `io.digibyte.presenter.interfaces`
- Interface: `BRAuthCompletion`
- Class: `AuthType`
- Enum: `Type`
- Methods: `files()`, `onComplete()`, `onCancel()`

### app/src/main/java/io/digibyte/presenter/interfaces/BROnSignalCompletion.java
- Package: `io.digibyte.presenter.interfaces`
- Interface: `BROnSignalCompletion`
- Methods: `files()`, `onComplete()`

### app/src/main/java/io/digibyte/presenter/interfaces/BreadPayment.java
- Package: `io.digibyte.presenter.interfaces`
- Interface: `BreadPayment`
- Methods: `files()`

### app/src/main/java/io/digibyte/tools/adapter/CurAdapter.java
- Package: `io.digibyte.tools.adapter`
- Class: `CurAdapter`
- Class: `CustomViewHolder`
- Methods: `files()`, `getItemAtPos()`, `getItems()`, `onCreateViewHolder()`, `onBindViewHolder()`, `getItemViewType()`, `getItemCount()`, `setTexts()`

### app/src/main/java/io/digibyte/tools/adapter/TransactionListAdapter.java
- Package: `io.digibyte.tools.adapter`
- Class: `TransactionListAdapter`
- Methods: `files()`, `updateTransactions()`, `notifyDataChanged()`, `findTransaction()`, `isPositionOnscreen()`, `addTransactions()`, `getTransactions()`, `onCreateViewHolder()`, `onBindViewHolder()`, `onViewRecycled()`, `onClick()`, `getItemViewType()`, `getItemCount()`, `getListItemDataForPosition()`, `getItemId()` …

### app/src/main/java/io/digibyte/tools/adapter/TransactionPagerAdapter.java
- Package: `io.digibyte.tools.adapter`
- Class: `TransactionPagerAdapter`
- Methods: `files()`, `getItem()`, `getCount()`

### app/src/main/java/io/digibyte/tools/animation/BRAnimator.java
- Package: `io.digibyte.tools.animation`
- Class: `BRAnimator`
- Interface: `OnAnimationEndListener`
- Interface: `OnSlideAnimationEnd`
- Methods: `files()`, `showBreadSignal()`, `showOrUpdateSendFragment()`, `showTransactionPager()`, `openScanner()`, `onClick()`, `showRequestFragment()`, `showMenuFragment()`, `isClickAllowed()`, `run()`, `startBreadActivity()`, `animateSignalSlide()`, `onAnimationEnd()`, `animateBackgroundDim()`, `onAnimationUpdate()` …

### app/src/main/java/io/digibyte/tools/animation/BRDialog.java
- Package: `io.digibyte.tools.animation`
- Class: `BRDialog`
- Methods: `files()`, `showCustomDialog()`

### app/src/main/java/io/digibyte/tools/animation/DecelerateOvershootInterpolator.java
- Package: `io.digibyte.tools.animation`
- Class: `DecelerateOvershootInterpolator`
- Methods: `files()`, `getInterpolation()`

### app/src/main/java/io/digibyte/tools/animation/SlideDetector.java
- Package: `io.digibyte.tools.animation`
- Class: `SlideDetector`
- Methods: `files()`, `onTouch()`, `onAnimationEnd()`, `removeCurrentView()`

### app/src/main/java/io/digibyte/tools/animation/SpringAnimator.java
- Package: `io.digibyte.tools.animation`
- Class: `SpringAnimator`
- Methods: `files()`, `showExpandCameraGuide()`, `springView()`, `shortSpringView()`, `showBubbleAnimation()`, `failShakeAnimation()`

### app/src/main/java/io/digibyte/tools/crypto/Base58.java
- Package: `io.digibyte.tools.crypto`
- Class: `Base58`
- Methods: `files()`, `encode()`, `decode()`, `copyOfRange()`, `divmod58()`, `divmod256()`

### app/src/main/java/io/digibyte/tools/crypto/CryptoHelper.java
- Package: `io.digibyte.tools.crypto`
- Class: `CryptoHelper`
- Methods: `files()`, `base58ofSha256()`, `doubleSha256()`, `sha256()`, `md5()`

### app/src/main/java/io/digibyte/tools/database/AppDatabase.java
- Package: `io.digibyte.tools.database`
- Class: `AppDatabase`
- Methods: `transactionDao()`

### app/src/main/java/io/digibyte/tools/database/Database.java
- Package: `io.digibyte.tools.database`
- Class: `Database`
- Interface: `TransacionStoreListener`
- Methods: `onTransactionsUpdate()`, `saveTransaction()`, `update()`, `containsTransaction()`, `findTransaction()`

### app/src/main/java/io/digibyte/tools/database/DigiTransaction.java
- Package: `io.digibyte.tools.database`
- Class: `DigiTransaction`
- Methods: `getUid()`, `setUid()`, `getTxHash()`, `setTxHash()`, `getTxAmount()`, `setTxAmount()`

### app/src/main/java/io/digibyte/tools/database/TransactionDao.java
- Package: `io.digibyte.tools.database`
- Interface: `TransactionDao`
- Methods: `getAll()`, `findByTxHash()`, `insertAll()`, `delete()`

### app/src/main/java/io/digibyte/tools/list/ListItemData.java
- Package: `io.digibyte.tools.list`
- Class: `ListItemData`
- Methods: `describeContents()`, `writeToParcel()`, `createFromParcel()`, `newArray()`

### app/src/main/java/io/digibyte/tools/list/ListItemViewHolder.java
- Package: `io.digibyte.tools.list`
- Class: `ListItemViewHolder`
- Methods: `getItemData()`, `getView()`, `process()`

### app/src/main/java/io/digibyte/tools/list/items/ListItemPromptData.java
- Package: `io.digibyte.tools.list.items`
- Class: `ListItemPromptData`

### app/src/main/java/io/digibyte/tools/list/items/ListItemPromptViewHolder.java
- Package: `io.digibyte.tools.list.items`
- Class: `ListItemPromptViewHolder`
- Methods: `process()`

### app/src/main/java/io/digibyte/tools/list/items/ListItemSyncingData.java
- Package: `io.digibyte.tools.list.items`
- Class: `ListItemSyncingData`

### app/src/main/java/io/digibyte/tools/list/items/ListItemSyncingViewHolder.java
- Package: `io.digibyte.tools.list.items`
- Class: `ListItemSyncingViewHolder`
- Methods: `process()`

### app/src/main/java/io/digibyte/tools/list/items/ListItemTransactionData.java
- Package: `io.digibyte.tools.list.items`
- Class: `ListItemTransactionData`
- Methods: `getTransactionItem()`, `equals()`, `hashCode()`, `update()`, `getTransactionDisplayTimeHolder()`, `describeContents()`, `writeToParcel()`, `createFromParcel()`, `newArray()`

### app/src/main/java/io/digibyte/tools/list/items/ListItemTransactionViewHolder.java
- Package: `io.digibyte.tools.list.items`
- Class: `ListItemTransactionViewHolder`
- Methods: `process()`, `setArrowIcon()`, `setAmount()`, `setTimeStamp()`

### app/src/main/java/io/digibyte/tools/manager/BRApiManager.java
- Package: `io.digibyte.tools.manager`
- Class: `BRApiManager`
- Methods: `files()`, `getInstance()`, `getCurrencies()`, `asyncUpdateCurrencyData()`, `asyncUpdateFeeData()`, `fetchRates()`, `updateFeePerKb()`, `getBlockInfo()`, `urlGET()`

### app/src/main/java/io/digibyte/tools/manager/BRClipboardManager.java
- Package: `io.digibyte.tools.manager`
- Class: `BRClipboardManager`
- Methods: `files()`, `putClipboard()`, `getClipboard()`, `coerceToText()`

### app/src/main/java/io/digibyte/tools/manager/BREventManager.java
- Package: `io.digibyte.tools.manager`
- Class: `BREventManager`
- Class: `Event`
- Methods: `files()`, `getInstance()`, `pushEvent()`, `onEnterBackground()`, `saveEvents()`, `pushToServer()`, `writeEventsToDisk()`, `getEventsFromDisk()`, `readFile()`

### app/src/main/java/io/digibyte/tools/manager/BRNotificationManager.java
- Package: `io.digibyte.tools.manager`
- Class: `BRNotificationManager`
- Methods: `files()`, `sendNotification()`

### app/src/main/java/io/digibyte/tools/manager/BRReportsManager.java
- Package: `io.digibyte.tools.manager`
- Class: `BRReportsManager`
- Methods: `files()`, `reportBug()`

### app/src/main/java/io/digibyte/tools/manager/BRSharedPrefs.java
- Package: `io.digibyte.tools.manager`
- Class: `BRSharedPrefs`
- Interface: `OnIsoChangedListener`
- Methods: `files()`, `onIsoChanged()`, `addIsoChangedListener()`, `removeListener()`, `getIso()`, `putIso()`, `getPhraseWroteDown()`, `putPhraseWroteDown()`, `getGreetingsShown()`, `putGreetingsShown()`, `getCurrencyListPosition()`, `putCurrencyListPosition()`, `getReceiveAddress()`, `putReceiveAddress()`, `getWalletName()` …

### app/src/main/java/io/digibyte/tools/manager/FontManager.java
- Package: `io.digibyte.tools.manager`
- Class: `FontManager`
- Methods: `files()`, `overrideFonts()`, `get()`, `setCustomFont()`

### app/src/main/java/io/digibyte/tools/manager/PromptManager.java
- Package: `io.digibyte.tools.manager`
- Class: `PromptManager`
- Enum: `PromptItem`
- Methods: `files()`, `getInstance()`, `nextPrompt()`, `hasPromptBeenDismissed()`, `shouldPrompt()`, `getPromptName()`

### app/src/main/java/io/digibyte/tools/manager/SyncManager.java
- Package: `io.digibyte.tools.manager`
- Class: `SyncManager`
- Interface: `onStatusListener`
- Methods: `files()`, `onSyncManagerStarted()`, `onSyncManagerUpdate()`, `onSyncManagerFinished()`, `onSyncFailed()`, `getProgress()`, `getLastBlockTimestamp()`, `addListener()`, `removeListener()`, `getInstance()`, `startSyncingProgressThread()`, `stopSyncingProgressThread()`, `syncFailed()`, `run()`, `isSyncing()`

### app/src/main/java/io/digibyte/tools/manager/TxManager.java
- Package: `io.digibyte.tools.manager`
- Class: `TxManager`
- Interface: `onStatusListener`
- Methods: `files()`, `onTxManagerUpdate()`, `addListener()`, `removeListener()`, `getInstance()`, `updateTxList()`, `run()`

### app/src/main/java/io/digibyte/tools/qrcode/QRUtils.java
- Package: `io.digibyte.tools.qrcode`
- Class: `QRUtils`
- Methods: `files()`, `encodeAsBitmap()`, `generateQR()`, `getQRImage()`, `guessAppropriateEncoding()`, `share()`, `getQRImageUri()`, `saveToExternalStorage()`

### app/src/main/java/io/digibyte/tools/security/AuthManager.java
- Package: `io.digibyte.tools.security`
- Class: `AuthManager`
- Interface: `OnPinSuccess`
- Methods: `files()`, `getInstance()`, `checkAuth()`, `authSuccess()`, `authFail()`, `isWalletDisabled()`, `disabledUntil()`, `setWalletDisabled()`, `setPinCode()`, `updateDots()`, `setDotSelected()`, `setDotUnSelected()`, `authPrompt()`, `isFingerPrintAvailableAndSetup()`, `onSuccess()`

### app/src/main/java/io/digibyte/tools/security/BRKeyStore.java
- Package: `io.digibyte.tools.security`
- Class: `BRKeyStore`
- Class: `AliasObject`
- Methods: `files()`, `useNewStorage()`, `storeEncryptedData()`, `createKeys()`, `constrains()`, `validateGet()`, `validateSet()`, `showKeyInvalidated()`, `getFilePath()`, `putPhrase()`, `getPhrase()`, `putCanary()`, `getCanary()`, `putMasterPublicKey()`, `getMasterPublicKey()` …

### app/src/main/java/io/digibyte/tools/security/BRSender.java
- Package: `io.digibyte.tools.security`
- Class: `BRSender`
- Interface: `UpdateTxFeeCallback`
- Class: `InsufficientFundsException`
- Class: `AmountSmallerThanMinException`
- Class: `SpendingNotAllowed`
- Class: `FeeNeedsAdjust`
- Class: `FeeOutOfDate`
- Class: `SomethingWentWrong`
- Methods: `files()`, `getInstance()`, `onTxFeeUpdated()`, `sendTransaction()`, `block()`, `showAdjustFee()`, `run()`, `tryPay()`, `tx()`, `confirmPay()`, `createConfirmation()`, `getReceiver()`, `isSmallerThanMin()`, `isLargerThanBalance()`, `notEnoughForFee()` …

### app/src/main/java/io/digibyte/tools/security/BitcoinUrlHandler.java
- Package: `io.digibyte.tools.security`
- Class: `BitcoinUrlHandler`
- Methods: `files()`, `isBitcoinUrl()`, `getScannedQRRequest()`, `getRequestFromString()`, `parsePaymentRequest()`, `parsePaymentACK()`, `getCertificatesFromPaymentRequest()`

### app/src/main/java/io/digibyte/tools/security/FingerprintUiHelper.java
- Package: `io.digibyte.tools.security`
- Class: `to`
- Class: `FingerprintUiHelper`
- Class: `for`
- Class: `FingerprintUiHelperBuilder`
- Interface: `Callback`
- Methods: `build()`, `isFingerprintAuthAvailable()`, `startListening()`, `stopListening()`, `onAuthenticationError()`, `onAuthenticationHelp()`, `onAuthenticationFailed()`, `onAuthenticationSucceeded()`, `showError()`, `run()`, `onAuthenticated()`, `onError()`

### app/src/main/java/io/digibyte/tools/security/PostAuth.java
- Package: `io.digibyte.tools.security`
- Class: `PostAuth`
- Methods: `files()`, `onCreateWalletAuth()`, `onPhraseCheckAuth()`, `onPhraseProveAuth()`, `onRecoverWalletAuth()`, `onPublishTxAuth()`, `setPhraseForKeyStore()`, `onCanaryCheck()`

### app/src/main/java/io/digibyte/tools/security/RootHelper.java
- Package: `io.digibyte.tools.security`
- Class: `RootHelper`
- Methods: `files()`, `isDeviceRooted()`, `checkRootA()`, `checkRootB()`, `checkRootC()`

### app/src/main/java/io/digibyte/tools/security/SmartValidator.java
- Package: `io.digibyte.tools.security`
- Class: `SmartValidator`
- Methods: `files()`, `isPaperKeyValid()`, `isValid()`, `isPaperKeyCorrect()`, `checkFirstAddress()`, `cleanPaperKey()`, `isWordValid()`

### app/src/main/java/io/digibyte/tools/security/X509CertificateValidator.java
- Package: `io.digibyte.tools.security`
- Class: `X509CertificateValidator`
- Methods: `files()`, `certificateValidation()`, `getName()`, `getRootCerts()`, `getCertificateFromBytes()`

### app/src/main/java/io/digibyte/tools/sqlite/BRDataSourceInterface.java
- Package: `io.digibyte.tools.sqlite`
- Interface: `BRDataSourceInterface`
- Methods: `files()`, `openDatabase()`, `closeDatabase()`

### app/src/main/java/io/digibyte/tools/sqlite/BRSQLiteHelper.java
- Package: `io.digibyte.tools.sqlite`
- Class: `BRSQLiteHelper`
- Methods: `files()`, `getInstance()`, `onCreate()`, `onUpgrade()`

### app/src/main/java/io/digibyte/tools/sqlite/CurrencyDataSource.java
- Package: `io.digibyte.tools.sqlite`
- Class: `CurrencyDataSource`
- Methods: `files()`, `getInstance()`, `putCurrencies()`, `deleteAllCurrencies()`, `getAllCurrencies()`, `getAllISOs()`, `getCurrencyByIso()`, `cursorToCurrency()`, `openDatabase()`, `closeDatabase()`

### app/src/main/java/io/digibyte/tools/sqlite/MerkleBlockDataSource.java
- Package: `io.digibyte.tools.sqlite`
- Class: `MerkleBlockDataSource`
- Methods: `files()`, `getInstance()`, `putMerkleBlocks()`, `deleteAllBlocks()`, `deleteMerkleBlock()`, `getAllMerkleBlocks()`, `cursorToMerkleBlock()`, `openDatabase()`, `closeDatabase()`

### app/src/main/java/io/digibyte/tools/sqlite/PeerDataSource.java
- Package: `io.digibyte.tools.sqlite`
- Class: `PeerDataSource`
- Methods: `files()`, `getInstance()`, `putPeers()`, `deletePeer()`, `deleteAllPeers()`, `getAllPeers()`, `cursorToPeer()`, `openDatabase()`, `closeDatabase()`

### app/src/main/java/io/digibyte/tools/sqlite/TransactionDataSource.java
- Package: `io.digibyte.tools.sqlite`
- Class: `TransactionDataSource`
- Interface: `OnTxAddedListener`
- Methods: `files()`, `onTxAdded()`, `addTxAddedListener()`, `removeListener()`, `getInstance()`, `putTransaction()`, `deleteAllTransactions()`, `getAllTransactions()`, `cursorToTransaction()`, `updateTxBlockHeight()`, `deleteTxByHash()`, `openDatabase()`, `closeDatabase()`

### app/src/main/java/io/digibyte/tools/threads/BRExecutor.java
- Package: `io.digibyte.tools.threads`
- Class: `for`
- Class: `BRExecutor`
- Methods: `files()`, `tasks()`, `getInstance()`, `forBackgroundTasks()`, `forLightWeightBackgroundTasks()`, `forSerializedTasks()`, `forMainThreadTasks()`, `rejectedExecution()`

### app/src/main/java/io/digibyte/tools/threads/ImportPrivKeyTask.java
- Package: `io.digibyte.tools.threads`
- Class: `ImportPrivKeyTask`
- Methods: `files()`, `doInBackground()`, `run()`, `onClick()`, `onPostExecute()`, `createTx()`, `hexStringToByteArray()`, `callURL()`

### app/src/main/java/io/digibyte/tools/threads/MainThreadExecutor.java
- Package: `io.digibyte.tools.threads`
- Class: `MainThreadExecutor`
- Methods: `files()`, `execute()`

### app/src/main/java/io/digibyte/tools/threads/Priority.java
- Package: `io.digibyte.tools.threads`
- Enum: `Priority`
- Methods: `files()`, `instantly()`

### app/src/main/java/io/digibyte/tools/threads/PriorityRunnable.java
- Package: `io.digibyte.tools.threads`
- Class: `PriorityRunnable`
- Methods: `files()`, `run()`, `getPriority()`

### app/src/main/java/io/digibyte/tools/threads/PriorityThreadFactory.java
- Package: `io.digibyte.tools.threads`
- Class: `PriorityThreadFactory`
- Methods: `files()`, `newThread()`, `run()`

### app/src/main/java/io/digibyte/tools/threads/PriorityThreadPoolExecutor.java
- Package: `io.digibyte.tools.threads`
- Class: `PriorityThreadPoolExecutor`
- Class: `PriorityFutureTask`
- Interface: `java`
- Methods: `files()`, `submit()`, `compareTo()`

### app/src/main/java/io/digibyte/tools/util/BRCompressor.java
- Package: `io.digibyte.tools.util`
- Class: `BRCompressor`
- Methods: `files()`, `gZipExtract()`, `gZipCompress()`, `bz2Extract()`, `bz2Compress()`, `isGZIPStream()`

### app/src/main/java/io/digibyte/tools/util/BRConstants.java
- Package: `io.digibyte.tools.util`
- Class: `BRConstants`
- Methods: `files()`

### app/src/main/java/io/digibyte/tools/util/BRCurrency.java
- Package: `io.digibyte.tools.util`
- Class: `BRCurrency`
- Methods: `files()`, `getFormattedCurrencyString()`, `getSymbolByIso()`, `getCurrencyName()`, `getMaxDecimalPlaces()`

### app/src/main/java/io/digibyte/tools/util/BRDateUtil.java
- Package: `io.digibyte.tools.util`
- Class: `BRDateUtil`
- Methods: `files()`, `getCustomSpan()`

### app/src/main/java/io/digibyte/tools/util/BRExchange.java
- Package: `io.digibyte.tools.util`
- Class: `BRExchange`
- Methods: `files()`, `getMaxAmount()`, `getBitcoinForSatoshis()`, `getSatoshisForBitcoin()`, `getBitcoinSymbol()`, `getAmountFromSatoshis()`, `getSatoshisFromAmount()`

### app/src/main/java/io/digibyte/tools/util/Bip39Reader.java
- Package: `io.digibyte.tools.util`
- Class: `Bip39Reader`
- Methods: `files()`, `bip39List()`, `cleanWord()`

### app/src/main/java/io/digibyte/tools/util/BytesUtil.java
- Package: `io.digibyte.tools.util`
- Class: `BytesUtil`
- Methods: `files()`, `readBytesFromStream()`

### app/src/main/java/io/digibyte/tools/util/CustomLogger.java
- Package: `io.digibyte.tools.util`
- Class: `CustomLogger`
- Methods: `files()`, `logThis()`

### app/src/main/java/io/digibyte/tools/util/FileHelper.java
- Package: `io.digibyte.tools.util`
- Class: `FileHelper`
- Methods: `files()`, `printDirectoryTree()`, `printFile()`, `getIndentString()`

### app/src/main/java/io/digibyte/tools/util/TrustedNode.java
- Package: `io.digibyte.tools.util`
- Class: `TrustedNode`
- Methods: `files()`, `getNodeHost()`, `getNodePort()`, `isValid()`

### app/src/main/java/io/digibyte/tools/util/TypesConverter.java
- Package: `io.digibyte.tools.util`
- Class: `TypesConverter`
- Methods: `files()`, `intToBytes()`, `bytesToInt()`, `toBytes()`, `lowerCaseCharArray()`, `toChars()`, `long2byteArray()`, `byteArray2long()`, `getNullTerminatedPhrase()`

### app/src/main/java/io/digibyte/tools/util/Utils.java
- Package: `io.digibyte.tools.util`
- Class: `Utils`
- Methods: `files()`, `isUsingCustomInputMethod()`, `isEmulatorOrDebug()`, `getFormattedDateFromLong()`, `formatTimeStamp()`, `isNullOrEmpty()`, `getPixelsFromDps()`, `bytesToHex()`, `hexToBytes()`, `createBitcoinUrl()`, `isFingerprintAvailable()`, `hideKeyboard()`, `getAgentString()`, `reverseHex()`, `getScreenSize()`

### app/src/main/java/io/digibyte/tools/util/ViewUtils.java
- Package: `io.digibyte.tools.util`
- Class: `ViewUtils`
- Methods: `increaceClickableArea()`

### app/src/main/java/io/digibyte/wallet/BRPeerManager.java
- Package: `io.digibyte.wallet`
- Class: `BRPeerManager`
- Interface: `OnTxStatusUpdate`
- Interface: `OnSyncSucceeded`
- Methods: `files()`, `getInstance()`, `syncStarted()`, `syncSucceeded()`, `getCurrentBlockHeight()`, `syncFailed()`, `txStatusUpdate()`, `corruptBlocks()`, `saveBlocks()`, `savePeers()`, `networkIsReachable()`, `deleteBlocks()`, `deletePeers()`, `updateFixedPeer()`, `addStatusUpdateListener()` …

### app/src/main/java/io/digibyte/wallet/BRWalletManager.java
- Package: `io.digibyte.wallet`
- Class: `BRWalletManager`
- Interface: `ClearedListener`
- Interface: `OnBalanceChanged`
- Methods: `files()`, `setBalance()`, `showSendConfirmDialog()`, `refreshBalance()`, `getBalance()`, `getInstance()`, `generateRandomSeed()`, `wipeKeyStore()`, `noWallet()`, `isPasscodeEnabled()`, `isNetworkAvailable()`, `refreshAddress()`, `wipeWalletButKeystore()`, `wipeBlockAndTrans()`, `onCleared()` …

### app/src/main/jni/digibytewallet-core/BRAddress.c
- Functions: `BRVarInt()`, `BRVarIntSet()`, `BRVarIntSize()`, `BRScriptElements()`, `BRScriptPushData()`, `BRAddressFromScriptPubKey()`, `BRAddressFromScriptSig()`, `BRAddressFromWitness()`, `BRAddressScriptPubKey()`, `BRAddressIsValid()`, `BRAddressHash160()`

### app/src/main/jni/digibytewallet-core/BRAddress.h
- Struct typedef: `(anonymous)`
- Functions: `BRAddressHash()`, `BRAddressEq()`, `BRVarInt()`, `BRVarIntSet()`, `BRVarIntSize()`, `BRScriptElements()`, `BRScriptPushData()`, `BRAddressFromScriptPubKey()`, `BRAddressFromScriptSig()`, `BRAddressFromWitness()`, `BRAddressScriptPubKey()`, `BRAddressIsValid()`, `BRAddressHash160()`

### app/src/main/jni/digibytewallet-core/BRArray.h
- (no class/function exports detected; resource/config content)

### app/src/main/jni/digibytewallet-core/BRAssetData.c
- (no class/function exports detected; resource/config content)

### app/src/main/jni/digibytewallet-core/BRAssetData.h
- Struct typedef: `(anonymous)`

### app/src/main/jni/digibytewallet-core/BRBIP32Sequence.c
- Functions: `_CKDpriv()`, `_CKDpub()`, `BRBIP32MasterPubKey()`, `BRBIP32PubKey()`, `BRBIP32PrivKey()`, `BRBIP32PrivKeyPath()`, `BRBIP32vPrivKeyPath()`, `BRBIP32SerializeMasterPrivKey()`, `BRBIP32ParseMasterPrivKey()`, `BRBIP32SerializeMasterPubKey()`, `BRBIP32ParseMasterPubKey()`, `BRBIP32APIAuthKey()`, `BRBIP32BitIDKey()`

### app/src/main/jni/digibytewallet-core/BRBIP32Sequence.h
- Struct typedef: `(anonymous)`
- Functions: `BRBIP32MasterPubKey()`, `BRBIP32PubKey()`, `BRBIP32PrivKey()`, `BRBIP32PrivKeyList()`, `BRBIP32PrivKeyPath()`, `BRBIP32vPrivKeyPath()`, `BRBIP32SerializeMasterPrivKey()`, `BRBIP32ParseMasterPrivKey()`, `BRBIP32SerializeMasterPubKey()`, `BRBIP32ParseMasterPubKey()`, `BRBIP32APIAuthKey()`, `BRBIP32BitIDKey()`

### app/src/main/jni/digibytewallet-core/BRBIP38Key.c
- Functions: `_BRAES256ECBEncrypt()`, `_BRAES256ECBDecrypt()`, `_BRBIP38DerivePassfactor()`, `_BRBIP38DeriveKey()`, `BRBIP38KeyIsValid()`, `BRKeySetBIP38Key()`, `BRKeyBIP38ItermediateCode()`, `BRKeySetBIP38ItermediateCode()`, `BRKeyBIP38Key()`

### app/src/main/jni/digibytewallet-core/BRBIP38Key.h
- Functions: `BRBIP38KeyIsValid()`, `BRKeySetBIP38Key()`, `BRKeyBIP38ItermediateCode()`, `BRKeyBIP38ItermediateCodeLS()`, `BRKeySetBIP38ItermediateCode()`, `BRKeyBIP38Key()`

### app/src/main/jni/digibytewallet-core/BRBIP39Mnemonic.c
- Functions: `BRBIP39Encode()`, `BRBIP39Decode()`, `BRBIP39PhraseIsValid()`, `BRBIP39DeriveKey()`

### app/src/main/jni/digibytewallet-core/BRBIP39Mnemonic.h
- Functions: `BRBIP39Encode()`, `BRBIP39Decode()`, `BRBIP39PhraseIsValid()`, `BRBIP39DeriveKey()`

### app/src/main/jni/digibytewallet-core/BRBIP39WordsEn.h
- (no class/function exports detected; resource/config content)

### app/src/main/jni/digibytewallet-core/BRBase58.c
- Functions: `BRBase58Encode()`, `BRBase58Decode()`, `BRBase58CheckEncode()`, `BRBase58CheckDecode()`

### app/src/main/jni/digibytewallet-core/BRBase58.h
- Functions: `BRBase58Encode()`, `BRBase58Decode()`, `BRBase58CheckEncode()`, `BRBase58CheckDecode()`

### app/src/main/jni/digibytewallet-core/BRBech32.c
- Functions: `BRBech32Decode()`, `BRBech32Encode()`

### app/src/main/jni/digibytewallet-core/BRBech32.h
- Functions: `BRBech32Decode()`, `BRBech32Encode()`

### app/src/main/jni/digibytewallet-core/BRBloomFilter.c
- Functions: `BRBloomFilterSerialize()`, `BRBloomFilterContainsData()`, `BRBloomFilterInsertData()`, `BRBloomFilterFree()`

### app/src/main/jni/digibytewallet-core/BRBloomFilter.h
- Struct typedef: `(anonymous)`
- Functions: `BRBloomFilterSerialize()`, `BRBloomFilterContainsData()`, `BRBloomFilterInsertData()`, `BRBloomFilterFree()`

### app/src/main/jni/digibytewallet-core/BRChainParams.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `BRTestNetVerifyDifficulty()`

### app/src/main/jni/digibytewallet-core/BRCrypto.c
- Functions: `_BRSHA1Compress()`, `BRSHA1()`, `_BRSHA256Compress()`, `BRSHA224()`, `BRSHA256()`, `BRSHA256_2()`, `_BRSHA512Compress()`, `BRSHA384()`, `BRSHA512()`, `_BRRMDCompress()`, `BRRMD160()`, `BRHash160()`, `_BRSHA3Compress()`, `BRSHA3_256()`, `BRKeccak256()`, `_BRMD5Compress()`, `BRMD5()`, `BRMurmur3_32()`, `_BRPoly1305Compress()`, `BRPoly1305()` …

### app/src/main/jni/digibytewallet-core/BRCrypto.h
- Functions: `mem_clean()`, `_var_clean()`, `BRSHA1()`, `BRSHA256()`, `BRSHA224()`, `BRSHA256_2()`, `BRSHA384()`, `BRSHA512()`, `BRRMD160()`, `BRHash160()`, `BRSHA3_256()`, `BRKeccak256()`, `BRMD5()`, `BRMurmur3_32()`, `BRPoly1305()`, `BRChacha20()`, `BRChacha20Poly1305AEADEncrypt()`, `BRChacha20Poly1305AEADDecrypt()`, `BRScrypt()`, `BRSkein()` …

### app/src/main/jni/digibytewallet-core/BRDigiAsset.c
- Struct typedef: `(anonymous)`
- Functions: `BRTXContainsAsset()`, `BRContainsAsset()`, `BRTestProtocolTag()`, `BROutpointIsAsset()`, `BRTxOutputIsAsset()`

### app/src/main/jni/digibytewallet-core/BRDigiAsset.h
- Functions: `BRTXContainsAsset()`, `BRContainsAsset()`, `BROutpointIsAsset()`, `BRTxOutputIsAsset()`

### app/src/main/jni/digibytewallet-core/BRInt.h
- Functions: `UInt128Eq()`, `UInt160Eq()`, `UInt256Eq()`, `UInt512Eq()`, `UInt128IsZero()`, `UInt160IsZero()`, `UInt256IsZero()`, `UInt512IsZero()`, `UInt256Reverse()`, `UInt16SetBE()`, `UInt16SetLE()`, `UInt32SetBE()`, `UInt32SetLE()`, `UInt64SetBE()`, `UInt64SetLE()`, `UInt128Set()`, `UInt160Set()`, `UInt256Set()`, `UInt16GetBE()`, `UInt16GetLE()` …

### app/src/main/jni/digibytewallet-core/BRKey.c
- Functions: `_ctx_init()`, `BRSecp256k1ModAdd()`, `BRSecp256k1ModMul()`, `BRSecp256k1PointGen()`, `BRSecp256k1PointAdd()`, `BRSecp256k1PointMul()`, `BRPrivKeyIsValid()`, `BRKeySetSecret()`, `BRKeySetPrivKey()`, `BRKeySetPubKey()`, `BRKeyPrivKey()`, `BRKeyPubKey()`, `BRKeyHash160()`, `BRKeyAddress()`, `BRKeySegwitAddress()`, `BRKeySign()`, `BRKeyVerify()`, `BRKeyClean()`, `BRKeyCompactSign()`, `BRKeyRecoverPubKey()`

### app/src/main/jni/digibytewallet-core/BRKey.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `BRSecp256k1ModAdd()`, `BRSecp256k1ModMul()`, `BRSecp256k1PointGen()`, `BRSecp256k1PointAdd()`, `BRSecp256k1PointMul()`, `BRPrivKeyIsValid()`, `BRKeySetSecret()`, `BRKeySetPrivKey()`, `BRKeySetPubKey()`, `BRKeyPrivKey()`, `BRKeyPubKey()`, `BRKeyHash160()`, `BRKeyAddress()`, `BRKeySegwitAddress()`, `BRKeySign()`, `BRKeyVerify()`, `BRKeyClean()`, `BRKeyCompactSign()`, `BRKeyRecoverPubKey()`

### app/src/main/jni/digibytewallet-core/BRMerkleBlock.c
- Functions: `_ceil_log2()`, `BRMerkleBlockSerialize()`, `BRMerkleBlockTxHashes()`, `_BRMerkleBlockRootR()`, `BRMerkleBlockIsValid()`, `BRMerkleBlockContainsTxHash()`, `BRMerkleBlockVerifyDifficulty()`, `BRMerkleBlockFree()`

### app/src/main/jni/digibytewallet-core/BRMerkleBlock.h
- Struct typedef: `(anonymous)`
- Functions: `BRMerkleBlockHash()`, `BRMerkleBlockEq()`, `BRMerkleBlockSerialize()`, `BRMerkleBlockTxHashes()`, `BRMerkleBlockSetTxHashes()`, `BRMerkleBlockIsValid()`, `BRMerkleBlockContainsTxHash()`, `BRMerkleBlockVerifyDifficulty()`, `BRMerkleBlockFree()`

### app/src/main/jni/digibytewallet-core/BRPaymentProtocol.c
- Struct typedef: `(anonymous)`
- Functions: `_ProtoBufVarInt()`, `_ProtoBufSetVarInt()`, `_ProtoBufSetLenDelim()`, `_ProtoBufFixed()`, `_ProtoBufSetFixed()`, `_ProtoBufField()`, `_ProtoBufString()`, `_ProtoBufSetString()`, `_ProtoBufBytes()`, `_ProtoBufSetInt()`, `_ProtoBufUnknown()`, `_BRPaymentProtocolOutput()`, `_BRPaymentProtocolOutputParse()`, `_BRPaymentProtocolOutputSerialize()`, `_BRPaymentProtocolOutputFree()`, `BRPaymentProtocolDetailsSerialize()`, `BRPaymentProtocolDetailsFree()`, `BRPaymentProtocolRequestSerialize()`, `BRPaymentProtocolRequestCert()`, `BRPaymentProtocolRequestDigest()` …

### app/src/main/jni/digibytewallet-core/BRPaymentProtocol.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `BRPaymentProtocolDetailsSerialize()`, `BRPaymentProtocolDetailsFree()`, `BRPaymentProtocolRequestSerialize()`, `BRPaymentProtocolRequestCert()`, `BRPaymentProtocolRequestDigest()`, `BRPaymentProtocolRequestFree()`, `BRPaymentProtocolPaymentSerialize()`, `BRPaymentProtocolPaymentFree()`, `BRPaymentProtocolACKSerialize()`, `BRPaymentProtocolACKFree()`, `BRPaymentProtocolInvoiceRequestSerialize()`, `BRPaymentProtocolInvoiceRequestCert()`, `BRPaymentProtocolInvoiceRequestDigest()`, `BRPaymentProtocolInvoiceRequestFree()`, `BRPaymentProtocolMessageSerialize()`, `BRPaymentProtocolMessageFree()`, `BRPaymentProtocolEncryptedMessageSerialize()`, `BRPaymentProtocolEncryptedMessageVerify()`, `BRPaymentProtocolEncryptedMessageDecrypt()`, `BRPaymentProtocolEncryptedMessageFree()`

### app/src/main/jni/digibytewallet-core/BRPeer.c
- Struct typedef: `(anonymous)`
- Functions: `_BRPeerIsIPv4()`, `_BRPeerAddKnownTxHashes()`, `_BRPeerDidConnect()`, `_BRPeerAcceptVersionMessage()`, `_BRPeerAcceptVerackMessage()`, `_BRPeerAcceptAddrMessage()`, `_BRPeerAcceptInvMessage()`, `_BRPeerAcceptTxMessage()`, `_BRPeerAcceptHeadersMessage()`, `_BRPeerAcceptGetaddrMessage()`, `_BRPeerAcceptGetdataMessage()`, `_BRPeerAcceptNotfoundMessage()`, `_BRPeerAcceptPingMessage()`, `_BRPeerAcceptPongMessage()`, `_BRPeerAcceptMerkleblockMessage()`, `_BRPeerAcceptRejectMessage()`, `_BRPeerAcceptFeeFilterMessage()`, `_BRPeerAcceptMessage()`, `_BRPeerOpenSocket()`, `_dummyThreadCleanup()` …

### app/src/main/jni/digibytewallet-core/BRPeer.h
- Struct typedef: `(anonymous)`
- Functions: `BRPeerHash()`, `BRPeerEq()`, `BRPeerSetEarliestKeyTime()`, `BRPeerSetCurrentBlockHeight()`, `BRPeerConnectStatus()`, `BRPeerConnect()`, `BRPeerDisconnect()`, `BRPeerScheduleDisconnect()`, `BRPeerSetNeedsFilterUpdate()`, `BRPeerVersion()`, `BRPeerLastBlock()`, `BRPeerFeePerKb()`, `BRPeerPingTime()`, `BRPeerSendMessage()`, `BRPeerSendFilterload()`, `BRPeerSendGetheaders()`, `BRPeerSendGetblocks()`, `BRPeerSendInv()`, `BRPeerSendGetdata()`, `BRPeerSendGetaddr()` …

### app/src/main/jni/digibytewallet-core/BRPeerManager.c
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `_BRTxPeerListHasPeer()`, `_BRTxPeerListCount()`, `_BRTxPeerListAddPeer()`, `_BRTxPeerListRemovePeer()`, `_peerTimestampCompare()`, `_BRPrevBlockHash()`, `_BRPrevBlockEq()`, `_BRBlockHeightHash()`, `_BRBlockHeightEq()`, `BRPeerManagerSetStartBlock()`, `_BRPeerManagerPeerMisbehavin()`, `_BRPeerManagerSyncStopped()`, `_BRPeerManagerBlockLocators()`, `_setApplyFreeBlock()`, `_BRPeerManagerAddPeer()`, `_BRPeerManagerLoadBloomFilter()`, `_updateFilterRerequestDone()`, `_updateFilterLoadDone()`, `_updateFilterPingDone()`, `_BRPeerManagerUpdateFilter()` …

### app/src/main/jni/digibytewallet-core/BRPeerManager.h
- Functions: `BRPeerManagerNew()`, `BRPeerManagerNewEx()`, `BRPeerManagerSetFixedPeer()`, `BRPeerManagerSetStartBlock()`, `BRPeerManagerConnectStatus()`, `BRPeerManagerConnect()`, `BRPeerManagerDisconnect()`, `BRPeerManagerRescan()`, `BRPeerManagerEstimatedBlockHeight()`, `BRPeerManagerLastBlockHeight()`, `BRPeerManagerLastBlockTimestamp()`, `BRPeerManagerSyncProgress()`, `BRPeerManagerPeerCount()`, `BRPeerManagerRelayCount()`, `BRPeerManagerFree()`, `BPPeerManagerMainNetNewEx()`, `BPPeerManagerTestNetNewEx()`

### app/src/main/jni/digibytewallet-core/BRSet.c
- Functions: `_BRSetInit()`, `_BRSetGrow()`, `BRSetClear()`, `BRSetCount()`, `BRSetContains()`, `BRSetIntersects()`, `BRSetAll()`, `BRSetApply()`, `BRSetUnion()`, `BRSetMinus()`, `BRSetIntersect()`, `BRSetFree()`

### app/src/main/jni/digibytewallet-core/BRSet.h
- Functions: `BRSetClear()`, `BRSetCount()`, `BRSetContains()`, `BRSetIntersects()`, `BRSetAll()`, `BRSetUnion()`, `BRSetMinus()`, `BRSetIntersect()`, `BRSetFree()`

### app/src/main/jni/digibytewallet-core/BRTransaction.c
- Functions: `BRRand()`, `BRTxInputSetAddress()`, `BRTxInputSetScript()`, `BRTxInputSetSignature()`, `BRTxInputSetWitness()`, `_BRTxInputData()`, `BRTxOutputSetAddress()`, `BRTxOutputSetAmount()`, `BRTxOutputSetScript()`, `_BRTransactionOutputData()`, `_BRTransactionData()`, `BRTransactionSerialize()`, `BRTransactionAddOutput()`, `BRTransactionShuffleOutputs()`, `BRTransactionSize()`, `BRTransactionVSize()`, `BRTransactionStandardFee()`, `BRTransactionIsSigned()`, `BRTransactionSign()`, `BRTransactionIsStandard()` …

### app/src/main/jni/digibytewallet-core/BRTransaction.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `BRTransactionHash()`, `BRTransactionEq()`, `BRRand()`, `BRTxInputSetAddress()`, `BRTxInputSetScript()`, `BRTxInputSetSignature()`, `BRTxInputSetWitness()`, `BRTxOutputSetAddress()`, `BRTxOutputSetAmount()`, `BRTxOutputSetScript()`, `BRTransactionSerialize()`, `BRTransactionAddInput()`, `BRTransactionAddInputBefore()`, `BRTransactionAddOutput()`, `BRTransactionShuffleOutputs()`, `BRTransactionSize()`, `BRTransactionVSize()`, `BRTransactionStandardFee()`, `BRTransactionIsSigned()`, `BRTransactionSign()` …

### app/src/main/jni/digibytewallet-core/BRWallet.c
- Functions: `_txFee()`, `_txChainIndex()`, `_BRWalletTxIsAscending()`, `_BRWalletTxCompare()`, `_BRWalletInsertTx()`, `_BRWalletContainsTx()`, `_BRWalletUpdateBalance()`, `BRWalletUnusedAddrs()`, `BRWalletBalance()`, `BRWalletUTXOs()`, `BRWalletTransactions()`, `BRWalletTotalSent()`, `BRWalletTotalReceived()`, `BRWalletFeePerKb()`, `BRWalletSetFeePerKb()`, `BRWalletReceiveAddress()`, `BRWalletInternalChangeAddress()`, `BRWalletAllAddrs()`, `BRWalletContainsAddress()`, `BRWalletAddressIsUsed()` …

### app/src/main/jni/digibytewallet-core/BRWallet.h
- Struct typedef: `(anonymous)`
- Functions: `BRUTXOHash()`, `BRUTXOEq()`, `BRWalletUnusedAddrs()`, `BRWalletReceiveAddress()`, `BRWalletInternalChangeAddress()`, `BRWalletAllAddrs()`, `BRWalletContainsAddress()`, `BRWalletAddressIsUsed()`, `BRWalletTransactions()`, `BRWalletTxUnconfirmedBefore()`, `BRWalletBalance()`, `BRWalletTotalSent()`, `BRWalletTotalReceived()`, `BRWalletUTXOs()`, `BRWalletFeePerKb()`, `BRWalletSetFeePerKb()`, `BRWalletGetAddressPrivateKey()`, `BRWalletSignTransaction()`, `BRWalletContainsTransaction()`, `BRWalletRegisterTransaction()` …

### app/src/main/jni/digibytewallet-core/README.md
- Contents: `# breadwallet-core`; `SPV bitcoin C library`; `[getting started](https://github.com/breadwallet/breadwallet-core/wiki)`

### app/src/main/jni/digibytewallet-core/crypto/groestl.c
- Functions: `groestl_hash()`

### app/src/main/jni/digibytewallet-core/crypto/groestl.h
- Functions: `groestl_hash()`

### app/src/main/jni/digibytewallet-core/crypto/odocrypt.c
- Functions: `Rot()`, `Odocrypt_Unpack()`, `Odocrypt_PreMix()`, `Odocrypt_ApplyMaskedSwaps()`, `Odocrypt_ApplyWordShuffle()`, `Odocrypt_ApplyPboxRotations()`, `OdoCrypt_ApplyPbox()`, `OdoCrypt_Pack()`, `Odocrypt_ApplySboxes()`, `Odocrypt_ApplyRotations()`, `Odocrypt_ApplyRoundKey()`, `Odocrypt_Encrypt()`, `OdoRandom_NextInt()`, `OdoRandom_Next()`, `OdoRandom_NextLong()`, `OdoRandom_Permutation8()`, `OdoRandom_Permutation16()`, `OdoRandom_Permutation()`, `Odocrypt_Init()`, `Odocrypt_Hash()`

### app/src/main/jni/digibytewallet-core/crypto/odocrypt.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `Odocrypt_Hash()`, `Odocrypt_Encrypt()`, `Odocrypt_Init()`

### app/src/main/jni/digibytewallet-core/crypto/qubit.c
- Functions: `qubit_hash()`

### app/src/main/jni/digibytewallet-core/crypto/qubit.h
- Functions: `qubit_hash()`

### app/src/main/jni/digibytewallet-core/crypto/sha256.h
- Struct typedef: `SHA256Context`
- Struct typedef: `HMAC_SHA256Context`
- Functions: `be32dec()`, `be32enc()`, `le32dec()`, `le32enc()`, `be32enc_vect()`, `be32dec_vect()`, `SHA256_Transform()`, `SHA256_Init()`, `SHA256_Update()`, `SHA256_Pad()`, `SHA256_Final()`, `HMAC_SHA256_Init()`, `HMAC_SHA256_Update()`, `HMAC_SHA256_Final()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/BRKeccak-800-SnP.c
- Functions: `KeccakP800_StaticInitialize()`, `KeccakP800_InitializeRoundConstants()`, `KeccakP800_InitializeRhoOffsets()`, `LFSR86540()`, `KeccakP800_Initialize()`, `KeccakP800_AddByte()`, `KeccakP800_AddBytes()`, `KeccakP800_OverwriteBytes()`, `KeccakP800_OverwriteWithZeroes()`, `KeccakP800_Permute_Nrounds()`, `KeccakP800_Permute_12rounds()`, `KeccakP800_Permute_22rounds()`, `fromBytesToWords()`, `fromWordsToBytes()`, `KeccakP800OnWords()`, `KeccakP800Round()`, `theta()`, `rho()`, `pi()`, `chi()` …

### app/src/main/jni/digibytewallet-core/crypto/sha3/BRKeccak-800-SnP.h
- Functions: `KeccakP800_StaticInitialize()`, `KeccakP800_Initialize()`, `KeccakP800_AddByte()`, `KeccakP800_AddBytes()`, `KeccakP800_OverwriteBytes()`, `KeccakP800_OverwriteWithZeroes()`, `KeccakP800_Permute_12rounds()`, `KeccakP800_Permute_22rounds()`, `KeccakP800_ExtractBytes()`, `KeccakP800_ExtractAndAddBytes()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/aes_helper.c
- (no class/function exports detected; resource/config content)

### app/src/main/jni/digibytewallet-core/crypto/sha3/blake.c
- Functions: `blake32()`, `blake64()`, `sph_blake224_init()`, `sph_blake224()`, `sph_blake224_close()`, `sph_blake224_addbits_and_close()`, `sph_blake256_init()`, `sph_blake256()`, `sph_blake256_close()`, `sph_blake256_addbits_and_close()`, `sph_blake384_init()`, `sph_blake384()`, `sph_blake384_close()`, `sph_blake384_addbits_and_close()`, `sph_blake512_init()`, `sph_blake512()`, `sph_blake512_close()`, `sph_blake512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/bmw.c
- Functions: `compress_small()`, `bmw32_init()`, `bmw32()`, `compress_big()`, `bmw64_init()`, `bmw64()`, `sph_bmw224_init()`, `sph_bmw224()`, `sph_bmw224_close()`, `sph_bmw224_addbits_and_close()`, `sph_bmw256_init()`, `sph_bmw256()`, `sph_bmw256_close()`, `sph_bmw256_addbits_and_close()`, `sph_bmw384_init()`, `sph_bmw384()`, `sph_bmw384_close()`, `sph_bmw384_addbits_and_close()`, `sph_bmw512_init()`, `sph_bmw512()` …

### app/src/main/jni/digibytewallet-core/crypto/sha3/brg_endian.h
- (no class/function exports detected; resource/config content)

### app/src/main/jni/digibytewallet-core/crypto/sha3/cubehash.c
- Functions: `cubehash_init()`, `cubehash_core()`, `sph_cubehash224_init()`, `sph_cubehash224()`, `sph_cubehash224_close()`, `sph_cubehash224_addbits_and_close()`, `sph_cubehash256_init()`, `sph_cubehash256()`, `sph_cubehash256_close()`, `sph_cubehash256_addbits_and_close()`, `sph_cubehash384_init()`, `sph_cubehash384()`, `sph_cubehash384_close()`, `sph_cubehash384_addbits_and_close()`, `sph_cubehash512_init()`, `sph_cubehash512()`, `sph_cubehash512_close()`, `sph_cubehash512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/groestl.c
- Functions: `groestl_small_init()`, `groestl_small_core()`, `groestl_big_init()`, `groestl_big_core()`, `sph_groestl224_init()`, `sph_groestl224()`, `sph_groestl224_close()`, `sph_groestl224_addbits_and_close()`, `sph_groestl256_init()`, `sph_groestl256()`, `sph_groestl256_close()`, `sph_groestl256_addbits_and_close()`, `sph_groestl384_init()`, `sph_groestl384()`, `sph_groestl384_close()`, `sph_groestl384_addbits_and_close()`, `sph_groestl512_init()`, `sph_groestl512()`, `sph_groestl512_close()`, `sph_groestl512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/hashblock.h
- Functions: `Hash9()`, `Hash6()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/keccak.c
- Functions: `keccak_init()`, `keccak_core()`, `sph_keccak224_init()`, `sph_keccak224()`, `sph_keccak224_close()`, `sph_keccak224_addbits_and_close()`, `sph_keccak256_init()`, `sph_keccak256()`, `sph_keccak256_close()`, `sph_keccak256_addbits_and_close()`, `sph_keccak384_init()`, `sph_keccak384()`, `sph_keccak384_close()`, `sph_keccak384_addbits_and_close()`, `sph_keccak512_init()`, `sph_keccak512()`, `sph_keccak512_close()`, `sph_keccak512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/skein.c
- Functions: `skein_small_init()`, `skein_big_init()`, `skein_small_core()`, `skein_big_core()`, `sph_skein224_init()`, `sph_skein224()`, `sph_skein224_close()`, `sph_skein224_addbits_and_close()`, `sph_skein256_init()`, `sph_skein256()`, `sph_skein256_close()`, `sph_skein256_addbits_and_close()`, `sph_skein384_init()`, `sph_skein384()`, `sph_skein384_close()`, `sph_skein384_addbits_and_close()`, `sph_skein512_init()`, `sph_skein512()`, `sph_skein512_close()`, `sph_skein512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_blake.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `sph_blake224_init()`, `sph_blake224()`, `sph_blake224_close()`, `sph_blake224_addbits_and_close()`, `sph_blake256_init()`, `sph_blake256()`, `sph_blake256_close()`, `sph_blake256_addbits_and_close()`, `sph_blake384_init()`, `sph_blake384()`, `sph_blake384_close()`, `sph_blake384_addbits_and_close()`, `sph_blake512_init()`, `sph_blake512()`, `sph_blake512_close()`, `sph_blake512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_bmw.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `sph_bmw224_init()`, `sph_bmw224()`, `sph_bmw224_close()`, `sph_bmw224_addbits_and_close()`, `sph_bmw256_init()`, `sph_bmw256()`, `sph_bmw256_close()`, `sph_bmw256_addbits_and_close()`, `sph_bmw384_init()`, `sph_bmw384()`, `sph_bmw384_close()`, `sph_bmw384_addbits_and_close()`, `sph_bmw512_init()`, `sph_bmw512()`, `sph_bmw512_close()`, `sph_bmw512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_cubehash.h
- Struct typedef: `(anonymous)`
- Functions: `sph_cubehash224_init()`, `sph_cubehash224()`, `sph_cubehash224_close()`, `sph_cubehash224_addbits_and_close()`, `sph_cubehash256_init()`, `sph_cubehash256()`, `sph_cubehash256_close()`, `sph_cubehash256_addbits_and_close()`, `sph_cubehash384_init()`, `sph_cubehash384()`, `sph_cubehash384_close()`, `sph_cubehash384_addbits_and_close()`, `sph_cubehash512_init()`, `sph_cubehash512()`, `sph_cubehash512_close()`, `sph_cubehash512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_echo.c
- Functions: `mix_column()`, `echo_small_init()`, `echo_big_init()`, `echo_small_compress()`, `echo_big_compress()`, `sph_echo224_init()`, `sph_echo224()`, `sph_echo224_close()`, `sph_echo224_addbits_and_close()`, `sph_echo256_init()`, `sph_echo256()`, `sph_echo256_close()`, `sph_echo256_addbits_and_close()`, `sph_echo384_init()`, `sph_echo384()`, `sph_echo384_close()`, `sph_echo384_addbits_and_close()`, `sph_echo512_init()`, `sph_echo512()`, `sph_echo512_close()` …

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_echo.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `sph_echo224_init()`, `sph_echo224()`, `sph_echo224_close()`, `sph_echo224_addbits_and_close()`, `sph_echo256_init()`, `sph_echo256()`, `sph_echo256_close()`, `sph_echo256_addbits_and_close()`, `sph_echo384_init()`, `sph_echo384()`, `sph_echo384_close()`, `sph_echo384_addbits_and_close()`, `sph_echo512_init()`, `sph_echo512()`, `sph_echo512_close()`, `sph_echo512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_groestl.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `sph_groestl224_init()`, `sph_groestl224()`, `sph_groestl224_close()`, `sph_groestl224_addbits_and_close()`, `sph_groestl256_init()`, `sph_groestl256()`, `sph_groestl256_close()`, `sph_groestl256_addbits_and_close()`, `sph_groestl384_init()`, `sph_groestl384()`, `sph_groestl384_close()`, `sph_groestl384_addbits_and_close()`, `sph_groestl512_init()`, `sph_groestl512()`, `sph_groestl512_close()`, `sph_groestl512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_keccak.h
- Struct typedef: `(anonymous)`
- Functions: `sph_keccak224_init()`, `sph_keccak224()`, `sph_keccak224_close()`, `sph_keccak224_addbits_and_close()`, `sph_keccak256_init()`, `sph_keccak256()`, `sph_keccak256_close()`, `sph_keccak256_addbits_and_close()`, `sph_keccak384_init()`, `sph_keccak384()`, `sph_keccak384_close()`, `sph_keccak384_addbits_and_close()`, `sph_keccak512_init()`, `sph_keccak512()`, `sph_keccak512_close()`, `sph_keccak512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_luffa.c
- Functions: `luffa3()`, `luffa4()`, `luffa4_close()`, `luffa5()`, `luffa5_close()`, `sph_luffa224_init()`, `sph_luffa224()`, `sph_luffa224_close()`, `sph_luffa224_addbits_and_close()`, `sph_luffa256_init()`, `sph_luffa256()`, `sph_luffa256_close()`, `sph_luffa256_addbits_and_close()`, `sph_luffa384_init()`, `sph_luffa384()`, `sph_luffa384_close()`, `sph_luffa384_addbits_and_close()`, `sph_luffa512_init()`, `sph_luffa512()`, `sph_luffa512_close()` …

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_luffa.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `sph_luffa224_init()`, `sph_luffa224()`, `sph_luffa224_close()`, `sph_luffa224_addbits_and_close()`, `sph_luffa256_init()`, `sph_luffa256()`, `sph_luffa256_close()`, `sph_luffa256_addbits_and_close()`, `sph_luffa384_init()`, `sph_luffa384()`, `sph_luffa384_close()`, `sph_luffa384_addbits_and_close()`, `sph_luffa512_init()`, `sph_luffa512()`, `sph_luffa512_close()`, `sph_luffa512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_shavite.c
- Functions: `c256()`, `c512()`, `shavite_small_init()`, `shavite_small_core()`, `shavite_big_init()`, `shavite_big_core()`, `sph_shavite224_init()`, `sph_shavite224()`, `sph_shavite224_close()`, `sph_shavite224_addbits_and_close()`, `sph_shavite256_init()`, `sph_shavite256()`, `sph_shavite256_close()`, `sph_shavite256_addbits_and_close()`, `sph_shavite384_init()`, `sph_shavite384()`, `sph_shavite384_close()`, `sph_shavite384_addbits_and_close()`, `sph_shavite512_init()`, `sph_shavite512()` …

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_shavite.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `sph_shavite224_init()`, `sph_shavite224()`, `sph_shavite224_close()`, `sph_shavite224_addbits_and_close()`, `sph_shavite256_init()`, `sph_shavite256()`, `sph_shavite256_close()`, `sph_shavite256_addbits_and_close()`, `sph_shavite384_init()`, `sph_shavite384()`, `sph_shavite384_close()`, `sph_shavite384_addbits_and_close()`, `sph_shavite512_init()`, `sph_shavite512()`, `sph_shavite512_close()`, `sph_shavite512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_simd.c
- Functions: `fft32()`, `fft64()`, `one_round_small()`, `compress_small()`, `one_round_big()`, `compress_big()`, `init_small()`, `init_big()`, `update_small()`, `update_big()`, `finalize_small()`, `finalize_big()`, `sph_simd224_init()`, `sph_simd224()`, `sph_simd224_close()`, `sph_simd224_addbits_and_close()`, `sph_simd256_init()`, `sph_simd256()`, `sph_simd256_close()`, `sph_simd256_addbits_and_close()` …

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_simd.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `sph_simd224_init()`, `sph_simd224()`, `sph_simd224_close()`, `sph_simd224_addbits_and_close()`, `sph_simd256_init()`, `sph_simd256()`, `sph_simd256_close()`, `sph_simd256_addbits_and_close()`, `sph_simd384_init()`, `sph_simd384()`, `sph_simd384_close()`, `sph_simd384_addbits_and_close()`, `sph_simd512_init()`, `sph_simd512()`, `sph_simd512_close()`, `sph_simd512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_skein.h
- Struct typedef: `(anonymous)`
- Functions: `sph_skein224_init()`, `sph_skein224()`, `sph_skein224_close()`, `sph_skein224_addbits_and_close()`, `sph_skein256_init()`, `sph_skein256()`, `sph_skein256_close()`, `sph_skein256_addbits_and_close()`, `sph_skein384_init()`, `sph_skein384()`, `sph_skein384_close()`, `sph_skein384_addbits_and_close()`, `sph_skein512_init()`, `sph_skein512()`, `sph_skein512_close()`, `sph_skein512_addbits_and_close()`

### app/src/main/jni/digibytewallet-core/crypto/sha3/sph_types.h
- Functions: `sph_bswap32()`, `sph_bswap64()`, `sph_enc16be()`, `sph_dec16be()`, `sph_enc16le()`, `sph_dec16le()`, `sph_enc32be()`, `sph_enc32be_aligned()`, `sph_dec32be()`, `sph_dec32be_aligned()`, `sph_enc32le()`, `sph_enc32le_aligned()`, `sph_dec32le()`, `sph_dec32le_aligned()`, `sph_enc64be()`, `sph_enc64be_aligned()`, `sph_dec64be()`, `sph_dec64be_aligned()`, `sph_enc64le()`, `sph_enc64le_aligned()` …

### app/src/main/jni/digibytewallet-core/crypto/skein.c
- Functions: `skein_hash()`

### app/src/main/jni/digibytewallet-core/crypto/skein.h
- Functions: `skein_hash()`

### app/src/main/jni/digibytewallet-core/maketest.sh
- Contents: `#!/bin/sh`; `gcc -o /tmp/test -I secp256k1/ *.c crypto/*.c crypto/sha3/*.c && /tmp/test`

### app/src/main/jni/digibytewallet-core/secp256k1/.travis.yml
- Contents: `language: c`; `sudo: false`; `addons:`

### app/src/main/jni/digibytewallet-core/secp256k1/README.md
- Contents: `libsecp256k1`; `============`; `[![Build Status](https://travis-ci.org/bitcoin-core/secp256k1.svg?branch=master)`

### app/src/main/jni/digibytewallet-core/secp256k1/autogen.sh
- Contents: `#!/bin/sh`; `set -e`; `autoreconf -if --warnings=all`

### app/src/main/jni/digibytewallet-core/secp256k1/contrib/lax_der_parsing.c
- Functions: `ecdsa_signature_parse_der_lax()`

### app/src/main/jni/digibytewallet-core/secp256k1/contrib/lax_der_parsing.h
- (no class/function exports detected; resource/config content)

### app/src/main/jni/digibytewallet-core/secp256k1/contrib/lax_der_privatekey_parsing.c
- Functions: `ec_privkey_import_der()`, `ec_privkey_export_der()`

### app/src/main/jni/digibytewallet-core/secp256k1/contrib/lax_der_privatekey_parsing.h
- (no class/function exports detected; resource/config content)

### app/src/main/jni/digibytewallet-core/secp256k1/include/secp256k1.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `secp256k1_context_destroy()`, `secp256k1_scratch_space_destroy()`

### app/src/main/jni/digibytewallet-core/secp256k1/include/secp256k1_ecdh.h
- (no class/function exports detected; resource/config content)

### app/src/main/jni/digibytewallet-core/secp256k1/include/secp256k1_recovery.h
- Struct typedef: `(anonymous)`

### app/src/main/jni/digibytewallet-core/secp256k1/src/basic-config.h
- (no class/function exports detected; resource/config content)

### app/src/main/jni/digibytewallet-core/secp256k1/src/bench.h
- Functions: `gettimedouble()`, `print_number()`, `run_benchmark()`, `have_flag()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/bench_ecdh.c
- Struct typedef: `(anonymous)`
- Functions: `bench_ecdh_setup()`, `bench_ecdh()`, `main()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/bench_ecmult.c
- Struct typedef: `(anonymous)`
- Functions: `bench_callback()`, `bench_ecmult()`, `bench_ecmult_setup()`, `bench_ecmult_teardown()`, `generate_scalar()`, `run_test()`, `main()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/bench_internal.c
- Struct typedef: `(anonymous)`
- Functions: `bench_setup()`, `bench_scalar_add()`, `bench_scalar_negate()`, `bench_scalar_sqr()`, `bench_scalar_mul()`, `bench_scalar_split()`, `bench_scalar_inverse()`, `bench_scalar_inverse_var()`, `bench_field_normalize()`, `bench_field_normalize_weak()`, `bench_field_mul()`, `bench_field_sqr()`, `bench_field_inverse()`, `bench_field_inverse_var()`, `bench_field_sqrt()`, `bench_group_double_var()`, `bench_group_add_var()`, `bench_group_add_affine()`, `bench_group_add_affine_var()`, `bench_group_jacobi_var()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/bench_recover.c
- Struct typedef: `(anonymous)`
- Functions: `bench_recover()`, `bench_recover_setup()`, `main()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/bench_sign.c
- Struct typedef: `(anonymous)`
- Functions: `bench_sign_setup()`, `bench_sign_run()`, `main()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/bench_verify.c
- Struct typedef: `(anonymous)`
- Functions: `benchmark_verify()`, `benchmark_verify_openssl()`, `main()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/ecdsa.h
- Functions: `secp256k1_ecdsa_sig_parse()`, `secp256k1_ecdsa_sig_serialize()`, `secp256k1_ecdsa_sig_verify()`, `secp256k1_ecdsa_sig_sign()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/ecdsa_impl.h
- Functions: `secp256k1_der_read_len()`, `secp256k1_der_parse_integer()`, `secp256k1_ecdsa_sig_parse()`, `secp256k1_ecdsa_sig_serialize()`, `secp256k1_ecdsa_sig_verify()`, `secp256k1_ecdsa_sig_sign()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/eckey.h
- Functions: `secp256k1_eckey_pubkey_parse()`, `secp256k1_eckey_pubkey_serialize()`, `secp256k1_eckey_privkey_tweak_add()`, `secp256k1_eckey_pubkey_tweak_add()`, `secp256k1_eckey_privkey_tweak_mul()`, `secp256k1_eckey_pubkey_tweak_mul()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/eckey_impl.h
- Functions: `secp256k1_eckey_pubkey_parse()`, `secp256k1_eckey_pubkey_serialize()`, `secp256k1_eckey_privkey_tweak_add()`, `secp256k1_eckey_pubkey_tweak_add()`, `secp256k1_eckey_privkey_tweak_mul()`, `secp256k1_eckey_pubkey_tweak_mul()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/ecmult.h
- Struct typedef: `(anonymous)`
- Functions: `secp256k1_ecmult_context_init()`, `secp256k1_ecmult_context_build()`, `secp256k1_ecmult_context_clone()`, `secp256k1_ecmult_context_clear()`, `secp256k1_ecmult_context_is_built()`, `secp256k1_ecmult()`, `secp256k1_ecmult_multi_var()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/ecmult_const.h
- Functions: `secp256k1_ecmult_const()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/ecmult_const_impl.h
- Functions: `secp256k1_wnaf_const()`, `secp256k1_ecmult_const()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/ecmult_gen.h
- Struct typedef: `(anonymous)`
- Functions: `secp256k1_ecmult_gen_context_init()`, `secp256k1_ecmult_gen_context_build()`, `secp256k1_ecmult_gen_context_clone()`, `secp256k1_ecmult_gen_context_clear()`, `secp256k1_ecmult_gen_context_is_built()`, `secp256k1_ecmult_gen()`, `secp256k1_ecmult_gen_blind()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/ecmult_gen_impl.h
- Functions: `secp256k1_ecmult_gen_context_init()`, `secp256k1_ecmult_gen_context_build()`, `secp256k1_ecmult_gen_context_is_built()`, `secp256k1_ecmult_gen_context_clear()`, `secp256k1_ecmult_gen()`, `secp256k1_ecmult_gen_blind()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/ecmult_impl.h
- Functions: `secp256k1_ecmult_odd_multiples_table()`, `secp256k1_ecmult_odd_multiples_table_globalz_windowa()`, `secp256k1_ecmult_odd_multiples_table_storage_var()`, `secp256k1_ecmult_context_init()`, `secp256k1_ecmult_context_build()`, `secp256k1_ecmult_context_is_built()`, `secp256k1_ecmult_context_clear()`, `secp256k1_ecmult_wnaf()`, `secp256k1_ecmult_strauss_wnaf()`, `secp256k1_ecmult()`, `secp256k1_strauss_scratch_size()`, `secp256k1_ecmult_strauss_batch()`, `secp256k1_ecmult_strauss_batch_single()`, `secp256k1_strauss_max_points()`, `secp256k1_wnaf_fixed()`, `secp256k1_ecmult_pippenger_wnaf()`, `secp256k1_pippenger_bucket_window()`, `secp256k1_pippenger_bucket_window_inv()`, `secp256k1_ecmult_endo_split()`, `secp256k1_pippenger_scratch_size()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/field.h
- Functions: `secp256k1_fe_normalize()`, `secp256k1_fe_normalize_weak()`, `secp256k1_fe_normalize_var()`, `secp256k1_fe_normalizes_to_zero()`, `secp256k1_fe_normalizes_to_zero_var()`, `secp256k1_fe_set_int()`, `secp256k1_fe_clear()`, `secp256k1_fe_is_zero()`, `secp256k1_fe_is_odd()`, `secp256k1_fe_equal()`, `secp256k1_fe_equal_var()`, `secp256k1_fe_cmp_var()`, `secp256k1_fe_set_b32()`, `secp256k1_fe_get_b32()`, `secp256k1_fe_negate()`, `secp256k1_fe_mul_int()`, `secp256k1_fe_add()`, `secp256k1_fe_mul()`, `secp256k1_fe_sqr()`, `secp256k1_fe_sqrt()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/field_10x26.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`

### app/src/main/jni/digibytewallet-core/secp256k1/src/field_10x26_impl.h
- Functions: `secp256k1_fe_verify()`, `secp256k1_fe_normalize()`, `secp256k1_fe_normalize_weak()`, `secp256k1_fe_normalize_var()`, `secp256k1_fe_normalizes_to_zero()`, `secp256k1_fe_normalizes_to_zero_var()`, `secp256k1_fe_set_int()`, `secp256k1_fe_is_zero()`, `secp256k1_fe_is_odd()`, `secp256k1_fe_clear()`, `secp256k1_fe_cmp_var()`, `secp256k1_fe_set_b32()`, `secp256k1_fe_get_b32()`, `secp256k1_fe_negate()`, `secp256k1_fe_mul_int()`, `secp256k1_fe_add()`, `secp256k1_fe_mul_inner()`, `secp256k1_fe_sqr_inner()`, `secp256k1_fe_mul()`, `secp256k1_fe_sqr()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/field_5x52.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`

### app/src/main/jni/digibytewallet-core/secp256k1/src/field_5x52_asm_impl.h
- Functions: `secp256k1_fe_mul_inner()`, `secp256k1_fe_sqr_inner()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/field_5x52_impl.h
- Functions: `secp256k1_fe_verify()`, `secp256k1_fe_normalize()`, `secp256k1_fe_normalize_weak()`, `secp256k1_fe_normalize_var()`, `secp256k1_fe_normalizes_to_zero()`, `secp256k1_fe_normalizes_to_zero_var()`, `secp256k1_fe_set_int()`, `secp256k1_fe_is_zero()`, `secp256k1_fe_is_odd()`, `secp256k1_fe_clear()`, `secp256k1_fe_cmp_var()`, `secp256k1_fe_set_b32()`, `secp256k1_fe_get_b32()`, `secp256k1_fe_negate()`, `secp256k1_fe_mul_int()`, `secp256k1_fe_add()`, `secp256k1_fe_mul()`, `secp256k1_fe_sqr()`, `secp256k1_fe_cmov()`, `secp256k1_fe_storage_cmov()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/field_5x52_int128_impl.h
- Functions: `secp256k1_fe_mul_inner()`, `secp256k1_fe_sqr_inner()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/field_impl.h
- Functions: `secp256k1_fe_equal()`, `secp256k1_fe_equal_var()`, `secp256k1_fe_sqrt()`, `secp256k1_fe_inv()`, `secp256k1_fe_inv_var()`, `secp256k1_fe_inv_all_var()`, `secp256k1_fe_is_quad_var()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/gen_context.c
- Functions: `default_error_callback_fn()`, `main()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/group.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `secp256k1_ge_set_xy()`, `secp256k1_ge_set_xquad()`, `secp256k1_ge_set_xo_var()`, `secp256k1_ge_is_infinity()`, `secp256k1_ge_is_valid_var()`, `secp256k1_ge_neg()`, `secp256k1_ge_set_gej()`, `secp256k1_ge_set_all_gej_var()`, `secp256k1_ge_set_table_gej_var()`, `secp256k1_ge_globalz_set_table_gej()`, `secp256k1_ge_set_infinity()`, `secp256k1_gej_set_infinity()`, `secp256k1_gej_set_ge()`, `secp256k1_gej_eq_x_var()`, `secp256k1_gej_neg()`, `secp256k1_gej_is_infinity()`, `secp256k1_gej_has_quad_y_var()`, `secp256k1_gej_double_nonzero()`, `secp256k1_gej_double_var()`, `secp256k1_gej_add_var()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/group_impl.h
- Functions: `secp256k1_ge_set_gej_zinv()`, `secp256k1_ge_set_xy()`, `secp256k1_ge_is_infinity()`, `secp256k1_ge_neg()`, `secp256k1_ge_set_gej()`, `secp256k1_ge_set_gej_var()`, `secp256k1_ge_set_all_gej_var()`, `secp256k1_ge_set_table_gej_var()`, `secp256k1_ge_globalz_set_table_gej()`, `secp256k1_gej_set_infinity()`, `secp256k1_ge_set_infinity()`, `secp256k1_gej_clear()`, `secp256k1_ge_clear()`, `secp256k1_ge_set_xquad()`, `secp256k1_ge_set_xo_var()`, `secp256k1_gej_set_ge()`, `secp256k1_gej_eq_x_var()`, `secp256k1_gej_neg()`, `secp256k1_gej_is_infinity()`, `secp256k1_gej_is_valid_var()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/hash.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `secp256k1_sha256_initialize()`, `secp256k1_sha256_write()`, `secp256k1_sha256_finalize()`, `secp256k1_hmac_sha256_initialize()`, `secp256k1_hmac_sha256_write()`, `secp256k1_hmac_sha256_finalize()`, `secp256k1_rfc6979_hmac_sha256_initialize()`, `secp256k1_rfc6979_hmac_sha256_generate()`, `secp256k1_rfc6979_hmac_sha256_finalize()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/hash_impl.h
- Functions: `secp256k1_sha256_initialize()`, `secp256k1_sha256_transform()`, `secp256k1_sha256_write()`, `secp256k1_sha256_finalize()`, `secp256k1_hmac_sha256_initialize()`, `secp256k1_hmac_sha256_write()`, `secp256k1_hmac_sha256_finalize()`, `secp256k1_rfc6979_hmac_sha256_initialize()`, `secp256k1_rfc6979_hmac_sha256_generate()`, `secp256k1_rfc6979_hmac_sha256_finalize()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/java/org/bitcoin/NativeSecp256k1.java
- Package: `org.bitcoin`
- Class: `holds`
- Class: `NativeSecp256k1`
- Methods: `undefined()`, `verify()`, `secp256k1_ecdsa_verify()`, `sign()`, `secKeyVerify()`, `secp256k1_ec_seckey_verify()`, `computePubkey()`, `cleanup()`, `cloneContext()`, `secp256k1_ctx_clone()`, `privKeyTweakMul()`, `privKeyTweakAdd()`, `pubKeyTweakAdd()`, `pubKeyTweakMul()`, `createECDHSecret()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/java/org/bitcoin/NativeSecp256k1Test.java
- Package: `org.bitcoin`
- Class: `holds`
- Class: `NativeSecp256k1Test`
- Methods: `verify()`, `testVerifyPos()`, `testVerifyNeg()`, `testSecKeyVerifyPos()`, `testSecKeyVerifyNeg()`, `create()`, `testPubKeyCreatePos()`, `testPubKeyCreateNeg()`, `sign()`, `testSignPos()`, `testSignNeg()`, `testPrivKeyTweakAdd_1()`, `testPrivKeyTweakMul_1()`, `testPrivKeyTweakAdd_2()`, `testPrivKeyTweakMul_2()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/java/org/bitcoin/NativeSecp256k1Util.java
- Package: `org.bitcoin`
- Class: `NativeSecp256k1Util`
- Class: `AssertFailException`
- Methods: `assertEquals()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/java/org/bitcoin/Secp256k1Context.java
- Package: `org.bitcoin`
- Class: `holds`
- Class: `Secp256k1Context`
- Methods: `isEnabled()`, `getContext()`, `secp256k1_init_context()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/java/org_bitcoin_NativeSecp256k1.c
- Functions: `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ctx_1clone()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1context_1randomize()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1destroy_1context()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdsa_1verify()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdsa_1sign()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ec_1seckey_1verify()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ec_1pubkey_1create()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1privkey_1tweak_1add()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1privkey_1tweak_1mul()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1pubkey_1tweak_1add()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1pubkey_1tweak_1mul()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdsa_1pubkey_1combine()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdh()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/java/org_bitcoin_NativeSecp256k1.h
- Functions: `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ctx_1clone()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1context_1randomize()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1privkey_1tweak_1add()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1privkey_1tweak_1mul()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1pubkey_1tweak_1add()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1pubkey_1tweak_1mul()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1destroy_1context()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdsa_1verify()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdsa_1sign()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ec_1seckey_1verify()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ec_1pubkey_1create()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ec_1pubkey_1parse()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdh()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/java/org_bitcoin_Secp256k1Context.c
- Functions: `Java_org_bitcoin_Secp256k1Context_secp256k1_1init_1context()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/java/org_bitcoin_Secp256k1Context.h
- Functions: `Java_org_bitcoin_Secp256k1Context_secp256k1_1init_1context()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/modules/ecdh/main_impl.h
- Functions: `secp256k1_ecdh()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/modules/ecdh/tests_impl.h
- Functions: `test_ecdh_api()`, `test_ecdh_generator_basepoint()`, `test_bad_scalar()`, `run_ecdh_tests()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/modules/recovery/main_impl.h
- Functions: `secp256k1_ecdsa_recoverable_signature_load()`, `secp256k1_ecdsa_recoverable_signature_save()`, `secp256k1_ecdsa_recoverable_signature_parse_compact()`, `secp256k1_ecdsa_recoverable_signature_serialize_compact()`, `secp256k1_ecdsa_recoverable_signature_convert()`, `secp256k1_ecdsa_sig_recover()`, `secp256k1_ecdsa_sign_recoverable()`, `secp256k1_ecdsa_recover()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/modules/recovery/tests_impl.h
- Functions: `recovery_test_nonce_function()`, `test_ecdsa_recovery_api()`, `test_ecdsa_recovery_end_to_end()`, `test_ecdsa_recovery_edge_cases()`, `run_recovery_tests()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/num.h
- Functions: `secp256k1_num_copy()`, `secp256k1_num_get_bin()`, `secp256k1_num_set_bin()`, `secp256k1_num_mod_inverse()`, `secp256k1_num_jacobi()`, `secp256k1_num_cmp()`, `secp256k1_num_eq()`, `secp256k1_num_add()`, `secp256k1_num_sub()`, `secp256k1_num_mul()`, `secp256k1_num_mod()`, `secp256k1_num_shift()`, `secp256k1_num_is_zero()`, `secp256k1_num_is_one()`, `secp256k1_num_is_neg()`, `secp256k1_num_negate()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/num_gmp.h
- Struct typedef: `(anonymous)`

### app/src/main/jni/digibytewallet-core/secp256k1/src/num_gmp_impl.h
- Functions: `secp256k1_num_sanity()`, `secp256k1_num_copy()`, `secp256k1_num_get_bin()`, `secp256k1_num_set_bin()`, `secp256k1_num_add_abs()`, `secp256k1_num_sub_abs()`, `secp256k1_num_mod()`, `secp256k1_num_mod_inverse()`, `secp256k1_num_jacobi()`, `secp256k1_num_is_one()`, `secp256k1_num_is_zero()`, `secp256k1_num_is_neg()`, `secp256k1_num_cmp()`, `secp256k1_num_eq()`, `secp256k1_num_subadd()`, `secp256k1_num_add()`, `secp256k1_num_sub()`, `secp256k1_num_mul()`, `secp256k1_num_shift()`, `secp256k1_num_negate()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/num_impl.h
- (no class/function exports detected; resource/config content)

### app/src/main/jni/digibytewallet-core/secp256k1/src/scalar.h
- Functions: `secp256k1_scalar_clear()`, `secp256k1_scalar_get_bits()`, `secp256k1_scalar_get_bits_var()`, `secp256k1_scalar_set_b32()`, `secp256k1_scalar_set_int()`, `secp256k1_scalar_get_b32()`, `secp256k1_scalar_add()`, `secp256k1_scalar_cadd_bit()`, `secp256k1_scalar_mul()`, `secp256k1_scalar_shr_int()`, `secp256k1_scalar_sqr()`, `secp256k1_scalar_inverse()`, `secp256k1_scalar_inverse_var()`, `secp256k1_scalar_negate()`, `secp256k1_scalar_is_zero()`, `secp256k1_scalar_is_one()`, `secp256k1_scalar_is_even()`, `secp256k1_scalar_is_high()`, `secp256k1_scalar_cond_negate()`, `secp256k1_scalar_get_num()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/scalar_4x64.h
- Struct typedef: `(anonymous)`

### app/src/main/jni/digibytewallet-core/secp256k1/src/scalar_4x64_impl.h
- Functions: `secp256k1_scalar_clear()`, `secp256k1_scalar_set_int()`, `secp256k1_scalar_get_bits()`, `secp256k1_scalar_get_bits_var()`, `secp256k1_scalar_check_overflow()`, `secp256k1_scalar_reduce()`, `secp256k1_scalar_add()`, `secp256k1_scalar_cadd_bit()`, `secp256k1_scalar_set_b32()`, `secp256k1_scalar_get_b32()`, `secp256k1_scalar_is_zero()`, `secp256k1_scalar_negate()`, `secp256k1_scalar_is_one()`, `secp256k1_scalar_is_high()`, `secp256k1_scalar_cond_negate()`, `secp256k1_scalar_reduce_512()`, `secp256k1_scalar_mul_512()`, `secp256k1_scalar_sqr_512()`, `secp256k1_scalar_mul()`, `secp256k1_scalar_shr_int()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/scalar_8x32.h
- Struct typedef: `(anonymous)`

### app/src/main/jni/digibytewallet-core/secp256k1/src/scalar_8x32_impl.h
- Functions: `secp256k1_scalar_clear()`, `secp256k1_scalar_set_int()`, `secp256k1_scalar_get_bits()`, `secp256k1_scalar_get_bits_var()`, `secp256k1_scalar_check_overflow()`, `secp256k1_scalar_reduce()`, `secp256k1_scalar_add()`, `secp256k1_scalar_cadd_bit()`, `secp256k1_scalar_set_b32()`, `secp256k1_scalar_get_b32()`, `secp256k1_scalar_is_zero()`, `secp256k1_scalar_negate()`, `secp256k1_scalar_is_one()`, `secp256k1_scalar_is_high()`, `secp256k1_scalar_cond_negate()`, `secp256k1_scalar_reduce_512()`, `secp256k1_scalar_mul_512()`, `secp256k1_scalar_sqr_512()`, `secp256k1_scalar_mul()`, `secp256k1_scalar_shr_int()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/scalar_impl.h
- Functions: `secp256k1_scalar_get_num()`, `secp256k1_scalar_order_get_num()`, `secp256k1_scalar_inverse()`, `secp256k1_scalar_is_even()`, `secp256k1_scalar_inverse_var()`, `secp256k1_scalar_split_lambda()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/scalar_low.h
- (no class/function exports detected; resource/config content)

### app/src/main/jni/digibytewallet-core/secp256k1/src/scalar_low_impl.h
- Functions: `secp256k1_scalar_is_even()`, `secp256k1_scalar_clear()`, `secp256k1_scalar_set_int()`, `secp256k1_scalar_get_bits()`, `secp256k1_scalar_get_bits_var()`, `secp256k1_scalar_check_overflow()`, `secp256k1_scalar_add()`, `secp256k1_scalar_cadd_bit()`, `secp256k1_scalar_set_b32()`, `secp256k1_scalar_get_b32()`, `secp256k1_scalar_is_zero()`, `secp256k1_scalar_negate()`, `secp256k1_scalar_is_one()`, `secp256k1_scalar_is_high()`, `secp256k1_scalar_cond_negate()`, `secp256k1_scalar_mul()`, `secp256k1_scalar_shr_int()`, `secp256k1_scalar_sqr()`, `secp256k1_scalar_split_128()`, `secp256k1_scalar_eq()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/scratch.h
- Struct typedef: `secp256k1_scratch_space_struct`
- Functions: `secp256k1_scratch_create()`, `secp256k1_scratch_destroy()`, `secp256k1_scratch_max_allocation()`, `secp256k1_scratch_resize()`, `secp256k1_scratch_reset()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/scratch_impl.h
- Functions: `secp256k1_scratch_create()`, `secp256k1_scratch_destroy()`, `secp256k1_scratch_max_allocation()`, `secp256k1_scratch_resize()`, `secp256k1_scratch_reset()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/secp256k1.c
- Functions: `default_illegal_callback_fn()`, `default_error_callback_fn()`, `secp256k1_context_create()`, `secp256k1_context_clone()`, `secp256k1_context_destroy()`, `secp256k1_context_set_illegal_callback()`, `secp256k1_context_set_error_callback()`, `secp256k1_scratch_space_create()`, `secp256k1_scratch_space_destroy()`, `secp256k1_pubkey_load()`, `secp256k1_pubkey_save()`, `secp256k1_ec_pubkey_parse()`, `secp256k1_ec_pubkey_serialize()`, `secp256k1_ecdsa_signature_load()`, `secp256k1_ecdsa_signature_save()`, `secp256k1_ecdsa_signature_parse_der()`, `secp256k1_ecdsa_signature_parse_compact()`, `secp256k1_ecdsa_signature_serialize_der()`, `secp256k1_ecdsa_signature_serialize_compact()`, `secp256k1_ecdsa_signature_normalize()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/testrand.h
- Functions: `secp256k1_rand_seed()`, `secp256k1_rand32()`, `secp256k1_rand_bits()`, `secp256k1_rand_int()`, `secp256k1_rand256()`, `secp256k1_rand256_test()`, `secp256k1_rand_bytes_test()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/testrand_impl.h
- Functions: `secp256k1_rand_seed()`, `secp256k1_rand32()`, `secp256k1_rand_bits()`, `secp256k1_rand_int()`, `secp256k1_rand256()`, `secp256k1_rand_bytes_test()`, `secp256k1_rand256_test()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/tests.c
- Struct typedef: `(anonymous)`
- Functions: `ECDSA_SIG_get0()`, `counting_illegal_callback_fn()`, `uncounting_illegal_callback_fn()`, `random_field_element_test()`, `random_field_element_magnitude()`, `random_group_element_test()`, `random_group_element_jacobian_test()`, `random_scalar_order_test()`, `random_scalar_order()`, `run_context_tests()`, `run_scratch_tests()`, `run_sha256_tests()`, `run_hmac_sha256_tests()`, `run_rfc6979_hmac_sha256_tests()`, `test_rand_bits()`, `test_rand_int()`, `run_rand_bits()`, `run_rand_int()`, `random_num_negate()`, `random_num_order_test()` …

### app/src/main/jni/digibytewallet-core/secp256k1/src/tests_exhaustive.c
- Struct typedef: `(anonymous)`
- Functions: `ge_equals_ge()`, `ge_equals_gej()`, `random_fe()`, `test_exhaustive_endomorphism()`, `test_exhaustive_addition()`, `test_exhaustive_ecmult()`, `ecmult_multi_callback()`, `test_exhaustive_ecmult_multi()`, `r_from_k()`, `test_exhaustive_verify()`, `test_exhaustive_sign()`, `test_exhaustive_recovery_sign()`, `test_exhaustive_recovery_verify()`, `main()`

### app/src/main/jni/digibytewallet-core/secp256k1/src/util.h
- Struct typedef: `(anonymous)`
- Functions: `secp256k1_callback_call()`

### app/src/main/jni/digibytewallet-core/test.c
- Functions: `BRIntsTests()`, `BRArrayTests()`, `hash_int()`, `eq_int()`, `BRSetTests()`, `BRBase58Tests()`, `BRBech32Tests()`, `BRHashTests()`, `BRMacTests()`, `BRDrbgTests()`, `BRCypherTests()`, `BRAuthEncryptTests()`, `BRKeyTests()`, `BRBIP38KeyTests()`, `BRAddressTests()`, `BRBIP39MnemonicTests()`, `BRBIP32SequenceTests()`, `BRTxOutputEqual()`, `BRTxInputEqual()`, `BRTransactionEqual()` …

### app/src/main/jni/transition/JNIBIP32Sequence.c
- (no class/function exports detected; resource/config content)

### app/src/main/jni/transition/JNIBIP32Sequence.h
- Functions: `Java_com_jniwrappers_BRBIP32Sequence_bip32BitIDKey()`

### app/src/main/jni/transition/JNIBase58.c
- (no class/function exports detected; resource/config content)

### app/src/main/jni/transition/JNIBase58.h
- Functions: `Java_com_jniwrappers_BRBase58_base58Encode()`

### app/src/main/jni/transition/JNIKey.c
- Functions: `Java_com_jniwrappers_BRKey_address()`

### app/src/main/jni/transition/JNIKey.h
- Functions: `Java_com_jniwrappers_BRKey_compactSign()`, `Java_com_jniwrappers_BRKey_setPrivKey()`, `Java_com_jniwrappers_BRKey_setSecret()`, `Java_com_jniwrappers_BRKey_encryptNative()`, `Java_com_jniwrappers_BRKey_decryptNative()`, `Java_com_jniwrappers_BRKey_address()`

### app/src/main/jni/transition/PeerManager.c
- Functions: `syncStarted()`, `syncStopped()`, `txStatusUpdate()`, `saveBlocks()`, `savePeers()`, `networkIsReachable()`, `threadCleanup()`, `Java_io_digibyte_wallet_BRPeerManager_rescan()`, `Java_io_digibyte_wallet_BRPeerManager_syncProgress()`

### app/src/main/jni/transition/PeerManager.h
- Functions: `Java_io_digibyte_wallet_BRPeerManager_create()`, `Java_io_digibyte_wallet_BRPeerManager_createNew()`, `CreateInternal()`, `Java_io_digibyte_wallet_BRPeerManager_connect()`, `Java_io_digibyte_wallet_BRPeerManager_rescan()`, `Java_io_digibyte_wallet_BRPeerManager_putBlock()`, `Java_io_digibyte_wallet_BRPeerManager_createBlockArrayWithCount()`, `Java_io_digibyte_wallet_BRPeerManager_putPeer()`, `Java_io_digibyte_wallet_BRPeerManager_createPeerArrayWithCount()`, `Java_io_digibyte_wallet_BRPeerManager_isCreated()`, `Java_io_digibyte_wallet_BRPeerManager_syncProgress()`, `Java_io_digibyte_wallet_BRPeerManager_getCurrentBlockHeight()`, `Java_io_digibyte_wallet_BRPeerManager_getEstimatedBlockHeight()`, `Java_io_digibyte_wallet_BRPeerManager_getLastBlockTimestamp()`, `Java_io_digibyte_wallet_BRPeerManager_peerManagerFreeEverything()`, `Java_io_digibyte_presenter_activities_IntroActivity_testCore()`, `Java_io_digibyte_wallet_BRPeerManager_connectionStatus()`, `Java_io_digibyte_wallet_BRPeerManager_getRelayCount()`, `Java_io_digibyte_wallet_BRPeerManager_setFixedPeer()`, `Java_io_digibyte_wallet_BRPeerManager_getCurrentPeerName()`

### app/src/main/jni/transition/core.c
- (no class/function exports detected; resource/config content)

### app/src/main/jni/transition/core.h
- Functions: `Java_io_digibyte_tools_security_BitcoinUrlHandler_parsePaymentRequest()`, `Java_io_digibyte_tools_security_BitcoinUrlHandler_getCertificatesFromPaymentRequest()`, `Java_io_digibyte_tools_security_BitcoinUrlHandler_parsePaymentACK()`

### app/src/main/jni/transition/wallet.c
- Functions: `callback()`, `balanceChanged()`, `txAdded()`, `txDeleted()`, `Java_io_digibyte_wallet_BRWalletManager_getMinOutputAmount()`, `Java_io_digibyte_wallet_BRWalletManager_getMinOutputAmountRequested()`, `Java_io_digibyte_wallet_BRWalletManager_getMaxOutputAmount()`, `Java_io_digibyte_wallet_BRWalletManager_walletFreeEverything()`, `BRWalletBCashSweepTx()`

### app/src/main/jni/transition/wallet.h
- Functions: `Java_io_digibyte_wallet_BRWalletManager_encodeSeed()`, `Java_io_digibyte_wallet_BRWalletManager_createWallet()`, `Java_io_digibyte_wallet_BRWalletManager_getMasterPubKey()`, `Java_io_digibyte_wallet_BRWalletManager_putTransaction()`, `Java_io_digibyte_wallet_BRWalletManager_createTxArrayWithCount()`, `Java_io_digibyte_wallet_BRWalletManager_validateAddress()`, `Java_io_digibyte_wallet_BRWalletManager_addressContainedInWallet()`, `Java_io_digibyte_wallet_BRWalletManager_getMinOutputAmount()`, `Java_io_digibyte_wallet_BRWalletManager_getMinOutputAmountRequested()`, `Java_io_digibyte_wallet_BRWalletManager_addressIsUsed()`, `Java_io_digibyte_wallet_BRWalletManager_feeForTransaction()`, `Java_io_digibyte_wallet_BRWalletManager_isCreated()`, `Java_io_digibyte_wallet_BRWalletManager_getReceiveAddress()`, `Java_io_digibyte_wallet_BRWalletManager_getPublicAddresses()`, `Java_io_digibyte_wallet_BRWalletManager_getTransactions()`, `Java_io_digibyte_wallet_BRWalletManager_tryTransaction()`, `Java_io_digibyte_wallet_BRWalletManager_transactionIsVerified()`, `Java_io_digibyte_wallet_BRWalletManager_getMaxOutputAmount()`, `Java_io_digibyte_wallet_BRWalletManager_localAmount()`, `Java_io_digibyte_wallet_BRWalletManager_bitcoinAmount()` …

### app/src/main/res/anim/empty_300.xml
- XML elements: `<set>`, `<alpha>`

### app/src/main/res/anim/enter_from_bottom.xml
- XML elements: `<set>`, `<translate>`

### app/src/main/res/anim/enter_from_left.xml
- XML elements: `<set>`, `<translate>`

### app/src/main/res/anim/enter_from_right.xml
- XML elements: `<set>`, `<translate>`

### app/src/main/res/anim/exit_to_bottom.xml
- XML elements: `<set>`, `<translate>`

### app/src/main/res/anim/exit_to_left.xml
- XML elements: `<set>`, `<translate>`

### app/src/main/res/anim/exit_to_right.xml
- XML elements: `<set>`, `<translate>`

### app/src/main/res/anim/fade_down.xml
- XML elements: `<set>`, `<alpha>`

### app/src/main/res/anim/fade_up.xml
- XML elements: `<set>`, `<alpha>`

### app/src/main/res/anim/overshoot_interpolator.xml
- XML elements: `<overshootInterpolator>`

### app/src/main/res/anim/shake.xml
- XML elements: `<set>`, `<translate>`

### app/src/main/res/animator/from_bottom.xml
- XML elements: `<objectAnimator>`

### app/src/main/res/animator/from_top.xml
- XML elements: `<objectAnimator>`

### app/src/main/res/animator/to_bottom.xml
- XML elements: `<objectAnimator>`

### app/src/main/res/color/activity_disabled_button_text.xml
- XML elements: `<selector>`, `<item>`

### app/src/main/res/drawable/b_blue.xml
- XML elements: `<layer-list>`, `<item-->`, `<item>`, `<shape>`, `<solid>`, `<corners>`

### app/src/main/res/drawable/bread_dialog_rounded.xml
- XML elements: `<shape>`, `<corners>`, `<solid>`

### app/src/main/res/drawable/bread_gradient.xml
- XML elements: `<shape>`, `<gradient>`

### app/src/main/res/drawable/bread_toggle.xml
- XML elements: `<selector>`, `<item>`

### app/src/main/res/drawable/bread_toggle_off.xml
- XML elements: `<shape>`, `<corners>`, `<solid>`

### app/src/main/res/drawable/bread_toggle_on.xml
- XML elements: `<shape>`, `<corners>`, `<gradient>`

### app/src/main/res/drawable/button_reset_pin.xml
- XML elements: `<shape>`, `<solid>`, `<stroke>`, `<corners>`

### app/src/main/res/drawable/completed_background.xml
- XML elements: `<shape>`, `<corners>`, `<solid>`

### app/src/main/res/drawable/dashed_edittext_underline.xml
- XML elements: `<layer-list>`, `<item>`, `<shape>`, `<stroke>`, `<size>`

### app/src/main/res/drawable/digi_byte_symbol.xml
- XML elements: `<vector>`, `<path>`, `<aapt>`, `<gradient>`, `<item>`

### app/src/main/res/drawable/finger_gradient.xml
- XML elements: `<shape>`, `<gradient>`

### app/src/main/res/drawable/ic_check_mark_blue.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/ic_check_mark_grey.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/ic_close_black_24dp.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/ic_close_white_24dp.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/ic_delete_gray.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/ic_delete_white.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/ic_digiid.xml
- XML elements: `<vector>`, `<path>`, `<aapt>`, `<gradient>`, `<item>`

### app/src/main/res/drawable/ic_fingerprint_error.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/ic_fingerprint_large.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/ic_fingerprint_success.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/ic_main_action.xml
- XML elements: `<vector>`, `<path>`, `<aapt>`, `<gradient>`, `<item>`

### app/src/main/res/drawable/ic_paper_phrase.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/ic_pen.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/ic_qrcode.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/import_gradient.xml
- XML elements: `<shape>`, `<gradient>`

### app/src/main/res/drawable/intro_bottom_right.xml
- XML elements: `<vector>`, `<path>`, `<aapt>`, `<gradient>`, `<item>`

### app/src/main/res/drawable/intro_create_button.xml
- XML elements: `<shape>`, `<gradient>`, `<corners>`, `<padding>`

### app/src/main/res/drawable/intro_dgb.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/intro_top_left.xml
- XML elements: `<vector>`, `<path>`, `<aapt>`, `<gradient>`, `<item>`

### app/src/main/res/drawable/keyboard_white_button.xml
- XML elements: `<selector>`, `<item>`

### app/src/main/res/drawable/locked.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/menu_close.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/nav_drawer_header.xml
- XML elements: `<vector>`, `<path>`, `<aapt>`, `<gradient>`, `<item>`

### app/src/main/res/drawable/notification_gradient.xml
- XML elements: `<shape>`, `<gradient>`

### app/src/main/res/drawable/phrase_field.xml
- XML elements: `<shape>`, `<solid>`, `<corners>`

### app/src/main/res/drawable/pin_round_corner.xml
- XML elements: `<shape>`, `<corners>`, `<solid>`

### app/src/main/res/drawable/pin_selected.xml
- XML elements: `<vector>`, `<path>`, `<aapt>`, `<gradient>`, `<item>`

### app/src/main/res/drawable/pin_unselected.xml
- XML elements: `<vector>`, `<path>`, `<aapt>`, `<gradient>`, `<item>`

### app/src/main/res/drawable/receive_share_qr.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/restore_gradient.xml
- XML elements: `<shape>`, `<gradient>`

### app/src/main/res/drawable/rounded_gradient_header.xml
- XML elements: `<shape>`, `<corners>`, `<gradient>`

### app/src/main/res/drawable/rounded_phrase_word.xml
- XML elements: `<shape>`, `<solid>`, `<corners>`, `<padding>`

### app/src/main/res/drawable/send_paste.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/send_qr_scan.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/settings.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/shadow_trans.xml
- XML elements: `<shape>`, `<solid>`

### app/src/main/res/drawable/share_copy.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/share_sms.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/shield.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/signal_layout.xml
- XML elements: `<shape>`, `<corners>`, `<solid>`, `<padding>`

### app/src/main/res/drawable/signal_left_graphic.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/signal_right_graphic.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/sync_alt.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/sync_wallet_progress.xml
- XML elements: `<layer-list>`, `<item>`, `<shape>`, `<corners>`, `<gradient>`, `<clip>`

### app/src/main/res/drawable/touch_id.xml
- XML elements: `<vector>`, `<path>`, `<aapt>`, `<gradient>`, `<item>`

### app/src/main/res/drawable/transaction_background.xml
- XML elements: `<shape>`, `<gradient>`, `<corners>`

### app/src/main/res/drawable/transaction_details_background.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/transaction_details_background_wrapper.xml
- XML elements: `<layer-list>`, `<item>`

### app/src/main/res/drawable/transaction_details_received.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/transaction_details_sent.xml
- XML elements: `<vector>`, `<path>`

### app/src/main/res/drawable/tx_rounded.xml
- XML elements: `<shape>`, `<corners>`, `<solid>`

### app/src/main/res/drawable/write_down_gradient.xml
- XML elements: `<shape>`, `<gradient>`

### app/src/main/res/drawable-hdpi/toast_layout_black.xml
- XML elements: `<shape>`, `<solid>`, `<corners>`, `<stroke>`

### app/src/main/res/drawable-hdpi/toast_layout_blue.xml
- XML elements: `<shape>`, `<solid>`, `<corners>`

### app/src/main/res/drawable-hdpi/toast_layout_orange.xml
- XML elements: `<shape>`, `<solid>`, `<corners>`, `<stroke>`

### app/src/main/res/layout/activity_about.xml
- XML elements: `<ScrollView>`, `<LinearLayout>`, `<include>`, `<TextView>`, `<View>`, `<ImageView>`

### app/src/main/res/layout/activity_advanced.xml
- XML elements: `<androidx.constraintlayout.widget.ConstraintLayout>`, `<io.digibyte.presenter.customviews.BRText>`, `<ListView>`

### app/src/main/res/layout/activity_bread.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<androidx.drawerlayout.widget.DrawerLayout>`, `<FrameLayout>`, `<androidx.coordinatorlayout.widget.CoordinatorLayout>`, `<com.google.android.material.appbar.AppBarLayout>`, `<com.google.android.material.appbar.CollapsingToolbarLayout>`, `<LinearLayout>`, `<TextView>` …

### app/src/main/res/layout/activity_bread_recycler.xml
- XML elements: `<androidx.recyclerview.widget.RecyclerView>`

### app/src/main/res/layout/activity_disabled.xml
- XML elements: `<androidx.constraintlayout.widget.ConstraintLayout>`, `<io.digibyte.presenter.customviews.BRButton>`, `<io.digibyte.presenter.customviews.BRText>`

### app/src/main/res/layout/activity_display_currency.xml
- XML elements: `<layout>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<include>`, `<TextView>`, `<ListView>`

### app/src/main/res/layout/activity_fingerprint.xml
- XML elements: `<layout>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<include>`, `<LinearLayout>`, `<androidx.appcompat.widget.AppCompatImageView>`, `<ScrollView>`, `<TextView>`, `<androidx.appcompat.widget.SwitchCompat>`, `<View>`

### app/src/main/res/layout/activity_import.xml
- XML elements: `<androidx.constraintlayout.widget.ConstraintLayout>`, `<io.digibyte.presenter.customviews.BRButton>`, `<io.digibyte.presenter.customviews.BRText>`, `<ImageView>`, `<RelativeLayout>`, `<ImageButton>`, `<LinearLayout>`

### app/src/main/res/layout/activity_input_words.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<include>`, `<TextView>`, `<View>`, `<GridLayout>`, `<LinearLayout>`, `<EditText>` …

### app/src/main/res/layout/activity_intro.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<io.digibyte.presenter.customviews.BRRelativeLayout>`, `<ImageView>`, `<LinearLayout>`, `<Button>`, `<TextView>`

### app/src/main/res/layout/activity_intro_recover.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<include>`, `<androidx.constraintlayout.widget.ConstraintLayout>`, `<ImageView>`, `<io.digibyte.presenter.customviews.BRText>`, `<View>`, `<Button>`

### app/src/main/res/layout/activity_nodes.xml
- XML elements: `<androidx.constraintlayout.widget.ConstraintLayout>`, `<io.digibyte.presenter.customviews.BRText>`, `<io.digibyte.presenter.customviews.BRButton>`

### app/src/main/res/layout/activity_notification.xml
- XML elements: `<androidx.constraintlayout.widget.ConstraintLayout>`, `<io.digibyte.presenter.customviews.BRText>`, `<View>`, `<ToggleButton>`

### app/src/main/res/layout/activity_paper_key.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<include>`, `<io.digibyte.presenter.customviews.BRText>`, `<androidx.viewpager.widget.ViewPager>`, `<TextView>`, `<View>`, `<LinearLayout>` …

### app/src/main/res/layout/activity_paper_key_prove.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<include>`, `<LinearLayout>`, `<TextView>`, `<com.google.android.material.textfield.TextInputLayout>`, `<EditText>`, `<Button>`

### app/src/main/res/layout/activity_pin.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<LinearLayout>`, `<androidx.appcompat.widget.AppCompatImageView>`, `<View>`, `<io.digibyte.presenter.customviews.BRKeyboard>`

### app/src/main/res/layout/activity_pin_template.xml
- XML elements: `<layout>`, `<data>`, `<import>`, `<variable>`, `<LinearLayout>`, `<include>`, `<ScrollView>`, `<TextView>`, `<View>`, `<io.digibyte.presenter.customviews.BRKeyboard>`

### app/src/main/res/layout/activity_qr_code.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<FrameLayout>`, `<ImageView>`

### app/src/main/res/layout/activity_restore.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<include>`, `<RelativeLayout>`, `<ImageView>`, `<TextView>`, `<ScrollView>`, `<LinearLayout>` …

### app/src/main/res/layout/activity_security_center.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<include>`, `<ImageView>`, `<TextView>`, `<ListView>`

### app/src/main/res/layout/activity_settings.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<LinearLayout>`, `<androidx.appcompat.widget.Toolbar>`, `<TextView>`, `<androidx.recyclerview.widget.RecyclerView>`

### app/src/main/res/layout/activity_spend_limit.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<include>`, `<TextView>`, `<androidx.recyclerview.widget.RecyclerView>`

### app/src/main/res/layout/activity_sync_blockchain.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<LinearLayout>`, `<include>`, `<ScrollView>`, `<TextView>`, `<Button>`

### app/src/main/res/layout/activity_write_down.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<include>`, `<FrameLayout>`, `<androidx.appcompat.widget.AppCompatImageView>`, `<ScrollView>`, `<TextView>`, `<Button>`

### app/src/main/res/layout/bread_alert_dialog.xml
- XML elements: `<androidx.constraintlayout.widget.ConstraintLayout>`, `<TextView>`, `<LinearLayout>`, `<Button>`

### app/src/main/res/layout/currency_list_item.xml
- XML elements: `<LinearLayout>`, `<TextView>`, `<androidx.appcompat.widget.AppCompatImageView>`

### app/src/main/res/layout/fingerprint_dialog_container.xml
- XML elements: `<layout>`, `<data>`, `<import>`, `<variable>`, `<io.digibyte.presenter.customviews.BRRelativeLayout>`, `<LinearLayout>`, `<TextView>`, `<RelativeLayout>`, `<ImageView>`, `<Space>`

### app/src/main/res/layout/fragment_bread_pin.xml
- XML elements: `<layout>`, `<data>`, `<import>`, `<variable>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<LinearLayout>`, `<View>`, `<TextView>`, `<io.digibyte.presenter.customviews.BRKeyboard>`

### app/src/main/res/layout/fragment_greetings.xml
- XML elements: `<io.digibyte.presenter.customviews.BRRelativeLayout>`, `<androidx.constraintlayout.widget.ConstraintLayout>`, `<LinearLayout>`, `<io.digibyte.presenter.customviews.BRText>`, `<io.digibyte.presenter.customviews.BRButton>`

### app/src/main/res/layout/fragment_menu.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<io.digibyte.presenter.customviews.BRRelativeLayout>`, `<LinearLayout>`, `<androidx.recyclerview.widget.RecyclerView>`, `<androidx.appcompat.widget.AppCompatImageView>`

### app/src/main/res/layout/fragment_notification.xml
- XML elements: `<layout>`, `<data>`, `<import>`, `<variable>`, `<io.digibyte.presenter.customviews.BRRelativeLayout>`, `<LinearLayout>`, `<androidx.appcompat.widget.AppCompatImageView>`, `<com.airbnb.lottie.LottieAnimationView>`, `<TextView>`

### app/src/main/res/layout/fragment_receive.xml
- XML elements: `<layout>`, `<data>`, `<import>`, `<variable>`, `<io.digibyte.presenter.customviews.BRRelativeLayout>`, `<LinearLayout>`, `<RelativeLayout>`, `<androidx.appcompat.widget.AppCompatImageView>`, `<TextView>`, `<EditText>` …

### app/src/main/res/layout/fragment_send.xml
- XML elements: `<layout>`, `<data>`, `<import>`, `<variable>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<LinearLayout>`, `<RelativeLayout>`, `<androidx.appcompat.widget.AppCompatImageView>`, `<TextView>`, `<EditText>` …

### app/src/main/res/layout/fragment_transaction_details.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<io.digibyte.presenter.customviews.BRLinearLayout>`, `<androidx.viewpager.widget.ViewPager>`

### app/src/main/res/layout/fragment_word_item.xml
- XML elements: `<RelativeLayout>`, `<io.digibyte.presenter.customviews.BRText>`

### app/src/main/res/layout/list_item_prompt.xml
- XML elements: `<RelativeLayout>`, `<androidx.constraintlayout.widget.ConstraintLayout>`, `<io.digibyte.presenter.customviews.BRText>`, `<ImageButton>`

### app/src/main/res/layout/list_item_syncing.xml
- XML elements: `<LinearLayout>`, `<TextView>`, `<ProgressBar>`

### app/src/main/res/layout/list_item_transaction.xml
- XML elements: `<layout>`, `<data>`, `<variable>`, `<RelativeLayout>`, `<LinearLayout>`, `<ImageView>`, `<io.digibyte.presenter.customviews.BRText>`, `<View>`

### app/src/main/res/layout/menu_list_item.xml
- XML elements: `<LinearLayout>`, `<androidx.appcompat.widget.AppCompatImageView>`, `<TextView>`

### app/src/main/res/layout/notification_bar.xml
- XML elements: `<androidx.appcompat.widget.Toolbar>`, `<androidx.constraintlayout.widget.ConstraintLayout>`, `<ImageView>`, `<io.digibyte.presenter.customviews.BRText>`

### app/src/main/res/layout/pin_pad.xml
- XML elements: `<LinearLayout>`, `<TextView>`, `<androidx.appcompat.widget.AppCompatImageButton>`

### app/src/main/res/layout/security_center_list_item.xml
- XML elements: `<RelativeLayout>`, `<io.digibyte.presenter.customviews.BRText>`, `<ImageView>`

### app/src/main/res/layout/settings_list_item.xml
- XML elements: `<RelativeLayout>`, `<TextView>`

### app/src/main/res/layout/settings_list_section.xml
- XML elements: `<RelativeLayout>`, `<TextView>`

### app/src/main/res/layout/settings_switch.xml
- XML elements: `<LinearLayout>`, `<TextView>`, `<androidx.appcompat.widget.SwitchCompat>`

### app/src/main/res/layout/spinner_item.xml
- XML elements: `<io.digibyte.presenter.customviews.BRButton>`

### app/src/main/res/layout/toast.xml
- XML elements: `<LinearLayout>`, `<io.digibyte.presenter.customviews.BRText>`

### app/src/main/res/layout/toolbar.xml
- XML elements: `<androidx.appcompat.widget.Toolbar>`, `<TextView>`

### app/src/main/res/layout/transaction_details_item.xml
- XML elements: `<layout>`, `<data>`, `<import>`, `<variable>`, `<io.digibyte.presenter.customviews.BRRelativeLayout>`, `<FrameLayout>`, `<LinearLayout>`, `<ViewSwitcher>`, `<TextView>`, `<EditText>` …

### app/src/main/res/layout/view_bip38password_dialog.xml
- XML elements: `<LinearLayout>`, `<io.digibyte.presenter.customviews.BRText>`, `<io.digibyte.presenter.customviews.BREdit>`

### app/src/main/res/raw/error_check.json
- Contents: `{"v":"5.1.3","fr":60,"ip":0,"op":90,"w":150,"h":150,"nm":"Fail","ddd":0,"assets"`

### app/src/main/res/raw/success_check.json
- Contents: `{"v":"4.12.2","fr":29.9700012207031,"ip":0,"op":70.0000028511585,"w":680,"h":680`

### app/src/main/res/values/attrs.xml
- XML elements: `<resources>`, `<declare-styleable>`, `<attr>`

### app/src/main/res/values/colors.xml
- XML elements: `<resources>`, `<item>`, `<color>`

### app/src/main/res/values/dimens.xml
- XML elements: `<resources>`, `<dimen>`

### app/src/main/res/values/ids.xml
- XML elements: `<resources>`, `<item>`

### app/src/main/res/values/integer.xml
- XML elements: `<resources>`, `<integer>`

### app/src/main/res/values/no_trans_strings.xml
- XML elements: `<resources>`, `<string>`

### app/src/main/res/values/strings.xml
- XML elements: `<resources>`, `<string>`

### app/src/main/res/values/styles.xml
- XML elements: `<resources>`, `<style>`, `<item>`

### app/src/main/res/values/values.xml
- XML elements: `<resources>`

### app/src/main/res/values-af/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-ar/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-bg/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-bn/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-bs/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-ca/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-cs/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-de/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-el/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-es/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-fa/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-fi/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-fil/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-fr/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-gu/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-hi-rIN/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-hr/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-hu/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-in/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-in-rID/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-is/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-it/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-iw/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-ja/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-jv/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-kn/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`

### app/src/main/res/values-ko/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-mk/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-ml/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-mn/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-mr/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-ms/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-mt/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-nb-rNO/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-nl/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-or/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-pa/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-pl/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-pt/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-pt-rBR/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-ro/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-ru/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-sl/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-sr/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-sv/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-sw/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-ta/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-te/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-th/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-tr/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-uk/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-ur/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-vi/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-xhdpi/dimens.xml
- XML elements: `<resources>`, `<dimen>`

### app/src/main/res/values-xxhdpi/dimens.xml
- XML elements: `<resources>`, `<dimen>`

### app/src/main/res/values-xxxhdpi/dimens.xml
- XML elements: `<resources>`, `<dimen>`

### app/src/main/res/values-zh/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-zh-rHK/strings.xml
- XML elements: `<resources>`, `<string>`

### app/src/main/res/values-zh-rSG/strings.xml
- XML elements: `<resources>`, `<string>`, `<address>`, `<sitename>`, `<b>`

### app/src/main/res/values-zh-rTW/strings.xml
- XML elements: `<resources>`, `<string>`

### app/src/main/res/xml/file_paths.xml
- XML elements: `<paths>`, `<files-path>`

### app/src/main/res/xml/preferences.xml
- XML elements: `<PreferenceScreen>`, `<PreferenceCategory>`, `<CheckBoxPreference>`, `<ListPreference>`, `<EditTextPreference>`

### app/src/main/secp/secp256k1/.travis.yml
- Contents: `language: c`; `sudo: false`; `addons:`

### app/src/main/secp/secp256k1/README.md
- Contents: `libsecp256k1`; `============`; `[![Build Status](https://travis-ci.org/bitcoin-core/secp256k1.svg?branch=master)`

### app/src/main/secp/secp256k1/autogen.sh
- Contents: `#!/bin/sh`; `set -e`; `autoreconf -if --warnings=all`

### app/src/main/secp/secp256k1/contrib/lax_der_parsing.c
- Functions: `ecdsa_signature_parse_der_lax()`

### app/src/main/secp/secp256k1/contrib/lax_der_parsing.h
- (no class/function exports detected; resource/config content)

### app/src/main/secp/secp256k1/contrib/lax_der_privatekey_parsing.c
- Functions: `ec_privkey_import_der()`, `ec_privkey_export_der()`

### app/src/main/secp/secp256k1/contrib/lax_der_privatekey_parsing.h
- (no class/function exports detected; resource/config content)

### app/src/main/secp/secp256k1/include/secp256k1.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `secp256k1_context_destroy()`, `secp256k1_scratch_space_destroy()`

### app/src/main/secp/secp256k1/include/secp256k1_ecdh.h
- (no class/function exports detected; resource/config content)

### app/src/main/secp/secp256k1/include/secp256k1_recovery.h
- Struct typedef: `(anonymous)`

### app/src/main/secp/secp256k1/src/basic-config.h
- (no class/function exports detected; resource/config content)

### app/src/main/secp/secp256k1/src/bench.h
- Functions: `gettimedouble()`, `print_number()`, `run_benchmark()`, `have_flag()`

### app/src/main/secp/secp256k1/src/bench_ecdh.c
- Struct typedef: `(anonymous)`
- Functions: `bench_ecdh_setup()`, `bench_ecdh()`, `main()`

### app/src/main/secp/secp256k1/src/bench_ecmult.c
- Struct typedef: `(anonymous)`
- Functions: `bench_callback()`, `bench_ecmult()`, `bench_ecmult_setup()`, `bench_ecmult_teardown()`, `generate_scalar()`, `run_test()`, `main()`

### app/src/main/secp/secp256k1/src/bench_internal.c
- Struct typedef: `(anonymous)`
- Functions: `bench_setup()`, `bench_scalar_add()`, `bench_scalar_negate()`, `bench_scalar_sqr()`, `bench_scalar_mul()`, `bench_scalar_split()`, `bench_scalar_inverse()`, `bench_scalar_inverse_var()`, `bench_field_normalize()`, `bench_field_normalize_weak()`, `bench_field_mul()`, `bench_field_sqr()`, `bench_field_inverse()`, `bench_field_inverse_var()`, `bench_field_sqrt()`, `bench_group_double_var()`, `bench_group_add_var()`, `bench_group_add_affine()`, `bench_group_add_affine_var()`, `bench_group_jacobi_var()` …

### app/src/main/secp/secp256k1/src/bench_recover.c
- Struct typedef: `(anonymous)`
- Functions: `bench_recover()`, `bench_recover_setup()`, `main()`

### app/src/main/secp/secp256k1/src/bench_sign.c
- Struct typedef: `(anonymous)`
- Functions: `bench_sign_setup()`, `bench_sign_run()`, `main()`

### app/src/main/secp/secp256k1/src/bench_verify.c
- Struct typedef: `(anonymous)`
- Functions: `benchmark_verify()`, `benchmark_verify_openssl()`, `main()`

### app/src/main/secp/secp256k1/src/ecdsa.h
- Functions: `secp256k1_ecdsa_sig_parse()`, `secp256k1_ecdsa_sig_serialize()`, `secp256k1_ecdsa_sig_verify()`, `secp256k1_ecdsa_sig_sign()`

### app/src/main/secp/secp256k1/src/ecdsa_impl.h
- Functions: `secp256k1_der_read_len()`, `secp256k1_der_parse_integer()`, `secp256k1_ecdsa_sig_parse()`, `secp256k1_ecdsa_sig_serialize()`, `secp256k1_ecdsa_sig_verify()`, `secp256k1_ecdsa_sig_sign()`

### app/src/main/secp/secp256k1/src/eckey.h
- Functions: `secp256k1_eckey_pubkey_parse()`, `secp256k1_eckey_pubkey_serialize()`, `secp256k1_eckey_privkey_tweak_add()`, `secp256k1_eckey_pubkey_tweak_add()`, `secp256k1_eckey_privkey_tweak_mul()`, `secp256k1_eckey_pubkey_tweak_mul()`

### app/src/main/secp/secp256k1/src/eckey_impl.h
- Functions: `secp256k1_eckey_pubkey_parse()`, `secp256k1_eckey_pubkey_serialize()`, `secp256k1_eckey_privkey_tweak_add()`, `secp256k1_eckey_pubkey_tweak_add()`, `secp256k1_eckey_privkey_tweak_mul()`, `secp256k1_eckey_pubkey_tweak_mul()`

### app/src/main/secp/secp256k1/src/ecmult.h
- Struct typedef: `(anonymous)`
- Functions: `secp256k1_ecmult_context_init()`, `secp256k1_ecmult_context_build()`, `secp256k1_ecmult_context_clone()`, `secp256k1_ecmult_context_clear()`, `secp256k1_ecmult_context_is_built()`, `secp256k1_ecmult()`, `secp256k1_ecmult_multi_var()`

### app/src/main/secp/secp256k1/src/ecmult_const.h
- Functions: `secp256k1_ecmult_const()`

### app/src/main/secp/secp256k1/src/ecmult_const_impl.h
- Functions: `secp256k1_wnaf_const()`, `secp256k1_ecmult_const()`

### app/src/main/secp/secp256k1/src/ecmult_gen.h
- Struct typedef: `(anonymous)`
- Functions: `secp256k1_ecmult_gen_context_init()`, `secp256k1_ecmult_gen_context_build()`, `secp256k1_ecmult_gen_context_clone()`, `secp256k1_ecmult_gen_context_clear()`, `secp256k1_ecmult_gen_context_is_built()`, `secp256k1_ecmult_gen()`, `secp256k1_ecmult_gen_blind()`

### app/src/main/secp/secp256k1/src/ecmult_gen_impl.h
- Functions: `secp256k1_ecmult_gen_context_init()`, `secp256k1_ecmult_gen_context_build()`, `secp256k1_ecmult_gen_context_is_built()`, `secp256k1_ecmult_gen_context_clear()`, `secp256k1_ecmult_gen()`, `secp256k1_ecmult_gen_blind()`

### app/src/main/secp/secp256k1/src/ecmult_impl.h
- Functions: `secp256k1_ecmult_odd_multiples_table()`, `secp256k1_ecmult_odd_multiples_table_globalz_windowa()`, `secp256k1_ecmult_odd_multiples_table_storage_var()`, `secp256k1_ecmult_context_init()`, `secp256k1_ecmult_context_build()`, `secp256k1_ecmult_context_is_built()`, `secp256k1_ecmult_context_clear()`, `secp256k1_ecmult_wnaf()`, `secp256k1_ecmult_strauss_wnaf()`, `secp256k1_ecmult()`, `secp256k1_strauss_scratch_size()`, `secp256k1_ecmult_strauss_batch()`, `secp256k1_ecmult_strauss_batch_single()`, `secp256k1_strauss_max_points()`, `secp256k1_wnaf_fixed()`, `secp256k1_ecmult_pippenger_wnaf()`, `secp256k1_pippenger_bucket_window()`, `secp256k1_pippenger_bucket_window_inv()`, `secp256k1_ecmult_endo_split()`, `secp256k1_pippenger_scratch_size()` …

### app/src/main/secp/secp256k1/src/field.h
- Functions: `secp256k1_fe_normalize()`, `secp256k1_fe_normalize_weak()`, `secp256k1_fe_normalize_var()`, `secp256k1_fe_normalizes_to_zero()`, `secp256k1_fe_normalizes_to_zero_var()`, `secp256k1_fe_set_int()`, `secp256k1_fe_clear()`, `secp256k1_fe_is_zero()`, `secp256k1_fe_is_odd()`, `secp256k1_fe_equal()`, `secp256k1_fe_equal_var()`, `secp256k1_fe_cmp_var()`, `secp256k1_fe_set_b32()`, `secp256k1_fe_get_b32()`, `secp256k1_fe_negate()`, `secp256k1_fe_mul_int()`, `secp256k1_fe_add()`, `secp256k1_fe_mul()`, `secp256k1_fe_sqr()`, `secp256k1_fe_sqrt()` …

### app/src/main/secp/secp256k1/src/field_10x26.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`

### app/src/main/secp/secp256k1/src/field_10x26_impl.h
- Functions: `secp256k1_fe_verify()`, `secp256k1_fe_normalize()`, `secp256k1_fe_normalize_weak()`, `secp256k1_fe_normalize_var()`, `secp256k1_fe_normalizes_to_zero()`, `secp256k1_fe_normalizes_to_zero_var()`, `secp256k1_fe_set_int()`, `secp256k1_fe_is_zero()`, `secp256k1_fe_is_odd()`, `secp256k1_fe_clear()`, `secp256k1_fe_cmp_var()`, `secp256k1_fe_set_b32()`, `secp256k1_fe_get_b32()`, `secp256k1_fe_negate()`, `secp256k1_fe_mul_int()`, `secp256k1_fe_add()`, `secp256k1_fe_mul_inner()`, `secp256k1_fe_sqr_inner()`, `secp256k1_fe_mul()`, `secp256k1_fe_sqr()` …

### app/src/main/secp/secp256k1/src/field_5x52.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`

### app/src/main/secp/secp256k1/src/field_5x52_asm_impl.h
- Functions: `secp256k1_fe_mul_inner()`, `secp256k1_fe_sqr_inner()`

### app/src/main/secp/secp256k1/src/field_5x52_impl.h
- Functions: `secp256k1_fe_verify()`, `secp256k1_fe_normalize()`, `secp256k1_fe_normalize_weak()`, `secp256k1_fe_normalize_var()`, `secp256k1_fe_normalizes_to_zero()`, `secp256k1_fe_normalizes_to_zero_var()`, `secp256k1_fe_set_int()`, `secp256k1_fe_is_zero()`, `secp256k1_fe_is_odd()`, `secp256k1_fe_clear()`, `secp256k1_fe_cmp_var()`, `secp256k1_fe_set_b32()`, `secp256k1_fe_get_b32()`, `secp256k1_fe_negate()`, `secp256k1_fe_mul_int()`, `secp256k1_fe_add()`, `secp256k1_fe_mul()`, `secp256k1_fe_sqr()`, `secp256k1_fe_cmov()`, `secp256k1_fe_storage_cmov()` …

### app/src/main/secp/secp256k1/src/field_5x52_int128_impl.h
- Functions: `secp256k1_fe_mul_inner()`, `secp256k1_fe_sqr_inner()`

### app/src/main/secp/secp256k1/src/field_impl.h
- Functions: `secp256k1_fe_equal()`, `secp256k1_fe_equal_var()`, `secp256k1_fe_sqrt()`, `secp256k1_fe_inv()`, `secp256k1_fe_inv_var()`, `secp256k1_fe_inv_all_var()`, `secp256k1_fe_is_quad_var()`

### app/src/main/secp/secp256k1/src/gen_context.c
- Functions: `default_error_callback_fn()`, `main()`

### app/src/main/secp/secp256k1/src/group.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `secp256k1_ge_set_xy()`, `secp256k1_ge_set_xquad()`, `secp256k1_ge_set_xo_var()`, `secp256k1_ge_is_infinity()`, `secp256k1_ge_is_valid_var()`, `secp256k1_ge_neg()`, `secp256k1_ge_set_gej()`, `secp256k1_ge_set_all_gej_var()`, `secp256k1_ge_set_table_gej_var()`, `secp256k1_ge_globalz_set_table_gej()`, `secp256k1_ge_set_infinity()`, `secp256k1_gej_set_infinity()`, `secp256k1_gej_set_ge()`, `secp256k1_gej_eq_x_var()`, `secp256k1_gej_neg()`, `secp256k1_gej_is_infinity()`, `secp256k1_gej_has_quad_y_var()`, `secp256k1_gej_double_nonzero()`, `secp256k1_gej_double_var()`, `secp256k1_gej_add_var()` …

### app/src/main/secp/secp256k1/src/group_impl.h
- Functions: `secp256k1_ge_set_gej_zinv()`, `secp256k1_ge_set_xy()`, `secp256k1_ge_is_infinity()`, `secp256k1_ge_neg()`, `secp256k1_ge_set_gej()`, `secp256k1_ge_set_gej_var()`, `secp256k1_ge_set_all_gej_var()`, `secp256k1_ge_set_table_gej_var()`, `secp256k1_ge_globalz_set_table_gej()`, `secp256k1_gej_set_infinity()`, `secp256k1_ge_set_infinity()`, `secp256k1_gej_clear()`, `secp256k1_ge_clear()`, `secp256k1_ge_set_xquad()`, `secp256k1_ge_set_xo_var()`, `secp256k1_gej_set_ge()`, `secp256k1_gej_eq_x_var()`, `secp256k1_gej_neg()`, `secp256k1_gej_is_infinity()`, `secp256k1_gej_is_valid_var()` …

### app/src/main/secp/secp256k1/src/hash.h
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Struct typedef: `(anonymous)`
- Functions: `secp256k1_sha256_initialize()`, `secp256k1_sha256_write()`, `secp256k1_sha256_finalize()`, `secp256k1_hmac_sha256_initialize()`, `secp256k1_hmac_sha256_write()`, `secp256k1_hmac_sha256_finalize()`, `secp256k1_rfc6979_hmac_sha256_initialize()`, `secp256k1_rfc6979_hmac_sha256_generate()`, `secp256k1_rfc6979_hmac_sha256_finalize()`

### app/src/main/secp/secp256k1/src/hash_impl.h
- Functions: `secp256k1_sha256_initialize()`, `secp256k1_sha256_transform()`, `secp256k1_sha256_write()`, `secp256k1_sha256_finalize()`, `secp256k1_hmac_sha256_initialize()`, `secp256k1_hmac_sha256_write()`, `secp256k1_hmac_sha256_finalize()`, `secp256k1_rfc6979_hmac_sha256_initialize()`, `secp256k1_rfc6979_hmac_sha256_generate()`, `secp256k1_rfc6979_hmac_sha256_finalize()`

### app/src/main/secp/secp256k1/src/java/org/bitcoin/NativeSecp256k1.java
- Package: `org.bitcoin`
- Class: `holds`
- Class: `NativeSecp256k1`
- Methods: `undefined()`, `verify()`, `secp256k1_ecdsa_verify()`, `sign()`, `secKeyVerify()`, `secp256k1_ec_seckey_verify()`, `computePubkey()`, `cleanup()`, `cloneContext()`, `secp256k1_ctx_clone()`, `privKeyTweakMul()`, `privKeyTweakAdd()`, `pubKeyTweakAdd()`, `pubKeyTweakMul()`, `createECDHSecret()` …

### app/src/main/secp/secp256k1/src/java/org/bitcoin/NativeSecp256k1Test.java
- Package: `org.bitcoin`
- Class: `holds`
- Class: `NativeSecp256k1Test`
- Methods: `verify()`, `testVerifyPos()`, `testVerifyNeg()`, `testSecKeyVerifyPos()`, `testSecKeyVerifyNeg()`, `create()`, `testPubKeyCreatePos()`, `testPubKeyCreateNeg()`, `sign()`, `testSignPos()`, `testSignNeg()`, `testPrivKeyTweakAdd_1()`, `testPrivKeyTweakMul_1()`, `testPrivKeyTweakAdd_2()`, `testPrivKeyTweakMul_2()` …

### app/src/main/secp/secp256k1/src/java/org/bitcoin/NativeSecp256k1Util.java
- Package: `org.bitcoin`
- Class: `NativeSecp256k1Util`
- Class: `AssertFailException`
- Methods: `assertEquals()`

### app/src/main/secp/secp256k1/src/java/org/bitcoin/Secp256k1Context.java
- Package: `org.bitcoin`
- Class: `holds`
- Class: `Secp256k1Context`
- Methods: `isEnabled()`, `getContext()`, `secp256k1_init_context()`

### app/src/main/secp/secp256k1/src/java/org_bitcoin_NativeSecp256k1.c
- Functions: `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ctx_1clone()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1context_1randomize()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1destroy_1context()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdsa_1verify()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdsa_1sign()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ec_1seckey_1verify()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ec_1pubkey_1create()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1privkey_1tweak_1add()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1privkey_1tweak_1mul()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1pubkey_1tweak_1add()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1pubkey_1tweak_1mul()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdsa_1pubkey_1combine()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdh()`

### app/src/main/secp/secp256k1/src/java/org_bitcoin_NativeSecp256k1.h
- Functions: `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ctx_1clone()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1context_1randomize()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1privkey_1tweak_1add()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1privkey_1tweak_1mul()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1pubkey_1tweak_1add()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1pubkey_1tweak_1mul()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1destroy_1context()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdsa_1verify()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdsa_1sign()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ec_1seckey_1verify()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ec_1pubkey_1create()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ec_1pubkey_1parse()`, `Java_org_bitcoin_NativeSecp256k1_secp256k1_1ecdh()`

### app/src/main/secp/secp256k1/src/java/org_bitcoin_Secp256k1Context.c
- Functions: `Java_org_bitcoin_Secp256k1Context_secp256k1_1init_1context()`

### app/src/main/secp/secp256k1/src/java/org_bitcoin_Secp256k1Context.h
- Functions: `Java_org_bitcoin_Secp256k1Context_secp256k1_1init_1context()`

### app/src/main/secp/secp256k1/src/modules/ecdh/main_impl.h
- Functions: `secp256k1_ecdh()`

### app/src/main/secp/secp256k1/src/modules/ecdh/tests_impl.h
- Functions: `test_ecdh_api()`, `test_ecdh_generator_basepoint()`, `test_bad_scalar()`, `run_ecdh_tests()`

### app/src/main/secp/secp256k1/src/modules/recovery/main_impl.h
- Functions: `secp256k1_ecdsa_recoverable_signature_load()`, `secp256k1_ecdsa_recoverable_signature_save()`, `secp256k1_ecdsa_recoverable_signature_parse_compact()`, `secp256k1_ecdsa_recoverable_signature_serialize_compact()`, `secp256k1_ecdsa_recoverable_signature_convert()`, `secp256k1_ecdsa_sig_recover()`, `secp256k1_ecdsa_sign_recoverable()`, `secp256k1_ecdsa_recover()`

### app/src/main/secp/secp256k1/src/modules/recovery/tests_impl.h
- Functions: `recovery_test_nonce_function()`, `test_ecdsa_recovery_api()`, `test_ecdsa_recovery_end_to_end()`, `test_ecdsa_recovery_edge_cases()`, `run_recovery_tests()`

### app/src/main/secp/secp256k1/src/num.h
- Functions: `secp256k1_num_copy()`, `secp256k1_num_get_bin()`, `secp256k1_num_set_bin()`, `secp256k1_num_mod_inverse()`, `secp256k1_num_jacobi()`, `secp256k1_num_cmp()`, `secp256k1_num_eq()`, `secp256k1_num_add()`, `secp256k1_num_sub()`, `secp256k1_num_mul()`, `secp256k1_num_mod()`, `secp256k1_num_shift()`, `secp256k1_num_is_zero()`, `secp256k1_num_is_one()`, `secp256k1_num_is_neg()`, `secp256k1_num_negate()`

### app/src/main/secp/secp256k1/src/num_gmp.h
- Struct typedef: `(anonymous)`

### app/src/main/secp/secp256k1/src/num_gmp_impl.h
- Functions: `secp256k1_num_sanity()`, `secp256k1_num_copy()`, `secp256k1_num_get_bin()`, `secp256k1_num_set_bin()`, `secp256k1_num_add_abs()`, `secp256k1_num_sub_abs()`, `secp256k1_num_mod()`, `secp256k1_num_mod_inverse()`, `secp256k1_num_jacobi()`, `secp256k1_num_is_one()`, `secp256k1_num_is_zero()`, `secp256k1_num_is_neg()`, `secp256k1_num_cmp()`, `secp256k1_num_eq()`, `secp256k1_num_subadd()`, `secp256k1_num_add()`, `secp256k1_num_sub()`, `secp256k1_num_mul()`, `secp256k1_num_shift()`, `secp256k1_num_negate()`

### app/src/main/secp/secp256k1/src/num_impl.h
- (no class/function exports detected; resource/config content)

### app/src/main/secp/secp256k1/src/scalar.h
- Functions: `secp256k1_scalar_clear()`, `secp256k1_scalar_get_bits()`, `secp256k1_scalar_get_bits_var()`, `secp256k1_scalar_set_b32()`, `secp256k1_scalar_set_int()`, `secp256k1_scalar_get_b32()`, `secp256k1_scalar_add()`, `secp256k1_scalar_cadd_bit()`, `secp256k1_scalar_mul()`, `secp256k1_scalar_shr_int()`, `secp256k1_scalar_sqr()`, `secp256k1_scalar_inverse()`, `secp256k1_scalar_inverse_var()`, `secp256k1_scalar_negate()`, `secp256k1_scalar_is_zero()`, `secp256k1_scalar_is_one()`, `secp256k1_scalar_is_even()`, `secp256k1_scalar_is_high()`, `secp256k1_scalar_cond_negate()`, `secp256k1_scalar_get_num()` …

### app/src/main/secp/secp256k1/src/scalar_4x64.h
- Struct typedef: `(anonymous)`

### app/src/main/secp/secp256k1/src/scalar_4x64_impl.h
- Functions: `secp256k1_scalar_clear()`, `secp256k1_scalar_set_int()`, `secp256k1_scalar_get_bits()`, `secp256k1_scalar_get_bits_var()`, `secp256k1_scalar_check_overflow()`, `secp256k1_scalar_reduce()`, `secp256k1_scalar_add()`, `secp256k1_scalar_cadd_bit()`, `secp256k1_scalar_set_b32()`, `secp256k1_scalar_get_b32()`, `secp256k1_scalar_is_zero()`, `secp256k1_scalar_negate()`, `secp256k1_scalar_is_one()`, `secp256k1_scalar_is_high()`, `secp256k1_scalar_cond_negate()`, `secp256k1_scalar_reduce_512()`, `secp256k1_scalar_mul_512()`, `secp256k1_scalar_sqr_512()`, `secp256k1_scalar_mul()`, `secp256k1_scalar_shr_int()` …

### app/src/main/secp/secp256k1/src/scalar_8x32.h
- Struct typedef: `(anonymous)`

### app/src/main/secp/secp256k1/src/scalar_8x32_impl.h
- Functions: `secp256k1_scalar_clear()`, `secp256k1_scalar_set_int()`, `secp256k1_scalar_get_bits()`, `secp256k1_scalar_get_bits_var()`, `secp256k1_scalar_check_overflow()`, `secp256k1_scalar_reduce()`, `secp256k1_scalar_add()`, `secp256k1_scalar_cadd_bit()`, `secp256k1_scalar_set_b32()`, `secp256k1_scalar_get_b32()`, `secp256k1_scalar_is_zero()`, `secp256k1_scalar_negate()`, `secp256k1_scalar_is_one()`, `secp256k1_scalar_is_high()`, `secp256k1_scalar_cond_negate()`, `secp256k1_scalar_reduce_512()`, `secp256k1_scalar_mul_512()`, `secp256k1_scalar_sqr_512()`, `secp256k1_scalar_mul()`, `secp256k1_scalar_shr_int()` …

### app/src/main/secp/secp256k1/src/scalar_impl.h
- Functions: `secp256k1_scalar_get_num()`, `secp256k1_scalar_order_get_num()`, `secp256k1_scalar_inverse()`, `secp256k1_scalar_is_even()`, `secp256k1_scalar_inverse_var()`, `secp256k1_scalar_split_lambda()`

### app/src/main/secp/secp256k1/src/scalar_low.h
- (no class/function exports detected; resource/config content)

### app/src/main/secp/secp256k1/src/scalar_low_impl.h
- Functions: `secp256k1_scalar_is_even()`, `secp256k1_scalar_clear()`, `secp256k1_scalar_set_int()`, `secp256k1_scalar_get_bits()`, `secp256k1_scalar_get_bits_var()`, `secp256k1_scalar_check_overflow()`, `secp256k1_scalar_add()`, `secp256k1_scalar_cadd_bit()`, `secp256k1_scalar_set_b32()`, `secp256k1_scalar_get_b32()`, `secp256k1_scalar_is_zero()`, `secp256k1_scalar_negate()`, `secp256k1_scalar_is_one()`, `secp256k1_scalar_is_high()`, `secp256k1_scalar_cond_negate()`, `secp256k1_scalar_mul()`, `secp256k1_scalar_shr_int()`, `secp256k1_scalar_sqr()`, `secp256k1_scalar_split_128()`, `secp256k1_scalar_eq()`

### app/src/main/secp/secp256k1/src/scratch.h
- Struct typedef: `secp256k1_scratch_space_struct`
- Functions: `secp256k1_scratch_create()`, `secp256k1_scratch_destroy()`, `secp256k1_scratch_max_allocation()`, `secp256k1_scratch_resize()`, `secp256k1_scratch_reset()`

### app/src/main/secp/secp256k1/src/scratch_impl.h
- Functions: `secp256k1_scratch_create()`, `secp256k1_scratch_destroy()`, `secp256k1_scratch_max_allocation()`, `secp256k1_scratch_resize()`, `secp256k1_scratch_reset()`

### app/src/main/secp/secp256k1/src/secp256k1.c
- Functions: `default_illegal_callback_fn()`, `default_error_callback_fn()`, `secp256k1_context_create()`, `secp256k1_context_clone()`, `secp256k1_context_destroy()`, `secp256k1_context_set_illegal_callback()`, `secp256k1_context_set_error_callback()`, `secp256k1_scratch_space_create()`, `secp256k1_scratch_space_destroy()`, `secp256k1_pubkey_load()`, `secp256k1_pubkey_save()`, `secp256k1_ec_pubkey_parse()`, `secp256k1_ec_pubkey_serialize()`, `secp256k1_ecdsa_signature_load()`, `secp256k1_ecdsa_signature_save()`, `secp256k1_ecdsa_signature_parse_der()`, `secp256k1_ecdsa_signature_parse_compact()`, `secp256k1_ecdsa_signature_serialize_der()`, `secp256k1_ecdsa_signature_serialize_compact()`, `secp256k1_ecdsa_signature_normalize()` …

### app/src/main/secp/secp256k1/src/testrand.h
- Functions: `secp256k1_rand_seed()`, `secp256k1_rand32()`, `secp256k1_rand_bits()`, `secp256k1_rand_int()`, `secp256k1_rand256()`, `secp256k1_rand256_test()`, `secp256k1_rand_bytes_test()`

### app/src/main/secp/secp256k1/src/testrand_impl.h
- Functions: `secp256k1_rand_seed()`, `secp256k1_rand32()`, `secp256k1_rand_bits()`, `secp256k1_rand_int()`, `secp256k1_rand256()`, `secp256k1_rand_bytes_test()`, `secp256k1_rand256_test()`

### app/src/main/secp/secp256k1/src/tests.c
- Struct typedef: `(anonymous)`
- Functions: `ECDSA_SIG_get0()`, `counting_illegal_callback_fn()`, `uncounting_illegal_callback_fn()`, `random_field_element_test()`, `random_field_element_magnitude()`, `random_group_element_test()`, `random_group_element_jacobian_test()`, `random_scalar_order_test()`, `random_scalar_order()`, `run_context_tests()`, `run_scratch_tests()`, `run_sha256_tests()`, `run_hmac_sha256_tests()`, `run_rfc6979_hmac_sha256_tests()`, `test_rand_bits()`, `test_rand_int()`, `run_rand_bits()`, `run_rand_int()`, `random_num_negate()`, `random_num_order_test()` …

### app/src/main/secp/secp256k1/src/tests_exhaustive.c
- Struct typedef: `(anonymous)`
- Functions: `ge_equals_ge()`, `ge_equals_gej()`, `random_fe()`, `test_exhaustive_endomorphism()`, `test_exhaustive_addition()`, `test_exhaustive_ecmult()`, `ecmult_multi_callback()`, `test_exhaustive_ecmult_multi()`, `r_from_k()`, `test_exhaustive_verify()`, `test_exhaustive_sign()`, `test_exhaustive_recovery_sign()`, `test_exhaustive_recovery_verify()`, `main()`

### app/src/main/secp/secp256k1/src/util.h
- Struct typedef: `(anonymous)`
- Functions: `secp256k1_callback_call()`

### app/src/test/resources/en-BIP39Words.txt
- Contents: `abandon`; `ability`; `able`

### app/src/test/resources/es-BIP39Words.txt
- Contents: `ábaco`; `abdomen`; `abeja`

### app/src/test/resources/fr-BIP39Words.txt
- Contents: `﻿abaisser`; `abandon`; `abdiquer`

### app/src/test/resources/ja-BIP39Words.txt
- Contents: `あいこくしん`; `あいさつ`; `あいだ`

### app/src/test/resources/zh-BIP39Words.txt
- Contents: `的`; `一`; `是`

### build.gradle
- Gradle config blocks: `android`, `dependencies`

### gradle/wrapper/gradle-wrapper.properties
- Key entries: `distributionBase=GRADLE_USER_HOME`; `distributionPath=wrapper/dists`; `zipStoreBase=GRADLE_USER_HOME`; `zipStorePath=wrapper/dists`; `distributionUrl=https\://services.gradle.org/distributions/gradle-6.8.1-bin.zip`

### import-summary.txt
- Contents: `ECLIPSE ANDROID PROJECT IMPORT SUMMARY`; `======================================`; `Ignored Files:`

### settings.gradle
- Gradle config blocks: general build configuration

### trusted_roots_ICS.txt
- Contents: `Issuer: C=US, O=thawte, Inc., OU=Certification Services Division, OU=(c) 2006 th`; `Issuer: C=GB, ST=Greater Manchester, L=Salford, O=Comodo CA Limited, CN=Secure C`; `Issuer: C=CN, O=WoSign CA Limited, CN=CA \xE6\xB2\x83\xE9\x80\x9A\xE6\xA0\xB9\xE`
