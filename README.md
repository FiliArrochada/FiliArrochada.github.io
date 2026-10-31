# FiliArrochada.github.io

The FiliArrochada organisation's GitHub Pages site, served at `https://filiarrochada.github.io/`.
Plain HTML and one stylesheet: no build step, no scripts, no external requests.

The projects live on the GitHub org page and its profile README (`.github` repo, `profile/README.md`),
the only project list. This site exists for the support page.

| Path | Page |
|---|---|
| `index.html` | Redirects to `https://github.com/FiliArrochada` |
| `support/index.html` | **Support Fili**, at `https://filiarrochada.github.io/support/`: every working way to pay, lowest fee first, and what support pays for |
| `support/pt/`, `support/fr/`, `support/it/` | The same page in Portuguese (Portugal), French and Italian. Keep all four in step, including the `hreflang` links in each `<head>` |
| `style.css` | Styles for the support page, light and dark |
| `robots.txt`, `sitemap.xml` | Crawler hints; add new pages to the sitemap |

Pages source: deploy from branch, root.

When GitHub Sponsors is approved, add it back to the support page as the first method (no fee for
personal sponsors) and to the hero.
