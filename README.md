# Purity Tube — Android

Direct download of the Purity Tube Android app.

**[⬇ Download the latest APK](https://github.com/furqaan3124-ai/puritytube-releases/raw/main/puritytube-latest.apk)**

| | |
|---|---|
| Version | 1.1.0 (versionCode 2) |
| Size | 45.7 MB |
| Requires | Android 7.0+ |
| Architecture | arm64-v8a |

`puritytube-latest.apk` always points at the newest build, so the download link
on the website never has to change. Each release is also kept under its own
version number.

## Installing

Android blocks installs from outside the Play Store by default, so the first
install asks for permission:

1. Download the APK and open it.
2. Android will offer to allow installs from your browser — accept it.
3. Open it again to install.

This is expected for an app distributed outside the Play Store, and the prompt
only appears once.

## arm64 only

This build targets `arm64-v8a`, which covers every Android phone sold for
years. It deliberately leaves out the x86/x86_64 libraries, which only emulators
use and which more than doubled the download for no benefit to a real device.

## Verifying the download

```
sha256  099a89fc03955d7c0dc811487eaaf9dea391a3e15b57c4fffac446cbfd1781d1
```

## Releases

| Version | File | Notes |
|---|---|---|
| 1.1.0 | `puritytube-v1.1.0.apk` | Fixes the feed getting stuck after the app had been in the background; plays a video when you open it; adds the featured shelf and in-app update notices |
| 1.0.0 | `puritytube-v1.0.0.apk` | First public build |
