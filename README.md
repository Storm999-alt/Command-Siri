<p align="center">
  <img src="logo.png" width="200" height="200">
</p>

<h1 align="center">Command Siri</h1>

<p align="center">
  <strong>Voice-controlled automation for macOS</strong><br>
  Press ⌘⇧Space · Speak · Press again · Run
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-11.0+-blue">
  <img src="https://img.shields.io/badge/Swift-5.9-orange">
  <img src="https://img.shields.io/badge/license-All%20Rights%20Reserved-red">
  <img src="https://img.shields.io/badge/offline-yes-brightgreen">
</p>

<p align="center">
  <b>No internet. No cloud. No accounts. Your voice stays on your Mac.</b>
</p>

---

## ✨ Features

| Category | Commands |
|----------|----------|
| **System** | `shutdown`, `restart`, `sleep`, `lock screen`, `brightness 50`, `volume 30`, `mute`, `unmute` |
| **Apps** | `open Safari`, `close Safari`, `open Chrome and find weather` |
| **Files** | `create file notes.txt`, `open folder Projects`, `zip folder Downloads`, `take screenshot` |
| **Info** | `battery`, `time`, `date`, `disk space`, `memory` |
| **Weather** | `weather London` (requires internet) |
| **Shortcuts** | `run shortcut MyShortcut` |

---

## 🚀 Quick Start

```bash
# 1. Download
curl -LO https://github.com/Storm999-alt/Command-Siri/releases/download/v1.0/Command.Siri.zip

# 2. Unzip
unzip Command.Siri.zip -d CommandSiri

# 3. Move to Applications
mv CommandSiri/Command\ Siri.app /Applications/

# 4. Remove quarantine
xattr -d com.apple.quarantine /Applications/Command\ Siri.app

# 5. Launch
open /Applications/Command\ Siri.app
