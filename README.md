# PokeScout Landing

Static landing page for **PokeScout** (pure HTML/CSS, no build step) deployed on Vercel.

## Files
- `index.html` — mobile-first landing page
- `vercel.json` — SPA-style rewrite to `index.html`
- `og-image.png` — social preview image (1200x630)

## Deploy
```bash
vercel --prod --yes
```

## Domain purchase + connect
1. Buy **pokescoutapp.com** on Namecheap (typically ~$12/year).
2. In Vercel Project → Settings → Domains, add `pokescoutapp.com` and `www.pokescoutapp.com`.
3. Update Namecheap DNS to Vercel records shown in dashboard.

## Cloudflare Email Routing setup
After domain is on Cloudflare DNS:
1. Cloudflare Dashboard → Email → Email Routing → Enable.
2. Create route: `hello@pokescoutapp.com` → `pax.operations@gmail.com`.
3. Also add:
   - `support@pokescoutapp.com` → `pax.operations@gmail.com`
   - `noreply@pokescoutapp.com` → `pax.operations@gmail.com`
4. Confirm forwarding destination when Google verification email arrives.

## Social handles recommendation
Use **@pokescoutapp** consistently:
- TikTok: `@pokescoutapp`
- Instagram: `@pokescoutapp`
- X/Twitter: `@pokescoutapp`
- Reddit: `u/pokescoutapp`
