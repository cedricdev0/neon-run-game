# Skyline Obby for Android

The Android app wraps the browser game in a fullscreen, hardware-accelerated WebView. The game page is bundled in `app/src/main/assets`; Three.js is loaded from jsDelivr, so the first launch needs an internet connection.

## Build

From this directory, run `gradle assembleDebug`. The installable debug APK is written to `app/build/outputs/apk/debug/app-debug.apk`.

## Touch controls

- Direction pad: move forward, backward, and sideways
- Look arrows: rotate the camera
- Jump button: jump
