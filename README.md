# Lamborghini Landing Page — Internship Task

## Overview

This project is a submission for an internship task: building a responsive, animated landing page using HTML, CSS, and JavaScript. It showcases the Lamborghini Gallardo LP560 with a hero section, car stats, and smooth entrance animations.

## Objective

- Recreate a polished, modern landing page from a design reference
- Apply responsive design principles (mobile-first, breakpoints for tablet/desktop)
- Add motion/interactivity using a JS animation library
- Practice clean, maintainable CSS using custom properties (variables)

## Tech stack

| Tool | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling, responsive layout, custom properties |
| JavaScript (vanilla) | Mobile menu toggle |
| GSAP 3.2.4 | Entrance animations |
| Ionicons 5.0.0 | Icons |
| Google Fonts (Montserrat) | Typography |

## Features implemented

- Fixed header with responsive nav (hamburger menu on mobile)
- Hero section with vertical rotated title and car image
- Two info cards showing 0–100 km/h time, top speed, and power stats
- GSAP-powered fade/slide-in animations on page load
- Fully responsive across mobile, tablet, and desktop breakpoints

## File structure

```
.
├── index.html        # Page markup
├── style.css         # Compiled styles
├── main.js           # Menu toggle + GSAP animations
└── lamborghini.png   # Car image
```

All four files must stay in the same folder — the HTML links to them with relative paths (e.g. `href="style.css"`).

## How to run

No build step needed.

1. Keep all four files together in one folder.
2. Open `index.html` in a browser, or serve it locally:
   ```bash
   npx serve .
   ```
3. View in browser.

## What I learned

- Structuring a landing page with semantic HTML
- Using CSS custom properties for a consistent, themeable design system
- Writing responsive layouts with `grid`/`flexbox` and media queries
- Integrating a third-party animation library (GSAP) for polish
- Debugging asset path issues between HTML and linked CSS/JS/image files

## Author

Submitted as part of internship coursework.
