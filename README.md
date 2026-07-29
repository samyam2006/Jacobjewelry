# Jacob Jewelry Miami

A modern, elegant website for **Jacob Jewelry Miami** — a fine jewelry, diamond, and custom-design showroom in Downtown Miami. Inspired by the clean, premium feel of leading jewelry retailers.

## Highlights

- **Single-page design** with smooth-scrolling sections: Hero, Collections, Custom Design, Services, About, Testimonials, and Visit/Contact.
- **Elegant palette** — charcoal/black, champagne gold, and warm cream, with a subtle Miami teal accent.
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

- **Photos:** The collection tiles and feature panels currently use tasteful gradient placeholders. Add real photos to `assets/` and swap the `.collection--*`, `.custom__media`, and `.about__media` backgrounds in `css/styles.css`.
- **Colors:** All colors are CSS variables at the top of `css/styles.css` (`:root`).
- **Content:** Copy, testimonials, and stats live directly in `index.html`.
