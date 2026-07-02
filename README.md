<p align="center">
  <img src="assets/logo.png" width="110" alt="Perch logo" />
</p>

<h1 align="center">Perch</h1>
<p align="center"><i>Land a thought. Take off saved.</i></p>

<p align="center">
  A floating note overlay for Android — write anywhere, over any app, without ever opening a notes app.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Android-3DDC84?logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/UI-Jetpack%20Compose-7F52FF?logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/github/v/release/YOUR_USERNAME/perch?color=blue" />
  <img src="https://img.shields.io/github/license/YOUR_USERNAME/perch" />
</p>

---

## 📖 About

Perch is a lightweight note-taking overlay that lives in your notification shade. Tap the tile, and a small floating note panel lands on top of whatever app you're already using — write, save, and dismiss it, all without breaking your flow or touching the app running underneath.

## ✨ Features

### 🌟 Core & Access
- **Quick Settings Tile** — a dedicated tile in the pull-down menu with a custom donut icon
- **Auto-close notification bar** — tapping the tile collapses the shade and instantly launches the overlay
- Custom 3D app logo used consistently across the loading screen, launcher icon, and auth screens

### 🪟 Floating Note Overlay
- **System-alert floating window** that hovers over any other app
- **Draggable & resizable** — drag from the top header, resize via the bottom-right handle
- **Keyboard-aware auto-scroll** (`imePadding`) so the overlay pushes up / scrolls as you type, keeping your text always visible
- **Quick markdown tools** — one-tap Bold, Italic, Strikethrough
- **Image attachments** directly inside the floating note
- **Auto-save indicator** — a brief visual dot confirms your text is being saved as you type

### 🎨 Note Themes & Customization
8 built-in themes, selectable as your default for new notes:
| Colors | Styles |
|---|---|
| Yellow, Blue, Green, Pink | Paper, Clipboard, Dark, Neon |

Text, cursor, and icon colors auto-adjust for contrast against each theme (e.g. white text on Dark/Neon, dark text on Paper/Yellow).

### 📁 Storage & Organization
- **Local-first** — notes are stored entirely on-device in a Room database, plain text/markdown, fully offline (no cloud dependency)
- **Bulk folder import** — pick a local folder and Perch recursively imports every `.txt` / `.md` file, preserving content and folder structure
- Every note tracks creation/edit timestamps and its folder/category

### 📱 Main App
- Shimmering skeleton loading screens while notes load from the database
- Notes dashboard with search, filtering, and List/Grid view toggle
- Full-screen editor for opening and editing notes outside the overlay

## 📸 Screenshots

| Overlay | Themes | Notes Dashboard |
|---|---|---|
| _add screenshot_ | _add screenshot_ | _add screenshot_ |

*(Tip: a short GIF of the overlay landing + auto-scrolling sells this app far better than static screenshots — most of what makes Perch nice to use is the motion.)*

## 🚀 Installation

1. Grab the latest APK from the [Releases](../../releases) page
2. Enable **Install from unknown sources** for your browser/file manager (Android will prompt you automatically)
3. Install, then grant the **"Display over other apps"** permission when asked — this is what powers the overlay
4. Add the **Perch tile** to your Quick Settings panel (swipe down twice → pencil/edit icon → drag Perch in)

> **A note on security warnings:** since this isn't distributed via the Play Store yet, some antivirus apps (Avira in particular) may flag the APK as "suspicious" on first install. This is a reputation-based false positive common to all self-signed, non-Play-Store apps that use the overlay permission — not a sign of actual malicious code. Feel free to verify independently via [VirusTotal](https://www.virustotal.com).

## 🛠️ Built With

- Kotlin
- Jetpack Compose
- Room (local database)
- Android `SYSTEM_ALERT_WINDOW` / `WindowManager` (floating overlay)
- `TileService` (Quick Settings Tile)

## 📱 Compatibility

Currently targeting Android [X] and up. Working on broader device support — see Roadmap.

## 🗺️ Roadmap

- [ ] Full compatibility pass across older and newer Android versions
- [ ] Liquid Glass note theme
- [ ] Additional themes (Terminal, Blueprint, Kraft Paper, Graph Paper, Midnight Ink)
- [ ] Gesture-based activation (alternative to the Quick Settings tile)
- [ ] Optional app lock (PIN/biometric)

## 🤝 Contributing

This is currently a solo project, but issues, suggestions, and pull requests are welcome — feel free to open one.

## 📄 License

Distributed under the MIT License. See `LICENSE` for details.

## 👤 Author

**Alight**
[GitHub](https://github.com/YOUR_USERNAME) · [Twitter/X](#) · [Contact](#)
