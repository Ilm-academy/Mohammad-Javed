# Mohammad Javed — Book landing page

Static marketing site for **Why Smart People Stay Broke — From Degree to Dollars** by Mohammad Javed: a single-page layout with sections for the book’s premise, themes, and calls to action.

## What’s in the repo

| Item | Purpose |
|------|--------|
| `index.html` | Full page: structure, inline Tailwind config, typography (Playfair Display + Inter), meta tags for SEO and social sharing |
| `LICENSE` | MIT License (Copyright © 2026 Ilmacademy) |

Referenced assets (for example under `images/`) should live next to `index.html` so paths like `images/launch-1.png` resolve correctly when the site is served.

## Tech stack

- Plain **HTML5**
- **Tailwind CSS** via CDN (`tailwindcss.com`) with a small custom theme (ink / gold palette, font families)
- **Google Fonts** (Playfair Display, Inter)

No build step or package manager is required.

## Run locally

**Option A — open the file**

Double-click `index.html` or open it from your browser. Some features behave best when the page is served over HTTP (relative URLs, certain security policies).

**Option B — quick static server** (from this folder)

If you have Python 3:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080` and open `index.html` if needed.

With Node.js (`npx`):

```bash
npx --yes serve .
```

## Deploying

Upload the folder to any static host (GitHub Pages, Netlify, Vercel, etc.) with `index.html` as the default document.

## License

See [LICENSE](LICENSE) for the MIT terms.
