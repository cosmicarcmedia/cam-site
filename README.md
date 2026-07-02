# Cosmic Arc Media, marketing site

Single-page static site for Cosmic Arc Media. No build step: `index.html` plus
`assets/` (logo and video poster SVGs). Explainer and sample videos are embedded
from YouTube; the contact form posts to FormSubmit and emails the inbox.

## Local preview

```
python3 -m http.server 8099
# open http://localhost:8099/
```

## Deploy

Hosted on Cloudflare Pages, connected to this repo. Every push to `main`
auto-publishes. No build command; output directory is the repo root.
