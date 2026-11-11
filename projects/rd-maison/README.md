# R. & D. Maison — Beauty for Every Shade

A responsive, single-page storefront for R. & D. Maison, built from the supplied original HTML and refined into a premium editorial-style shopping experience.

## Features

- Responsive layout with a custom CSS brand-art hero (the original embedded photograph has been removed).
- Product catalogue with category, skin type, concern and shade-family filters.
- Live search across product names, ingredients, shades and descriptions.
- Sort by featured order, price and product name.
- Product detail panels with shade selection and quantity controls.
- Persistent cart using browser local storage.
- Checkout request composed and sent to the store's WhatsApp number.
- Foundation shade finder, FAQs, ingredient glossary, contact and TikTok links.
- SEO metadata, keyboard focus styles, reduced-motion support and Product/Organization structured data.

## Run locally

This is a static website. Open `index.html` in a browser, or run a local server:

```bash
python -m http.server 4173
```

Then visit `http://localhost:4173`.

## Deploy to Vercel

Import the GitHub repository into Vercel. No build command is required; use the repository root as the output directory.

## Important production notes

This release is a front-end storefront. Cart persistence is browser-local, and checkout sends an order request to WhatsApp. It does **not** currently provide server-side inventory, customer accounts, order database, admin dashboard, automated order confirmation, payment processing or a secure backend. Those require a backend/database and should be implemented before treating the store as a full production commerce platform.

Product names, prices, claims, delivery/returns wording, contact details and social links were carried forward from the supplied source. The store owner should verify them before public launch.