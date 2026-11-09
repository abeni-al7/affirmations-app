# Affirmations

A simple app that shows a scrolling list of positive affirmations, each paired with an image.

Built while following Google's [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/course) course (the "Affirmations" codelab).

## Features

- Scrollable list of 10 affirmation cards, each with a cropped image and text
- Respects safe-drawing insets

## Built with

- Kotlin, Jetpack Compose, Material 3
- `LazyColumn` of `Card`s, data class model (`Affirmation`) and a `Datasource` class
- String and drawable resources referenced with `@StringRes` / `@DrawableRes`
- Min SDK 24, target/compile SDK 35

## Run it

1. Open the project folder in Android Studio and let Gradle sync.
2. Run the `app` configuration on an emulator or device (Android 7.0 / API 24 or newer).

Or, with a device or emulator connected:

```sh
./gradlew installDebug
```
