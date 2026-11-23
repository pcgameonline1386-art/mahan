# Yamaha piano article

A lightweight, dependency-free Persian RTL article page for learning about Yamaha piano types.

## Run locally

Requires Python 3. From PowerShell in this folder, run:

```powershell
python -m http.server 4173 --bind 127.0.0.1
```

Then open http://localhost:4173 in your browser. Python serves the static HTML and CSS; no packages or build step are required.

## Article images

The hero banner and five in-article image slots are deliberately empty so that they can be replaced with the supplied images. Update the labelled slots in `index.html` when image files are available.