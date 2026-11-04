SMART IRRIGATION WEATHER ALERT - ANDROID APP

This folder contains the Android app source code and a GitHub Actions workflow that can build a debug APK in the cloud.

MOBILE-ONLY BUILD STEPS (Android phone):
1. Sign in to GitHub or create a free account at https://github.com.
2. Create a new repository. Give it a name such as smart-irrigation-weather-alert. Choose Public or Private.
3. Upload ALL files and folders from this ZIP into the repository, including the hidden .github/workflows/build-apk.yml file. The easiest way is to extract the ZIP in a file manager, then use GitHub in Chrome and upload the files. Make sure the .github/workflows/build-apk.yml path is preserved.
4. Open the repository's Actions tab. Select "Build Android APK" and tap "Run workflow" if it has not started automatically.
5. Wait for the workflow to finish successfully (the first build can take several minutes).
6. Open the completed workflow run. Under Artifacts, download "smart-irrigation-weather-alert-apk".
7. Extract the downloaded artifact ZIP. It contains the .apk file. Tap the APK to install it. Android may ask you to allow installation from that browser or file manager; only allow it for this APK if you trust the source.

IMPORTANT:
- This is a debug APK for testing, not a Play Store release.
- The APK has not been built or device-tested yet. A successful cloud build is required before it can be installed.
- The app provides irrigation guidance only; it does not operate a pump automatically.
- Crop water values are sample values and should be verified locally before real farm use.
