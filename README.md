# خدمات فنی یاسین

سایت فارسی خدمات نصب و تعمیر کولر گازی، اجرای VRF و لوله‌کشی مسی در کاشان و اطراف.

## Cloudflare Workers

- Worker name: `cold-night-2bcb`
- Static assets: `public/`
- Worker entry: `src/index.js`
- Deploy command: `npx wrangler deploy`
- Build command: خالی (نیازی به build step نیست)

پس از اتصال این مخزن به Worker موجود در Cloudflare از مسیر **Settings → Builds → Connect**، شاخه `main` را برای production انتخاب کنید. پیش از فعال کردن deploy خودکار، مطمئن شوید پروژه Worker موجود با همین نام و تنظیمات است.


## Deployment trigger

This commit triggers the first Cloudflare Workers Builds deployment from the connected `main` branch.


## IndexNow
The public asset `public/0a63536d64014974a657ba1131385b3d.txt` verifies the site for IndexNow submissions.
