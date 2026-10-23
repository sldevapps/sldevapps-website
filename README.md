# S&L App Development website

Static site (plain HTML/CSS/JS, no build step) for Cloudflare Pages.

- `index.html` home page, `support.html`, `privacy.html`
- `styles.css`, `script.js`
- `assets/` web-sized logo, favicon and app icons (`Company_Logo.png` is the full-size original)

## Before launch
- Replace `hello@yourdomain.com` / `support@yourdomain.com` (search for `TODO`)
- Write the real privacy policy text in `privacy.html`

## Cloudflare Pages
Framework preset: None. Build command: (blank). Output directory: `/`.

## Local preview
`python3 -m http.server 8000`, then open http://127.0.0.1:8000
