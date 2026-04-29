# nBari Apparels

A modern, single-page boutique website for **nBari Apparels** — a Pakistan-based brand specializing in elegant abayas and modest wear. Built as a single self-contained HTML file with custom CSS, ready to deploy anywhere.

🛍️ **Cash on Delivery available across Pakistan**

---

## ✨ Features

- **Single-file build** — everything (HTML, CSS, JS) lives in `nbari-apparels.html`. No build step, no dependencies.
- **Boutique-style design** — clean typography, generous whitespace, and a soft luxury palette tuned for fashion retail.
- **Responsive layout** — looks great on mobile, tablet, and desktop.
- **Hero section** — featured abaya image with brand tagline and call-to-action.
- **Product showcase** — card-based grid with named abaya collection pieces.
- **Social integration** — direct links to the brand's Instagram and Facebook pages.
- **Lightweight & fast** — no frameworks, no trackers, instant load.

---

## 🚀 Quick Start

### Option 1 — Open locally
Just double-click `nbari-apparels.html` in any modern browser.

### Option 2 — Serve locally
```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```
Then visit `http://localhost:8000/nbari-apparels.html`.

---

## 🌐 Publish on GitHub Pages (Free Hosting)

1. Create a new **public** repository on GitHub named `nbari-apparels`.
2. Upload `nbari-apparels.html` and **rename it to `index.html`**.
3. Go to **Settings → Pages**.
4. Under **Source**, choose the `main` branch and `/ (root)` folder, then **Save**.
5. Within ~1 minute, your site will be live at:
   ```
   https://<your-username>.github.io/nbari-apparels/
   ```

> 💡 Tip: To use a custom domain (e.g. `nbariapparels.com`), add it under **Settings → Pages → Custom domain** and update your DNS records.

---

## 📁 Project Structure

```
nbari-apparels/
├── index.html              # main site (rename from nbari-apparels.html)
├── images/                 # product photos (abayas, hero image, etc.)
│   └── Black Fancy Abaya.jpeg
└── README.md
```

---

## 🛠 Customizing

All styles live in the `<style>` block at the top of the HTML file. Common tweaks:

| What to change | Where to look |
|---|---|
| Brand colors | `:root` CSS variables at the top |
| Hero image | `.hero` background / `<img>` in hero section |
| Product cards | `.product-grid` section |
| Social links | Footer `<a>` tags (Instagram / Facebook URLs) |
| Contact info | Footer info block |

---

## 📱 Connect with nBari Apparels

- **Instagram:** [@nbari.apparels1](https://www.instagram.com/nbari.apparels1?igsh=NDYzeTN1Yzd4MGly)
- **Facebook:** [nBari Apparels](https://www.facebook.com/share/1D5c4FT1NF/)

---

## 📜 License

© nBari Apparels. All product images and brand assets belong to nBari Apparels.
The website code is free to adapt for personal or commercial use.

---

*Made with ❤️ for modest fashion.*
