# Bunnyboo — premium playful storefront

A responsive, blush-and-cream concept storefront for Bunnyboo's bunny-ear headband. Built as a lightweight static HTML/CSS/JavaScript site, deployable to Vercel.

## Local preview

No build step is needed. Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 4173
```

Then visit http://localhost:4173.

## Deploy to Vercel

1. Import this GitHub repository into Vercel.
2. Choose **Other** as the framework preset (or the equivalent static-site option).
3. Leave the build command empty and set the output directory to `.` if Vercel asks.
4. Deploy.
5. Add the domain in Vercel project settings. Copy the exact DNS records shown by Vercel into Hostinger's DNS Zone Editor.

## Important before taking real orders

This is a **visual storefront prototype**, not a fully operational store. The cart currently demonstrates UI behavior only; it does not reserve stock or accept payment. Before launch:

- Verify the physical sample, materials, dimensions, sizing, age guidance, and product claims with the supplier.
- Replace illustration-based product art with original photographs of the real item.
- Set a researched selling price after including product cost, packaging, shipping, payment fees, applicable taxes, and returns.
- Connect a proper catalog/cart/checkout backend (for example, Shopify or WooCommerce), payment gateway, stock control, shipping, and order confirmation.
- Add working customer support, privacy, terms, cancellation, shipping, and refund policies.
- Connect the newsletter form to a consent-based mailing-list provider; currently it only provides a demo confirmation.

The design deliberately avoids fake reviews, fake scarcity, unsupported safety promises, and unverified delivery or discount claims.

## Design direction

- Premium but playful, childlike without feeling cluttered
- Cream, blush pink, soft peach, butter yellow, and mint
- Large editorial typography, rounded cards, simple navigation, visible product CTA
- Responsive mobile layout, FAQ accordions, accessible labels, and reduced-motion support

## License

Bunnyboo storefront code in this repository is provided under the MIT License. See the separate OpenPage upstream project if adopting its code; this repo's current storefront is a fresh static implementation inspired by the general prompt-to-site workflow, not a copy of OpenPage's source.
