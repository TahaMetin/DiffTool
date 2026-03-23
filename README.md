# ⚡ DiffTool — Private Text & File Comparison

A fully browser-based text and file diff tool. No server. No uploads. No accounts. Your data never leaves your machine.

---

## Why This Exists

Most online diff tools send your text to a remote server for processing. That's a problem when you're comparing **source code, configuration files, contracts, API keys, internal documents**, or anything else you'd rather keep private.

DiffTool was built with one goal: **give you a professional-grade diff experience that works entirely on your own device.** Everything runs in your browser using vanilla JavaScript — no backend, no telemetry, no data collection of any kind.

---

## ✨ Features

- **Text & File modes** — paste text directly or drag & drop any file (TXT, JS, PY, HTML, JSON, XML, CSV, MD, and more)
- **LCS-based diff engine** — accurate line-by-line comparison using the Longest Common Subsequence algorithm
- **Word-level diff** — highlights exactly which words changed within a modified line
- **Side-by-side & Unified views** — switch between layouts depending on your preference
- **Statistics** — added, deleted, modified, and unchanged line counts at a glance
- **Export** — download results as HTML or plain text, or copy to clipboard
- **Options** — ignore case, ignore whitespace, toggle line numbers
- **Keyboard shortcut** — `Ctrl+Enter` to compare instantly

---

## 🚀 Run It Yourself

No installation. No dependencies. No build step.

1. Download [`index.html`](./index.html)
2. Open it in your browser
3. Start comparing

That's it. The file is fully self-contained — one HTML file with all CSS and JavaScript included.

---

## 🔒 Privacy

- All processing happens **locally in your browser**
- **Nothing is sent to any server**
- No cookies, no analytics, no tracking
- Works completely **offline** after the page loads (fonts may require an internet connection on first load)

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
