# LUMA Python Camera downloads

Android camera app preview built with Python 3.12, Chaquopy and CameraX.

- `LUMA-Python-0.2.0.apk`: latest installable preview with offline produce recognition and nutrition lookup.
- `LUMA-Python-0.2.0.apk.sha256`: checksum for the latest APK.
- `LUMA-Python-source.zip`: source and build instructions, excluding private signing files.
- `permissions-and-interactions.md`: Chinese permission and interaction guide.
- `release-info.json`: latest build metadata and validation limits.
- `model-validation.json`: desktop inference checks, not an accuracy benchmark.

On GitHub, open the APK and choose **Download raw file** (the download-arrow button).
Requires Android 7.0 or later and a 64-bit ARM or x86_64 device.
Signed with the same project preview certificate as v0.1.0. Install over the old
version to retain the private album; do not uninstall first.

In the camera, select the **识物** mode and photograph one fruit or vegetable in
the center. Existing album photos can also be recognized from their detail page.
Confirm the suggested name before viewing nutrition, or manually select a food.
22 produce categories have model candidates and 34 foods have reference data.
Nutrition is from USDA SR28 (2015), per 100g raw edible portion; it is not measured
from the photo. Tomatoes, carrots and other unsupported model categories are
available through manual lookup. Installed offline Chinese TTS is required for
the optional spoken summary. No Internet or microphone permission is added.

22 Python tests, 3 QR decoder JVM tests, 2 input-normalization JVM tests and 3
desktop reference-image inference checks passed. The packaged Python nutrition
data was loaded successfully from the final APK archive. Signature, permissions,
bundled model and 16KB alignment checks passed. Device camera recognition, TTS,
flash and native UI still require physical-device testing; software emulators
did not finish booting in this environment. This is a preview, not a store release.

The old `LUMA-Python-0.1.0.apk` is retained as an earlier camera-only preview.

This branch provides generated downloads for a separate app. It is not an
opencodex feature branch and is not intended to be merged into the release branches.
