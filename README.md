# stemflow: downloads

stemflow turns a song into a ready-to-play **Ableton Live 12** set: stems, MIDI, chords, sections and genre drums,
written straight into a Live set built from your own Live install. It runs on your computer and uses **no generative
AI**: the models only analyse the song.

This repository only hosts the installers. The app is closed source. Website: **https://stemflow-five.vercel.app**

## Download

**[Download for Mac (Apple Silicon)](https://github.com/Alejandro-Candela/stemflow-releases/releases/latest/download/stemflow-mac-arm64.dmg)**
· **[Download for Windows (x64)](https://github.com/Alejandro-Candela/stemflow-releases/releases/latest/download/stemflow-win-x64.exe)**
· [all versions](https://github.com/Alejandro-Candela/stemflow-releases/releases)

The Windows version is the first Windows alpha: it hasn't met many PCs yet.

## What you need

- A Mac with Apple Silicon (M1 or later), macOS 13 or newer, or a Windows 10/11 x64 PC.
- Ableton Live 12 (any edition).
- About 10 GB free and an internet connection for the first launch.

## Install on a Mac (alpha: not signed by Apple yet)

1. Open the DMG and drag **stemflow** into Applications.
2. Open stemflow. macOS says it can't check it for malicious software: click **Done**.
3. Open **System Settings → Privacy & Security**, scroll down to "stemflow was blocked…", click **Open Anyway** and
   confirm with your password. Once per version.
4. The first launch sets everything up (a few minutes, several GB). Keep it open.

Alpha versions don't update themselves on a Mac: download the new one and replace the app.

## Install on Windows (alpha: not signed yet)

1. Run **stemflow-win-x64.exe**. Windows says it protected your PC: click **More info → Run anyway**.
2. It installs for you only (no admin password) and opens. The first launch sets everything up (a few minutes,
   several GB). Keep it open.

New versions: download and run the new installer.

**Something broke?** In stemflow, **Help → Show Logs**, and send `setup.log` and `engine.log` to the person who
invited you. stemflow sends nothing anywhere by itself.
