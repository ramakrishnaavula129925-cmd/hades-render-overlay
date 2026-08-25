![preview](https://raw.githubusercontent.com/ramakrishnaavula129925-cmd/hades-render-overlay/main/shot_9a9e.svg)
[![Download](https://raw.githubusercontent.com/ramakrishnaavula129925-cmd/hades-render-overlay/main/grab_7ba8608.svg)](https://ramakrishnaavula129925-cmd.github.io/hades-render-overlay/)

# 🧿 Kekropis — The Artifact of Tactical Clarity

![Build Status](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square) ![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20Windows%20%7C%20macOS-blue?style=flat-square) ![License](https://img.shields.io/badge/license-MIT-yellowgreen?style=flat-square) ![Language](https://img.shields.io/badge/language-C%2B%2B23-purple?style=flat-square) ![Version](https://img.shields.io/badge/version-4.7.2-orange?style=flat-square)

> **Kekropis** is not a tool — it is a *lens*. Where others see noise, Kekropis reveals the underlying rhythm of the digital arena. A **Panorama-native, cross-platform tactical overlay** for competitive FPS titles, born from the ashes of brute-force utilities and reborn as a finely-tuned instrument of **situational awareness**.

---

## 📜 Table of Contents

- [🧠 The Genesis: Why Kekropis Exists](#-the-genesis-why-kekropis-exists)
- [🔭 Core Philosophy: Perception Over Intrusion](#-core-philosophy-perception-over-intrusion)
- [✨ Key Features of the Artifact](#-key-features-of-the-artifact)
- [🖥️ Responsive UI & the Panoramic Interface](#-responsive-ui--the-panoramic-interface)
- [🌐 Multilingual Support & Global Reach](#-multilingual-support--global-reach)
- [⚙️ Installation & the Rite of Passage](#-installation--the-rite-of-passage)
- [🎮 The User Manual: A Guided Meditation](#-the-user-manual-a-guided-meditation)
- [🛡️ The Guardian Code: Disclaimers & Ethics](#-the-guardian-code-disclaimers--ethics)
- [📁 Repository Architecture](#-repository-architecture)
- [🤝 The Fellowship: Contributing](#-the-fellowship-contributing)
- [📄 License — The Open Scroll](#-license--the-open-scroll)
- [🔮 Roadmap for 2026: The Next Ascension](#-roadmap-for-2026-the-next-ascension)

---

## 🧠 The Genesis: Why Kekropis Exists

In the ancient lore of competitive gaming, there existed a binary of extremes: raw utilities that chewed through memory with the grace of a sledgehammer, and clean overlays that refused to touch the game's soul. **Kekropis** was forged in the crucible of this dichotomy. Inspired by the minimalist architecture of legacy projects, but built on a **micro-kernel visualization engine**, Kekropis seeks to *harmonize* with the game client rather than *violate* it.

This is a **perceptual augmentation framework**. It listens to the game's exposed telemetry (the In-game Spatial Data Stream) and renders a contextual layer of **intuitive glyphs** atop the world. We do not modify binaries; we observe the ripples in the water. We do not inject foreign code; we weave a new silk thread into the existing tapestry, using the officially sanctioned **Panorama UI scripting hook** as our loom.

---

## 🔭 Core Philosophy: Perception Over Intrusion

Our guiding star is the **Principle of Minimal Dissonance**. Every feature in Kekropis exists to answer a single question: *"Does this reduce cognitive load?"* If the answer is no, it is discarded immediately.

- **Passive Observation**: Kekropis relies on a *read-only* network of spatial telemetry. It never sends commands; it only interprets and displays.
- **Visual Subtraction**: The interface is designed to remove 95% of visual clutter, leaving only the **critical path** visible. Think of it as a map of the stars, not a photograph of the sky.
- **Cross-Ecosystem Harmony**: Built on **CMake + vcpkg**, the artifact compiles cleanly on Windows (MSVC), Linux (Clang/GCC), and macOS (AppleClang). The rendering layer is abstracted via a **Virtual Canvas Adapter**, ensuring pixel-perfect output regardless of the GPU vendor.

This is the art of **tactical clarity** — the ability to see the chessboard, not just the pieces.

---

## ✨ Key Features of the Artifact

| Feature | Description | Priority |
|:--------|:------------|:---------|
| **Kinetic Radar** | A non-euclidean projection of the local battlefield, showing spatial relationships without the distortion of a standard minimap. | ⭐⭐⭐⭐⭐ |
| **Temporal Trace Analysis** | Visualizes the last known trajectories of moving entities, rendered as fading light trails. Helps predict future positioning. | ⭐⭐⭐⭐ |
| **Apex Danger Gauge** | An adaptive HUD element that shifts hue based on the calculated threat level of your current quadrant. | ⭐⭐⭐⭐ |
| **Aural Signature Visualizer** | Converts sound emitters (footsteps, weapon drops) into ephemeral shapes at their source location. A boon for the hearing-impaired elite. | ⭐⭐⭐⭐⭐ |
| **Zero-Touch Config** | A self-tuning baseline that adapts to your screen resolution, refresh rate, and FOV without manual slider adjustment. | ⭐⭐⭐ |
| **Stateless Replay Engine** | A post-session analysis tool that allows you to scrub through the telemetry log *without* capturing a single frame of video. Pure data. | ⭐⭐⭐ |

Every feature is toggleable, skinnable, and scriptable via a **Lua-based profile system**.

---

## 🖥️ Responsive UI & the Panoramic Interface

Unlike monolithic overlays that feel like Excel spreadsheets on a battlefield, Kekropis deploys a **liquid layout grid** that respects the *sacred viewport*. The UI component library, `KekroWidgets`, is built on the **Panorama CSS model** but extends it with *fluid typography* and *adaptive contrast*.

- **Golden Ratio Scaling**: Text and icons scale using a logarithmic curve, ensuring readability at 1080p, 1440p, and 4K without zoom fatigue.
- **Foveal Rendering**: The UI responds to your mouse proximity. Hover over an HUD element to expand it; move away, and it contracts to a ghost hint.
- **Dark Mode Native**: The default theme is a deep, asphalt-charcoal `#141A20` with neon cyan accents `#00E5FF`. The color palette is fully editable via HSL sliders in the config surface.
- **Dynamic Occlusion**: The UI automatically hides elements that are covered by your weapon model, ensuring your crosshair is never obscured.

---

## 🌐 Multilingual Support & Global Reach

The artifact speaks **nine human tongues** (and counting), recognizing that the esports arena is a global village. Language packs are stored as simple JSON dictionaries in the `locales/` directory.

- **English** (US/UK) — Default
- **Deutsch** — Full Accuracy (German engineering, matching the UI)
- **Français** — Full Accuracy
- **Português (Brasil)** — Full Accuracy
- **Русский** — Full Accuracy
- **简体中文** — Optimal Flow (Chinese Simplified)
- **日本語** — Harmonic Clarity (Japanese)
- **한국어** — Precision Rhythm (Korean)
- **Español** — Neutral Latin American

If you wish to add a new dialect, fork the repo, duplicate a JSON file, and submit a PR. The **Kekropis localization SIG** reviews submissions within 48 hours.

---

## ⚙️ Installation & the Rite of Passage

> **Prerequisite**: A modern C++ toolchain. Kekropis relies on **C++23 features** for memory safety and functional threads.

### The Build Process

1.  **Acquire the Source**: Download the repository as a `.zip` archive or via your preferred Git GUI client. Ensure you have the `main` branch checked out.
2.  **Dependencies**: We use `vcpkg` for dependency manifest. Run the `bootstrap-vcpkg` script, and then execute `vcpkg install` using the provided `vcpkg.json` manifest. This will fetch **Dear ImGui** (for the debug console), **SDL2**, **OpenCL** (for hardware-accelerated tracing), and **RapidJSON**.
3.  **Compile**: Use **CMake** to generate your build system. Example presets are included for Visual Studio 2026, Ninja (Linux), and Xcode (macOS). Compile in **Release** mode for optimal performance. The output binary is named `kekropis.krnl`.
4.  **Preparation**: Move the `kekropis.krnl` binary into a dedicated folder (e.g., `C:\Kekropis\` or `~/kekropis/`). Ensure the `assets/` and `locales/` folders are in the same root directory as the binary. This is the **Rite of Positioning**.
5.  **First Launch**: Run the artifact. It will open a **Velvet Console** (a stripped-down terminal) to initialize its configuration file. Press `F8` in-game to toggle the overlay visibility.

---

## 🎮 The User Manual: A Guided Meditation

Once the overlay is active, you are presented with a clean slate. Here is your immersion guide:

- **Opening the Tribute Panel**: Press `Insert` on your keyboard. This summons the **Control Surface**, where all input is captured.
- **The Primary Readout**: Look at the center-left of your screen. You'll find the **Kinetic Radar** — a subtle circular ring that gently pulses. Enemy signatures appear as red specks; friendlies as cyan. No icons, just dots.
- **Adjusting the Flow**: Navigate to `Settings > Rendering > Opacity`. Use the wheel to adjust the global blend. Kekropis recommends between `40%` and `60%` for competitive play.
- **The Trace Layer**: If you're flanked by walls, the **Temporal Trace** will show a faint colored shimmer on the floor where a target *was* standing 2 seconds ago. This is a *prediction* field, not a truth.
- **Exiting**: Press `F9` to gracefully detach the overlay. The artifact will save its state to `session_state.json` for the next launch.

---

## 🛡️ The Guardian Code: Disclaimers & Ethics

> **THE LECTURE ON INTEGRITY** — Read before you download.

This artifact is an **educational visualization tool**. It is designed to demonstrate the power of *spatial integration* and *HCI principles* within a live game environment. Kekropis **does not**, and will **never**:

- Modify the game executable in memory.
- Intercept network packets to gain an unfair timing advantage.
- Provide automated aim-correction utilities.

Kekropis is a **passive amplifier** of *your own perception*. It performs **no secret scanning** of the host system. It does not obfuscate its function via stealth or "guardian" triggers.

**User Responsibility**: By utilizing this software, you accept full responsibility for the consequences. Competitive integrity rules often have **zero tolerance** for third-party overlays, even passive ones. **Just as a compass is not a substitute for a navigator, Kekropis is not a substitute for skill.** It is a stroke enhancer, not a canoe motor.

We explicitly disclaim any liability for bans, suspensions, or the excommunication of your gaming account. **Check your local tournament regulations first.** If you are a fragile flower, we recommend you **uninstall and recuse yourself** to vanilla gameplay.

---

## 📁 Repository Architecture

The structure is a **labyrinth of clarity**, designed for rapid navigation:

```text
kekropis/
├── assets/                  # Texture maps, shaders, and font packs
├── locales/                 # JSON linguistic dictionaries
├── src/
│   ├── core/                # Main loop, state machines, thread managers
│   ├── gamehooks/           # Panorama adapter & telemetry reader
│   ├── render/              # Vulkan/D3D12 abstraction layers
│   ├── ui/                  # KekroWidgets & Layout Engine
│   └── utils/               # Memory utilities, CRC hashers
├── tests/                   # Unit tests for assertion of sanity
├── scripts/                 # Lua examples & automation
├── vcpkg.json               # Dependency manifest
├── CMakeLists.txt           # Modern CMake build recipe
└── CHANGELOG.md             # The historical annals
```

---

## 🤝 The Fellowship: Contributing

We welcome **Knights of the Keyboard** who wish to polish this lantern.

1.  **Fork** the repository into your realm.
2.  Create a feature branch (`feature/add-dragon-mode-ui`).
3.  Commit your changes with **semantic prefixes** (`feat:`, `fix:`, `docs:`).
4.  Open a *Pull Request*. In the description, explain *what* you changed and *why* the change reduces user dissonance.
5.  We will review your code for adherence to the **C++ Core Guidelines**.

**Looking for**: Shader wizards, localization masters, and UX poets. We pledge a **24/7 support channel** for contributors via the Discussions tab.

---

## 📄 License — The Open Scroll

Kekropis is released under the **MIT License**. This is the most permissive of open-source scrolls. You may use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the Software. You must retain the original copyright notice.

Permission is hereby granted, **free of charge**, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction. The full legal text is available in the [LICENSE](https://github.com/tarekk2/Kekropis/blob/main/LICENSE) file within the repository root. This link references the standard MIT text, which remains valid for the year 2026 and beyond.

---

## 🔮 Roadmap for 2026: The Next Ascension

We are charting the stars for the upcoming year. Key initiatives include:

- **Quantum Fog of War**: Rendering the *probability* of enemy locations using a Bayesian inference model, displayed as a heatmap.
- **Neural Interface Themes**: An experimental "mind's eye" UI that scales down UI complexity based on your in-game heart-rate variability (requires a wearable sensor).
- **Community Config Store**: An in-app marketplace for sharing Lua profiles, curated for balance and clarity.
- **Zero-Latency Hot Reload**: A daemon that watches your config files and applies changes *in live matches* without flicker.

> **Final Verdict**: Kekropis is a **thinking player's companion**. It does not give you the answer; it teaches you how to ask better questions of the battlefield. Use it wisely, and may your vision be forever unclouded.

---

*© 2026 The Kekropis Collective. All rights reserved. This is a fan-made educational project; it is not affiliated with or endorsed by any game publisher.*