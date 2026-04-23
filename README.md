# Gray Wyot — Portfolio

Minimal mixing & mastering portfolio. Astro + Tailwind CSS v4. Zero JS by default.

## Dev

```bash
npm install
npm run dev       # http://localhost:4321
npm run build     # dist/ → static site
npm run preview
```

## Deploy (Vercel, free)

1. Push this repo to GitHub:
   ```bash
   git init && git add -A && git commit -m "init: portfolio v1"
   git branch -M main
   git remote add origin git@github.com:<your-user>/graywyot-portfolio.git
   git push -u origin main
   ```
2. Go to <https://vercel.com/new> → Import repo → Framework: **Astro** (auto-detected) → Deploy.
3. URL: `graywyot.vercel.app` (or your custom project name). Custom domain `graywyot.com` can be added later in Project → Settings → Domains.

## Before going live — replace these placeholders

- `src/pages/index.astro`
  - `FORMSPREE_ENDPOINT` → real Formspree form URL (sign up at <https://formspree.io>, create a form, paste endpoint)
  - `SOUNDBETTER_URL` → your real SoundBetter profile URL
  - `hello@graywyot.com` → your real contact email (2 places: contact section + footer)
- `public/favicon.svg` — optional upgrade to a real mark

## Stack

- [Astro 6](https://astro.build)
- [Tailwind CSS v4](https://tailwindcss.com) via `@tailwindcss/vite`
- Google Fonts: Fraunces (serif display), Inter (body)

## Design language

Warm paper background, deep ink text, terracotta accent. Editorial, typography-first.
Inspired by Anthropic's Claude Design System + apple.com minimalism.
