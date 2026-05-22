# Dar Safi — Moroccan Pottery Site

A single-page example site for a Moroccan pottery business.

## Open it
Unzip the folder and double-click `index.html` — it opens in any browser.

## What's inside
- `index.html` — the whole site (HTML + CSS + JS in one file)
- `images/` — all photos used on the page (hero, about, process, products)

## Edit it
Everything is in `index.html`. Search for these to swap content quickly:

- **Business name:** `Dar Safi` (in the nav, footer, page title)
- **Address / phone / email:** inside the `<div class="contact-info">` block
- **Hours:** inside the same contact block
- **Product names, descriptions, prices:** inside the `.product-grid` section
- **Story copy:** inside the `.about-text` block
- **Hero headline:** inside the `<h1>` tag

To swap a photo, drop a new file into `/images/` and update the `<img src="...">` path in the HTML.

## Contact form
The form currently shows a thank-you message but does NOT actually send anything. To make it work, wire it to a service like:
- [Formspree](https://formspree.io) (easiest — just change the form's `action` attribute)
- [Netlify Forms](https://docs.netlify.com/forms/setup/) (free if hosted on Netlify)
- Your own backend

## Image credits
Stock photos used as placeholders are from [Unsplash](https://unsplash.com) (free for commercial use). For a real launch, replace them with photos of the actual pottery.

## Fonts
Loaded from Google Fonts (Fraunces + Inter). Requires internet on first load; after that browsers cache them.
