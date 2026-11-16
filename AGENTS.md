# TRY ESPORT Wiki — AI Development Rules

## Purpose
Build a free, beginner-friendly Traditional Chinese PUBG esports knowledge website. This is an educational fan project, not an official PUBG site.

## Stack and deployment
- Static HTML, CSS, and vanilla JavaScript only; no build step, API keys, database, or paid dependencies.
- Host with GitHub Pages. Use relative links so project-site URLs work.
- All content should work offline after download.

## Structure
- `index.html`: home page and content directory.
- `pages/*.html`: one topic per page, lowercase kebab-case filenames.
- `css/style.css`: shared design system and responsive layouts.
- `js/main.js`: shared navigation and small interactions.
- `README.md`: overview and deployment instructions.
- `ASSIGNMENT.md`: submission description.

## Visual rules
- Dark navy background, purple/cyan accents, readable contrast.
- Shared header, navigation, footer, article card and back-to-home link.
- Mobile-first responsive layout, semantic HTML and keyboard-accessible links.
- No externally hosted images or fonts required.

## Content rules
- Write in Traditional Chinese (Taiwan usage), with English game terms explained on first use.
- Every article must have one H1, an intro, at least two H2 sections, a practical example, and a short takeaway.
- Explain tactical concepts as suggestions, not guaranteed winning strategies.
- Avoid invented tournament facts or current balance claims. Cite official sources for facts that may change.
- Do not copy copyrighted game artwork or imply endorsement by PUBG/KRAFTON.

## Adding a page
1. Read this file and inspect an existing page.
2. Create `pages/topic-name.html` from the existing article structure.
3. Add a new article card to `index.html`, with a working relative link.
4. Reuse `css/style.css` and `js/main.js`; do not duplicate shared CSS.
5. Update the article list in `README.md`.
6. Check links, responsive view, and browser console for errors.

## AI modification constraints
- Preserve working pages and navigation.
- Do not change existing filenames or URLs without updating every link.
- Do not add frameworks, trackers, remote dependencies or authentication without permission.
- Keep code understandable to a beginner, with meaningful HTML and CSS names.
- Before finishing, report changed files and basic checks performed.

## Suggested next pages
- `pages/rotation-guide.html`: rotation planning
- `pages/team-communication.html`: team callouts
- `pages/map-awareness.html`: map awareness
