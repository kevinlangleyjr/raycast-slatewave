<div align="center">

<img src="https://getslatewave.com/brand/icon.png" alt="" height="64" align="middle">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://getslatewave.com/brand/wordmark-light.png">
  <img alt="Slatewave" src="https://getslatewave.com/brand/wordmark.png" height="64" align="middle">
</picture>

# Slatewave (Raycast)

A dark [Raycast](https://www.raycast.com) theme on a slate foundation with a teal signature. Part of the [Slatewave family](#slatewave-family) — one palette across editors, terminals, prompts, notes, and more.

> _Slate below, teal above._

</div>

---

## What it styles

Slatewave maps the twelve Raycast theme tokens onto the Slatewave palette:

- **Background** — `#282c34`, the same slate the editor and terminal sit on
- **Background secondary** — `#1e293b`, deeper slate for detail panes and layered surfaces
- **Text** — `#e2e8f0`, slate-200 body text
- **Selection & loader** — `#5eead4`, the Slatewave teal signature
- **Accent colors** — rose, orange, amber, teal, sky, lilac, and pink, tuned to match the rest of the Slatewave family

---

## Installation

Custom Raycast themes require an active **Raycast Pro** subscription.

### Import via Theme Studio

1. Open Raycast and search for **Theme Studio** (or run `Manage Themes → Create New Theme`).
2. Open `slatewave.json` in this repo and copy the contents.
3. In Theme Studio, choose **Import Theme** and paste the JSON.
4. Set Slatewave as your active theme in **Raycast Settings → Appearance**.

### From a local clone

```sh
git clone https://github.com/kevinlangleyjr/raycast-slatewave \
  ~/Development/raycast-slatewave
```

Then follow the import steps above.

---

## Palette

Slatewave shares its palette with the companion VSCode, Obsidian, and oh-my-posh themes. The anchor colors used in this theme:

| | Hex | Tailwind | Role |
|---|---|---|---|
| ![#282c34](https://placehold.co/20x20/282c34/282c34.png) | `#282c34` | — | `background` |
| ![#1e293b](https://placehold.co/20x20/1e293b/1e293b.png) | `#1e293b` | slate-800 | `backgroundSecondary` |
| ![#e2e8f0](https://placehold.co/20x20/e2e8f0/e2e8f0.png) | `#e2e8f0` | slate-200 | `text` |
| ![#5eead4](https://placehold.co/20x20/5eead4/5eead4.png) | `#5eead4` | teal-300 | `selection`, `loader`, `green` — **primary accent** |
| ![#fb7185](https://placehold.co/20x20/fb7185/fb7185.png) | `#fb7185` | rose-400 | `red` |
| ![#ff4500](https://placehold.co/20x20/ff4500/ff4500.png) | `#ff4500` | — | `orange` |
| ![#fbbf24](https://placehold.co/20x20/fbbf24/fbbf24.png) | `#fbbf24` | amber-400 | `yellow` |
| ![#38bdf8](https://placehold.co/20x20/38bdf8/38bdf8.png) | `#38bdf8` | sky-400 | `blue` |
| ![#b388ff](https://placehold.co/20x20/b388ff/b388ff.png) | `#b388ff` | — | `purple` |
| ![#f472b6](https://placehold.co/20x20/f472b6/f472b6.png) | `#f472b6` | pink-400 | `magenta` |

See the [VSCode theme README](https://github.com/kevinlangleyjr/vscode-slatewave#palette) for the full scale and syntax mapping.

---

## Slatewave family

One palette. Every tool.

- **Editors** — [VSCode](https://github.com/kevinlangleyjr/vscode-slatewave) · [Neovim](https://github.com/kevinlangleyjr/neovim-slatewave) · [Helix](https://github.com/kevinlangleyjr/helix-slatewave) · [Zed](https://github.com/kevinlangleyjr/zed-slatewave) · [Sublime Text](https://github.com/kevinlangleyjr/sublime-text-slatewave) · [JetBrains](https://github.com/kevinlangleyjr/jetbrains-slatewave)
- **Terminals** — [Alacritty](https://github.com/kevinlangleyjr/alacritty-slatewave) · [Ghostty](https://github.com/kevinlangleyjr/ghostty-slatewave) · [iTerm2](https://github.com/kevinlangleyjr/iterm2-slatewave) · [WezTerm](https://github.com/kevinlangleyjr/wezterm-slatewave) · [Windows Terminal](https://github.com/kevinlangleyjr/windows-terminal-slatewave)
- **Prompts** — [Oh My Posh](https://github.com/kevinlangleyjr/slatewave-omp) · [Starship](https://github.com/kevinlangleyjr/starship-slatewave)
- **Multiplexer** — [tmux](https://github.com/kevinlangleyjr/tmux-slatewave)
- **Notes** — [Obsidian](https://github.com/kevinlangleyjr/obsidian-slatewave) · [Logseq](https://github.com/kevinlangleyjr/logseq-slatewave)
- **Launcher** — [Alfred](https://github.com/kevinlangleyjr/alfred-slatewave)
- **Chat** — [Slack](https://github.com/kevinlangleyjr/slack-slatewave)

See [getslatewave.com](https://getslatewave.com) for the full family.

---

## Contributing

Issues and PRs welcome. For palette changes, include a before/after screenshot of the same Raycast view so the visual tradeoff is obvious.

---

## License

WTFPL — Do What The Fuck You Want To Public License. See [LICENSE](LICENSE).
