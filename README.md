# Nightstand — Marketing Site

Static marketing website for the Nightstand iOS/Android app.

## Pages

- **`index.html`** — Main marketing/landing page
- **`privacy.html`** — Privacy Policy + Terms of Use
- **`support.html`** — Support FAQ + contact

## Deploying to Vercel

### Option A: Vercel CLI
```bash
npm i -g vercel
cd nightstand-site
vercel
```
Follow the prompts. On first deploy, set up the project. Subsequent deploys: `vercel --prod`

### Option B: Vercel Dashboard (no CLI)
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → New Project
3. Import your repo
4. Framework preset: **Other** (no build step needed)
5. Deploy — done

### Custom domain
After deploying, go to your project in the Vercel dashboard → Settings → Domains → add your domain (e.g. `nightstandapp.com`).

## Before going live

Update these placeholders:

| File | Placeholder | Replace with |
|------|------------|--------------|
| `privacy.html` | `support@nightstandapp.com` | Your real support email |
| `support.html` | `support@nightstandapp.com` | Your real support email |
| `index.html` | `#download` links | Real App Store URL when live |
| `images/icon.png` | _(missing)_ | App icon (1024×1024, PNG) |
| Privacy Policy date | April 1, 2025 | Update to actual publish date |

## Adding screenshots (optional)

Drop phone/tablet screenshots into `images/` and add them to `index.html` for more visual punch. Recommended: 390×844 PNG (iPhone 14 size).
