# Favourite Digital Labs — Portfolio

A responsive, accessible-minded portfolio for Favour and Favourite Digital Labs, built with **HTML5 and CSS3 only**. It has no JavaScript, framework, build step, or external dependency.

## Files

- `index.html` — semantic page structure and content
- `css/style.css` — design tokens, layout, responsive rules, interaction states
- `assets/images/` — reserved for a real portrait and optional social preview image
- `assets/icons/` — reserved for any future static icon assets

The hero artwork and project mockups are built in CSS, so the site works without image assets.

## Open locally

1. Extract the ZIP file.
2. Open `index.html` in a modern browser.
3. To edit the design, change `css/style.css`.

No server or installation is required for local viewing.

## Before publishing

1. Confirm the displayed name, phone number, and email address.
2. Replace project concept cards with actual project screenshots, descriptions, and real live/source links when available.
3. Add real GitHub, LinkedIn, or other social URLs.
4. Add a portrait at `assets/images/portrait.jpg` only if you update the HTML to use it; the current hero uses a CSS-built abstract visual.
5. Replace `assets/images/og-preview-placeholder.png` in the Open Graph metadata with a real social-sharing image, or remove that metadata field until you have one.
6. Add genuine testimonials only with permission.
7. Update the copyright year when needed.

## Design decisions

- **Palette:** charcoal, warm ivory, and electric lime, with muted sage and blush for project mockups.
- **Typography:** system sans-serif for clear UI text paired with a system serif for editorial emphasis. No external fonts are loaded.
- **Art direction:** editorial typography, thin technical rules, a CSS-built code-window illustration, and custom project concept mockups.
- **Content strategy:** describes the current learning journey without inventing clients, credentials, results, or proficiency scores.
- **Responsive behaviour:** fluid type and spacing, CSS Grid/Flexbox, and breakpoints at 900px and 680px.
- **Accessibility:** semantic landmarks, skip link, meaningful section headings, visible keyboard focus, reduced-motion support, and descriptive link text.

## Honest limitations

- This is a static site. It does not include JavaScript or a backend.
- The navigation uses HTML anchor links. On small screens, the navigation remains visible and horizontally scrollable rather than using a JavaScript hamburger menu.
- Email and telephone links open the visitor's email or phone app; the site does not send messages itself.
- No contact form is included because form submissions need a backend or a form-processing service.
- Project cards are clearly labelled concepts; they do not link to nonexistent demos or repositories.
- The site has not been run through Lighthouse or a formal accessibility audit. Test it with your target browsers and devices before launch.

## Deploy

Upload the contents of this folder to any static hosting provider that serves HTML and CSS, such as GitHub Pages, Netlify, or a conventional web host. Keep `index.html` at the site root and preserve the `css/` and `assets/` folder structure.
