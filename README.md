# ⚡ DiffTool — Private Text & File Comparison

A fully browser-based text and file diff tool. No server. No uploads. No accounts. Your data never leaves your machine.

https://tahametin.github.io/DiffTool/

---

## Why This Exists

Most online diff tools send your text to a remote server for processing. That's a problem when you're comparing **source code, configuration files, contracts, API keys, internal documents**, or anything else you'd rather keep private.

DiffTool was built with one goal: **give you a professional-grade diff experience that works entirely on your own device.** Everything runs in your browser using vanilla JavaScript — no backend, no telemetry, no data collection of any kind.

---

## ✨ Features

- **Text & File modes** — paste text directly or drag & drop any file (TXT, JS, PY, HTML, JSON, XML, CSV, MD, and more)
- **Advanced Diff Engine** — high-performance comparison using the **Myers Diff Algorithm** with prefix/suffix stripping optimizations
- **Syntax Highlighting** — professional code highlighting for JavaScript, Python, HTML, CSS, C-like, and more (via Prism.js)
- **Interactive Minimap** — high-level overview of changes with draggable viewport for quick navigation
- **Action History** — locally stored history of your previous comparisons to quickly jump back to work
- **Word-level diff** — highlights exactly which words changed within a modified line
- **Side-by-side & Unified views** — switch between layouts depending on your preference
- **Fullscreen Mode** — distraction-free comparison with zoom controls and synchronized navigation
- **Bilingual Support** — fully localized UI in both **Turkish** and **English**
- **Statistics** — added, deleted, modified, and unchanged line counts at a glance
- **Export** — download results as HTML or plain text, or copy to clipboard
- **Keyboard shortcuts** — `F7/Shift+F7` for navigation, `Ctrl+Enter` to compare instantly

---

## 🚀 Run It Yourself

No installation. No dependencies. No build step.

1. Download [`index.html`](./index.html)
2. Open it in your browser
3. Start comparing

That's it. The file is fully self-contained — one HTML file with all CSS and JavaScript included.

---

## 🔒 Privacy & Security

- **Local Processing** — All diffing and rendering happen **locally in your browser**.
- **Zero Data Leakage** — Nothing is ever sent to a server.
- **Action History** — Stored exclusively in your browser's `localStorage`. You can clear it at any time.
- **Security First** — Inputs are rigorously escaped to prevent XSS (Cross-Site Scripting) attacks.
- **Zero Tracking Cookies** — No analytics, no tracking, no third-party scripts.
- **Offline Ready** — Works completely offline after the initial load.

---

## 📁 Project Structure

```
/
└── index.html   # The entire application — open this in your browser
└── README.md
```

---

## License 

MIT — do whatever you want with it.
