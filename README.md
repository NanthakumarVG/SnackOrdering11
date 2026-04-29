# Snack Ordering App

A simple Android snack ordering app (sample project) that demonstrates user registration, login, ordering, and basic admin features. Built with Kotlin and Android SDK using a local SQLite-based persistence layer.

## Features
- User registration and login
- Browse snacks and place orders
- Admin view for managing or viewing orders
- Local storage via Room/SQLite

## Project structure (key files)
- `app/src/main/java/com/example/snackordering/`
  - `MainPage.kt` — main landing page UI
  - `LoginActivity.kt` — login screen
  - `RegisterActivity.kt` — registration screen
  - `AdminActivity.kt` — admin interface
  - `Order.kt`, `User.kt` — data models
  - `OrderDatabase.kt`, `UserDatabase.kt`, `*DatabaseHelper.kt` — local DB helpers/DAOs

## Prerequisites
- Android Studio (recommended)
- JDK 8 or higher
- Android SDK and an emulator or physical device

## Getting started
1. Clone the repository:

	git clone https://github.com/NanthakumarVG/SnackOrdering11.git
	cd SnackOrdering11

2. Open the project in Android Studio: `File → Open` and select the project root.
3. Let Gradle sync and download dependencies.
4. Run on an emulator or device using the Run button or via command line:

	Windows:

	./gradlew assembleDebug
	./gradlew installDebug

## Build and test
- Build (Gradle wrapper): `./gradlew assembleDebug`
- Install to connected device: `./gradlew installDebug`
- Run unit tests: `./gradlew test`
- Run instrumentation tests: `./gradlew connectedAndroidTest`

## Notes
- Resources like drawables and themes are in `app/src/main/res/`.
- If you change the database schema, increment the version in the database helper classes.

## Contributing
If you find issues or want to improve the app, open an issue or submit a pull request.

## License
This project is provided as-is. Add a license file if you intend to use or distribute it publicly.

https://drive.google.com/file/d/1fX5Ru1-ybDv42lNH43bg-_Lu6qkjwwgx/view?usp=drivesdk