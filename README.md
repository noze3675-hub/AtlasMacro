# AtlasMacro

(Official website) https://atlaslap.com

Advanced real-time mouse & keyboard macro tool for gamers and power-users.  
Raw input recording, flexible playback modes, profiles and editable mouse paths.  
Runs locally · No telemetry.

<img width="722" height="437" alt="A" src="https://github.com/user-attachments/assets/6ef4990a-0be6-436a-9f77-75e4ece30726" />


> This repository is for documentation, changelogs and issue tracking.  
> The **source code is private** and is **not** published on GitHub.

---

# What is AtlasMacro?

**AtlasMacro** is a Windows desktop app that records raw mouse and keyboard input and replays it with high precision.

It is designed for:

- **Gamers** – recoil patterns, micro-adjustment sequences, repeatable movement paths, consistent timings.
- **Power-users & creators** – repetitive click/keyboard workflows, UI automation, testing, and timing-critical macros.

Unlike simple “macro recorders”, AtlasMacro focuses on **raw input, profiles and editing tools** so you can fine-tune *how* the macro behaves instead of just playing back a blind recording.

---


# Recording & live feedback

- Records **raw mouse** and **keyboard** input with millisecond timing.
- Real-time delta display so you can see movement while recording.
- Macro log view that groups moves and clicks into readable lines instead of a raw spam of events.

# Playback & control

- **Play modes**:  
  - **Once** – play macro a single time.  
  - **Loop** – repeat until stopped.  
  - **Hold** – play only while a hotkey is held.
- **Mouse start modes**:  
  - Free mouse,  
  - Center lock,  
  - Lock at current position.
- Global speed control with scaling for delays, tuned for smooth and natural feeling playback.
- Smoothing options for tiny delays and interpolation steps to avoid “teleport” mouse movement.

# Profiles & workflow

- Up to **10 profiles** with per-profile macro files, names and hotkeys.
- Quick **profile switching** via hotkeys (Prev/Next) – ideal for multi-weapon or multi-setup games.
- Each profile can load its own `.amc` macro file from the AtlasMacro data folder.
- Profile configuration can be saved/loaded as `.apf` files for easy backup and sharing.

<img width="458" height="427" alt="C" src="https://github.com/user-attachments/assets/1ba81fb2-ec3b-423d-a38b-30debf65eb32" />

# Advanced path editing

- Built-in **mouse path editor** window:
  - Visualizes the recorded trajectory.
  - Allows you to smooth or adjust points before committing changes.
- Edited paths are written back into the macro so you can refine one recording instead of re-recording over and over.

<img width="725" height="547" alt="B" src="https://github.com/user-attachments/assets/90327927-4b89-4971-b790-8919a8c8949e" />

# “Eye” overlay window

- Optional compact **Eye** window that shows at a glance:
  - Active profile name (P1–P10),
  - Master ON/OFF state,
  - Recording status (**REC / NO REC**),
  - Playback status (**PLAY / NO PLAY**).
- Designed to sit on a second monitor or on top of a game for quick status feedback without opening the full UI.

# Hotkeys & hold logic

- Separate hotkeys for:
  - **Record**
  - **Play**
  - **Profile switching**
  - **Hold** modifier
- Hold binding can invert features while a key is held (for example, temporarily disabling macros while a key is pressed).
- Hotkey fields are captured directly from the keyboard so you don’t have to remember key codes.

# tability & safety

- All macro data is stored under `C:\AtlasMacro` in clearly separated folders (Data, Profile_Save, etc.).
- Profiles and macro files are simple text/binary formats designed for reliability.
- Focus on predictable behavior — no hidden automation outside what you configure.

# Licensing

AtlasMacro is a **commercial (Pro) tool**.  
The app includes a small activation window where you enter your license key. The license is verified online and then stored locally on your machine.

- License status and time remaining are shown inside the main UI.
- Activation is bound to your hardware ID; there is no always-online requirement during normal macro use.

---

# System requirements

- **OS:** Windows 10 or Windows 11 (64-bit)
- **Input:** Standard mouse & keyboard (raw input capable)
- **Internet:** Required only for initial license activation
- **Permissions:** Runs as a normal user; no kernel drivers or intrusive hooks

---

# Download

The installer and latest builds are available on the official website:

**Main site:** https://atlaslap.com

All downloads, updates and pricing are managed from the website, not from GitHub.

---

# FAQ (short)

**Is this a cheat / injector?**  
No. AtlasMacro does not inject into games or modify game memory.  
It works as a **desktop macro tool** that sends mouse/keyboard input, similar to other macro software.

**Is the source code open?**  
No. AtlasMacro is a closed-source commercial product. This repository exists for public information and issue tracking.

**Does it send my macros to a server?**  
No. Macros and configuration data are stored locally under `C:\AtlasMacro`. Telemetry is not required for normal use.

---

# Support & feedback

If you have questions, bug reports or feature requests:

- Open a GitHub **Issue** in this repository, or  
- Use the support / contact options on the website.
- sopport@atlaslap.com

AtlasMacro is built and maintained by a single developer — thoughtful feedback is highly appreciated.
