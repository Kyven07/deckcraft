# DeckCraft — Markdown Slide Studio

> A minimalist, client-side Markdown slide deck creator featuring Apple-inspired aesthetics, real-time split-screen rendering, presenter notes, and native PDF export.

## Live Demonstration

Deployable to GitHub Pages with zero build steps:
`https://<your-username>.github.io/deckcraft/`

## Key Capabilities

* **Markdown-driven authoring:** Write presentations in standard Markdown syntax using simple `---` delimiters to divide slides.
* **Apple-inspired design language:** Toggle seamlessly between an ambient `#f5f5f7` studio light canvas and a deep dark-slate aesthetic with translucent frosted glass chrome.
* **Client-side persistence:** Auto-save your drafts and active slide index directly to `localStorage` with a 300ms debounce loop.
* **Zero-drift line numbers:** Maintain strict 1:1 vertical alignment between the line-number gutter and code lines via preserved monospace whitespace.
* **Non-destructive presenter notes:** Isolate speaker notes using `Note: ...` or `> [!NOTE]` syntax without displaying them on the public slide canvas.
* **Browser-native PDF compilation:** Print or export complete 16:9 presentation decks via native browser print stylesheets (`@media print`).
* **Zero build dependencies:** Run instantly in any modern web browser as a standalone, self-contained `index.html` file.

## Keyboard Hotkeys

| Key Binding | Target Action |
| :--- | :--- |
| **Space** / **→** / **PageDown** | Advance to next slide |
| **←** / **PageUp** | Return to previous slide |
| **F** | Toggle full-screen presentation mode |
| **N** | Toggle speaker notes drawer |
| **Esc** | Exit full-screen presentation mode |
| **Tab** | Insert standard 2-space indentation |

## Quick Deployment to GitHub Pages

1. Create a new public repository on [GitHub](https://github.com) named `deckcraft`.
2. Push your `index.html` and `README.md` files to the `main` branch.
3. Open **Settings > Pages**, choose **Deploy from a branch** (`main` / root), and click **Save**.
4. Your application will be live at `https://<your-username>.github.io/deckcraft/` within a minute.

## Built With

* [Tailwind CSS](https://tailwindcss.com/) (CDN runtime)
* [Marked.js](https://marked.js.org/) (Client-side Markdown parsing)
* Modern Web Standards (HTML5 Fullscreen API, Web Storage API, CSS Print Media)

## License

MIT License. Free for personal and commercial presentations.
