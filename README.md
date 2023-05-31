# Shopify Node.js x Express.js x React.js Boilerplate

An embedded app starter template to get up and ready with Shopify app development with JavaScript. This is heavily influenced by the choices Shopify Engineering team 

## Tech Stack

- React.js
  - `raviger` for routing.
- Express.js
- MongoDB
- Vite
- Ngrok
- Apollo/Client

## Why I made this

The Shopify CLI generates an amazing starter app but it still needs some more boilerplate code and customizations so I can jump on to building apps with a simple clone. This includes:

- MongoDB based session and database management.
- Monetization (recurring subscriptions) ready to go.
- Webhooks isolated and setup.
- React routing taken care of (I miss Next.js mostly because of routing and under the hood improvements).
- Misc boilerplate code and templates to quickly setup inApp subscriptions, routes, webhooks and more.

### Misc

- Storing data is kept to a minimal to allow building custom models for flexibility.
  - Session persistence is also kept to a minimal and based on the Redis example provided by Shopify, but feel free to modify as required.
