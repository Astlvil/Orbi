ORBIT v5 by Malel - Skyworth 55 inch Google TV (Android 11). Built on the v3 layout.
1. Unzip, upload the CONTENTS to your GitHub repository (overwrite existing files).
2. Check .github/workflows/build.yml exists (copy in build-workflow-copy.txt).
3. Actions tab: wait for the green tick. Releases: download OrbitTV.apk.
4. TV: Downloader > the release link > Install. Same signing key as before, so it updates v3/v4 in place.
Photo backgrounds and Biglel photos come from Wikimedia Commons and need internet.
Optional home screen: adb shell cmd package set-home-activity com.orbit.tv/.MainActivity
Undo: adb uninstall com.orbit.tv
