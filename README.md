# The Portfolio Hub

A static split-screen portfolio landing page built in a single `index.html` file. The page presents two identity-driven profile paths, "The Visionary" and "The Scholar", with a cinematic hover experience, a tagline for each persona, and a mobile-friendly stacked layout.

## Overview

This project is designed as a lightweight personal portfolio homepage with:

- A two-panel hero layout for showcasing two different personas or career tracks
- Tailwind CSS via CDN for utility styling
- Custom CSS for motion, glow effects, responsive layout shifts, and typography
- A small JavaScript snippet that renders the site version in the footer
- No build step, framework, or package installation required

## Preview Features

- Split-screen desktop experience with expanding hover panels
- Responsive mobile layout that stacks both sections vertically
- Color-coded visual identity for each side
- Minimal animated center divider and anchor element
- Pointer cursor on panels and buttons, plus a custom favicon
- Single-file setup that is easy to edit and deploy

## Tech Stack

- HTML5
- Tailwind CSS via CDN
- Custom CSS
- Vanilla JavaScript
- Google Fonts (`Inter` and `Playfair Display`)

## Documentation

- [VERSIONING.md](VERSIONING.md)
- [CHANGELOG.md](CHANGELOG.md)

## Project Structure

```text
.
|-- CHANGELOG.md
|-- VERSIONING.md
|-- favicon.ico
|-- index.html
|-- media/
|   |-- apple-touch-icon.png
|   |-- favicon-32.png
|   |-- favicon-512.png
|   |-- watermark-Black.png
|   `-- watermark-White.png
`-- README.md
```

## Getting Started

Because this is a static project, you can run it locally in either of these ways:

### Option 1: Open the file directly

Open `index.html` in your browser.

### Option 2: Serve it locally

If you want a local server, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Customization Guide

Most updates can be made directly inside `index.html`.

### Edit personal details

Update the text content inside the two main `<a>` sections to change:

- Names
- Titles
- Taglines
- Descriptions
- Call-to-action labels

### Change colors

Edit the CSS variables near the top of the file:

```css
:root {
  --obsidian: #0B0B0B;
  --dev-blue: #abd1f3;
  --scholar-pink: #F01FE2;
}
```

### Update links

The two panels link to their live portfolio sites:

- The Visionary (Shirin Zahra): `https://shirinzahra-portfolio.sfworks.top`
- The Scholar (Ungku Farhah): `https://ungkufarhah-portfolio.sfworks.top`

Change the `href` values on the two `<a class="side-link">` elements to point somewhere else.

### Update the favicon

Replace `favicon.ico` and the files in `media/` (`favicon-32.png`, `favicon-512.png`, `apple-touch-icon.png`). Browsers cache favicons heavily, so hard refresh to see changes.

### Update the version

See [VERSIONING.md](VERSIONING.md).

### Adjust interaction behavior

You can tune hover expansion, glow intensity, animation timing, and responsive breakpoints in the embedded `<style>` block.

## Deployment

This project can be deployed on any static hosting platform, including:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

Since there is no build process, deployment is as simple as uploading `index.html` together with `favicon.ico` and the `media/` folder.

## Notes

- The page uses external CDNs for Tailwind CSS and Google Fonts, so an internet connection is needed for those assets to load.
- On mobile, each panel grows with its content so the buttons are never cut off by the footer.
