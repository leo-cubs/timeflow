# Rounded

A configurable interval timer for mobile — set work/rest intervals, repetitions, and audio warning cues, save multiple presets, and find the best meeting time across cities with a drag-to-scrub timezone planner.

Single-file static app: `index.html`. No build step, no dependencies beyond a Google Fonts stylesheet link.

## Features

- **Timer** — configurable work interval, rest interval, repetitions, and an audio warning cue in the final seconds of each interval. Visual rep progress, a countdown ring, and a screen wake-lock while running.
- **Setup** — save and load named interval presets (stored in the browser via `localStorage`).
- **Meet** — add cities from a 120+ city database, drag a shared timeline bar (or tap the time readout to type an exact time) to see everyone's local time and day/night status at a glance, plus a "Best time" button that finds the slot with the most overlap in working hours.

## Running locally

It's a static file — open `index.html` directly in a browser, or serve it:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.
