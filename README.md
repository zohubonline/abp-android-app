# CWK | Chanmari West Kohhran Android App

GitHub Actions build-ready Android WebView app.

Website:
https://believe-church-builder-hy5hukqnfrkapyqp.hostingersite.com/

## APK build without Android Studio

1. Create a new GitHub repository.
2. Upload ALL files/folders from this project to the repository root.
   `.github` must also be uploaded.
3. Make sure the default branch is `main`.
4. Open the repository's **Actions** tab.
5. Select **Build CWK Android APK**.
6. Click **Run workflow**.
7. Wait until the build has a green check mark.
8. Open the completed workflow.
9. Under **Artifacts**, download **CWK-Android-APK**.
10. Extract it and install `CWK-Chanmari-West-Kohhran.apk` on Android.

The workflow can also build automatically whenever code is pushed to `main`.

No Android Studio, local Android SDK, or local Gradle installation is required.
