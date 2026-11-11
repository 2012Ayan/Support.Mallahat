# Mallahat — GitHub Pages Edition

A high-performance, dependency-free campaign site built with **one HTML file** for the main application, plus two small policy pages.

## Files

- `index.html` — entire application: HTML, CSS and JavaScript
- `privacy.html` — privacy/cookie information
- `terms.html` — campaign terms
- `404.html` — custom GitHub Pages 404
- `.nojekyll` — optional GitHub Pages configuration

## Features

- Dark purple / white / black visual system
- Neo-Brutalism + Liquid Glass + Glassmorphism
- Animated CSS/vector falcon
- Interactive manifesto
- Local “Drop an Egg” suggestion box
- Falcon Pong
- Falcon Match memory game
- Falcon Reflex reaction game
- Responsive design
- Reduced-motion support
- No backend
- No API keys
- No build system
- No npm dependencies

## GitHub Pages

1. Create a GitHub repository.
2. Upload all files from this folder.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save and wait for GitHub Pages to publish.

## Security

This is a static site. There are no secrets to hide because the application does not use private API credentials.

The suggestion box is intentionally local-only. If you later make it shared across students, do not put a database password or API key into this HTML. Use a secure server-side API, validate input server-side, rate-limit submissions, minimize collected data, and follow your school's privacy/safeguarding requirements.

## Performance

The site uses vanilla HTML/CSS/JS and Canvas, so there is no framework bundle or build step. For an even more performance-focused production version, self-host fonts or remove the Google Fonts import.

## Accessibility

The interface includes semantic headings/navigation, labeled inputs, keyboard controls for games, responsive layouts and a `prefers-reduced-motion` mode. Perform a final WCAG audit on the deployed site.
