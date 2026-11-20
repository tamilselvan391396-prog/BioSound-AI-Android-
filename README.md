# BioSound AI — Android WebView wrapper

This Android project packages the existing BioSound AI website in a native Android shell.

Website: https://tamilselvan391396-prog.github.io/Sound-Ai-v2.2/

## Build on an Android phone using GitHub

1. Download and extract this ZIP on your phone.
2. Open https://github.com/new and create a **Public** repository named `BioSound-AI-Android`.
3. In the new repository choose **Add file → Upload files**.
4. Upload the *contents* of this extracted folder (including `.github`, `app`, and the Gradle files), then commit to `main`.
5. Open the repository's **Actions** tab. If prompted, enable GitHub Actions.
6. Open **Build BioSound AI APK** and tap **Run workflow** (or wait for the push-triggered build).
7. When the run turns green, open it, scroll to **Artifacts**, and download `BioSound-AI-APK`.
8. Extract the downloaded artifact ZIP and tap `app-debug.apk` to install. Android may ask you to allow installs from your browser or file manager.

## Important

- This is an online WebView app: the phone needs internet to load the website and model.
- Android will request microphone permission. Grant it for live listening.
- The wrapper requests microphone access only; it does not request storage, contacts, or location.
- The website must continue to be available over HTTPS.
- This creates a debug APK for testing/sideloading, not a signed Play Store release.
- Test live microphone listening after installation. WebView microphone support can depend on the website's browser APIs and the Android System WebView version.
