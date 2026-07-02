<p align="center">
  <img src="assets/logo.png" width="100" alt="Perch logo" />
</p>

<h1 align="center">Perch</h1>
<p align="center"><i>Land a thought. Take off saved.</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Android-3DDC84?logo=android&logoColor=white" />
  <img src="https://img.shields.io/github/license/YOUR_USERNAME/perch" />
</p>

<p align="center">
  <img src="assets/hero.gif" width="600" alt="Perch overlay in action" />
</p>

---

I kept losing thoughts mid-task because by the time a notes app opened, whatever I wanted to write down was already gone. So I built Perch — a note that just shows up on top of whatever you're already doing, instead of making you leave it.

Tap the Perch tile in your notification shade (same place as your Wi-Fi and Bluetooth toggles), and a small note lands right over your current screen. Write, close it, done. The app underneath never even notices it happened.

## What it does

- **One tap from anywhere** — a Quick Settings tile opens the note, no matter what app you're in
- **Write and go** — drag it, resize it, close it. It saves itself as you type, no save button needed
- **Add images**, format text with quick bold/italic/strikethrough buttons, right inside the note
- **8 note styles** to choose from — classic yellow sticky, paper, clipboard, dark, neon, and more
- **Everything stays on your device** — notes are stored locally in plain markdown, nothing goes to a server
- **Bring your existing notes in** — import a whole folder of `.txt`/`.md` files in one go

## Screenshots

<p align="center">
  <img src="assets/screenshot-overlay.png" width="260" />
  <img src="assets/screenshot-themes.png" width="260" />
  <img src="assets/screenshot-dashboard.png" width="260" />
</p>

## Getting Perch

1. Download the latest APK from [Releases](../../releases)
2. Install it (Android will ask you to allow installs from this source — that's normal for anything outside the Play Store)
3. Grant the "display over other apps" permission when prompted — that's what makes the overlay work
4. Add the Perch tile to your Quick Settings (swipe down twice → edit icon → drag Perch in)

> Some antivirus apps flag non-Play-Store APKs that use the overlay permission as "suspicious" — this is a reputation-based false positive, not a sign of anything malicious. You're welcome to verify independently on [VirusTotal](https://www.virustotal.com).

## Built with

Kotlin, Jetpack Compose, Room.

## License

MIT — see `LICENSE`.

## Made by

**Alight** — [GitHub](https://github.com/Alightttt) [X/Twitter] (https://x.com/0xalyt)
