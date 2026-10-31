# demorcleak

**DEMORCE** media tools — static GitHub Pages site.

## Enable Pages (required once)

1. Open https://github.com/hexed00/demorcleak/settings/pages
2. **Source** → Deploy from a branch
3. Branch: **main** / folder: **/ (root)** → Save

Live URL after a minute:

**https://hexed00.github.io/demorcleak/**

## Upload media (required for bg + icon)

Download the pack, then drag these into the repo root on GitHub:

- `bg.mp4` (or `bg_small.mp4`)
- `icon.jpg`
- `styles.css`
- `app.js`

Pack is in the project artifacts as `demorcleak-static.zip`.

Or from the repo **Add file → Upload files** and drop them.

## Features

- Discord avatar / banner by user ID
- Spotify cover art (oEmbed)
- Pinterest + Cobalt media fetch
- Client-side GIF studio

## Local

```bash
npx serve .
```
