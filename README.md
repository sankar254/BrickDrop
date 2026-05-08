# BrickDrop
A retro Tetris-style brick game built as a TrimUI Smart Pro-inspired handheld console, playable in the browser.

A fully playable retro brick-dropping puzzle game rendered in the browser — 
styled as a TrimUI Smart Pro handheld console with an LCD green display, 
physical D-pad layout, and tactile button controls.

## Features
- Classic 7-tetromino gameplay with ghost piece preview
- Hard drop (Space), soft drop, and wall-kick rotation
- Combo scoring system with level progression
- Particle burst effects on line clears
- CRT scanline + screen flicker effect
- Retro sound effects (move, rotate, place, clear, level up, game over)
- High score persisted via localStorage
- Fully playable on desktop and mobile (touch controls)
- SVG icon D-pad — no font rendering issues
- Apple HIG-compliant touch targets (min 44×44pt)

## Controls
| Key         | Action       |
|-------------|--------------|
| Arrow Left  | Move left    |
| Arrow Right | Move right   |
| Arrow Down  | Soft drop    |
| Arrow Up    | Rotate       |
| Space       | Hard drop    |
| P           | Pause        |

## Tech
- Vanilla HTML, CSS, JavaScript
- Canvas 2D rendering
- Web Audio API for sound effects
- No dependencies, no build step
