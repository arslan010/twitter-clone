## Fwitter - Twitter clone in flutter
A working Twitter clone written in Flutter using Firebase auth,realtime,firestore database and storage.


## Dependencies
<details>
     <summary> Click to expand </summary>
     
* [intl](https://pub.dev/packages/intl)
* [uuid](https://pub.dev/packages/uuid)
* [http](https://pub.dev/packages/http)
* [share](https://pub.dev/packages/share)
* [provider](https://pub.dev/packages/provider)
* [url_launcher](https://pub.dev/packages/url_launcher)
* [google_fonts](https://pub.dev/packages/google_fonts)
* [image_picker](https://pub.dev/packages/image_picker)
* [firebase_auth](https://pub.dev/packages/firebase_auth)
* [google_sign_in](https://pub.dev/packages/google_sign_in)
* [firebase_analytics](https://pub.dev/packages/firebase_analytics)
* [firebase_database](https://pub.dev/packages/firebase_database)
* [shared_preferences](https://pub.dev/packages/shared_preferences)
* [flutter_advanced_networkimage](https://pub.dev/packages/flutter_advanced_networkimage)
     
</details>

## Screenshots

Welcome Page               |  Login Page               | Signup Page               |  Forgot Password Page
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](screenshots/Auth/screenshot_1.jpg)|![](screenshots/Auth/screenshot_2.jpg)|![](screenshots/Auth/screenshot_3.jpg)|![](screenshots/Auth/screenshot_4.jpg)|

Home Page Sidebaar         |  Home Page       |   Home Page               |  Home Page
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](screenshots/Home/screenshot_5.jpg)|![](screenshots/Home/screenshot_2.jpg)|![](screenshots/Home/screenshot_7.jpg)|![](screenshots/Home/screenshot_6.jpg)|

Compose Tweet Page                  | Reply To Tweet       |   Reply to Tweet      |     Compose Retweet with comment
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](screenshots/CreateTweet/screenshot_1.jpg)|![](screenshots/CreateTweet/screenshot_2.jpg)|![](screenshots/CreateTweet/screenshot_4.jpg)|![](screenshots/CreateTweet/screenshot_3.jpg)|

Tweet Detail Page         |  Tweet Thread              |   Nested Tweet Thread     | Tweet options
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](screenshots/TweetDetail/screenshot_3.jpg)|![](screenshots/TweetDetail/screenshot_4.)|![](screenshots/TweetDetail/screenshot_1.)|![](screenshots/TweetDetail/screenshot_2.jpg)|

Notification Page         |  Notification Page         |   Notification Page       | Notification Setting Page
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](screenshots/Notification/screenshot_1.jpg)|![]( screenshots/Notification/screenshot_2.jpg )|![]( screenshots/Notification/screenshot_3.jpg )|![]( screenshots/Notification/screenshot_4.jpg )|

Profile Page                |  Profile Page            |   Profile  Page       | Profile  Page
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![]( screenshots/Profile/screenshot_1.jpg )|![]( screenshots/Profile/screenshot_2.jpg )|![]( screenshots/Profile/screenshot_4.jpg )|![]( screenshots/Profile/screenshot_7.jpg )|

Select User Page                |  Chat Page            |    Chat Users List       | Conversation Info Page
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![]( screenshots/Chat/screenshot_1.jpg )|![]( screenshots/Chat/screenshot_2.jpg )|![]( screenshots/Chat/screenshot_3.jpg )|![]( screenshots/Chat/screenshot_4.jpg )|

Search Page                |  Search Setting Page            |  Tweet Options - 1     | Tweet Options - 2
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![]( screenshots/Search/screenshot_1.jpg )|![]( screenshots/Search/screenshot_2.jpg )|![]( screenshots/TweetDetail/screenshot_5.jpg )|![]( screenshots/TweetDetail/screenshot_6.jpg )|


Setting Page                |  Account Setting Page    |  Privacy Setting Page    | Privacy Settings Page
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![]( screenshots/Settings/screenshot_1.jpg )|![]( screenshots/Settings/screenshot_2.jpg )|![]( screenshots/Settings/screenshot_4.jpg )|![]( screenshots/Settings/screenshot_3.jpg )|

Content Prefrences Page      |  Display Setting Page    |  Data Settings Page    | Accessibility Settings
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![]( screenshots/Settings/screenshot_5.jpg )|![]( screenshots/Settings/screenshot_6.jpg )|![]( screenshots/Settings/screenshot_7.jpg )|![]( screenshots/Settings/screenshot_8.jpg )|

  Users who likes Tweet        |  About Setting Page    |  Licenses Settings     |  Settings
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![]( screenshots/TweetDetail/screenshot_7.jpg )|![]( screenshots/Settings/screenshot_9.jpg )|![]( screenshots/Settings/screenshot_10.jpg )|![]( screenshots/Settings/screenshot_81.jpg )|





## Getting started 


Sonu Sharma edited this page on Nov 27, 2022 · [10 revisions](https://github.com/TheAlphamerc/flutter_twitter_clone/wiki/Gettings-Started/_history)

#### 1. [Flutter Environment Setup](https://flutter.dev/docs/get-started/install)

> **Note**: Flutter sdk version 3.3.8 is recommended to run project

#### 2\. Clone the repo

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   $ git clone https://github.com/TheAlphamerc/flutter_twitter_clone.git  $ cd flutter_twitter_clone/   `

#### 3\. Setup the firebase app

1.  You'll need to create a Firebase instance. Follow the instructions at [https://console.firebase.google.com](https://console.firebase.google.com/).
    
2.  Once your Firebase instance is created, you'll need to enable Google authentication.
    

*   Go to the Firebase Console for your new instance.
    
*   Click "Authentication" in the left-hand menu
    
*   Click the "sign-in method" tab
    
*   Click "Google" and enable it
    
*   Click "Email/Password" and enable it
    

1.  Enable the Firebase Database
    

*   Go to the Firebase Console
    
*   Click "Database" in the left-hand menu
    
*   Click the "Create Database" button
    
*   It will prompt you to set up, rules, for the sake of simplicity, let us choose test mode, for now.
    
*   On the next screen select any of the locations you prefer.
    

1.  (skip if not running on Android)
    

*   Create an app within your Firebase instance for Android, with package name > com.thealphamerc.flutter\_twitter\_clone\_dev
    
*   Run the following command to get your SHA-1 key:
    

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   keytool -exportcert -list -v \  -alias androiddebugkey -keystore ~/.android/debug.keystore   `

*   In the Firebase console, in the settings of your Android app, add your SHA-1 key by clicking "Add Fingerprint".
    

1.  Enable firebase storage (otherwise storing images will not work)
    
2.  Add "FcmServerKey" to Firebase Remote Config Follow below steps to get FCM server key.
    

*   Open your project in firebase.
    
*   Click on gear icon in sidebar. A popup will open then click on project settings


![alt text](image.png)
    
*   Open Cloud messaging tab

![alt text](image-1.png)
    
*   You can get FCM server key from there

![alt text](image-2.png)
    
*   Go to firebase remote config
    
*   Create parameter with name FcmServerKey
    
*   Add below json to default value field.
    

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML     `{            "key": "FCM server key here"       }` 

Check below firebase config screenshot

![alt text](image-3.png)

7 Add another parameter in remote config to get the latest app version and supported builds

> This step is optional for development mode.

*   Open Remote Config section in fireabse.
    
*   Add supportedBuild as parameter key and below JSON in Default value.
    
*   Copy app version and build no. from pubspec.yaml
    
    ![alt text](image-4.png)

Replace  and  in below JSON content with actual value and add this in default value field as per below screenshot.

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML `{     "name":"",     "versions":[]    }`

![alt text](image-5.png)

After adding supportedBuild key click on Publish Change button

*   Download google-services.json
    
*   place google-services.json into /android/app/.
    

1.  (skip if not running on iOS)
    

*   Create an app within your Firebase instance for iOS, with your app package name
    
*   Follow instructions to download GoogleService-Info.plist
    
*   Open XCode, right click the Runner folder, select the "Add Files to 'Runner'" menu, and select the GoogleService-Info.plist file to add it to /ios/Runner in XCode
    
*   Open /ios/Runner/Info.plist in a text editor. Locate the CFBundleURLSchemes key. The second item in the array value of this key is specific to the Firebase instance. Replace it with the value for REVERSED\_CLIENT\_ID from GoogleService-Info.plist
        


## Directory Structure
<details>
     <summary> Click to expand </summary>
  
```
|-- lib
|   |-- helper
|   |   |-- constant.dart
|   |   |-- customRoute.dart
|   |   |-- enum.dart
|   |   |-- routes.dart
|   |   |-- theme.dart
|   |   |-- utility.dart
|   |   '-- validator.dart
|   |-- main.dart
|   |-- model
|   |   |-- chatModel.dart
|   |   |-- feedModel.dart
|   |   |-- notificationModel.dart
|   |   '-- user.dart
|   |-- page
|   |   |-- Auth
|   |   |   |-- forgetPasswordPage.dart
|   |   |   |-- selectAuthMethod.dart
|   |   |   |-- signin.dart
|   |   |   |-- signup.dart
|   |   |   |-- verifyEmail.dart
|   |   |   '-- widget
|   |   |       '-- googleLoginButton.dart
|   |   |-- common
|   |   |   |-- sidebar.dart
|   |   |   |-- splash.dart
|   |   |   |-- usersListPage.dart
|   |   |   '-- widget
|   |   |       '-- userListWidget.dart
|   |   |-- feed
|   |   |   |-- composeTweet
|   |   |   |   |-- composeTweet.dart
|   |   |   |   |-- state
|   |   |   |   |   '-- composeTweetState.dart
|   |   |   |   '-- widget
|   |   |   |       |-- composeBottomIconWidget.dart
|   |   |   |       |-- composeTweetImage.dart
|   |   |   |       '-- widgetView.dart
|   |   |   |-- feedPage.dart
|   |   |   |-- feedPostDetail.dart
|   |   |   '-- imageViewPage.dart
|   |   |-- homePage.dart
|   |   |-- message
|   |   |   |-- chatListPage.dart
|   |   |   |-- chatScreenPage.dart
|   |   |   |-- conversationInformation
|   |   |   |   '-- conversationInformation.dart
|   |   |   '-- newMessagePage.dart
|   |   |-- notification
|   |   |   '-- notificationPage.dart
|   |   |-- profile
|   |   |   |-- EditProfilePage.dart
|   |   |   |-- follow
|   |   |   |   |-- followerListPage.dart
|   |   |   |   '-- followingListPage.dart
|   |   |   |-- profileImageView.dart
|   |   |   |-- profilePage.dart
|   |   |   '-- widgets
|   |   |       '-- tabPainter.dart
|   |   |-- search
|   |   |   '-- SearchPage.dart
|   |   '-- settings
|   |       |-- accountSettings
|   |       |   |-- about
|   |       |   |   '-- aboutTwitter.dart
|   |       |   |-- accessibility
|   |       |   |   '-- accessibility.dart
|   |       |   |-- accountSettingsPage.dart
|   |       |   |-- contentPrefrences
|   |       |   |   |-- contentPreference.dart
|   |       |   |   '-- trends
|   |       |   |       '-- trendsPage.dart
|   |       |   |-- dataUsage
|   |       |   |   '-- dataUsagePage.dart
|   |       |   |-- displaySettings
|   |       |   |   '-- displayAndSoundPage.dart
|   |       |   |-- notifications
|   |       |   |   '-- notificationPage.dart
|   |       |   |-- privacyAndSafety
|   |       |   |   |-- directMessage
|   |       |   |   |   '-- directMessage.dart
|   |       |   |   '-- privacyAndSafetyPage.dart
|   |       |   '-- proxy
|   |       |       '-- proxyPage.dart
|   |       |-- settingsAndPrivacyPage.dart
|   |       '-- widgets
|   |           |-- headerWidget.dart
|   |           |-- settingsAppbar.dart
|   |           '-- settingsRowWidget.dart
|   |-- state
|   |   |-- appState.dart
|   |   |-- authState.dart
|   |   |-- chats
|   |   |   '-- chatState.dart
|   |   |-- feedState.dart
|   |   |-- notificationState.dart
|   |   '-- searchState.dart
|   '-- widgets
|       |-- bottomMenuBar
|       |   |-- HalfPainter.dart
|       |   |-- bottomMenuBar.dart
|       |   '-- tabItem.dart
|       |-- customAppBar.dart
|       |-- customWidgets.dart
|       |-- newWidget
|       |   |-- customClipper.dart
|       |   |-- customLoader.dart
|       |   |-- customProgressbar.dart
|       |   |-- customUrlText.dart
|       |   |-- emptyList.dart
|       |   |-- rippleButton.dart
|       |   '-- title_text.dart
|       '-- tweet
|           |-- tweet.dart
|           '-- widgets
|               |-- parentTweet.dart
|               |-- retweetWidget.dart
|               |-- tweetBottomSheet.dart
|               |-- tweetIconsRow.dart
|               |-- tweetImage.dart
|               '-- unavailableTweet.dart
|-- pubspec.yaml
```

</details>
     


## Visitors Count

<img align="left" src = "https://profile-counter.glitch.me/flutter_twitter_clone/count.svg" alt ="Loading">
