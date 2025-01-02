# React Native WhatsApp Clone

This is a practice project to build a WhatsApp-like messaging app using React Native and Expo. The app is designed for learning purposes and mimics basic WhatsApp functionalities.

## Prerequisites

- Node.js installed on your system (v14 or later is recommended)
- Expo CLI installed globally (`npm install -g expo-cli`)
- Android Studio (for Android emulation)
- Xcode (for iOS emulation, macOS only)

## Getting Started

1. **Install Dependencies**
   Run the following command to install all required npm packages:

   ```bash
   npm install
   ```

2. **Prebuild the App**
   If you need to customize native configurations, you can prebuild the app to generate native projects for Android and iOS:
   ```bash
   npx expo prebuild --clean
   ```

## Setting Up Test Devices

### Android

1. **Install Android Studio**

   - Download and install Android Studio from [here](https://developer.android.com/studio).
   - Open Android Studio and set up an Android Virtual Device (AVD) using the Virtual Device Manager.
   - Ensure the Android emulator is running before proceeding.

2. **Start the App on Android**
   Run the following command:
   ```bash
   npm run android
   ```

### iOS

1. **Install Xcode**

   - Download and install Xcode from the Mac App Store.
   - Open Xcode and install the required command-line tools.

2. **Start the App on iOS**
   Run the following command:
   ```bash
   npm run ios
   ```
