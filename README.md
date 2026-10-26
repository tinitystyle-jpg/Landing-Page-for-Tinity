# Tactical Wear Landing Page (Starter)

A responsive Next.js landing page inspired by a direct-to-customer apparel product page.

## Included

- Mobile-friendly product landing page
- Product offer and feature sections
- Waist-size selector
- Customer details form
- Quantity and delivery-area selection
- Automatic subtotal, delivery charge and total calculation
- Demo form validation and demo-only confirmation
- No backend, database, payments or courier API connected yet

## Important before publishing

The product name, product illustration, price, crossed-out price, product claims, size range and delivery fees are sample content. Replace them with your actual product details and verified terms. The current product illustration is a custom SVG illustration, not an actual product photo.

The submit button intentionally does **not** save customer information or create a courier booking. Connect a secure backend and verify the complete workflow before taking live orders.

## Run locally

Install Node.js (LTS) from https://nodejs.org/

Then, in this project folder, run:

```bash
npm install
npm run dev
```

Open http://localhost:3000

## Deploy to Vercel

1. Create a GitHub account at https://github.com/
2. Create a new repository and upload these project files.
3. Sign in to https://vercel.com/ and import the GitHub repository.
4. Deploy with the default Next.js settings.

Vercel's Hobby plan is for personal, non-commercial use. For a real store, choose a plan that permits your commercial use.

## Later integration plan

1. Add a database such as Supabase for orders.
2. Add server-side validation and order creation.
3. Keep courier API credentials in server-side environment variables.
4. Integrate Steadfast's official merchant API.
5. Add an order dashboard, duplicate-order protections and error handling.
6. Test in a safe workflow before creating real parcels.
