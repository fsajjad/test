# Simple E-Commerce Demo

This is a simple e-commerce demo built with Next.js, TypeScript, and Tailwind CSS.

## Phase 1: Setup & Basic Pages

- ✅ Initialize Project: Set up a new Next.js project with TypeScript and Tailwind CSS.
- ✅ Create Pages:
  - ✅ Home (/)
  - ✅ Products (/products)
  - ✅ Product Details (/products/[id])
  - ✅ Cart (/cart)

## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- `/src/app/page.tsx` - Home page
- `/src/app/products/page.tsx` - Products listing page
- `/src/app/products/[id]/page.tsx` - Product details page
- `/src/app/cart/page.tsx` - Shopping cart page
- `/src/app/layout.tsx` - Root layout with header and footer

## Next Steps

- Phase 2: Implement product display with real data
- Phase 3: Add shopping cart functionality
- Phase 4: Deploy the application