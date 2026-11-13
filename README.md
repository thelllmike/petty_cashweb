# petty_cashweb

Marketing website for **Petty Cash** — the pocket cash book for small businesses
([Google Play](https://play.google.com/store/apps/details?id=com.pettycash.app)).

A static site: no build step, no dependencies.

```
index.html      landing page
privacy.html    privacy policy
css/styles.css  styles (colours and type follow the app's design tokens)
js/main.js      sticky nav, mobile menu, scroll reveal
assets/         app icon, favicon, social share image
vercel.json     clean URLs (/privacy)
```

## Run locally

```bash
python3 -m http.server 4173   # http://localhost:4173
```

## Deploy

Hosted on Vercel as a static project (framework preset: **Other**, no build command).
