# LibrePiano

[![license](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![made with](https://img.shields.io/badge/made%20with-HTML5-E34F26?logo=html5&logoColor=white)](https://github.com/eagnespuerto/librepiano)
[![website](https://img.shields.io/badge/website-live-brightgreen)](https://eagnespuerto.github.io/librepiano/)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-support%20me-FF5E5B?logo=kofi&logoColor=white)](https://ko-fi.com/eagnespuerto)
[![Linktree](https://img.shields.io/badge/Linktree-soitsagnes-43E55E?logo=linktree&logoColor=white)](https://linktr.ee/soitsagnes)

A free, single-file virtual piano you can play in any modern browser — with your computer keyboard, with touch, or with mouse clicks. Includes an optional sheet-music PDF viewer.

No build step, no dependencies to install. Just open `librepiano.html`.

## Features

- **3-octave keyboard** with shift controls (±3 octaves) for full piano range
- **Computer keyboard mapping** across three rows:
  - `Z S X D C V G B H N J M` — lower octave
  - `Q 2 W 3 E R 5 T 6 Y 7 U` — middle octave
  - `I 9 O 0 P [ = ]` — upper octave
- **Touch and mouse** support for tablets, phones, and desktops
- **Six instrument voices**: Piano, Organ, Harpsichord, Electric Piano, Strings, Sine — synthesized live via the Web Audio API (no sample files)
- **Adjustable note labels**: show note names, keyboard shortcuts, both, or none
- **Volume control**
- **PDF sheet-music viewer**: upload a PDF and scroll through pages side-by-side with the piano (renders locally via pdf.js, nothing uploaded)
- **Standard C-major piano layout** with correctly biased black-key positions

## Usage

Open `librepiano.html` in any modern browser (Chrome, Firefox, Safari, Edge). Click or press a key to start — browsers require a user interaction before audio plays.

To host it, drop the single HTML file on any static host (GitHub Pages, Netlify, your own server). pdf.js is loaded from a CDN.

## License

[MIT](LICENSE)
