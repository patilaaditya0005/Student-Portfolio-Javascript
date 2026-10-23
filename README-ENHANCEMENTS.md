# Aaditya Patil Portfolio — Enhanced Version

This is an enhanced copy of the existing portfolio project. Existing page content and JavaScript features were retained; the changes focus on cleanup, accessibility, responsiveness, and visual consistency.

## Pages and assets
- `index.html` — home page
- `about.html` — about page
- `education.html` — education page
- `skills.html` — searchable/filterable skills page
- `projects.html` — searchable/filterable project page with expandable details and demo video
- `contact.html` — contact form with validation, character counter, copy-email button, and email-app handoff
- `style.css` — shared site styling
- `script.js` — existing interactions plus contact-page features
- `assets/`, project images, and `demo.mp4` — retained assets

## Improvements made
1. Fixed invalid markup in `index.html` (an extra closing button tag) and corrected the Back to Top button's `aria-label`.
2. Removed accidental Markdown code-fence text from `skills.html`, which could otherwise appear as page content.
3. Added meta descriptions and a dark browser theme color to pages that were missing them.
4. Added `aria-current="page"` to the active navigation link on every page.
5. Added a keyboard-accessible “Skip to main content” link and main landmark target to each page.
6. Added `aria-expanded` state updates to the existing Read More, My Journey, and Education Show More interactions.
7. Added lazy loading and async decoding to non-hero images; prioritized loading the home hero portrait.
8. Added consistent focus indicators, refined button styling, a subtle active-navigation underline, and small hover refinements.
9. Improved mobile spacing and retained reduced-motion support.
10. Preserved existing skill search/filter, project search/filter/expand, heading toggle, rotating role text, reveal animations, and Back to Top behavior.

## Checks performed
- JavaScript syntax check (`node --check script.js`) passed.
- HTML files checked for one main landmark, a skip link, duplicate IDs, stray Markdown fences, and broken local asset/link paths.
- CSS opening and closing brace counts match.

## Notes
- The contact form opens a draft in the visitor's default email application; it does not send email directly from the website. Direct website submissions require a backend or a form service.
- Review personal details and project claims before publishing.
