# Machan AI Android

Starter Android WebView app for the hosted Machan AI website.

## Build APK with GitHub Actions
1. Upload all files in this project to the root of your `machan-ai-android` GitHub repository, preserving folder paths.
2. Open the repository's **Actions** tab.
3. Choose **Build Machan AI APK** and run the workflow, or push a commit to `main`.
4. Open the completed workflow run and download the `machan-ai-debug-apk` artifact.

This starter app wraps the hosted website and requests microphone permission for browser speech features. It does not yet implement a wake word or long-press power-button integration. Those require additional native Android work and device-specific testing.
