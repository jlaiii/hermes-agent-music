# Hermes Agent Music

**Live project page:** https://jlaiii.github.io/hermes-agent-music/

Procedural ambient sounds, nature, and beats for coders — generated entirely in your browser using the Web Audio API. No samples, no downloads, no external files. Works offline.

## What This Is

A single-file static site that synthesizes 17 different sound environments and beats in real time. Each sound is built from oscillators, noise buffers, and filters — no pre-recorded audio. Every scene loops forever and uses virtually zero bandwidth after the initial page load.

## Scenes

### Weather
- **Rain** — Filtered brown noise with soft drizzle
- **Thunder** — Deep lowpass rumble bursts, randomized timing
- **Wind** — Band-passed noise with slow amplitude swells
- **Ocean** — Pink noise with slow crashing cycles
- **Fire** — Crackling bursts with warm low-end noise
- **Snow** — Ultra-quiet filtered noise with crisp crackles

### Nature
- **Night Crickets** — Rhythmic chirping pulse waves
- **Forest Birds** — Random high-pitched chirps with decay
- **Stream** — Bubbling water texture, fast modulation

### Ambient / Drones
- **Drone Pad** — Four detuned oscillators, slowly beating
- **Space Drone** — Sub-oscillators with slow filter sweeps
- **Binaural Beat** — 5 Hz theta (left 200 Hz, right 205 Hz)

### Generative Music
- **Arpeggio Dream** — Random pentatonic arpeggios with reverb
- **Piano Drift** — Slow minor-pentatonic notes, long release

### Beats
- **Lo-Fi Beat** — 75 BPM, vinyl crackle, brushed snare, chord stabs
- **Deep House** — 124 BPM, four-on-floor kick, rolling bassline, pad chords
- **Techno Drive** — 130 BPM, hard kick, industrial percussion, distorted bass

## Features

- **Quick Presets** — One-click layered combos: Deep Focus, Rainy Code, Forest Morning, Sleep Drift, Night Drive, Lo-Fi Work
- **Per-scene volume sliders** with live adjustment
- **Mixer** showing which scenes are active
- **Sleep timer** — 15 / 30 / 60 minute auto-stop
- **Visualizer** — Real-time frequency bar display
- **Keyboard shortcuts** — `1-9` toggles first 9 scenes, `0` stops all
- **Fade in/out** — Smooth gain ramps on play/stop

## Usage

1. Open the live site
2. Click **Start Audio Engine**
3. Click any **Play** button or a **Quick Preset**
4. Adjust volume sliders as needed

Lower your system volume before first play — some scenes are bass-heavy.

## Tech

- Pure HTML + CSS + JavaScript (single file)
- Web Audio API — oscillators, buffer sources, biquad filters, convolver reverb, channel merger
- No build step, no dependencies, no CDN scripts
- GitHub Pages hosting

## License

MIT
