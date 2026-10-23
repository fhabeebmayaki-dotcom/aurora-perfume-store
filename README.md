# AURORA — Perfume Store (Demo Storefront)

An elegant, full-frame luxury perfume e-commerce demo inspired by a TikTok web-design showcase — rebuilt bigger, sharper and fully interactive. Ivory/taupe/champagne palette, serif display type, and a working boutique shopping experience.

## What's inside
- **Hero** — "Discover Your Scent" with a framed product photo, live stats, and a scrolling fragrance-name marquee
- **Product grid** — 8 fragrances with real photography, scent-family tags and note summaries
- **Family filters** — All / Floral / Woody / Oriental / Fresh, filtering instantly in vanilla JS
- **Quick-view modal** — full note pyramid (top / heart / base), long description, and a 50 ml / 100 ml size selector that reprices live (50 ml = 80% of the 100 ml price)
- **Scent quiz** — 3 questions; answers score the four scent families and recommend a real product, with a working "Add to Bag" and retake
- **Cart drawer** — add/remove, quantity steppers, live total, free-shipping progress note ($150 threshold), and a checkout success state with order number
- **Extras** — story section, service pillars, newsletter form with success message, toast notifications, scroll-reveal animations, fully responsive

## Run it
Open `index.html` in any browser. No build step, no dependencies beyond Google Fonts.

## Make it yours (buyer guide)
- **Products:** edit the `PRODUCTS` array at the top of the script — name, family, price, notes, description, image
- **Photos:** replace files in `images/` (Unsplash placeholders — swap in your own product photography before launch)
- **Prices/sizes:** change `price` per product; the 50 ml multiplier is `data-mult` on the size buttons
- **Brand:** change the AURORA wordmark, announcement bar, footer details, and the CSS variables in `:root` for a new palette
- **Checkout:** the demo checkout is a front-end success state; connect the `checkoutBtn` handler to Stripe/your provider for live orders

## Files
- `index.html` — the entire site (embedded CSS + JS)
- `images/` — 10 product/lifestyle photos
- `README.md` — this file
