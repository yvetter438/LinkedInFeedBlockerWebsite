# LinkedIn Feed Blocker Website

Marketing site and legal docs for the [LinkedIn Feed Blocker](https://github.com/yvetter438/LinkedInFeedBlockerWebsite) Chrome extension.

## Pages

| Page | URL |
|------|-----|
| Landing page | `/` |
| Privacy Policy | `/privacy-policy.html` |
| Terms of Service | `/terms-of-service.html` |

Source markdown for legal docs is also kept in the repo root (`privacy-policy.md`, `terms-of-service.md`).

## GitHub Pages

This site is a static HTML site — no build step required.

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**
4. Choose the `main` branch and `/ (root)` folder
5. Save — your site will be live at `https://yvetter438.github.io/LinkedInFeedBlockerWebsite/`

## Before launch

Replace these placeholders across the site and markdown files:

- `[DATE]` — last updated date
- Support email: `yannick.vetter@outlook.com`
- `[YOUR NAME/COMPANY]` — in Terms of Service
- `[YOUR STATE/COUNTRY]` — governing law
- Chrome Web Store link — update the "Add to Chrome" buttons in `index.html`

## Local preview

Open `index.html` in a browser, or run a simple server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
