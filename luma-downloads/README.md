# LUMA Python Camera downloads

Android camera app preview built with Python 3.12, Chaquopy and CameraX.

- `LUMA-Python-0.1.0.apk`: installable preview, 42,739,825 bytes.
- `LUMA-Python-0.1.0.apk.sha256`: checksum for the APK.
- `LUMA-Python-source.zip`: source and build instructions, excluding private signing files.
- `permissions-and-interactions.md`: Chinese permission and interaction guide.
- `release-info.json`: build metadata and validation limits.

On GitHub, open the APK and choose **Download raw file** (the download-arrow button).
Requires Android 7.0 or later and a 64-bit ARM or x86_64 device.
Signed with the project's local preview certificate; this is a test build.
8 Python tests and 3 QR decoder JVM tests passed. APK signature, alignment and
embedded-runtime checks passed. Device camera, flash and native UI still need
physical-device validation; software emulators did not finish booting in this environment.

This branch provides generated downloads for a separate app. It is not an
opencodex feature branch and is not intended to be merged into the release branches.
