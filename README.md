# Tharaphy NY shop

Online shop for [@tharaphyny_amigurumi](https://www.instagram.com/tharaphyny_amigurumi/): handmade anime amigurumi, earrings, hair clips and other handmade goods. Planned domain: **tharaphy.com**.

## Status (Nov 10, 2026)

Design mockups are done for steps 1–3. Open the files in `mockups/` in a browser, or see the `*-desktop.png` snapshots.

| Step | Page | Status |
|---|---|---|
| 1 | Homepage (`mockups/home.html`) | Approved |
| 2 | Product page (`mockups/product.html`) | Approved |
| 3 | Cart with market pickup (`mockups/cart.html`) | Waiting for feedback |
| 4 | Admin: photos, products, stock, markets, orders | Not started |
| 5 | About, Custom orders, Markets pages, then launch | Not started |

## Decisions so far

- **Look:** cozy knit shop. Oatmeal linen, cocoa text, sage and rose accents, Fraunces (soft) headings with Nunito body. Shared styles are in `mockups/cozy.css`.
- **Categories:** Anime amigurumi, Earrings, Hair clips, Handmade goods (non-anime). Fandom filters: Demon Slayer, Chainsaw Man, Studio Ghibli, Naruto, One Piece, Jujutsu Kaisen, Genshin. More can be added later.
- **Stock:** every product shows a count ("4 in stock", "Only 1 left", "Sold out").
- **Markets:** a different market every Saturday. The site shows this week's market in the top banner and the next 4 on the homepage. Shoppers can choose free pickup at a specific Saturday market in the cart.
- **Payments:** Stripe Checkout (card, Apple Pay, Google Pay). Build and test in Stripe test mode first.
- **Admin:** option B, a private admin page on the site for uploading photos, adding products, stock counts and the market schedule.
- **Hosting plan:** Next.js on Vercel, code in this GitHub repository.

## Open questions

1. Shipping price and free-shipping threshold (mockup uses $6, free over $75 as examples).
2. Real upcoming Saturday markets: name, place, hours.
3. Sales tax: Stripe Tax, or leave off for now.

## To do (owner)

- Buy **tharaphy.com** (looked available Nov 10, 2026).
- Create a **Stripe** account before checkout is built.
- Add original product photos to `photos/`.
