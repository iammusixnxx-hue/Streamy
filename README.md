# Streamy — Complete Android V1

A minimal, dark, aesthetic Android media-downloader shell based on the Streamy design.

## Current V1
- Kotlin + Jetpack Compose
- Dark UI with gradient Streamy branding
- Paste HTTP/HTTPS URL
- Real Android DownloadManager integration
- Saves permitted direct files to the public Downloads folder
- Home / Downloads / History / Me navigation shell
- Basic error handling
- No storage permission required for the normal public Downloads flow on modern Android

## Deliberate limitation
This project does not rip protected/copyrighted streams from YouTube or Spotify, bypass DRM, or circumvent platform restrictions. Use it for media/files you own or are authorized to download, and for sources that explicitly permit downloads.

## Build
Open the project folder in Android Studio, allow Gradle sync, then run the `app` configuration on an Android device/emulator.

The ZIP does not contain the Gradle wrapper JAR, so an Android development environment will need to provide Gradle/Android Studio. This chat environment cannot compile and sign an APK.

## V2 roadmap
- Persistent download database
- Download progress UI
- MIME/file-type detection
- Audio/video format choices when the source exposes permitted variants
- Download history
- Share/open file actions
- Adaptive launcher icon
- Supported-source integrations that comply with each provider's terms
