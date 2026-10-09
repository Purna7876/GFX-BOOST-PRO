# GFX BOOST PRO Android

Native Android WebView wrapper for the bundled offline HTML app. No network permission required. Features are in-app profiles and practice tools; it does not modify games, unlock FPS, or automate headshots.

## Build APK (Android Studio)
Open this folder as a project in Android Studio, let Gradle sync, then choose Build > Build Bundle(s) / APK(s) > Build APK(s). Debug APK: `app/build/outputs/apk/debug/app-debug.apk`.

## Build APK (GitHub Actions)
Upload the contents of this folder to a GitHub repository, then open Actions > Build Android APK > Run workflow. After it succeeds, download the `GFX-BOOST-PRO-debug-APK` artifact, unzip it and install `app-debug.apk` on Android. GitHub Actions access and permissions may be required.

This project does not contain a precompiled APK. A release APK for public distribution should be signed with a private release key.
