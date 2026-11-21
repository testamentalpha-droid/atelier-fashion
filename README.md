# Atelier — Shopify Fashion Theme Starter

This repository contains:
- `theme/`: Shopify Online Store 2.0 theme source (Liquid).
- `preview/`: static design preview that can be deployed to Vercel.

## Important testing note
Vercel cannot execute Shopify Liquid. The `preview/` folder is a visual prototype for checking layout and responsive styling. To test real Shopify behavior (products, cart, variants, sections, settings), upload `theme/` as a ZIP to a Shopify development store or use Shopify's supported theme preview tooling.

## GitHub + Vercel
1. Extract this ZIP.
2. Upload the extracted files and folders to your GitHub repository.
3. In Vercel, import the repository.
4. Set the Vercel project Root Directory to `preview`.
5. Deploy.

## Shopify theme package
Zip the *contents* of the `theme/` folder (not the folder itself) when preparing a theme upload. This starter is a foundation, not a Theme Store submission-ready product.
