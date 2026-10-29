# Math-Mania

![Math-Mania logo](assets/images/math-mania-logo.png)

Math-Mania is a Flutter application designed to make mathematics practice more engaging through interactive mini-games and puzzles.

## Features

The source tree includes modules for:

- Quick calculation and mental arithmetic
- Guess the sign and correct-answer challenges
- Picture puzzles and mathematical pairs
- Magic triangles, number pyramids, and math grids
- Square-root challenges and a calculator
- App themes, game timing, scoring, and shared UI components

## Tech stack

- **Flutter & Dart** for cross-platform app development
- **Provider** and related Flutter packages for app state and UI behavior
- **SharedPreferences** for local preferences
- **Firebase Core, Analytics, and Crashlytics** dependencies are declared in `pubspec.yaml`
- **SVG assets**, GIFs, and custom Montserrat/Poppins fonts

## Getting started

### Prerequisites

Install the Flutter SDK and the platform tools for the device you want to run on. For Android builds, install a compatible JDK and Android SDK.

### Run locally

1. Clone the repository:

   ```bash
   git clone <YOUR_GITHUB_REPOSITORY_URL>
   cd Math-Mania
   ```

2. Install dependencies:

   ```bash
   flutter pub get
   ```

3. Check the project:

   ```bash
   flutter analyze
   flutter test
   ```

4. Run on a connected device or emulator:

   ```bash
   flutter run
   ```

Some platform or Firebase features may require additional local configuration. Do not commit machine-specific files such as `android/local.properties` or credentials and API secrets.

## Project structure

```text
lib/          Dart application source
assets/       Images, SVGs, GIFs, and fonts
android/      Android project configuration
ios/          iOS project configuration
web/          Web project configuration
windows/      Windows project configuration
macos/        macOS project configuration
linux/        Linux project configuration
test/         Automated tests
```

## License

This project includes a MIT License. See [LICENSE](LICENSE) for details.
