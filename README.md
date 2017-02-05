# Harker Bell Schedule iOS App :clock11:

<a href="https://goo.gl/rrk7mV">
    <img alt="Get it on the App Store!" src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Download_on_the_App_Store_Badge.svg" width="185px"/>
</a>

## Push Notification System

Push notifications are pushed using [OneSignal](https://onesignal.com/)

## Usage
Install CocoaPods. In the root directory of the project, in terminal, type
`pod install`.

Open `harker-bellschedule-ios.xcworkspace`

Inside of `AppDelegate.swift`, inside the function

```swift
func application(_ application: UIApplication, didFinishLaunchingWithOptions launchOptions: [UIApplicationLaunchOptionsKey: Any]?) -> Bool {}
```

Add the function `OneSignal.initWithLaunchOptions(launchOptions, appId: "your-app-id")`, with the app key that OneSignal provides you for the project.

## License
iOS, the App Store and the App Store logo are trademarks of Apple Inc.
