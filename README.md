# Oabulk — OfficeAlly Bulk Scraper (Android)

Android app: paste Transaction IDs, it builds the OfficeAlly links, scrapes them in parallel in the background and exports CSV.

## Build APK with GitHub Actions
1. Upload this whole project (including the hidden `.github` folder) to a GitHub repo
2. Open the **Actions** tab -> **Build oabulk** -> wait for the green tick (or **Run workflow**)
3. Open the finished run -> **Artifacts** -> download `oabulk-apk` -> unzip -> install `app-debug.apk`

## Use
1. Tap **Login / OfficeAlly kholo**, log in, tap the green "Login ho gaya" button
2. Paste IDs (one per line), set Parallel (start with 3), tap **Start**
3. Tap **CSV Download** (saved to Downloads and share sheet opens)

> Exports contain patient data. Share only with authorized people.
