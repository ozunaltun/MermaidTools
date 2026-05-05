# mermaid.tools 🧜‍♀️

A fast, single-file visual editor for [Mermaid.js](https://mermaid.js.org/) diagrams that runs entirely in your browser. 

Write Mermaid syntax on the left, see it render in real-time on the right, and tweak the layout and styling visually without ever touching CSS. When you're done, export your diagram as a production-ready PNG, SVG, or PDF.

**[Try it live at mermaid.tools](https://mermaid.tools/)**

![mermaid.tools screenshot](https://mermaid.tools/og-image.png) 

## ✨ Features

- **Zero-Build Monolith**: The entire application is a single `index.html` file. No build steps, no bundlers, no backend required.
- **Live Preview**: See your diagram update instantly as you type.
- **Visual Editing**: Drag sliders to adjust border radius, stroke width, padding, node spacing, and more.
- **12 Built-in Themes**: Switch between multiple light and dark themes, or customize your own colors.
- **Instant Export**: Export high-resolution PNGs (up to 4x), SVGs, and PDFs with a single click.
- **Templates & Shapes**: Insert common shapes or load pre-built templates for Org Charts, Flowcharts, Sequence Diagrams, etc.
- **Privacy First**: Everything runs locally in your browser. Your diagrams never leave your machine.
- **Local Storage**: Automatically saves your work, keeps a history of your latest versions, and supports multiple local projects.

## 🚀 Getting Started

Since the app is a single file, getting started is completely frictionless:

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. Start diagramming!

### Deployment
To deploy your own instance, simply host the `index.html` file on any static hosting provider like Vercel, Netlify, GitHub Pages, or Cloudflare Pages.

## 🛠 Tech Stack

- **Vanilla JavaScript & CSS** — No frameworks, just modern browser APIs.
- **Mermaid.js** (via CDN) — For diagram parsing and rendering.
- **svg-pan-zoom** (via CDN) — For canvas interactions.
- **jsPDF** (via CDN) — For PDF exports.
- **LZ-String** (via CDN) — For compressing diagram state into shareable URLs.

## 📝 License

MIT
