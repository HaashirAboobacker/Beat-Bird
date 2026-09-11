# Beat Bird 🐦🎵

A rhythm-based Flappy Bird clone — obstacle patterns, speed, and intensity all sync to the beat of the background track. Dodge planes, ravens, and eagles, collect beat orbs for combos, and try to survive the full song.

**▶ Play it here:** (https://haashiraboobacker.github.io/Bird-Beat/)



## How to play

- **Space / Click / Tap** — flap
- **M** — mute / unmute
- Collect the ♫ orbs on the beat to build combo streaks
- Difficulty ramps up as the song's sections change
- Survive the whole track to win

## Music

The game comes with a default track (`without_me.mp3`) baked in — it starts playing automatically the moment you interact with the page, no setup needed.

**Want to use your own song instead?**
1. Click the 📁 **Load MP3** button in the top-right corner of the game (visible on the start screen).
2. Choose any audio file from your device.
3. The game analyzes the track's beats automatically and re-syncs gameplay to it — obstacle spawns, orbs, and difficulty will all follow your song's actual rhythm instead of the default track.
4. You can also just drag and drop an audio file anywhere onto the game window.

The uploaded song only replaces the default for that session — reloading the page brings back the default track.

## Settings

Click the ⚙️ gear icon (top-right, start/game-over/victory screens only) to adjust:
- 🎵 **Music volume** — default 65%
- 💥 **Effects volume** — default 90%
- 🎯 **Difficulty** and ⚡ **Level speed**

These controls (along with the Load MP3 and mute buttons) hide automatically while a run is in progress and reappear once you crash, win, or return to the start screen.

## Running locally

No build step needed — it's a single self-contained HTML file plus one audio file.

1. Download `index.html` and `without_me.mp3` and keep them in the same folder.
2. Open `index.html` in any modern browser.

## Files

| File | Description |
|---|---|
| `index.html` | The game itself — HTML, CSS, and JS in one file |
| `without_me.mp3` | Default background track |
