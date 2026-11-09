# musictime

A browser drum machine with a bassline and a guitar tuner, in a single HTML file — no install, no samples. All sounds are synthesized with the Web Audio API.

**Live:** https://robyoungsf.github.io/musictime/

Or open `index.html` in a browser.

## Features

- **Drum machine:** 16-step sequencer with 8 drums (kick, snare, clap, closed/open hat, tom, rim, cowbell), per-track level and mute
- **Beat presets:** Rock, Hip Hop, House, Funk, Trap, Reggaeton, Disco, Breakbeat, Bossa Nova, Drum & Bass, Jazz ii–V–I
- **Tempo, swing, kit** (Punchy, 808, Lo-fi) and master volume
- **Bassline:** key, scale, 5 bass sounds, octave, and chord progressions (incl. ii–V–I and 12-bar blues); click a step to add/remove, scroll over a note to change its pitch
- **Guitar tuner:** mic pitch detection with a cents needle, 6 tunings, and reference tones per string
- Settings are saved in the browser and restored on reload

## Keyboard

- `Space` — play / stop
- `↑` / `↓` — tempo (hold Shift for ±10)
- `1`–`8` — trigger a drum
