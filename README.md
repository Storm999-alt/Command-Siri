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
  <img src="https://img.shields.io/badge/license-All%20Rights%20Reserved-red">
  <img src="https://img.shields.io/badge/offline-yes-brightgreen">
</p>

<p align="center">
  <b>No internet. No cloud. No accounts. Your voice stays on your Mac.</b>
</p>

---

<p align="center">
  <strong>✨ &nbsp; F E A T U R E S &nbsp; ✨</strong>
</p>

<p align="center">
  <sub>what you can do with your voice</sub>
</p>

| Category | Commands |
|----------|----------|
| **System** | `shutdown`, `restart`, `sleep`, `lock screen`, `brightness 50`, `volume 30`, `mute`, `unmute` |
| **Apps** | `open Safari`, `close Safari`, `open Chrome and find weather` |
| **Files** | `create file notes.txt`, `open folder Projects`, `zip folder Downloads`, `take screenshot` |
| **Info** | `battery`, `time`, `date`, `disk space`, `memory` |
| **Weather** | `weather London` (requires internet) |
| **Shortcuts** | `run shortcut MyShortcut` |

---

## Quick Start

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
```

--- 

## Usage

**Voice mode**
1. Press <kbd>⌘</kbd> + <kbd>⇧</kbd> + <kbd>Space</kbd>
2. Speak a command
3. Press <kbd>⌘</kbd> + <kbd>⇧</kbd> + <kbd>Space</kbd> again to execute

**Text mode**
1. Press <kbd>T</kbd>
2. Type your command
3. Press <kbd>Enter</kbd> to execute

**Settings**

-- Click the slider icon (bottom center) to adjust:
-- Microphone sensitivity
-- Visual effects intensity
-- Sound hints
-- Quiet start
-- Window behavior on focus loss

---

## Commands reference

**System**
```text
shutdown                    → Shuts down your Mac
restart                     → Restarts your Mac
sleep                       → Puts your Mac to sleep
lock screen                 → Locks the screen
brightness 50               → Sets brightness (0-100)
volume 30                   → Sets volume (0-100)
mute                        → Mutes audio
unmute                      → Unmutes audio
```

**Applications**
```text
open Safari                 → Launches Safari
close Safari                → Quits Safari
open Chrome and find cats   → Searches in Chrome
```

**Files & Folders**
```text
create file test.txt        → Creates file on Desktop
open folder Projects        → Opens ~/Documents/Projects
zip folder Downloads        → Archives Downloads folder
take screenshot             → Saves screenshot to Desktop
```

**System Info**
```text
battery                     → Shows battery percentage
time                        → Shows current time
date                        → Shows today's date
disk space                  → Shows free disk space
memory / ram                → Shows memory usage
```

**Weather**
```text
weather London              → Shows temperature and conditions
weather moscow              → Works for any city
```
*Internet required for weather only*
