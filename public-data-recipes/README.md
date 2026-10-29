# Public Data Recipes (draft, not deployed)

A static site that's ready for GitHub Pages. It has no build step for visitors. To regenerate the pages, run `python3 _build/build.py`.

Placeholders to replace before going live (each needs Liora's approval):
- `https://liorablyth.github.io/public-data-recipes`: the base URL in canonical tags, sitemap.xml, robots.txt and llms.txt (set as BASE in _build/build.py).
- `PAYMENT_LINK_PLACEHOLDER` in sponsor.html.
- `CONTACT_EMAIL_PLACEHOLDER` in sponsor.html and about.html.
- Chrome Web Store links for Holdfast and Hushframe in tools.html (only the Firefox links are verified).

Publish only the site files. `.gitignore` excludes research/, founder/, _build/ and REPORT_zh.md.
To re-test the recipes: `for f in _build/snippets/*.py; do python3 $f; done`
