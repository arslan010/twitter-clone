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
![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Home/screenshot_5.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Home/screenshot_2.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Home/screenshot_7.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Home/screenshot_6.jpg?raw=true)|

Compose Tweet Page                  | Reply To Tweet       |   Reply to Tweet      |     Compose Retweet with comment
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/CreateTweet/screenshot_1.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/CreateTweet/screenshot_2.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/CreateTweet/screenshot_4.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/CreateTweet/screenshot_3.jpg?raw=true)|

Tweet Detail Page         |  Tweet Thread              |   Nested Tweet Thread     | Tweet options
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/TweetDetail/screenshot_3.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/TweetDetail/screenshot_4.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/TweetDetail/screenshot_1.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/TweetDetail/screenshot_2.jpg?raw=true)|

Notification Page         |  Notification Page         |   Notification Page       | Notification Setting Page
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Notification/screenshot_1.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Notification/screenshot_2.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Notification/screenshot_3.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Notification/screenshot_4.jpg?raw=true)|

Profile Page                |  Profile Page            |   Profile  Page       | Profile  Page
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Profile/screenshot_1.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Profile/screenshot_2.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Profile/screenshot_4.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Profile/screenshot_7.jpg?raw=true)|

Select User Page                |  Chat Page            |    Chat Users List       | Conversation Info Page
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Chat/screenshot_1.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Chat/screenshot_2.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Chat/screenshot_3.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Chat/screenshot_4.jpg?raw=true)|

Search Page                |  Search Setting Page            |  Tweet Options - 1     | Tweet Options - 2
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Search/screenshot_1.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Search/screenshot_2.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/TweetDetail/screenshot_5.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/TweetDetail/screenshot_6.jpg?raw=true)|


Setting Page                |  Account Setting Page    |  Privacy Setting Page    | Privacy Settings Page
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Settings/screenshot_1.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Settings/screenshot_2.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Settings/screenshot_4.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Settings/screenshot_3.jpg?raw=true)|

Content Prefrences Page      |  Display Setting Page    |  Data Settings Page    | Accessibility Settings
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Settings/screenshot_5.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Settings/screenshot_6.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Settings/screenshot_7.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Settings/screenshot_8.jpg?raw=true)|

  Users who likes Tweet        |  About Setting Page    |  Licenses Settings     |  Settings
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/TweetDetail/screenshot_7.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Settings/screenshot_9.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Settings/screenshot_10.jpg?raw=true)|![](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/screenshots/Settings/screenshot_81.jpg?raw=true)|





## Getting started 
* Project setup instructions are given at [Wiki](https://github.com/TheAlphamerc/flutter_twitter_clone/wiki/Gettings-Started) section.

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
     
## Contributing

If you wish to contribute a change to any of the existing feature or add new in this repo,
please review our [contribution guide](https://github.com/TheAlphamerc/flutter_twitter_clone/blob/master/CONTRIBUTING.md),
and send a [pull request](https://github.com/TheAlphamerc/flutter_twitter_clone/pulls). I welcome and encourage all pull requests. It usually will take me within 24-48 hours to respond to any issue or request.

## Created & Maintained By

[Sonu Sharma](https://github.com/TheAlphamerc) ([Twitter](https://www.twitter.com/TheAlphamerc)) ([Youtube](https://www.youtube.com/user/sonusharma045sonu/)) ([Insta](https://www.instagram.com/_sonu_sharma__)) ([Dev.to](https://dev.to/thealphamerc))
  ![Twitter Follow](https://img.shields.io/twitter/follow/thealphamerc?style=social) 

> If you found this project helpful or you learned something from the source code and want to thank me, consider buying me a cup of :coffee:
>
> * [PayPal](https://paypal.me/TheAlphamerc/)

> You can also nominate me for Github Star developer program
> https://stars.github.com/nominate


## Contributors
[![](https://sourcerer.io/fame/TheAlphamerc/TheAlphamerc/flutter_twitter_clone/images/0)](https://sourcerer.io/fame/TheAlphamerc/TheAlphamerc/flutter_twitter_clone/links/0)[![](https://sourcerer.io/fame/TheAlphamerc/TheAlphamerc/flutter_twitter_clone/images/1)](https://sourcerer.io/fame/TheAlphamerc/TheAlphamerc/flutter_twitter_clone/links/1)[![](https://sourcerer.io/fame/TheAlphamerc/TheAlphamerc/flutter_twitter_clone/images/2)](https://sourcerer.io/fame/TheAlphamerc/TheAlphamerc/flutter_twitter_clone/links/2)

## Sponsors
* [Abdulbasit](https://github.com/AbdulbasitSaid)
## Visitors Count

<img align="left" src = "https://profile-counter.glitch.me/flutter_twitter_clone/count.svg" alt ="Loading">
