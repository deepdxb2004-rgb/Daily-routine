# Deep Daily Routine

A lightweight, mobile-friendly Progressive Web App (PWA) for daily routine reminders and habit tracking. No build tools or paid services are required.

## Features
- Water tracker with an editable daily target
- Daily habits for meals, toilet routine, movement, fruit/fibre and sleep wind-down
- Cigarette counter for awareness and progress tracking
- Editable wake/sleep times and reminder interval
- Local device storage; no account or backend required
- Installable on Android from a GitHub Pages URL
- Basic offline caching after first load

## Publish with GitHub Pages
1. Create a new repository on GitHub, for example `deep-daily-routine`.
2. Upload **all files in this folder** (`index.html`, `manifest.webmanifest`, `icon.svg`, `sw.js`, and `README.md`) to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish. Your app URL will look like `https://YOUR-USERNAME.github.io/deep-daily-routine/`.
7. Open that URL in Chrome on Android. Use Chrome's menu → **Add to Home screen** (or **Install app** if shown).

## Reminders and notifications
The app can show browser notifications while it is open and notification permission has been granted. Mobile browsers may suspend a web app when it is closed, so this GitHub Pages version cannot guarantee exact-time reminders while fully closed. Reliable background push reminders require a push service/backend or a native Android app.

## Privacy and data
The app stores routine data in the browser's local storage on the device. Clearing browser site data can erase the stored tracker data. There is no sign-in, analytics, or external data transmission.

## Customise
Open the app's settings panel to change wake time, sleep time, hydration target and reminder interval. The default hydration target is a moderate starting point, not a medical prescription; adjust for activity, climate and any clinician-advised fluid restriction.
