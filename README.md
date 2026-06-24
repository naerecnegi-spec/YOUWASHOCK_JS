# YOU WA SHOCK ! (Native JSFX Clone for REAPER)

This is a native JSFX (Jesusonic) clone of the famous freeware exciter/maximizer VST plugin **"YOU WA SHOCK !"**.

Because the original plugin is a 32-bit VST built on the legacy SynthMaker engine, it has a well-known compatibility bug in modern DAWs: when a track contains a MIDI item, the MIDI messages sent to the VST cause it to crackle, pop, or produce glitchy noise.

This JSFX clone resolves this issue completely by running natively inside REAPER's audio engine, bypassing the need for a 32-bit bridge, and completely ignoring MIDI input.

## Features

- **MIDI Noise Fix**: 100% immune to MIDI-induced clicking and crackling.
- **64-bit Native**: Lightweight, stable, and highly optimized for REAPER.
- **Zero Latency**: Implemented with phase-coherent 2nd-order crossovers.
- **4 Classic Presets**:
  - **Preset A (Balanced)**: The standard master-bus enhancer.
  - **Preset B (Bass Punchy)**: Enhances low frequencies and punch.
  - **Preset C (Air / Sparkle)**: Adds high-end air and brilliance (asymmetric excitation).
  - **Preset D (Heavy / Fat)**: Warm, dense saturation across the entire frequency range.
- **Safety Soft-Clipper**: Never clips digitally above `0 dBFS` (capped at `-0.45 dBFS`).

## Installation

1. Download the [YOU_WA_SHOCK.jsfx](YOU_WA_SHOCK.jsfx) file.
2. In REAPER, open the menu: **Options** -> **Show REAPER resource path in explorer/finder...**
3. Locate the **`Effects`** folder in the directory that opens.
4. Copy the `YOU_WA_SHOCK.jsfx` file into that `Effects` folder.
5. In REAPER's FX Browser, right-click and select **Scan for new plugins** (or restart REAPER).
6. Search for `YOU WA SHOCK` in the FX Browser and add it to your track.
