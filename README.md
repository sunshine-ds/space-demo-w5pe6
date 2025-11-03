# Hello Space

A tiny, single-file responsive HTML page that says "Hello Space". Built with Tailwind CSS (CDN) and a lightweight starfield for a subtle space-themed background. This project is intentionally compact and accessible — perfect as a micro landing page, demo, or starting point.

## Features

- Single HTML file (index.html) — no build step required
- Fully responsive design using Tailwind CSS CDN
- Dark mode support (toggle + persists preference)
- Accessible controls and keyboard shortcuts
- Subtle animated starfield for ambiance (canvas implementation)
- Small interactive features: copy greeting, random greeting
- Production-ready markup, semantic and accessible

## Usage

1. Download or clone the repository.

2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).

That's it — it works offline and requires no server.

### Keyboard shortcuts

- Press `d` to toggle dark mode
- Press `c` to copy the greeting text to clipboard

## Customization

- Change the greeting text inside the `<h1 id="greeting">Hello Space</h1>` element.
- Modify the starfield behavior in the inline script (`STAR_COUNT`, twinkle speed) if desired.
- Tailwind configuration is included inline at the top of the file for quick theming.

## Accessibility & Progressive Enhancements

- Dark mode respects system preferences and persists the user's choice via `localStorage`.
- The page respects `prefers-reduced-motion` and disables the starfield animation when requested.
- Buttons are keyboard-accessible and include ARIA attributes where relevant.

## License

This project is licensed under the MIT License — see the LICENSE file for details.
