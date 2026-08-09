# CALPAK Checkout Demo

PayPhi-style cart/checkout drawer for **CALPAK** (Luka Duffel).

## Structure

```
public/
  images/product/   # product media (local files only — no CDN)
  fonts/            # brand fonts (when used)
  *-logo.*          # brand logo
src/
  data/product.js   # brand + catalog (local image paths)
  App.jsx           # UI + checkout flow
  base.css          # shared layout
  index.css         # brand skin
```

## Stack

- React + Vite
- Local assets only (images / fonts / logos)

## Run

```bash
npm install
npm run dev
```
