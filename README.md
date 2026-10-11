# JK Shorts Android demo

This is a **local HTML demo wrapped in an Android WebView**. It is NOT yet a live multi-user short-video service. Accounts, cloud uploads, public feed, real likes/comments and notifications require backend development. Video selection only works locally in the demo.

## Build on GitHub using a phone
1. Open your GitHub `JK-short` repository.
2. Upload the **contents** of this ZIP to the repository root, preserving directories (`app/`, `.github/workflows/`, etc.). The existing `JK_Shorts_Demo.html` can remain.
3. Open **Actions**, choose **Build JK Shorts APK**, then **Run workflow** (or wait for the push run).
4. When the run succeeds, open the run, scroll to **Artifacts**, download `JK-Shorts-APK`, unzip it and install `app-debug.apk` on your Android phone.

**Important:** GitHub's browser file uploader may not preserve nested paths on all phones. A Git client or GitHub web editor can create paths. Do not upload the ZIP as a single file: it must be extracted into the repository.

Android may warn when installing an APK from outside the Play Store. Only install APKs you built and trust. Debug APK is for testing, not Play Store distribution.
