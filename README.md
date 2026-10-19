# Simple PDF Editor

A static, browser-based PDF editor. It can add text, images, freehand drawings,
shapes, and highlights, then download the edited PDF. PDF files are processed
in your browser and are not uploaded to a server.

## Run locally

Open `index.html` in a modern browser, or serve this folder over HTTP:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000>.

The PDF.js and pdf-lib libraries are loaded from cdnjs, so an internet
connection is required for the editor to load.
