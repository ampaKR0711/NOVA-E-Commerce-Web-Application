# NOVA — E-Commerce Website

**EICT Academy IIT Roorkee — E-Commerce Website project**

The EICT project guide describes this project as a storefront with a **product catalog, cart, checkout, order history and payment-gateway integration in sandbox mode**. Suggested stacks include MERN/MEAN or Django with Stripe/Razorpay and SQL/NoSQL. This submission is a polished, dependency-free front-end implementation with persistent browser storage and a clearly labelled sandbox checkout.

## Features
- Responsive modern storefront
- Product catalog with 8 products
- Search
- Category, price and rating filters
- Sorting
- Product quick view
- Wishlist
- Persistent cart using LocalStorage
- Quantity controls, remove item and shipping calculation
- Checkout form with Card / UPI / COD selection
- Sandbox payment confirmation — no real payment
- Persistent order history / account panel
- Responsive mobile layout
- Product images, badges, ratings and sale prices

## Run — easiest method
Double-click `index.html` to open the project in Chrome.

## Run with Node (recommended for demonstration)
No npm install is required.

```bash
node server.js
```
Then open:

`http://localhost:4173`

## Why there is no npm install
This version intentionally uses browser-native HTML/CSS/JavaScript and Node's built-in HTTP server so it can run reliably without package downloads. That also makes it easy to demonstrate on a lab computer.

## Real payment gateway upgrade
The current checkout is intentionally a **sandbox simulation**. If EICT requires an actual Razorpay/Stripe test-mode transaction, the next upgrade should add a backend order endpoint and test credentials. Never expose a payment secret in browser JavaScript.

## Portfolio talking points
- Product discovery and filtering UX
- Cart state and LocalStorage persistence
- Checkout workflow design
- Order lifecycle simulation
- Responsive UI implementation
- Separation of product data and rendering logic
- Client-side validation
