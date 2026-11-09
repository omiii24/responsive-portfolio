# Responsive Portfolio — Responsive Website

**Created by:** Om Pawar

This project is a responsive personal portfolio website. It introduces the portfolio owner, presents skills and selected projects, includes an About section, and provides a contact call-to-action.

## Project links
- **GitHub repository:** https://github.com/omiii24/responsive-portfolio
- **Live website:** https://omiii24.github.io/responsive-portfolio/

## Website sections
1. **Header / Navigation** — Portfolio identity and navigation links to the main page sections.
2. **Hero** — Introductory headline, supporting text, and primary call-to-action.
3. **About** — Short introduction and background information.
4. **Skills** — Technologies and skills presented as a clear list or tags.
5. **Projects** — Selected project cards with descriptions and relevant links.
6. **Contact** — Contact information or a contact call-to-action.
7. **Footer** — Closing information and relevant links.

## Technologies
- HTML5 for semantic page structure.
- CSS3 for styling, spacing, colours, and typography.
- Flexbox for alignment and flexible component layouts.
- CSS Grid for multi-column content and project cards.
- CSS media queries for responsive layout changes.
- Fluid sizing techniques such as `clamp()` where used in the stylesheet.

## Responsive breakpoints
Use the exact media-query values in the repository's `style.css` as the source of truth. The layout should be reviewed at:
| Device | Suggested viewport | What to inspect |
|---|---:|---|
| Desktop | 1440px | Full navigation, hero layout, multi-column sections and project cards. |
| Tablet | 768px | Adjusted spacing, columns and alignment; check for overlap. |
| Mobile | 375px | Stacked content, readable navigation, card width and no horizontal scrolling. |

Before submission, replace this table's generic breakpoint description with the exact `@media` values from the final `style.css`, if they differ from the values documented in the project.

## Repository files
- `index.html` — webpage structure and content.
- `style.css` — styling and responsive media queries.
- `README.md` — project documentation.

## Run locally
1. Clone or download this repository.
2. Keep the HTML and CSS files in the same project folder.
3. Open `index.html` in a web browser.
4. Resize the browser or use Developer Tools device emulation to inspect responsive layouts.

## Testing checklist
- [ ] Inspect at 1440px width.
- [ ] Inspect at 768px width.
- [ ] Inspect at 375px width.
- [ ] Confirm navigation links move to the correct sections.
- [ ] Confirm project cards resize or stack cleanly.
- [ ] Check that text and buttons remain readable and usable.
- [ ] Check for overlapping content and unwanted horizontal scrolling.

Only mark a check as complete after manually testing it.

## Implementation note
This README is organized to document the portfolio project and its responsive behavior. Confirm the exact section names, repository file names, and CSS media-query breakpoints against the current GitHub source before final submission.
