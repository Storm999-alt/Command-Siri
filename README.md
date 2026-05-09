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
  <strong>■ ■ ■  &nbsp; F E A T U R E S &nbsp; ■ ■ ■ </strong>
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

<p align="center">
  <strong>■ ■ ■  &nbsp; Q U I C K &nbsp; S T A R T &nbsp; ■ ■ ■ </strong>
</p>

<p align="center">
  <sub>install & run in 5 commands</sub>
</p>

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

<p align="center">
  <strong>■ ■ ■  &nbsp; U S A G E &nbsp; ■ ■ ■ </strong>
</p>

<p align="center">
  <sub>voice mode · text mode · settings</sub>
</p>

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

<p align="center">
  <strong>■ ■ ■  &nbsp; C O M M A N D S &nbsp; R E F E R E N C E &nbsp; ■ ■ ■ </strong>
</p>

<p align="center">
  <sub>you can speak naturally · not just fixed phrases</sub>
</p>

**You don't have to memorize exact words. Say it your way.**

| Instead of | You can say |
|------------|-------------|
| `shutdown` | "turn off my computer", "power down", "shut down" |
| `restart` | "reboot", "restart my mac" |
| `sleep` | "go to sleep", "sleep mode" |
| `lock screen` | "lock my mac", "lock screen" |
| `brightness 50` | "set brightness to 50", "make screen darker" |
| `open Safari` | "launch Safari", "start Safari" |
| `close Safari` | "quit Safari", "shut Safari" |

---

<p align="center">
  <strong>◈ ◈ ◈  &nbsp; N A T U R A L &nbsp; L A N G U A G E &nbsp; E X A M P L E S &nbsp; ◈ ◈ ◈</strong>
</p>

<p align="center">
  <sub>speak as you wish — the parser understands you</sub>
</p>

<br>

| You say | Command understands |
|:--------|:-------------------|
| *"hey, can you open Safari and find weather forecast"* | `open Safari.app and search "weather forecast"` |
| *"set volume to 30 percent"* | `volume 30%` |
| *"what's the battery level right now"* | `battery` |
| *"show me current time"* | `time` |
| *"please, open Telegram"* | `open Telegram.app` |
| *"create a file called notes"* | `create file notes.txt` |
| *"sleep this computer"* | `sleep` |
| *"mute the sound please"* | `mute` |
| *"unmute, thanks"* | `unmute` |
| *"restart my macbook right now"* | `restart` |
| *"close terminal please"* | `close Terminal.app` |
| *"lock my screen"* | `lock screen` |
| *"show me memory on the macbook"* | `memory`|

<br>

<p align="center">
  <sub>· no memorization · just speak naturally ·</sub>
</p>

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

---

<p align="center">
  <strong>  &nbsp; L I C E N S E &nbsp; </strong>
</p>

<p align="center">
  <sub>personal · non-commercial · all rights reserved</sub>
</p>

<p align="center">
  © 2026 Paul. All rights reserved.
</p>

<p align="center">
  <strong>Personal, non-commercial use only.</strong>
</p>

<p align="center">
  <code>✓</code> Download and use for free<br>
  <code>✓</code> Share the link with friends<br>
  <code>✗</code> Commercial sale or distribution<br>
  <code>✗</code> Modifying and redistributing<br>
  <code>✗</code> Removing author credits
</p>

<p align="center">
  <sub>· proprietary software · all rights reserved ·</sub>
</p>
