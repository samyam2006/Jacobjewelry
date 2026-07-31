# Jacob Jewelry Miami

A modern, elegant website for **Jacob Jewelry Miami** — a fine jewelry, diamond, and custom-design showroom in Downtown Miami. Inspired by the clean, premium feel of leading jewelry retailers.

## Highlights

- **Single-page design** with smooth-scrolling sections: Hero, Collections, Signature Gold, Custom Design, Services, About, and Visit/Contact.
- **Editorial jewelry look** — full-bleed photographic splashes, refined serif/sans typography, and hand-drawn line icons (no emoji).
- **Elegant palette** — onyx, champagne gold, and warm ivory.
- **Responsive** — looks great from mobile to widescreen, with a mobile menu.
- **Embedded Google Map**, click-to-call phone links, and full store hours.
- **No build step** — plain HTML, CSS, and vanilla JavaScript.

## Business details

- **Phone:** (786) 302-7208
- **Address:** 1 NE 1st St #105, Miami, FL 33132
- **Hours:**
  - Mon–Thu: 10:30 AM – 5:00 PM
  - Fri: 10:30 AM – 3:30 PM
  - Sat–Sun: Closed

## Structure

```
index.html      # Page markup
css/styles.css  # Styles & responsive layout
js/main.js      # Nav, scroll reveal, small interactions
assets/         # Drop real product/showroom photos here
```

## Running locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Customizing

- **Photos:** The four splash images (hero, signature, custom, about) are referenced as CSS variables at the very top of `css/styles.css` (`--img-hero`, `--img-signature`, `--img-custom`, `--img-about`). To use your own photography, drop files into `assets/` and point each variable at them, e.g. `--img-hero: url("../assets/hero.jpg");`. A dark gradient sits behind every image, so the layout still looks intentional if a photo is slow to load.
- **Colors:** All colors are CSS variables in the same `:root` block.
- **Content:** All copy, categories, and stats live directly in `index.html`.

> Note: the current splash photos are served from an image CDN via absolute URLs. For a permanent production site, download them into `assets/` and switch the CSS variables to local paths so the site never depends on an external host.
