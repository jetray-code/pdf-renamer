# PDF Smart Renamer (Standalone)

A zero-installation, browser-based tool to bulk rename PDF files based on their content titles.

## Features
- **Zero Backend**: Runs 100% in your browser. No Python or installation required.
- **Privacy Focused**: Your files never leave your computer. Processing happens locally in the browser tab.
- **Chrome App (PWA)**: Can be "installed" to your desktop with a single click.
- **Smart Detection**: Automatically identifies the best title using font size and landscape detection.
- **Direct File Access**: Uses the modern File System Access API to rename files directly on your hard drive.

## How to Run
Because of browser security rules, this tool must be served from a web server (it will not work if you double-click the file).

### Option 1: Local Server (For testing)
If you have Python installed, run:
```bash
python3 -m http.server 8000
```
Then open **http://localhost:8000** in Chrome or Edge.

### Option 2: Web Hosting (For users)
Upload these files to any free static host (like Netlify, GitHub Pages, or Vercel). Once opened via a URL, the user can click **"Install App"** to add it to their Start Menu/Desktop.

## Requirements
- **Google Chrome** or **Microsoft Edge** (Required for the File System Access API).
