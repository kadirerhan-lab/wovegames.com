# wovegames.com

Static company website for **Wove Games** — hand-written HTML/CSS, no build step, no JavaScript, no trackers, no cookies.

## Layout

| Path | What |
| --- | --- |
| `index.html` | English home page |
| `tr/index.html` | Turkish home page (language switch in the header) |
| `404.html` | Not-found page (GitHub Pages picks it up automatically) |
| `assets/css/site.css` | The one stylesheet (mobile first, light + dark via `prefers-color-scheme`) |
| `assets/logo.svg` | Full logo: mark + wordmark (colour) |
| `assets/logo-mono.svg` | One-colour logo (`currentColor`, weave knocked out) |
| `assets/logo-mark.svg` | Mark only (square, 64×64 viewBox) |
| `assets/logo-mark-512.png`, `assets/logo-512.png` | PNG exports |
| `assets/og.png` | 1200×630 social-sharing card |
| `favicon.svg` | Favicon (same mark) |
| `assets/img/` | Game card images and SVG illustrations |
| `CNAME`, `.nojekyll`, `robots.txt`, `sitemap.xml` | GitHub Pages / SEO plumbing |

## Brand

- Mark: a white **W** ribbon on coral with a yellow thread woven over–under through its legs ("wove").
- Colours: coral `#F26B4E` (text variant `#B8422A`), sun `#F7C948`, teal `#1F7A8C`, ink `#22304A`, cream `#FFF9F2`, blue `#2F7BD9`.
- Fonts: Fredoka (headings) + Nunito (body) from Google Fonts; the wordmark itself is drawn as vector strokes, not text.

## Editing

Edit the HTML directly; keep `index.html` and `tr/index.html` in sync. Fill in the contact section where the
`<!-- TODO: contact email -->` comment is. Deployment is plain GitHub Pages from the repository root.

## Preview locally

Any static server works, e.g. `python -m http.server 8080` in this folder, then open `http://localhost:8080/`.
