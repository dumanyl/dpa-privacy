# DPA privacy policy drafts (#57)

- `index.html` — bilingual page ready to host (Play needs a public HTTPS URL)
- `PRIVACY.pt.md` / `PRIVACY.en.md` — same content as markdown

## Publish (pick one)

1. **GitHub Pages** (fast): put `index.html` in a public repo `docs/` or `gh-pages` branch; enable Pages; use the `https://…github.io/…` URL in Play Console → App content → Privacy policy.
2. **Netlify / Cloudflare Pages**: drag-drop this folder or connect a repo; URL becomes the privacy link.
3. **Existing site**: copy `index.html` to e.g. `/privacy/`.

Play accepts one URL; the page switches pt/en in-browser (`#en` forces English).

## Review checklist for Dumany

- [ ] Contact email OK (`ldumany@gmail.com`) or change before publish
- [ ] 30-day route-log retention matches production `ROUTE_LOG_RETENTION_DAYS`
- [ ] M-Pesa paragraph OK until live payments
- [ ] After Crashlytics + reports + M-Pesa go live in production, re-read §5–§7
