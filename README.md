# Pista House London — Restaurant Website

A complete restaurant website with a built-in private content management system. Built for Pista House London, an authentic Hyderabadi restaurant in East Ham, London E6.

**Live site:** https://aetherom.github.io/Pistahouselondon/ · https://www.pistahouselondon.co.uk

---

## ✨ Features

### Public website
- Single-page experience — hero, story, signature dish slider, searchable menu, reviews, gallery with lightbox, ordering, map & enquiry form, FAQs
- Themed transitions — page-turn for Menu, star-rating for Reviews, film-strip for Gallery, delivery for Order, geo-pin for Find Us
- Fully responsive — glassy mobile dock and animated menu-card navigation
- Live menu sync — content updates from a private admin panel without touching code
- SEO ready — JSON-LD Restaurant + FAQ schema, Open Graph / Twitter cards, canonical URL, robots.txt, sitemap.xml, custom 404
- UK-compliant — PECR cookie consent (essential-only storage), UK GDPR privacy policy, allergen advice, Terms page
- Accessibility — aria labels, keyboard-navigable gallery, visible focus states, reduced-motion support
- Performance — preloaded hero, lazy-loaded images, zero heavy dependencies

### Admin panel (private)
- 2-step verification — PIN + one-time emailed key, with forgot-PIN reset
- Draft → Publish workflow with one-click Discard
- Full control — menu, prices, photos, gallery, contact, order links, policies, holiday banner
- Strict validation — nothing can be published blank
- Image uploads to Google Drive, one-click JSON backup/restore

---

## 🛠 Tech stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML/CSS/JS — no frameworks |
| Hosting | GitHub Pages |
| CMS & backend | Google Apps Script |
| Database | Google Sheets |
| Media storage | Google Drive |
| Email (2FA keys) | Google MailApp |

---

## 📁 Project structure

    ├── index.html          # Main website (single page)
    ├── privacy/index.html  # Privacy & Cookie Policy
    ├── terms/index.html    # Terms of Use
    ├── 404.html            # Custom not-found page
    ├── robots.txt          # Crawler rules
    └── sitemap.xml         # Search-engine sitemap

The admin panel is deployed privately via Google Apps Script and is not part of this public repository.

---

## 🚀 Running locally

No build step — open `index.html` in a browser, or serve the folder with `npx serve .`

---

## ⚙️ Owner operations

Daily content changes (menu, prices, photos, holiday banner) are made through the private admin panel and go live on Publish.

---

## 📄 License

© Pista House London. All rights reserved. Not licensed for reuse.
