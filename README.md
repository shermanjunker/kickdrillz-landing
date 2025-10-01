# KickDrillz Landing (Netlify-ready)

This repo contains a static landing page + Netlify form.

## Files
- `index.html` — main site. All links route users to **request-info.html**.
- `request-info.html` — Netlify Forms-powered info request.
- `thanks.html` — submission confirmation.
- `assets/` — logo + apparel mockups.
- `_redirects` — keeps `/thanks` working.

## Quick deploy — GitHub ➜ Netlify
1. Create a new GitHub repo (e.g., `kickdrillz-site`) and upload these files.
2. Go to Netlify → **Add new site** → **Import from Git** → pick the repo.
3. Build config: *No build command*, Publish directory: `/` (root).
4. After deploy, open **Forms** tab in Netlify; you should see `kd-request` form.
5. Add notifications under **Site settings → Forms → Notifications**.

## Point your domain to Netlify
- In Namecheap (or GoDaddy), add a CNAME for `www` ➜ your `*.netlify.app` subdomain.
- Redirect the root `kickdrillz.com` ➜ `https://www.kickdrillz.com` using URL redirect (301).

## Local preview
Open `index.html` in your browser (no server required).

---

Made with ❤️ using Tailwind CDN.
