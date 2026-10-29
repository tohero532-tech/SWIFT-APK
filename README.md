# Swift Browser

A lightweight, fast Android browser with Google as the search engine.

## Features
- Google search from the address bar, with live Google suggestions as you type
- Speed-dial home page
- Multiple tabs
- Built-in ad blocker (on by default)
- Data saver (blocks images)
- Night mode, desktop-site mode, incognito mode
- Downloads to your phone's Downloads folder
- File upload, full-screen video, opens WhatsApp / phone / Play Store links in their apps
- Can be set as your default browser
- No extra libraries — tiny APK

## Get the APK (no software needed — free on GitHub)
1. Create a free account at github.com and click **New repository** (any name, Public or Private).
2. Click **uploading an existing file**, drag in **everything inside this folder** (including the hidden `.github` folder — easiest is to upload the unzipped folder contents), then **Commit changes**.
3. Open the **Actions** tab. A build named "Build APK" starts automatically (about 3–5 minutes).
4. When it shows a green tick, open it and download **SwiftBrowser-APK** at the bottom. Unzip it → `SwiftBrowser.apk`.
5. Copy to your phone, tap it, and allow "Install unknown apps" when asked.

Tip: on GitHub's web uploader, hidden folders can be skipped. If the Actions tab says there are no workflows, click **Add file → Create new file**, name it `.github/workflows/build-apk.yml`, and paste the contents of that file.

## Or build with Android Studio
Open this folder in Android Studio → wait for sync → **Build → Build App Bundle(s) / APK(s) → Build APK(s)**.
