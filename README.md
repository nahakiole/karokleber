# KaroKleber

Paste 5 mm square-grid note space into PDFs. Click a line to drop a red marker. On export, each marker becomes a ~30 cm tall 5 mm grid and a new page starts after it. Everything runs locally in your browser.

![Demo](demo.gif)

## Features

* Load PDFs via button or drag and drop
* Zoom control for precise marker placement
* Red markers instead of bulky previews, with Undo
* Trims excess top/bottom whitespace on import
* Export to PDF with a page break after each grid
* Sharp output using high-resolution rendering
* No server, no upload

## Usage

* **Click** on a page to insert a marker
* **Undo** reverts the last split
* **Zoom** from 25% to 150% to see more or less
* Each marker exports as a ~30 cm 5 mm grid and forces a page break after it

## Tech

* [PDF.js] for rendering
* [pdf-lib] for PDF creation
* Pure frontend, no build step

## Local development

* Edit `index.html` and refresh the browser

## License

MIT

[PDF.js]: https://mozilla.github.io/pdf.js/
[pdf-lib]: https://pdf-lib.js.org/
