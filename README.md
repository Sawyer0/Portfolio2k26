# Dawan Sawyer: Portfolio

Personal portfolio for Dawan Sawyer, Full Stack AI Developer.

## Design and performance choices

- One hand-written `index.html`. No framework and no build step; a small inline script powers the project detail dialog.
- CSS is inlined in the `<head>`, so first paint needs exactly one request.
- System font stack: no web-font download, no layout shift.
- No images; the favicon is an inline SVG data URI.
- Semantic HTML, a skip link, visible focus states, and automatic dark mode via `prefers-color-scheme`.
- Strict Content-Security-Policy and security headers in `vercel.json`.

## Deploy

Import this repo in Vercel (Framework preset: Other, no build command, output directory `.`).
