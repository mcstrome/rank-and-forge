# Rank & Forge — Static Landing (Cloudflare Pages)

## Deploy
- Create Cloudflare Pages project → Framework preset: None → Output dir: `/`.
- Set custom domain `rankandforge.com`.

## Configure
- Replace `FORM_ID` in `index.html` with your Formspree endpoint.
- Replace `YOUR_CF_ANALYTICS_TOKEN` with your Cloudflare Web Analytics token.
- Swap `/assets/logo.svg` with your final logo and add a branded Open Graph image at `/assets/og.png` when available.

## Notes
- CSP allows Google Fonts + Formspree. If you add scripts, update CSP.
- Honeypot `_hp` reduces spam. Enable Formspree spam filter too.
