# SpaceBar

Experimental browser build of a neon orbit-jump arcade game.

Live build:

- [https://zephyrsai.github.io/spacebarv2](https://zephyrsai.github.io/spacebarv2)

## What It Is

`SpaceBar` is a single-file HTML canvas game where you:

- launch from orbit to orbit
- build combo and fever
- route through moving targets
- use gravity assists around planets, stars, and rare black holes
- trigger music-reactive visuals and small replay moments for successful bend landings

## Controls

### Desktop

- `Space` / `Enter`: start or launch
- Hold `Space` / `Enter`: temporarily speed up the current orbit
- Release after holding: launch
- `Esc`: pause
- `R`: instant restart
- `Left` / `Right` or `A` / `D`: route choice when a fork is active

### Touch

- Tap target ring: launch
- Hold on the playfield: temporarily speed up the current orbit
- Release after holding: launch
- Use on-screen `Pause` / `Retry` buttons

## Graphics

Graphics presets are built into the title screen:

- `Minimal`
- `Low`
- `Medium`
- `High`

The default is intended to be `High`, and user-selected settings are persisted across refreshes.

## Current Features

- gravity slow-time near strong gravity fields
- gravity echo replay at the bottom of the screen after successful bend landings
- praise popups for strong jumps and slingshot landings
- per-mode gameplay tuning
- lives system
- first-run tutorial
- mobile/touch support

## Notes

- This project is intentionally self-contained in one HTML file.
- Audio and rendering are generated in-browser; no external assets are required for the core game.
- `node_modules` is present only for local tooling support.

## Please fork it and modify it to your heart's content. But please give proper credit. 🫡
