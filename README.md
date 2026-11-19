# ACADEMIA Android

Android WebView wrapper for the live ACADEMIA Student Hub website.

## Build an APK with GitHub Actions
1. Upload the contents of this project to the root of your `academia-android` GitHub repository.
2. Open **Actions**.
3. Select **Build ACADEMIA Android APK** and tap **Run workflow** (or wait for the push-triggered build).
4. Open the completed workflow run and download the `ACADEMIA-debug-apk` artifact.
5. Extract the downloaded artifact ZIP to get `app-debug.apk`.

This creates a debug APK for testing and direct installation. A release APK for Play Store distribution needs a signing key and a separate release build.

The app loads https://academia-studenthub-ng.netlify.app/ and requires internet access. Supabase credentials remain on the website; do not put a Supabase service-role key in this Android project.
