# BINAIRO / TAKUZU

A standalone Binairo / Takuzu game built with HTML, CSS and JavaScript. It works offline, has no external dependencies, and runs on both desktop and mobile devices.

## Features

- Arcade, Zen, Chrono and Print modes.
- 6x6, 8x8, 10x10 and 12x12 difficulty grids.
- Responsive interface aligned with the Sudoku game from the same collection.
- Visual themes: Classic, Sakura, Matcha, Fuji and Dark.
- Internationalization: English, Chinese, Hindi, Spanish, French and Japanese.
- Built-in sounds with a persistent mute button.
- Keyboard navigation: arrow keys, 0/1, Delete, H, Space and Escape.
- Current-game saving and resume button.
- Printable A4 puzzle sheets, 6 grids per page.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| Arrow keys | Move around the grid |
| 0 / 1 | Fill the selected cell |
| Delete / Backspace | Clear the selected cell |
| H | Request a hint |
| Space | Pause / resume |
| Escape | Quit or close a modal |

## GitHub Pages publishing

The game is contained in `binairo.html`. To publish it with GitHub Pages:

1. Copy `binairo.html`, `README.md`, `LICENSE` and `preview.png` into the repository.
2. Rename `binairo.html` to `index.html` if the game should be the home page.
3. Enable GitHub Pages from the repository settings.

## Development

The file is intentionally monolithic so it remains easy to download, share and use offline. Before publishing, check the JavaScript syntax:

```bash
node --check binairo_check.js
```

To validate the full HTML file, extract the `<script>` block into a temporary JavaScript file or use an HTML validator.

## License

MIT. See `LICENSE`.
