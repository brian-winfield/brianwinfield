# Backyard Demolition

Simple first-person shooter that runs in the browser (three.js). Walk around a small neighborhood and wreck it: houses, windows, fences, crates, barrels and cars. No enemies, no people.

## Play

Open `index.html` in Chrome, Edge or Firefox. It needs an internet connection the first time, because three.js loads from a CDN. Nothing to install.

If it runs slowly, open `index.html?low` instead. That mode turns off shadows and renders at a lower resolution.

## Controls

| Action | Key |
|---|---|
| Move | W A S D |
| Look | Mouse |
| Sprint / Jump | Shift / Space |
| Shoot / Aim | Left click / Right click |
| Rifle / Rocket launcher | 1 / 2 (or mouse wheel) |
| Reload | R |
| Pause | Esc |

## What breaks

- **Windows:** one shot.
- **Crates, furniture, fences:** a few rifle shots, or any rocket.
- **Red barrels and cars:** explode when destroyed, and set off chain reactions.
- **House walls:** rockets only. The rifle just leaves bullet holes.

Rockets also throw nearby objects around.
