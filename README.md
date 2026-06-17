# Achieve

Marketing site for the Achieve habit tracker & AI coach iOS app.

## Local preview

```bash
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

## Deploy

This is a static site. Deploy the repo root to any static host (GitHub Pages, Netlify, Vercel, etc.).

For GitHub Pages: enable Pages in repo settings and set the source to the `main` branch root.

## Replace the hero screenshot

The hero uses an inline SVG mockup. To use a real App Store screenshot instead, replace the `<svg class="phone-frame">…</svg>` block in `index.html` with:

```html
<img class="phone-img" src="assets/phone-screenshot.jpg" alt="Achieve app on iPhone" />
```

And restore the `.phone-img` CSS from the original design.

## App Store link

Update the download button `href` in `index.html` when your App Store listing is live.
