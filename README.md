# MyAITask – Jekyll on Netlify

Monetization-ready site with:
- Landing page (Razorpay buttons placeholders)
- Resources (affiliate links)
- Products (digital downloads via Razorpay buttons)
- Write for Us (guest post payments via Razorpay)
- Blog (Markdown posts)
- Legal pages (Privacy/Terms/Refund)
- Netlify build config + sitemap/feed

## Deploy
1) Create a **new GitHub repo** (empty) and upload all files.
2) Netlify → **Add new site** → **Import from Git** → pick the repo.
3) After connecting your domain, set `url:` in `_config.yml` to your real domain.

## Razorpay
Replace `data-payment_button_id` placeholders in `index.html`, `products.md`, `write-for-us.md` with your real IDs.
