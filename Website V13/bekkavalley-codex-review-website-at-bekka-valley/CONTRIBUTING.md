# Contributing Guide

Thanks for helping improve the Bekka Valley website.

## Team workflow
1. Create a branch from `work` with a descriptive name: `feature/<short-topic>` or `fix/<short-topic>`.
2. Keep PRs focused on one goal (copy change, layout tweak, bug fix, etc.).
3. Request at least one review before merging.
4. Include screenshots for visible UI changes.

## Local development
Run a local preview server from this project folder:

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173` in your browser.

## Project structure
- `index.html`, `about.html`, `products.html`, `shop.html`, `contact.html` — static pages
- `styles.css` — shared styling across pages
- `app.js` — shop page product rendering and local cart interactions
- `Shop images/` — static image assets

## Coding guidelines
- Keep visual style consistent with current brand palette and spacing rhythm.
- Reuse existing CSS classes where possible before adding new selectors.
- Prefer semantic HTML (`section`, `nav`, `main`, `footer`) for new blocks.
- When adding JS behavior, avoid global side effects outside `DOMContentLoaded`.

## Pre-PR checklist
- [ ] Page loads without console errors.
- [ ] New links and buttons work on mobile and desktop viewport widths.
- [ ] Text copy is proofread and brand-consistent.
- [ ] Screenshots added to PR for visual changes.
