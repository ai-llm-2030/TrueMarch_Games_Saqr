# Saqr

**Emirati falconry in the dunes: ride the thermals, stoop steep, chase down hare and houbara, then fly two falcons together.**

<p align="center">
  <img src="assets/screenshot-title.png" alt="Saqr — title screen" width="820">
</p>

<p align="center">
  <a href="https://ai-llm-2030.github.io/TrueMarch_Games_Saqr/"><b>▶ Play Saqr in your browser</b></a>
</p>

## Gameplay

<p align="center">
  <img src="assets/screenshot-play.png" alt="Saqr — gameplay" width="820">
</p>

## More screenshots

<table>
<tr><td width="50%"><img src="assets/screenshot-flights.png" alt="The flights of the season"><br><sub>The flights of the season</sub></td><td width="50%"><img src="assets/screenshot-results.png" alt="A day's result"><br><sub>A day's result</sub></td></tr>
<tr><td width="50%"><img src="assets/screenshot-how.png" alt="How to fly"><br><sub>How to fly</sub></td><td width="50%"><img src="assets/screenshot-pause.png" alt="On the glove"><br><sub>On the glove</sub></td></tr>
</table>

## Controls

| Keys | Action |
|---|---|
| Drag from the falcon | Draw her flight line (drag again in the air to change it) |
| Hold Space or hold the mouse still | Stoop · tap-then-hold for a steep stoop · let go to pull out |
| Esc | Back |
| P | Pause |
| M | Sound on / off |

## Run it yourself

No install, no build step, no server code, no network. The game runs entirely in your browser and keeps your progress in the browser's local storage.

```bash
git clone https://github.com/ai-llm-2030/TrueMarch_Games_Saqr.git
cd TrueMarch_Games_Saqr
python3 -m http.server 8000
# open http://localhost:8000
```

Opening `index.html` directly works too in most browsers; a local server is the most reliable way.

## What's inside

```
TrueMarch_Games_Saqr/
├── index.html        the whole game: one file, plain JavaScript and <canvas>
├── assets/           the pictures in this README
├── LICENSE
└── README.md
```

Written from scratch in vanilla JavaScript: every sprite, background and sound is drawn or synthesised in code (Canvas 2D and the Web Audio API). No libraries, no frameworks, no third-party assets.

## About

**Saqr** is one of the 120+ games made by **[TrueMarch](https://truemarch.com)**. This repository is the standalone single-player edition of the game.

## License

© 2026 TrueMarch. All rights reserved. The source is published so you can read it, learn from it and play the game; see [LICENSE](LICENSE).
