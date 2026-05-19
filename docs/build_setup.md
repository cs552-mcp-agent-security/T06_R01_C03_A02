# Build setup

## Prerequisites

- Flutter SDK 3.22 or newer (`flutter --version`)
- Dart 3.4+
- For web: `flutter config --enable-web`
- For Android: Android Studio with `cmdline-tools;latest` installed

## Common commands

```bash
flutter pub get
flutter run -d chrome           # local dev for web
flutter build web --release     # release artifacts under build/web/
flutter build apk --release     # Android APK
```

## Finnkino API

The app fetches showtimes from `https://www.finnkino.fi/xml/Schedule` — a public
XML feed; no API key required.
