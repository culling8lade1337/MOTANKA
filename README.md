# MOTANKA

Website for **Motanka CPH**, a Ukrainian street food truck in Copenhagen. Portfolio project.

Instagram: [@motanka_cph](https://www.instagram.com/motanka_cph)

## What it does

- Trilingual interface: Danish, English and Ukrainian. The language follows the browser and the choice is remembered.
- Menu with category filters (soup, mains, sweet, drinks). Each dish shows its name in the chosen language and in Ukrainian script.
- Links to Instagram and Google Maps.
- Responsive from phone width up, keyboard accessible, respects reduced motion.

## Design

- Black and red street-poster look: oversized condensed display type, flat surfaces, pill buttons.
- The wordmark keeps the brand's woven **O**, redrawn as a vector from the profile image.
- Red cross-stitch bands between sections refer to Ukrainian embroidery. The name itself refers to the motanka, a traditional faceless cloth doll.
- Fonts: Fira Sans Extra Condensed (display) and Onest (text), both from Google Fonts with Cyrillic support.

## Tech

One static file, `index.html`: plain HTML, CSS and JavaScript. No build step, no dependencies.

```bash
# open it directly, or serve the folder
python3 -m http.server 8000
```

## Editing the content

Texts for all three languages are in the `UI` object and the dishes are in the `MENU` array at the bottom of `index.html`. The menu is sample content. Add `price: '85 kr'` to a dish to show a price.

## Deploy

Works on any static host. For GitHub Pages: Settings, Pages, deploy from branch `main`, folder `/ (root)`.
