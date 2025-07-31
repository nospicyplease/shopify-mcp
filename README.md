# Shopify Storefront Proxy

This repository exposes a simple API endpoint that forwards GraphQL queries to the Shopify Storefront API. The endpoint is implemented as a Vercel/Next.js API route in `pages/api/storefront-graphql.js`.

## Running locally

1. Install dependencies:

```bash
npm install
```

2. Set the required environment variable in a `.env` file or your shell:

```bash
export SHOPIFY_STOREFRONT_ACCESS_TOKEN=your_storefront_token
```

3. Start the development server with Vercel (or `next dev` if you have Next.js installed):

```bash
npx vercel dev
```

The API will be available at `http://localhost:3000/api/storefront-graphql`.
