<div align="center">

# Slatewave (Raycast)

A dark Raycast theme on a slate foundation with a teal signature. Designed as a twin to the [Slatewave VSCode theme](https://github.com/kevinlangleyjr/vscode-slatewave), [Slatewave Obsidian theme](https://github.com/kevinlangleyjr/obsidian-slatewave), and [Slatewave oh-my-posh prompt](https://github.com/kevinlangleyjr/slatewave-omp) — launcher, editor, terminal, and notes share a single color vocabulary.

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

## Companion themes

Slatewave is one palette, many surfaces. Run them all and your launcher, editor, terminal, and notes speak the same visual language.

- **Launcher** — this repo
- **Editor** — [vscode-slatewave](https://github.com/kevinlangleyjr/vscode-slatewave)
- **Notes** — [obsidian-slatewave](https://github.com/kevinlangleyjr/obsidian-slatewave)
- **Prompt** — [slatewave-omp](https://github.com/kevinlangleyjr/slatewave-omp)

---

## Contributing

Issues and PRs welcome. For palette changes, include a before/after screenshot of the same Raycast view so the visual tradeoff is obvious.

---

## License

WTFPL — Do What The Fuck You Want To Public License. See [LICENSE](LICENSE).
