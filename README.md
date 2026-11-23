# UN64 — Unleashed 64

Unleashed 64 is a project to run all N64 games Unleashed on overclocked hardware.

## ⬇️ Download UN64 Patcher v0.046

**[Download UN64 Patcher.exe](https://github.com/4estOC/UN64/raw/main/UN64%20Patcher.exe)** · [Supported games](Supported%20Games.txt)

A standalone Windows app (Windows 7 or later, 64-bit). No installer and nothing else to download: run the exe.

Windows SmartScreen may warn the first time because the exe isn't code-signed: click **More info → Run anyway**.

## What it does

UN64 Patcher patches Nintendo 64 ROMs. It can:

- widen the 3D camera to **3:2, 16:10, 16:9 or 21:9**
- switch video output to **480i**, or to the Analogue 3D re-scaled modes **360p / 360i / 540i** (experimental)
- raise the frame-rate cap to **40 or 60 fps** for selected games

It is built and tuned for the **Analogue 3D** running games in Unleashed mode. See [Supported Games.txt](Supported%20Games.txt) for which game supports which feature.

## How to use

1. Run **UN64 Patcher.exe**.
2. **Source**: add your ROMs, or drag files or folders onto the window.
3. **Destination** (optional): choose where the patched ROMs are saved. By default they go next to the originals.
4. Pick the aspect ratio, resolution and frame rate, then click **Patch all**.

The original ROM is never changed; the patcher writes a patched copy.

## No game data included

This repository and the download contain **no ROMs, game assets or decompiled code**. You need your own unmodified USA ROM dumps (`.z64`, `.v64` or `.n64`).

All patches are experimental and largely untested on real hardware. Use at your own risk.
