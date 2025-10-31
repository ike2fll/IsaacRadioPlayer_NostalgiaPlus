# Nostalgia‑Plus Radio (Ready to Build)

- Full‑screen background uses your provided logo
- Play / Stop buttons
- Streams: https://listen.samcloud.com/w/143377?type=mp3
- GitHub Actions included to build a Debug APK

## Steps
1. Create a new empty GitHub repo.
2. Upload this folder (all files) to the repo.
3. Go to Actions → run **Android APK (Debug)**.
4. Download artifact **app-debug-apk** and install on your phone.

To change stream URL: edit `MainActivity.kt` → `streamUrl`.