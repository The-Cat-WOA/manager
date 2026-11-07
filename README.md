# WoA Bot Android

This repository builds the WoA Crew Bot Android APK with GitHub Actions.

## One-time setup
1. Upload the ZIP you gave ChatGPT to the repository root. Name it exactly `WoA_App(2).zip` (or `WoA_App.zip`).
2. Commit the upload to the `main` branch.
3. Open the **Actions** tab and open **Build APK**.
4. When the run finishes successfully, open it and download the **WoA-Bot-APK** artifact. Extract it to get `app-debug.apk`.

The workflow also uploads **WoA-Build-Log** if the build fails.

The workflow is configured for the current project ZIP layout (`woa-app/settings.gradle.kts`) and enables AndroidX/Jetifier before building.
