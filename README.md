# asatheesh23.github.io

Personal academic website for **Dr Satheesh Abimannan, PhD, FHEA** — Dean, College of Computing, Euro University of Bahrain.

Plain HTML/CSS/JS, no build step required.

## Files

```
index.html          Homepage (About, Experience, Research, Teaching, Publications preview, Recognition, Contact)
publications.html   Full publication list with filters
css/style.css        All styling
js/script.js          Nav toggle + active-section highlighting
assets/satheesh-headshot.jpg
```

## Publish on GitHub Pages

1. Create a repository named exactly **`asatheesh23.github.io`** on GitHub (this special name is required for a user site).
2. Add these files to the repository root (keep the folder structure above — don't nest them inside a subfolder).
3. Commit and push to the `main` branch.
4. In the repo, go to **Settings → Pages**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`, then **Save**.
5. Your site will be live at `https://asatheesh23.github.io/` within a minute or two.

### Quick way via the GitHub web UI (no git needed)
- On github.com, create the repo, then use **Add file → Upload files** and drag in `index.html`, `publications.html`, and the `css`, `js`, `assets` folders (drag the whole folders in — GitHub preserves the paths).

## Updating content later
- **Bio / experience / teaching / contact**: edit the relevant section in `index.html`.
- **New publication**: add a `<li class="pub-item">` entry to the "Recent journal articles" list in `index.html`, and a fuller `<li class="full-pub-item">` entry to `publications.html`.
- **Photo**: replace `assets/satheesh-headshot.jpg` and keep the same filename, or update the `src` in `index.html`.

## Notes
- Fonts (Fraunces, Inter) load from Google Fonts via CDN — no local font files needed.
- The site is fully responsive and works without JavaScript (JS only powers the mobile menu, scroll-highlighting and the publications filter).
