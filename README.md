# Logo stuff

> This is a collection of logo files for my projects, identities, etc.

## Commands

### Trim SVG whitespace

Remove whitespace by fitting the viewBox to the drawing area using Inkscape:

```bash
inkscape --export-area-drawing --export-plain-svg --export-filename=output.svg input.svg
```

To overwrite the original file directly:

```bash
inkscape --export-area-drawing --export-plain-svg --export-overwrite input.svg
```
