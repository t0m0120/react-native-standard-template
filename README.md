## ReactNative(TS) + Firebase + ReactNavigation

ReactNavigation and ReactNativeFirebase are added to the ReactNaticeProject created from react-native-template-typescript.

## HowToUse

```bash
$ git clone git@github.com:t0m0120/react-native-standard-template.git
```


Adding a certificate to iOS/Android

### Android 

Download the google-services.json file and place it inside of your project at the following location: /android/app/google-services.json.

https://rnfirebase.io/#2-android-setup

### iOS

Add GoogleService-Info.plist to the iOS directory

https://rnfirebase.io/#generating-ios-credentials

### Linking

https://rnfirebase.io/#4-autolinking--rebuilding


```bash
# Android apps
npx react-native run-android

# iOS apps
cd ios/
pod install --repo-update
cd ..
npx react-native run-ios
```

## Rename Project

use [react-native-rename](https://www.npmjs.com/package/react-native-rename)

```bash
$ npx react-native-rename hogehoge
```