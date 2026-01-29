# Final Project: Accessible Professional Portfolio
**Student:** Bonheur shema  
**Course:** Web Development Foundations  
**Target Compliance:** WCAG 2.2 Level AA

## Overview

This is a small static website demonstrating accessible and responsive design principles. It includes a simple site with a home page, an About page, a Contact page, and a single stylesheet.

## Files

- `index.html` — Home page
- `about.html` — About page
- `contact.html` — Contact page
- `style.css` — Main styles (responsive and accessible-focused)

## Features ✨

- **Accessibility-first**: semantic HTML, clear headings, accessible form labels, focus styles, and ARIA where appropriate.
- **Responsive layout**: mobile-first CSS and media queries so the site adapts to different screen sizes.
- **Lightweight**: static HTML/CSS only for fast loading and easy testing.

## How to view locally 🔧

1. Open `index.html` directly in your browser (double-click) or use a local server for best results:
   - Python 3: `python -m http.server 8000` then visit `http://localhost:8000`
   - Or install the VS Code "Live Server" extension and click "Go Live".
### Operable
- **Skip-to-Content Link:** A hidden link appears on first focus, allowing keyboard users to bypass the navigation menu.
- **Keyboard Navigation:** All interactive elements (links, buttons, inputs) are reachable via `Tab` and have a highly visible focus indicator (`outline: 4px solid #FFBF47`).
- **No Keyboard Traps:** Users can navigate into and out of all site sections using only a keyboard.

### Understandable
- **Form Labels:** Every form input has a programmatically linked `<label>` using the `for` attribute.
- **Predictable Nav:** The navigation menu remains consistent in position and behavior across all pages.

### Robust
- **Clean Code:** Valid HTML5 and CSS3 structure ensuring compatibility across different browsers and assistive technologies.

## Testing Tools Used
- **WAVE (Web Accessibility Evaluation Tool):** Used to identify and fix contrast and structural errors.
- **Axe DevTools:** Used for deep-dive auditing of ARIA attributes.
- **Manual Testing:** Full site walkthrough performed using only the `Tab`, `Shift+Tab`, and `Enter` keys.

## Development & Contribution 🙌

- To modify: edit the `.html` files and `style.css` in the project root.
- To test changes: use a local server, refresh the page, and run accessibility checks.
- Contributions: fork the project, make changes, and open a pull request.

## Contact

See `contact.html` for author/contact details included in the project.

---

Thanks for reviewing this accessible, responsive site! ⚡
