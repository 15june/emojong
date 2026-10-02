# Emojong 🀄

A mobile-friendly emoji tile-match game inspired by mahjong. One HTML file, no build step, no dependencies.

## How to play

Tap any tile that isn't covered to send it to the tray. Collect 3 of the same emoji to clear them. If all 7 tray slots fill up, the round is over. Clear the whole board to move to the next level.

## Features

- Layered boards that grow taller and wider each level
- 7 rotating emoji themes: fruit, critters, snacks, sea life, garden, space, party
- Every deal is solvable, and Shuffle rebuilds a winnable board from whatever is in your tray
- Shuffle, Hint and Undo power-ups (limited per level, bonus points for unused ones)
- Combo scoring for quick back-to-back matches
- Sound effects, haptics on Android, confetti on a cleared board
- Progress saved in the browser with localStorage
- Respects safe areas on notched phones, dark mode and reduced-motion settings

## Run it

Open `index.html` in any modern browser. To host it, enable GitHub Pages for this repo (Settings → Pages → Deploy from branch → `main` / root).
