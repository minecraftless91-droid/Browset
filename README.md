# Android APK Project (GitHub Actions Ready)

## How to Build the APK on Mobile Using GitHub
1. Extract this ZIP archive using **ZArchiver**.
2. Create a new repository on **GitHub** in your browser.
3. Upload all extracted files (make sure the `.github/workflows/build-apk.yml` folder is included) or push via Termux/Git.
4. Open the **Actions** tab in your GitHub repository.
5. Wait for **Build Android Debug APK** to finish (~2-3 minutes), then download `app-debug-apk` from **Artifacts**, extract it, and install `app-debug.apk`.

## Customizing Your App
- **App UI / Game Code:** Replace `app/src/main/assets/index.html` with your own HTML/JS/CSS code.
- **App Name:** Edit `app/src/main/res/values/strings.xml`.
- **Package ID:** Edit `applicationId` in `app/build.gradle`.
