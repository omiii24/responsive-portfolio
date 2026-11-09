# Week 2 Task: Implementation of Responsive Web Design

## Project overview
This project is a responsive personal portfolio website for a fictional frontend developer. It demonstrates a flexible layout that adapts to desktop, tablet, and smartphone screens.

## Files included
- `index.html` — semantic page structure and content.
- `style.css` — visual styling, flexible layouts, and responsive breakpoints.
- `README.md` — this project documentation.

## Methods used
1. **Semantic HTML:** The page uses `header`, `nav`, `main`, `section`, `article`, and `footer` elements to give the content a clear structure.
2. **Viewport configuration:** The viewport meta tag ensures the layout uses the device's actual screen width.
3. **Flexible layout:** CSS Grid and Flexbox arrange the hero, about, projects, navigation, and footer sections.
4. **Fluid sizing:** `clamp()`, `min()`, and percentage-based widths help text and containers scale with the available screen space.
5. **Media queries:** Breakpoints at 900px and 620px adjust the layout for tablets and mobile devices.
6. **Responsive visuals:** Project illustrations are made with CSS shapes, so they resize without requiring large image downloads.
7. **Accessibility:** Navigation has an accessible label, decorative artwork is not exposed as meaningful content, and reduced-motion preferences are respected.

## Layout adjustments by device
| Device category | Approximate viewport | Layout behavior |
|---|---:|---|
| Desktop | 1200px and above | Two-column hero, horizontal navigation, three project cards in one row. |
| Tablet | 621px–900px | Reduced spacing, two-column project grid, more compact hero. |
| Mobile | 620px and below | Single-column hero and project cards, compact two-row navigation, smaller spacing and fluid headings. |

The breakpoints are practical design choices rather than rules tied to specific device models. The layout should be checked at intermediate widths as well.

## Testing procedure
1. Open `index.html` in a modern browser.
2. Open Developer Tools and enable the device toolbar / responsive mode.
3. Test at widths such as 1440px (desktop), 768px (tablet), and 375px (mobile).
4. Check that navigation remains readable, text does not overflow, project cards stack correctly, and the contact button fits the screen.
5. Resize gradually between the target widths to identify any awkward transitions.

## Challenges and solutions
- **Different screen widths:** Grid and Flexbox were used instead of fixed-width positioning.
- **Text scaling:** Fluid font sizing with `clamp()` keeps headings readable across viewports.
- **Small-screen navigation:** The navigation links move to a second row on narrow screens.
- **Visual consistency:** CSS-based project illustrations scale with their containers.
- **Motion accessibility:** A reduced-motion media query limits animated transitions for users who request less motion.

## Conclusion
The portfolio demonstrates responsive web design through semantic HTML, flexible CSS layouts, fluid sizing, and media queries. Its content remains organized and usable across desktop, tablet, and mobile viewport sizes.

## Customization
Replace the fictional name, introduction, project descriptions, and `hello@example.com` email address with your own details before submitting.
