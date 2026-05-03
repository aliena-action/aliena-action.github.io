# ALIENA One-Page Artist Profile

This repository is a simple, mobile-first artist profile / landing page for **ALIENA**.
It uses only plain **HTML + CSS** (no JavaScript, no framework).

## Files in this project

- `index.html`
  - Contains the page content and section structure.
  - This is where you edit text, links, release dates, and section order.

- `style.css`
  - Contains all visual styling (colors, spacing, typography, layout).
  - Edit this if you want to change the look and mood.

- `assets/`
  - Upload your images here.

## Image upload instructions (important)

Upload the images into the `assets` folder with these exact filenames:

- `assets/profile.png`
- `assets/lead-single-cover.jpg`
- `assets/ep-cover.jpg`

Do not change those names unless you also update the image paths in `index.html`.


## Pre-release status

This page is currently designed for **pre-release** use.
It intentionally shows schedule text and placeholders:

- Lead Single — 2026.06.03
- EP — 2026.06.10
- Streaming links coming soon

Do not add live streaming URLs until the release is public.

## Where to replace links

Open `index.html` and find the **Links** section.

- Replace Instagram URL here:
  - `href="https://instagram.com/your-account"`
- Replace contact email here:
  - `href="mailto:your-contact@example.com"`

## Where to replace streaming links later

Right now, streaming placeholders are intentionally non-clickable `<span>` elements.

Open `index.html` and update these placeholders when links are ready:

1. In the **Lead Single** release card:
   - `<span class="button button-disabled">Streaming links coming soon</span>`
2. In the **EP** release card:
   - `<span class="button button-disabled">Streaming links coming soon</span>`
3. In the **Links** section list:
   - `<span class="button button-disabled inline">Streaming links coming soon</span>`

When you have real URLs, replace each `<span ...>` with an `<a ...>` link.

## How to preview locally

You can preview without installing anything:

1. Open this folder on your computer.
2. Double-click `index.html`.
3. It will open in your browser.

If images do not appear, check that the filenames exactly match the names above.

## Optional later step: publish with GitHub Pages

Later, you can publish this page using **GitHub Pages** from this repository.
That will give you a public URL for sharing.
