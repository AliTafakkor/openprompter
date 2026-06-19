# OpenPrompter

A free, browser-based teleprompter with remote control support. No install needed — open in any browser and go.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Live](https://img.shields.io/badge/live-demo-brightgreen)](https://alitafakkor.github.io/openprompter)

## Features

- **File support** — load `.txt`, `.md`, or `.docx` files
- **Auto-scroll** — smooth continuous scrolling with adjustable speed
- **Manual mode** — scroll freely; momentum scrolling makes remote control feel natural
- **Remote control** — map any clicker or remote buttons to actions via Remote Setup
- **Fullscreen** — toolbar auto-hides, ideal for on-stage presenting
- **Customizable** — background color, text color, font size, reading guide line, mirror mode
- **Persistent** — remote mappings, settings, and last loaded file all survive a page refresh

## Usage

1. Visit the [live demo](https://alitafakkor.github.io/openprompter) or open `index.html` locally in any modern browser
2. Click **Open File** to load your script (`.txt`, `.md`, or `.docx`)
3. Press **Play** or `Space` to start auto-scrolling
4. Click **Remote Setup** to map your clicker buttons

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Play / Pause |
| `↑` / `↓` | Speed up / down |
| `M` | Toggle manual scroll |
| `R` | Reset to top |
| `F` | Fullscreen |
| `Esc` | Pause |

## Remote Setup

Click **Remote Setup** in the toolbar, then click **Set** next to any action and press a button on your remote to assign it. Mappings are saved automatically and persist across sessions.

| Action | Auto mode | Manual mode |
|--------|-----------|-------------|
| Play·Pause / Reset to Top | Play or pause | Jump to top |
| Speed Up / Scroll Up | Speed +1 | Scroll up |
| Speed Down / Scroll Down | Speed −1 | Scroll down |
| Toggle Manual | Switch to manual | Switch to auto |

## License

MIT © [Ali Tafakkor](https://github.com/AliTafakkor)
