# Customization Checklist

Use this list when turning the template into your own site.

## Branding

- [ ] Replace `YOUR_PROJECT_NAME` and `YOUR_BRAND_NAME` in `index.html`, `public/manifest.json`, and `README.md`
- [ ] Swap `public/logo.svg` for your logo (keep the filename or update references)
- [ ] Swap `public/hero.jpg` for your hero background
- [ ] Swap `public/og-image.png` for social sharing (recommended 1200×630)
- [ ] Replace `public/favicon.png` and `public/icon-192.png`
- [ ] Replace `public/media-01.jpg` … `public/media-08.jpg` with real course or gallery images (update `alt` text to match)

## Contact & locations

- [ ] Update phone numbers (`tel:` and `https://wa.me/…`) and visible phone copy
- [ ] Update `mailto:your@email.com` and footer email
- [ ] Replace `YOUR_CITY_*` and `YOUR_ADDRESS_LINE_*` placeholders
- [ ] Replace `YOUR_REGION_ONE`, `YOUR_REGION_TWO`, and `YOUR_STAT_HIGHLIGHT` in the stats strip

## SEO

- [ ] Set `YOUR_PROJECT_DESCRIPTION` everywhere it appears (meta, Open Graph, Twitter, JSON-LD)
- [ ] Replace `https://yourdomain.com` with your real domain (canonical, OG/Twitter URLs, JSON-LD, `public/robots.txt`, `public/sitemap.xml`)
- [ ] Adjust `public/sitemap.xml` if you add more pages
- [ ] Review `public/robots.txt` `Sitemap:` URL after deployment

## Deployment

- [ ] Point DNS to your host and configure HTTPS
- [ ] Confirm asset paths (`public/…`) match how your host serves static files (some platforms use `public/` as the web root; you may need to move files or change paths)

## Analytics

- [ ] Add your analytics snippet where the `ANALYTICS PLACEHOLDER` comments are in `index.html`

## Legal

- [ ] Add a privacy policy page and link it from the footer if you collect data or use analytics
- [ ] Add terms of use if needed
- [ ] Update `LICENSE` with your legal name or entity

## Project metadata

- [ ] Edit `package.json` (`name`, `description`, `author`, `homepage`, `repository`)
- [ ] Point `git remote` at your own repository when you are ready
