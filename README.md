Lamborghini Landing Page

A single-page, animated landing page for the Lamborghini Gallardo LP560, built with plain HTML, CSS, and JavaScript.

Features
Responsive layout (mobile menu toggle + desktop nav)
Animated entrance effects powered by GSAP
Ionicons for the menu and stat icons
Custom CSS variables for easy theming (colors, fonts, sizes)
File structure
.
├── index.html        # Page markup
├── style.css         # Compiled styles
├── main.js           # Menu toggle + GSAP animations
└── lamborghini.png   # Car image

Note: index.html, style.css, main.js, and lamborghini.png must all sit in the same folder — the HTML references them with relative paths (e.g. href="style.css"), not an assets/ subfolder.

Running it

No build step required.

Keep all four files in one folder.
Open index.html directly in a browser, or serve the folder locally:
bash
   npx serve .
   # or
   python -m http.server 8000
Visit the page (e.g. http://localhost:8000).
Dependencies (loaded via CDN)
GSAP 3.2.4 — animations
Ionicons 5.0.0 — icons
Google Fonts: Montserrat — typography

An internet connection is needed for these to load, since they aren't bundled locally.

Customization

Key design tokens live at the top of style.css under :root:

--first-color — accent yellow
--bg-color — background
--text-color — body text
--icon-color — icon accent
--body-font — typeface

Adjust these to re-theme the page without touching layout code.
