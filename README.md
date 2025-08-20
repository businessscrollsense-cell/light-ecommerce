<div align="center">
<h2>Svelte Commerce</h2>
</div>

<div align="center">

**The open-source frontend for any eCommerce. Built with a headless approach, using a modern JS stack. We have WIP for MedusaJS, Shopify. The API approach also allows you to merge Svelte Commerce with any third-party tool like payment gateways, POS or AI.**

</div>

## What is it?

- Svelte Commerce is a PWA storefront for your existing eCommerce based on Sveltekit.
- It is possible to connect with any eCommerce backend that provides an API
- We are working on adaptors of Medusajs, Shopify

## Features

- 👨🏻‍💻 Its both SSR and SPA
- 🚀 Superfast
- 🔗 It is possible to connect with any eCommerce backend if the backend has Rest API
- 🔓 Svelte Commerce is free and open source. Download and modify it the way you want
- 🛒 Most of the essential features for ecommerce are already integrated
- 💰 No need to make a big leap or invest huge amount. Just take this opend source project and attach to existing backend.

## Get Started

```
git clone https://github.com/john920215/svelte-commerce.git
cd svelte-commerce
npm i
npm run dev
```

Thats all !

Open http://localhost:3000 on chrome. Your app should be live with awesome svelte-commerce up and running

## Development
run `npm link` inside `litekart-utils` repo
run `npm link @misiki/litekart-utils` inside this repo
run `npm link` inside `litekart-connector` repo
run `npm link @misiki/litekart-connector` inside this repo

## Configuration

There are 3 places to configure

1. `src/lib/config/`
   All non secret and application wide configs are stored here. If required, change according to your requirement.

2. `.env`
   All secrets stored here

3. `src/lib/services/index.ts`
   This is used to define which service to use. Only 1 of the listed service can be active at a time. Valid values are
   - `export * from '@misiki/litekart-connector'`
   - `export * from '@misiki/medusa-connector'`

## Deployment

The following envirnoment variable is mandatory

```
PUBLIC_LITEKART_DOMAIN=arialshop.com
PUBLIC_LITEKART_API_URL=https://api.litekart.in
```

You can replace the env variable with your store domain

## Features

Svelte ecommerce - Headless, Authentication, Cart & Checkout, TailwindCSS, Server Rendered, Proxy + API Integrated, Animations, Lazy Loading, Loading Indicators, Carousel, Instant Search, Faceted Filters, Open Source

## Updates

Please refer to [CHANGELOG.md](CHANGELOG.md) for updates