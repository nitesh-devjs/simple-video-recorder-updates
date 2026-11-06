# Simple Video Recorder updates

This public repository hosts the app update manifest and signed Android APK releases. Source code remains in the private `simple-video-recorder-android` repository.

The app checks `latest.json` when opened, verifies the APK SHA-256, then asks Android to install updates. Android always asks the device owner to confirm installation.
