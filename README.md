# Apple Music TV 🎵

A lightweight, dedicated Google TV and Android TV web wrapper client for Apple Music, designed to sit cleanly on Leanback launchers and [Projectivy Launcher](https://github.com/spocky/mLauncher).

---

## Features

- **Native TV Launcher Tile:** Full Leanback launcher integration with a 16:9 custom banner optimized for Projectivy and default Android TV home rows.
- **Widescreen Experience:** Automatically requests the desktop Apple Music web player (`music.apple.com`) scaled for 1080p and 4K displays.
- **Session Persistence:** Remembers your login, cookies, and music queue across app restarts.
- **Hardware Remote Support:** Maps the remote `Back` button to in-page navigation and history.

---

## Installation

### Method 1: Sideload via Downloader App (Recommended for TV)
1. Install the **Downloader** app from the Google TV / Android TV Play Store.
2. In Downloader's URL box, enter the direct download link for the latest `.apk` from the [Releases](../../releases) tab.
3. Select **Install** when prompted (ensure *Install unknown apps* permission is granted to Downloader in TV Settings).

### Method 2: Sideload via USB or LocalSend
1. Download `app-debug.apk` from the latest [Release](../../releases).
2. Transfer it to your TV using a USB flash drive or a file transfer utility like **LocalSend** / **Send Files to TV**.
3. Open a TV file manager (e.g., AnExplorer, File Commander) and click the APK to install.

---

## Remote Navigation & Tips

Because the underlying engine is Apple's desktop web application, directional D-Pad focus can vary depending on active menus. 

For the smoothest control:
- **Phone Trackpad:** Use the built-in trackpad feature in the official **Google TV** or **Google Home** mobile app on your phone.
- **Mouse Utility:** Use utilities like **Mouse Toggle for Android TV** or connect a physical Bluetooth mouse / air-mouse remote.
- **Projectivy Launcher Customization:** Press and hold **OK/Select** on the Apple Music home tile in Projectivy to adjust card dimensions, banner art, or focus border animations.

---

## Building from Source

1. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<YOUR-USERNAME>/AppleMusicTV.git
