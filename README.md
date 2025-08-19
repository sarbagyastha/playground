# Flutter Playground

A basic Flutter project for experimentation and learning.

## Getting Started

This project is a starting point for a Flutter application. It includes:

- Basic Flutter app structure with a counter example
- Platform-specific configurations for Android, iOS, and Web
- Standard Flutter dependencies and build configuration
- Analysis options for consistent code quality

## Prerequisites

- Flutter SDK (latest stable version)
- Dart SDK (included with Flutter)
- Android Studio / VS Code with Flutter extensions
- For iOS development: Xcode (macOS only)

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
