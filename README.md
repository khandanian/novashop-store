# NovaShop Store

A responsive Persian RTL demo storefront built with vanilla HTML, CSS and JavaScript.

## Demo URL
https://khandanian.github.io/novashop-store/

## Features
- 12 fictional products with category, rating, and price
- Search, category and maximum-price filters, sorting
- Product detail dialog
- Persistent shopping cart with quantity controls
- Automatic 5% discount for carts >= 10,000,000 toman
- Free shipping for carts >= 3,000,000 toman; otherwise 120,000 toman
- Demo checkout form and locally stored order history
- Responsive dark-mode layout
- Data saved to localStorage

## Important limitations
**This is a portfolio demo, not a real store.** Products, prices, ratings, and orders are fictional. No real payment is collected, no order is sent to a seller, and nothing is shipped. Checkout form details are stored only in the current browser; do not use sensitive real information. Clearing browser data deletes the cart and orders.

## Run
Open `index.html` or serve locally with `python -m http.server 8080`.

## GitHub Pages
In **Settings → Pages**, set **Source: GitHub Actions** once. The included workflow deploys pushes to `main`; it does not try to enable Pages automatically.
