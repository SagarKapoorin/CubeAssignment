# Cube Frontend Assignment
Website Link : https://gtgshop.netlify.app

Responsive single-page build from the provided Figma design using vanilla HTML, CSS, and JavaScript.

## Features
- Pixel-perfect layout across desktop/tablet/mobile; header collapses to hamburger on smaller screens.
- Product gallery with arrows, dots, and thumbnails that swap the main image; stateful JS for accessibility.
- Fragrances + Purchase Type radio groups drive the Add to Cart URL (9 combinations) with subscription sections expanding per selection.
- Stats counters animate from 0 on scroll (IntersectionObserver); subtle hover/transition touches per design.
- Semantic HTML table for pricing data plus labeled controls, alt text, and focusable interactive elements.
- Assets exported/optimized from Figma; lazy loading applied where appropriate; no frameworks or external deps.
- Added animation at lot of places

## Project Structure
- index.html — main page markup and semantic structure.
- css/style.css — styling, layout system, breakpoints, and component states.
- js/main.js — gallery logic, radio handling, subscription toggles, add-to-cart mapping, and counter animation.
- assets/ — exported images/icons used across the page.
