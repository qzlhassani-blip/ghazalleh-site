# Ghazalleh Hassani — Personal Site

A bilingual one-page personal site, told as three nights of Scheherazade's story.
Two static files. No build step, no dependencies, no server.

```
index.html   Persian (default page, RTL)
en.html      English (LTR)
```

A language switch in the top bar moves between the two.

## Features

- Pure HTML and CSS with a small amount of vanilla JavaScript
- Light and dark themes, following the visitor's system preference
- Fully responsive, down to small phones
- Portrait embedded in the page itself — no separate image files
- Hand-drawn SVG ornaments: a brush ensō, bamboo, a folding fan, a career constellation

## Running locally

Open `index.html` in any browser. That is all.

## Deploying

Upload both HTML files to the root of any static host.
Keep the filenames as they are — the language switch links to them by name.

This repository is published with GitHub Pages:

- **Settings → Pages → Build and deployment**
- Source: `Deploy from a branch`
- Branch: `main`, folder: `/ (root)`

## Fonts

Loaded from Google Fonts, so the page needs an internet connection to render
as designed: Scheherazade New, Vazirmatn, Aref Ruqaa, Cormorant Garamond,
IBM Plex Sans, IBM Plex Mono, Shippori Mincho.

## Contact

hassaniqazal@gmail.com
