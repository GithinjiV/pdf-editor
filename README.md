# PDF Filler

A small PDF form filler that runs entirely in the browser. Open a PDF, type on it, tick boxes, add a signature or stamp, and save a new copy. Nothing is uploaded: the file never leaves your computer.

**Use it online:** https://githinjiv.github.io/pdf-editor/

## What it does

- **Text**: click where the writing should sit and type. Double-click to edit later.
- **Tick**: click a box to tick it.
- **Whiteout**: cover existing text with a white box.
- **Image**: add a signature or stamp. The paper background is removed automatically, with a slider to adjust it.
- **Library**: keep signatures and stamps in the browser for one-click reuse.
- Move anything by dragging, nudge with the arrow keys, resize images from the corner, and delete with Del.
- **Save PDF** (or Ctrl+S) downloads "… (filled).pdf". The original is not changed.

## Run it locally

Open `index.html` in a browser. It needs no server and no internet connection.

## Built with

- [PDF.js](https://github.com/mozilla/pdf.js) 3.11.174 (Apache-2.0) to show the pages
- [pdf-lib](https://github.com/Hopding/pdf-lib) 1.17.1 (MIT) to write the new PDF

Both are bundled in `vendor/` with their licences.
