# Compliance Check App — Legal Pages

Static legal landing page for TikTok Developer / API review. Contains:

- `index.html` — landing page with app name, description, and **visible** links to both legal docs
- `terms.html` — Terms & Conditions
- `privacy-policy.html` — Privacy Policy

## Before submitting to TikTok

- [ ] Confirm the App Name on these pages exactly matches the name you enter in the TikTok Developer portal (currently: **Compliance Check App**)
- [ ] Confirm the app name does not contain "TikTok" branding (it doesn't)
- [ ] Confirm the contact email is correct and monitored (currently: `nam@offspringdigital.com`)
- [ ] Replace the placeholder "About This App" description in `index.html` with real product copy if this is more than a dummy/placeholder
- [ ] Update the effective dates in `terms.html` / `privacy-policy.html` if you change the content later

## Hosting for free (GitHub Pages)

1. Create a public GitHub repo (e.g. `compliance-check-app-legal`).
2. Push these three files (`index.html`, `terms.html`, `privacy-policy.html`) to the repo root.
3. Go to **Settings → Pages**, set source to the `main` branch (root), and save.
4. Your live URL will be `https://<your-username>.github.io/compliance-check-app-legal/`.
5. Use that URL as your Privacy Policy / Terms URL in the TikTok Developer portal (link directly to `/privacy-policy.html` and `/terms.html`, or the root `index.html` which links to both).

Alternative: publish via Notion or Google Docs "Publish to web" and paste the same content.
