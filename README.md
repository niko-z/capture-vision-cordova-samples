# Dynamsoft Capture Vision samples for Cordova Edition

This repository contains multiple samples that demonstrate how to use the [Dynamsoft Capture Vision](https://www.dynamsoft.com/capture-vision/docs/introduction/) Cordova Edition.

## System Requirements

### Cordova Platforms

- Cordova Android: 9.0.0+ (10.1.1+ recommended)
- Cordova iOS: 6.2.0

### Android

- Supported OS: Android 5.0 (API Level 21) or higher.
- Supported ABI: **armeabi-v7a**, **arm64-v8a**, **x86** and **x86_64**.
- Development Environment: Android Studio 3.4+ (Android Studio 4.2+ recommended).
- JDK: 1.8+

### iOS

- Supported OS: **iOS 11.0** or higher.
- Supported ABI: **arm64** and **x86_64**.
- Development Environment: Xcode 7.1 and above (Xcode 13.0+ recommended), CocoaPods 1.11.0+.

## Samples

| Sample Name | Description |
| ----------- | ----------- |
| `BarcodeReaderSimpleSample` | This is a sample that illustrates the simplest way to recognize barcodes from video streaming with Dynamsoft Capture Vision Cordova SDK. |

### Install the Dependencies

```bash
cordova plugin add dynamsoft-capture-vision-cordova
```

> If you use a sample as the template to initialize your project, you don't need to manually add the dependency. The dependencies will be added when you add the platforms.

### Run the Project

#### Run Android on Windows or macOS

1. Add the platform first with the following command.

    ```bash
    cordova platform add android
    ```

2. Run the Project with the following command.

    ```bash
    cordova run android
    ```

> You might meet issues on gradle path if it is the first time to run Cordova on your Windows system. The following steps will help you on solving this issue:
>
> - Open **Environment Variables**
> - Look for **Path** in the **System variables**, open it.
> - Click **New** and add the path of your gradle bin folder to the environment variables. For exmaple: "C:\Users\admin\\.gradle\wrapper\dists\gradle-6.4-all\gradle-6.4\bin".

#### Run iOS on macOS

1. Add the platform first.

    ```bash
    cordova platform add ios
    ```

2. Open the **platforms/ios/SimpleBarcodeScanner.xcworkspace** with Xcode. Complete the *Signing & Capabilities* section of the project configuration via Xcode to avoid any signature errors during the build.

## License

- You can also request an extension for your trial license in the [customer portal](https://www.dynamsoft.com/customer/license/trialLicense?product=dbr&utm_source=github)

## Contact

https://www.dynamsoft.com/company/contact/
