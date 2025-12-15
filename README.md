# Hidden Math of Music 🎶

A single-file HTML “sound lab” that generates tones with the Web Audio API and shows live visuals to explain why some intervals feel **smooth** and others feel **spicy**.

Includes:
- Waveform (time domain)
- Spectrum (frequency domain)
- Ratio geometry (Lissajous symmetry from musical intervals)
- Music-reactive cymatics-style plasma disc (resonance “mode snapping”)
- A clearer “sacred geometry” view (clean symmetric curves that react to audio)

---

## Run it

1. Save the project as `index.html` (single file).
2. Open it in a modern browser (Chrome / Edge / Firefox / Safari).
3. Click **Play** (browsers require a user gesture to start audio).

No build step. No dependencies.

---

## How to use

### Top bar
- **Play / Stop**: start/stop the synth
- **Copy link**: copies a shareable URL that includes your current settings in the hash
- **Surprise**: randomizes settings

### Sound Lab controls
- Base frequency (Hz)
- Wave type (sine / triangle / sawtooth / square)
- Harmonics (brightness)
- Attack / Release (envelope)
- Interval or chord
- Second tone mix (how loud the interval/chord is vs the root)
- Detune: Off / Tiny / Medium
- Live mini view mode:
  - Ideal
  - Live (osc pair)
  - Live (texture)
  - Live (cymatics)

### Visual sections
- **Visuals**: waveform + spectrum + ratio geometry
- **Music-Reactive Cymatics**: plasma membrane resonance disc (audio-driven)
- **Reactive Sacred Geometry**: clearer, line-based symmetry view (audio-driven)

---

## Good presets to try

Smooth:
- Octave (2:1)
- Fifth (3:2)
- Fourth (4:3)

Spicy:
- Minor 2nd (16:15)
- Tritone-ish (45:32)

Tip:
- Use **Live (osc pair)** + **Detune: Tiny** to see phase drift / beating and how symmetry “smears”.

---

## Sharing links (URL hash)

The app stores settings in the URL hash so links reproduce the same UI state.

Common keys:
- `f` base frequency
- `w` wave type
- `h` harmonics
- `a` attack
- `r` release
- `i` interval ratio or `CHORD:*`
- `m` mix
- `d` detune level
- `lm` live mini view mode

Use **Copy link** to generate a share URL.

---

## Troubleshooting

- If visuals look blank: click **Play** first (audio unlock).
- If Copy link doesn’t work: some browsers require HTTPS or clipboard permission.
- Performance: cymatics views cap render rate (~30fps) and adapt internal resolution to stay smooth.

---

## License

MIT (give credit where it is due).
