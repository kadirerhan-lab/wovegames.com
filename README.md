# wovegames.com

Static company website for **Wove Games** — hand-written HTML/CSS, no build step, no JavaScript, no trackers, no cookies.

## Layout

| Path | What |
| --- | --- |
| `index.html` | English home page |
| `tr/index.html` | Turkish home page (language switch in the header) |
| `404.html` | Not-found page (GitHub Pages picks it up automatically) |
| `assets/css/site.css` | The one stylesheet (mobile first, light + dark via `prefers-color-scheme`) |
| `assets/logo.svg` | Wordmark "wove" with eyes + GAMES (letters use `currentColor`, default ink; eyes keep their colours) |
| `assets/logo-mono.svg` | One-colour wordmark (`currentColor`, eyes knocked out with a solid pupil) |
| `assets/logo-mark.svg` | App-icon mark (64×64 viewBox): glossy ink square, two eyes, lime smile, sparkle |
| `assets/logo-mark-512.png`, `assets/logo-512.png` | PNG exports (transparent; the wordmark PNG is the ink version for light backgrounds) |
| `assets/og.png` | 1200×630 social-sharing card (dark, with the mark and tagline) |
| `favicon.svg` | Favicon: the mark simplified for 16–32 px (bigger eyes, no fine strokes) |
| `assets/img/` | Game card images and SVG illustrations |
| `assets/archive/` | Previous weave-W logo set, kept for reference, not referenced by any page |
| `CNAME`, `.nojekyll`, `robots.txt`, `sitemap.xml` | GitHub Pages / SEO plumbing |

## Brand

- Logo: the owner's "eyed wove" concept — chunky rounded lowercase **wove**, the o and the e look out with cartoon eyes (white ball, lime iris, ink pupil, highlight), a lime sparkle top-right, wide-tracked **GAMES** beneath. Meaning: "hayal dokumak" — we weave dreams.
- Mark / favicon: dark rounded square with the two eyes and a small lime smile.
- Palette ("jelly"): ink `#14121F`, cream `#FFF8EC`, lime `#A6F000` (text-safe `#4F7A00` light / `#C8FF4D` dark), hot pink `#FF3D9A` (text `#C3127A` / `#FF7DC0`), electric blue `#2F80FF` (`#1B5FD6` / `#8DBBFF`), sun `#FFD23F`, grape `#7B3FE4` (links `#5B21B6` light / lime dark). Light theme on cream, dark theme on ink; all body text ≥ 4.5:1.
- Surfaces: glossy gradients + inner highlight on cards, buttons, pills and icon bubbles; soft radial blobs and a wave divider; gentle CSS-only motion (hero mark bobs, blobs drift), fully disabled under `prefers-reduced-motion`.
- Fonts: Fredoka (headings) + Nunito (body) from Google Fonts; the wordmark itself is drawn as vector strokes, not text.

## Editing

Edit the HTML directly; keep `index.html` and `tr/index.html` in sync. Fill in the contact section where the
`<!-- TODO: contact email -->` comment is. Deployment is plain GitHub Pages from the repository root.

## Preview locally

Any static server works, e.g. `python -m http.server 8080` in this folder, then open `http://localhost:8080/`.
