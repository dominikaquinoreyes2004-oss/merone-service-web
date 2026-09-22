# Merone Service SRL — GitHub + Cloudflare

Static website for Merone Service SRL. The site is configured for Cloudflare Workers Static Assets.

## Repository structure
- `wrangler.jsonc` — tells Wrangler to publish `./public`
- `public/index.html` — website
- `public/styles.css` — styling
- `public/script.js` — mobile menu
- `public/assets/` — exact logo and all website photography

## Cloudflare Workers Builds
Use these settings in the existing project:
- Root directory: `/`
- Build command: `exit 0`
- Deploy command: `npx wrangler deploy`
- Production branch: `main`

Do not upload this ZIP as a ZIP inside GitHub. Extract it first and upload the extracted contents so `wrangler.jsonc` is at repository root and `public/` is directly underneath it.

## Main contact
WhatsApp: +1 (829) 755-9560
Address: Avenida España, Plaza La Realeza, Local 8B, Punta Cana, República Dominicana
Coverage: Punta Cana y Zona Este
