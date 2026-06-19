# paulogaspar7.github.io

A small workshop of browser-native tools by Paulo Gaspar, served via GitHub Pages.

Each tool is a single, self-contained HTML page: **no servers, no uploads, no accounts**. They run
entirely in the browser and do one job well.

🔗 **Live site:** https://paulogaspar7.github.io

## Projects

| # | Project | What it does | Status |
|---|---------|--------------|--------|
| 01 | [Downsizer](./downsizer/) | Picture-desk batch image resizer — drop in photos, cap their longest side, and download the downscaled set. PNG · JPEG · WebP, fully client-side. | Live |

## Structure

```
.
├── index.html        # Homepage — the project index
└── downsizer/
    └── index.html    # Downsizer tool
```

The homepage (`index.html`) is the front door and lists every published tool. New projects are added as
their own subdirectory with an `index.html`, then linked from the homepage and the table above.

## Running locally

These are static pages — open `index.html` directly, or serve the folder for clean relative paths:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## License

Personal projects. Feel free to read the source for ideas.
