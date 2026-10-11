# HTML Launcher — v1.0.0

> A clean, browser-based **playground for HTML, CSS, and JavaScript**.  
> Upload an `.html` file or paste your code and instantly preview the result in a secure, isolated environment — no installation, no server, no account required.

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-Playground-red?logo=html5" />
  <img src="https://img.shields.io/badge/JavaScript-Vanilla-yellow?logo=javascript" />
  <img src="https://img.shields.io/badge/CSS3-Modern-blue?logo=css3" />
  <img src="https://img.shields.io/badge/Works%20on-iPhone%20%7C%20iPad-black?logo=apple" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey" />
</p>

---

## Features

| Feature | Description |
|---------|-------------|
| 📂 **Upload & Run** | Pick an `.html` / `.htm` file (up to 10 MB) and run it instantly in your browser. |
| ✍️ **Code Editor** | Prefer typing? Paste HTML, CSS, and JavaScript directly into the built-in editor. |
| 🖱️ **Drag & Drop** | Drop an HTML file straight onto the page — no file picker needed. |
| 🔒 **Isolated Preview** | Your document runs inside a sandboxed `<iframe>` — separate from the host page. |
| 🖥️ **Full-Screen Mode** | Expand the preview to a full-screen view for testing layouts and interactions. |
| ↻ **Instant Rerun** | Reset or reload the preview any time without re-uploading the file. |
| 📱 **Mobile-First Design** | Works beautifully on iPhone, iPad, and desktop — safe-area aware. |
| 🎨 **Modern UI** | Clean responsive layout with subtle animations and a live status indicator. |
| ⚡ **Zero Setup** | No installs, no accounts, no server — everything runs client-side. |

---

## Getting Started

### Prerequisites
- A modern browser (Chrome, Firefox, Edge, Safari)
- That's it — no build step, no dependencies

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/timignatenko/HTML-Launcher.git
cd HTML-Launcher

# 2. Run the app
# Option A — just open index.html in your browser
# Option B — serve it locally (recommended)
python -m http.server 8000
# then visit http://localhost:8000
```

Or simply visit the live demo:

> **🔗 [timignatenko.github.io/HTML-Launcher](https://timignatenko.github.io/HTML-Launcher/index.html)**

---

## Usage

### 1️⃣ Upload a file
Click **Choose file** or drag an `.html` document onto the drop zone.  
Files must be `.html` or `.htm` and under **10 MB**.

### 2️⃣ Or paste your code
Expand **"Or paste HTML code manually"** and drop your markup into the editor.  
A **Load example** button is available if you want a starting point.

### 3️⃣ Run it
Press **▶ Run HTML** — the preview appears instantly inside the sandboxed frame.

### 4️⃣ Explore the result
- **↻ Run again** — re-executes the current document.
- **⛶ Full screen** — expands the preview to fill the viewport.
- **↻ Reset** — clears the preview and prepares the app for a new file.

> **Tip:** On iPhone, use the **Share Sheet → Save to Files** to bring in an HTML file from another app.

---

## Project Structure

```
HTML-Launcher/
├── index.html
└── README.md
```

Everything lives in a single `index.html` — no external assets required.

---

## Tech Stack

- **HTML5** — semantic, accessible structure
- **CSS3** — modern layout, custom properties, responsive design
- **Vanilla JavaScript** — no frameworks, no dependencies
- **[FileReader API](https://developer.mozilla.org/en-US/docs/Web/API/FileReader)** — reads local HTML files entirely in the browser
- **[Sandboxed iframes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe#sandbox)** — safely isolates the previewed document
- **[Blob API](https://developer.mozilla.org/en-US/docs/Web/API/Blob)** — measures pasted code size on the fly

---

## Privacy

Your HTML is processed **locally** in your browser.  
It is **not uploaded** to any server, not cached, and not logged.  
Only external resources *referenced inside your own document* may connect to the internet.

---

## Author

Developed by **[Tim](https://github.com/timignatenko)**

---

## License

This project is open-source under the **MIT License**.  
Feel free to use, modify, and distribute.

---

<p align="center"><b>⭐ Star this repo if you found it useful!</b></p>
