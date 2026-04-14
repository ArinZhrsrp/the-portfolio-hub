# The Portfolio Hub

A static split-screen portfolio landing page built in a single `index.html` file. The page presents two identity-driven profile paths, "The Architect" and "The Scholar", with a cinematic hover experience, a custom cursor on desktop, and a mobile-friendly stacked layout.

## Overview

This project is designed as a lightweight personal portfolio homepage with:

- A two-panel hero layout for showcasing two different personas or career tracks
- Tailwind CSS via CDN for utility styling
- Custom CSS for motion, glow effects, responsive layout shifts, and typography
- A small JavaScript cursor effect for desktop interaction
- No build step, framework, or package installation required

## Preview Features

- Split-screen desktop experience with expanding hover panels
- Responsive mobile layout that stacks both sections vertically
- Color-coded visual identity for each side
- Minimal animated center divider and anchor element
- Single-file setup that is easy to edit and deploy

## Tech Stack

- HTML5
- Tailwind CSS via CDN
- Custom CSS
- Vanilla JavaScript
- Google Fonts (`Inter` and `Playfair Display`)

## Project Structure

```text
.
├── index.html
└── README.md
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

The two panels currently link to `#architect` and `#scholar`. Replace those `href` values with real destination URLs when the portfolio pages are ready.

### Adjust interaction behavior

You can tune hover expansion, glow intensity, animation timing, and responsive breakpoints in the embedded `<style>` block.

## Deployment

This project can be deployed on any static hosting platform, including:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

Since there is no build process, deployment is as simple as uploading `index.html`.

## Notes

- The page uses external CDNs for Tailwind CSS and Google Fonts, so an internet connection is needed for those assets to load.
- The custom cursor is shown on larger screens only.
- Current panel links are placeholders and should be replaced with real portfolio destinations.
