# Masjid Clock (MOUJ SYNC) — Landing Page

A private, offline-first landing page (`index.html`) for **Masjid Clock**, with the APK hosted directly in the same repository so your main source repo (`moujjcare-cmyk/namaz-app`) can remain completely private.

## Included Files
- `index.html` — Complete mobile-first landing page (MOUJ SYNC dark/light theme, Urdu Nastaleeq + English toggle, live offline QR code generator, multi-video guide tabs, 6-card visual slider, and update notes).
- `Masjid-Clock.apk` — Latest Android APK (~3.8 MB) served directly from this repository.
- `assets/guide-video.mp4` — Compressed installation & permissions walkthrough video (~4.7 MB).
- `assets/Logo.jpg` & `assets/1.jpg` to `assets/6.jpg` — Official logo and 6-card visual Urdu guide.

## Deploy to GitHub Pages
1. Create a new public repository on GitHub (e.g., `masjid-clock-Landing`).
2. Upload `index.html`, `Masjid-Clock.apk`, `README.md`, and the `assets/` folder.
3. Go to **Settings -> Pages -> Branch: `main` / `/ (root)` -> Save**.
4. To release an app update later, simply replace `Masjid-Clock.apk` and update the version notes in `index.html`.
