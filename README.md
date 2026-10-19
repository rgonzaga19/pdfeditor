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

## Publish with GitHub Pages

1. Push this folder to the root of a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch to publish and the `/ (root)` folder, then save.
5. Open the Pages URL shown in the settings. GitHub Pages serves `index.html`
   automatically.

## Use the editor

Choose a PDF or drop it onto the page. Select a tool, click or drag on a page,
and use the format controls to adjust the selected item. Use the page and zoom
controls to navigate; click **Save changes** to download a new PDF.
