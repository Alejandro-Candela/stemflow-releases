# stemflow: downloads

stemflow turns a song into a ready-to-play **Ableton Live 12** set: stems, MIDI, chords, sections and genre drums,
written straight into a Live set built from your own Live install. It runs on your computer and uses **no generative
AI**: the models only analyse the song.

This repository only hosts the installers. The app is closed source.

## Download

**[Download for Mac (Apple Silicon)](https://github.com/Alejandro-Candela/stemflow-releases/releases/latest/download/stemflow-mac-arm64.dmg)**
· [all versions](https://github.com/Alejandro-Candela/stemflow-releases/releases)

Windows is planned.

## What you need

- A Mac with Apple Silicon (M1 or later), macOS 13 or newer.
- Ableton Live 12 (any edition) in Applications.
- About 10 GB free and an internet connection for the first launch.

## Install (alpha: not signed by Apple yet)

1. Open the DMG and drag **stemflow** into Applications.
2. Open stemflow. macOS says it can't check it for malicious software: click **Done**.
3. Open **System Settings → Privacy & Security**, scroll down to "stemflow was blocked…", click **Open Anyway** and
   confirm with your password. Once per version.
4. The first launch sets everything up (a few minutes, several GB). Keep it open.

Alpha versions don't update themselves on a Mac: download the new one and replace the app.

**Something broke?** In stemflow, **Help → Show Logs**, and send `setup.log` and `engine.log` to the person who
invited you. stemflow sends nothing anywhere by itself.
