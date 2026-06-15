# Custom imagery

Drop your own images into this `images/` folder using the exact filenames below.
Until a file is present, that slot shows a plain grey placeholder (the page still works).

| File | Where it appears | Suggested size |
|------|------------------|----------------|
| `data-1.jpg` | Hero screen 4 — tile "41 data centres" | ~800×900, portrait, cover |
| `data-2.jpg` | Hero screen 4 — tile "5 continents" | ~800×900, portrait, cover |
| `data-3.jpg` | Hero screen 4 — tile "99.9% uptime" | ~800×900, portrait, cover |
| `post-1.jpg` | "From the field" — card 1 (Deployment) | ~900×500, landscape, cover |
| `post-2.jpg` | "From the field" — card 2 (Comparison) | ~900×500, landscape, cover |
| `post-3.jpg` | "From the field" — card 3 (How-to) | ~900×500, landscape, cover |

Notes
- `.jpg` is assumed. To use PNG/WebP, change the extension in `ishosting-prototype.html` (search for `images/`).
- Images are referenced with relative paths, so keep this folder next to the HTML file.
- The hero tiles have a dark gradient over the lower portion for white-text legibility — darker/busier photos still read fine.
