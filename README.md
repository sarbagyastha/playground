# Alpha

A Flutter application with Firebase authentication.

## Getting Started

This project is a Flutter application featuring:

- Material Design with green theme
- Firebase Authentication (login/logout)
- Responsive design for multiple platforms
- Modern Flutter architecture with authentication state management

## Prerequisites

- Flutter SDK (latest stable version)
- Dart SDK (included with Flutter)
- Android Studio / VS Code with Flutter extensions
- For iOS development: Xcode (macOS only)
- Firebase project with Authentication enabled

## Firebase Setup

1. Create a Firebase project at https://console.firebase.google.com
2. Enable Authentication and set up Email/Password sign-in method
3. Add your app configurations:
   - For Android: Download `google-services.json` and place it in `android/app/`
   - For iOS: Download `GoogleService-Info.plist` and place it in `ios/Runner/`
   - For Web: Add your Firebase config to `web/index.html`

## Installation

1. Clone this repository
2. Ensure Flutter is installed and in your PATH
3. Run `flutter pub get` to install dependencies
4. Run `flutter run` to start the app

## Project Structure

```
lib/
  main.dart          # Main application entry point
android/             # Android-specific code and configuration
ios/                 # iOS-specific code and configuration  
web/                 # Web-specific code and configuration
pubspec.yaml         # Project dependencies and metadata
analysis_options.yaml # Dart/Flutter linting rules
```

## Running the App

- **Debug mode**: `flutter run`
- **Release mode**: `flutter run --release` 
- **Web**: `flutter run -d chrome`
- **Android**: `flutter run -d android`
- **iOS**: `flutter run -d ios` (macOS only)

## Building

- **Android APK**: `flutter build apk`
- **iOS**: `flutter build ios`
- **Web**: `flutter build web`

This project demonstrates the basic Flutter app template with Material Design components.
