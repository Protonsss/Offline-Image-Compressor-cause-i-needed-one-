# SnapZip — Offline Image Compressor

Drag & drop images → resize/convert (WebP / JPEG / PNG) → download a ZIP — **all local, no uploads**.

## Features
- **Private & offline**: runs 100% in your browser (Canvas + JSZip + FileSaver).
- **Batch**: drop multiple files or use **Add Images**.
- **Convert**: output to **WebP**, **JPEG**, or **PNG**.
- **Quality control**: slider with live %.
- **Smart resize**: set **Max Width/Height** (keeps aspect ratio).
- **Live previews**: thumbnail, filename, dimensions, size.
- **At-a-glance totals**: count + combined size.
- **Progress bar**: shows ZIP build progress.
- **One-click ZIP**: `snapzip_<timestamp>.zip`.
- **Clean UI**: minimal, keyboard-free flow.
- **HEIC**: works if your browser/OS supports HEIC decoding.

## Quick start
- **Fastest**: open `index.html` in a modern browser.  
- **Best** (if your browser blocks file downloads from file://):  
  ```bash
  python3 -m http.server 5500
  # visit http://localhost:5500
