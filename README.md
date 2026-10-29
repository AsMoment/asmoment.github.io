# AsMoment Website v2

A multi-page, responsive beta website for AsMoment.

## Pages
- `index.html` — homepage
- `why-asmoment.html` — product philosophy and differentiation
- `privacy.html` — privacy architecture and supported storage
- `ai.html` — forward-looking AsMoment + AI direction
- `beta.html` — beta invitation/contact

## Preview locally
From this directory:
```bash
python3 -m http.server 8000
```
Then open `http://localhost:8000`.

## Publish to GitHub Pages
Copy/commit the contents of this folder to the root of `AsMoment/asmoment.github.io`, push to `main`, then enable GitHub Pages from the `main` branch and `/ (root)`.

## Production checklist
- Confirm all product/security wording against the implementation.
- Add/link the authoritative Terms of Service and Privacy Statement before replacing the production site.
- Replace the email-only beta flow with the preferred enrollment form if desired.
- Test on current Chrome, Firefox, Safari, iOS Safari, and Android Chrome.
- The only external design dependency is Google Fonts; the site has system-font fallbacks.
- No GoDaddy-provided photography is included.


## v2.1 changes

- Replaced temporary four-space symbols with Material Symbols corresponding to the Flutter app:
  `person`, `diversity_1`, `hub`, and `campaign`.
- Standardized space names and subtitles:
  My Little Corner / Only you; Family & Friends / People you choose;
  My Communities / Groups you create or join; Town Square / Open to everyone.
- Added the space accent palette: teal, warm orange, blue, and indigo.
- Added a human-centered storytelling section with prepared photography slots.
  These are intentionally stylized placeholders so no unapproved or ambiguously licensed
  photography is bundled into the site. Replace them with approved/licensed photographs later.
- Added POCIANET LLC product/copyright identification.
- Preserved the existing product, privacy architecture, cloud-storage, cross-platform,
  restrained-AI, and beta positioning.
