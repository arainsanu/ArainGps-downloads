# ArainGps

An ad-free GPS photo stamper for Android, created by Sanu Arain for field workers.

**[Download the latest Android APK](https://github.com/arainsanu/ArainGps-downloads/releases/latest/download/ArainGps.apk)**

[Website](https://araingps.vercel.app) · [All releases](https://github.com/arainsanu/ArainGps-downloads/releases)

## What the app does

- Capture photos with GPS coordinates, address and date/time stamps.
- Customize stamp layouts and add your company logo.
- Organize field photos in project albums.
- Export photo reports as PDF and share your work.
- Work without advertisements.

## Install

1. Open the download link on your Android phone. The browser downloads `ArainGps.apk`; it may ask you to confirm the download.
2. Open the downloaded APK. If Android asks, allow **Install unknown apps** for the browser or file manager used to open it.
3. Tap **Install**, then open ArainGps.
4. Grant camera and location permissions for capture and GPS stamps. Other permissions are requested when needed.

Requires Android 7.0 or newer. Internet access supports address and map services. Android security prompts cannot be skipped by the website.

## Updates

Install a newer official APK over the existing release. Updates must use the same package ID (`com.araingps.stamper`) and signing certificate. A debug build is a separate app. If Android reports a signature conflict, back up your photos and reports before considering uninstalling an older differently signed app.

The latest-download URL stays the same across releases because every release uses the asset name `ArainGps.apk`. SHA-256 checksums are provided with releases.

## Distribution and support

This repository contains public app downloads and documentation. Android project source, signing keys and passwords are kept private. No account or app password is required to download the APK.

For support, [open an issue](https://github.com/arainsanu/ArainGps-downloads/issues) or email [onlinesolfin@gmail.com](mailto:onlinesolfin@gmail.com). Avoid posting private photos or location information in public issues.

## For the app owner

Build future releases from the private Android Studio project. Keep a secure backup of the original signing key and password; never upload them here. Increment the version code, build a signed release APK using the same key, and publish it as `ArainGps.apk` in a new GitHub release marked latest. Upload its SHA-256 checksum as well. Private, machine-specific signing instructions are saved locally with the project.
