# Quote Generator - Copilot Instructions

## Project Overview

A minimal, sleek quote generator webpage built with vanilla HTML/CSS/JavaScript. Single-file implementation (`index.html`) with no external dependencies. The app displays random quotes from a hardcoded array on button click, with a responsive gradient UI that works beautifully on mobile and desktop.

## Architecture

**Single-file design:** All HTML, CSS, and JavaScript are in `index.html` to keep the project minimal (< 8KB).

- **Styling:** Inline CSS with responsive design (mobile-first, breakpoint at 600px)
- **Quotes data:** Static array with 12+ quotes - edit directly in the script section
- **Interaction:** Vanilla JavaScript event handler prevents consecutive duplicate quotes

## Key Code Patterns

### Adding Quotes
Edit the `quotes` array in `index.html` (around line 80):
```javascript
const quotes = [
    { text: "Your quote", author: "Author Name" },
];
```

### Quote Display Logic
`getQuote()` function (line 96) ensures different quotes on each click using index tracking. No external API used - all quotes are local.

## Common Tasks

- **Test locally:** Open `index.html` directly in any browser
- **Deploy to GitHub Pages:** Push repo, enable Pages in Settings (source: main branch, root folder)
- **Customize colors:** Edit the gradient value in CSS `background: linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- **Add quotes programmatically:** Extend the `quotes` array (max ~100 quotes before considering API-based loading)

## Design Principles

- **No frameworks:** Vanilla JS for minimal overhead
- **Responsive:** Works 320px (mobile) to 4K+ (desktop)
- **Single file:** Easy to host anywhere (GitHub Pages, Netlify, Vercel, local)
- **Accessibility:** Semantic HTML, readable color contrast (WCAG AA)

## Deployment Checklist

- Update GitHub repo URL in README.md
- Test on mobile and desktop browsers
- For production: Consider GitHub Pages or Netlify for free, instant hosting
