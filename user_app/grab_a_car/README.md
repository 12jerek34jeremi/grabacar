# Grab A car

An app enabling user to rent a car.

## flutter version
Flutter version 3.27.4 with dart 3.6.2 is used in this project.

output of `flutter --version`:
```output
Flutter 3.27.4 • channel stable • https://github.com/flutter/flutter.git
Framework • revision d8a9f9a52e (5 weeks ago) • 2025-01-31 16:07:18 -0500
Engine • revision 82bd5b7209
Tools • Dart 3.6.2 • DevTools 2.40.3
```

## How to run.
1. Set up a database and insert some data. See [script folder](../../script) for more info.
2. Modify [connection_credentials.json file](./assets/connection_credentials.json). Write credentials for connecting to the database you just set up.
3. Run:
    * `flutter pub get`
    * `flutter run`