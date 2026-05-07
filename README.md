# Seedwise — Free Guide Landing Page

Lead magnet capture page for *"The 4 Ways to Raise Financially Confident Kids"* — a free PDF guide by Seedwise.

## Deploy to Vercel

1. Push this repo to GitHub
2. Connect the repo in [Vercel Dashboard](https://vercel.com/new)
3. Deploy — no build step needed (static HTML)

## Project Structure

```
seedwise-free-guide/
├── index.html          # Landing page (~25KB)
├── vercel.json         # Cache headers + security
├── robots.txt          # Search engine directives
├── sitemap.xml         # SEO sitemap
├── README.md
└── images/
    └── guide-cover.jpg # Lead magnet cover (43KB)
```

## Before Going Live

1. Replace `https://seedwise.com/free-guide` in meta tags with your actual URL
2. Connect the email capture forms to your ESP (Systeme.io, ConvertKit, etc.)
3. Add your ESP's form action URL to both `<form>` elements
4. Update the Seedwise Collection link in the bridge note section

---

© 2026 Seedwise — Financial Wisdom Collection
