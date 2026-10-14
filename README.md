# KYARÉ — Luxury Perfume E-Commerce Website

**scent, in every shade.**

A complete, responsive, client-side luxury perfume e-commerce website for the KYARÉ brand.

## Features

- **Brand Identity**: Elegant serif + clean sans typography, cream/botanical color palette, consistent bottle silhouette across all 10 fragrances.
- **10 Signature Fragrances**: Full product data with notes, personality, descriptions, sizes, and prices (IDR placeholders).
- **Working Shopping Cart**: Add / remove / quantity, localStorage persistence, live totals, elegant drawer.
- **WhatsApp Checkout**: Generates a pre-filled order message and opens WhatsApp.
- **Fragrance Finder Quiz**: Interactive mood-based recommendation.
- **Search & Filters**: Search by name/notes, filter by mood category, sort by price/name.
- **Product Detail Modal**: Size selection, quantity, add to cart.
- **Gift Sets**: Discovery set and complete collection.
- **Newsletter form** (frontend validation + note about backend requirement).
- **Contact**: Exact WhatsApp, Instagram, and email links as specified.
- **Policies**: Privacy, Shipping, Returns (editable placeholders).
- **Fully Responsive**: Desktop, tablet, mobile with hamburger menu.
- **Accessible**: Semantic HTML, keyboard support (Escape closes modals), focusable controls.

## How to Run

1. Open `index.html` in a modern browser, **or**
2. Serve locally:

```bash
cd kyare-website
python3 -m http.server 8080
# then visit http://localhost:8080
```

No build step required. Pure HTML + CSS + vanilla JavaScript.

## Project Structure

```
kyare-website/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   └── images/          (placeholder — bottles are CSS-rendered for consistency)
└── README.md
```

## Notes

- Product bottles are rendered with CSS for perfect consistency of silhouette across the collection (matching the required rectangular glass bottle with cylindrical cap). Cap colors and labels change per fragrance.
- Prices are editable placeholders in Indonesian Rupiah.
- Cart and checkout are fully functional on the client side. Real payment processing or order management requires a backend.
- Newsletter subscription is a demo; real email collection needs a service (Mailchimp, etc.).
- Contact details are exactly as provided:
  - WhatsApp: 085286707303 → https://wa.me/6285286707303
  - Instagram: @zky.a4
  - Email: zkyaa4@gmail.com

## Customization

- Edit product data, prices, and sizes in `js/script.js` (the `products` array).
- Colors and typography live in `css/style.css` under `:root`.
- Announcement bar text is at the top of `index.html`.

© 2026 KYARÉ. All rights reserved.
