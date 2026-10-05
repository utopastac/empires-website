# empires.f-90.co.uk

Marketing, privacy, and support site for [Empires](https://github.com/utopastac/empires-ios) (iOS), hosted as a subdomain of f-90.

## Stack

Plain HTML / CSS / JS (same shape as Pixelator’s `public/ios` pages). Nested CSS with variables; Syne + Sora via Google Fonts.

## Local preview

```sh
cd /Users/becter/code/empires-website
python3 -m http.server 8080
```

Open http://localhost:8080

## Deploy

GitHub Pages from this repo’s root (or `main` branch), custom domain `empires.f-90.co.uk`.

DNS: CNAME `empires` → your GitHub Pages host. Keep `CNAME` as `empires.f-90.co.uk`.

App Store listing URLs:

- Support: `https://empires.f-90.co.uk/support`
- Privacy Policy: `https://empires.f-90.co.uk/privacy`

## Assets

- `assets/app-icon.png` / `app-icon-256.png` — from the Empires iOS App Icon
- `assets/logotype.svg` — Empires wordmark
- `assets/screenshots/` — drop App Store / marketing screenshots here when ready
