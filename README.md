Playing Cards Selector

Quick demo that renders a full deck of 52 playing cards in order by suit (Spades, Hearts, Diamonds, Clubs) and rank (A, 2-10, J, Q, K). Click or tap any card to toggle selection. The UI shows a live counter and progress bar.

How to use

1. Open `index.html` in your browser (no build required).
2. Click or tap cards to select/unselect them.
3. The footer and progress bar update live with the percentage selected.

Files

- `index.html` — Single-page React app (uses CDN React + Babel for JSX). Minimal ES6 code.
- `styles.css` — Styling for layout, responsive grid, and card visuals.

Notes

- Designed to be mobile-friendly using CSS Grid and responsive breakpoints.
- No external images; suits use Unicode characters.

Possible next steps

- Replace CDN with a proper React build (Create React App / Vite) if you want production bundling.
- Add keyboard accessibility, bulk select, or export selected cards.
