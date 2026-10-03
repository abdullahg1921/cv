# Muhammad Abdullah, DevOps Engineer portfolio

Single-page portfolio: experience, case studies with architecture diagrams, and stack.
Plain HTML, CSS and a little JavaScript. No build step, no framework.

Live: https://abdullahg1921.github.io/cv/

## Files

| File | Purpose |
|------|---------|
| `index.html` | The whole site |
| `Muhammad_Abdullah_DevOps_CV.pdf` | CV linked from the Download buttons (add this yourself) |
| `og-image.png` | Preview image for LinkedIn and other link shares |
| `favicon.svg` | Browser tab icon |
| `404.html` | Not-found page |
| `robots.txt`, `sitemap.xml` | Search engine hints |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |
| `optional-deploy-pages.yml` | Deploy through GitHub Actions (optional) |

## Preview locally

    python3 -m http.server 8000

Then open http://localhost:8000

## Deploy

Settings -> Pages -> Source: "Deploy from a branch" -> Branch: `main`, folder `/ (root)`.
Pushes to `main` publish automatically.

## If the site URL changes

Update the URL in `index.html` (canonical, `og:url`, `og:image`, JSON-LD), `robots.txt`,
`sitemap.xml` and the links in `404.html`.
