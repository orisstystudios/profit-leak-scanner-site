# Auditink public website

Landing page, blog, support and privacy pages for the Auditink Shopify app
(Orissty Studios), served free by GitHub Pages at
https://orisstystudios.github.io/profit-leak-scanner-site/

- `index.html`: landing page (all buttons go to the App Store listing with `utm_` tags,
  so installs from the site show up in the Partner Dashboard)
- `blog/index.html`: blog list. Add a card here for every new post, newest first.
- `blog/<slug>/index.html`: one folder per article. Copy `shopify-profit-leaks/` as a template.
- `support.html`, `privacy-policy.html`: the App Store listing's Support and Privacy URLs. Do not rename.
- `assets/site.css`: shared styles (same colors as the app). `assets/`: icons, social card, images.
- `sitemap.xml`: add each new article URL.
- Every page ends with the Cloudflare Web Analytics snippet (visitor counter, no cookies). Copy it into new pages.

Writing rule for public text: no dashes as punctuation, use commas or full stops.
Publish = commit and push to `main`; GitHub Pages updates in about a minute.
