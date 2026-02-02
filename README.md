# Surfaxe landing page (static)

This folder contains a ready-to-deploy static landing page:
- `index.html`
- `styles.css`
- `thanks.html`
- `privacy.html`

## What to customize first

1) Replace placeholder links in `index.html` under **Start now**:
- Stripe payment link
- Intake form link (Tally/Typeform/Google Form)

2) Replace the contact email `hello@surfaxe.com` if needed.

3) Optional: change pricing and the case study blurb.

## Quick deploy (easy)

### Netlify (fastest)
- Go to Netlify → Add new site → Deploy manually
- Drag this folder contents into the upload area

### Vercel
- `npm i -g vercel`
- `cd surfaxe-landing`
- `vercel` (choose “Other” / static)

## Notes
- This page intentionally avoids heavy images so it still sells even when images don’t load.
- Compliance language avoids incentives/review gating.
