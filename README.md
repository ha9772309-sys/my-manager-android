# My Manager — Android starter app

This is a native Android starter project with personal/business tasks, PKR income and expense records, a home overview, English/Urdu toggle, and local device storage.

## Build using only an Android phone (GitHub Actions)
1. Create/sign in to a GitHub account in your browser.
2. Create a new repository, for example `my-manager-android`.
3. Upload the contents of this project ZIP to the repository. Make sure the `.github/workflows/android-build.yml` file is included. If your phone's ZIP/file picker hides folders beginning with a dot, create the `.github/workflows` folders in GitHub and add `android-build.yml` using the exact file from this project.
4. Open the repository's **Actions** tab. If prompted, enable workflows.
5. Select **Build My Manager APK**, choose **Run workflow**, then run it.
6. Wait for the workflow to finish successfully.
7. Open the completed workflow run, find **Artifacts**, and download `My-Manager-debug-apk`.
8. Extract the downloaded artifact ZIP. Tap `app-debug.apk` and allow installation from your browser/files app if Android asks.

## Important
- This is source code plus a cloud-build workflow, not a prebuilt APK.
- A successful cloud build is required before installing.
- Android may show an unknown-app warning because this is a debug APK. Only install the APK you built from your own repository.
- Version 1 stores tasks and money records locally on this phone. Uninstalling the app or clearing its data can erase them.
- No cloud sync, notifications, voice commands, or AI chat in this first version.
