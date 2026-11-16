# 1976 MOOG + TR-808

A combined synthesizer and drum machine project for the Akai MPC Key 37, built with the inMusic MPC Plugin Builder SDK.

## Status

- [x] MPC SDK example packaged and installed successfully on the MPC Key 37.
- [ ] Confirm SDK synth and drum-synth example source layouts.
- [ ] Implement the Moog-inspired subtractive synth engine.
- [ ] Implement synthesized TR-808-style drum voices.
- [ ] Build and test the combined instrument on MPC hardware.

## Planned modules

- `Source/Moog/` — oscillators, mixer, filter, envelopes, modulation.
- `Source/TR808/` — kick, snare, clap, hats, toms, rimshot, cowbell.
- `Source/Engine/` — voice management, mixing, parameters.
- `Interface/` — MPC plugin controls and layout.
- `Presets/` — instrument presets.

## Build

Use the build and packaging commands documented by the installed MPC SDK. Start with the SDK's own synthesizer and drum-synth examples; adapt their actual project structure rather than assuming a generic VST layout.

## Important

This repository contains project planning and source work. It is not yet a completed or installable MOOG + TR-808 plugin.
