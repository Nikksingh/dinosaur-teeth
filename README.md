# Dinosaur Teeth — Landing Page

High-converting single-page sales landing page for **Dinosaur Teeth Herbal Toothpowder & Mouthwash**.

- **Live site:** https://nikksingh.github.io/dinosaur-teeth/
- **Primary conversion:** "BUY NOW" → Razorpay payment page (`https://rzp.io/rzp/pay-for-dino`)

## Overview

A mobile-first, single-file (`index.html`) landing page for the Dinosaur Teeth D2C oral-care product.
All product information, pricing, imagery and testimonials are sourced from the official website
[dinosaurteeth.in](https://dinosaurteeth.in/). No ingredients, certifications, claims or testimonials
were invented.

## Sections

Hero → Trust strip → Problem + Difference → Benefits → How It Works → Why Dino (brand story)
→ Featured (Hindustan Times) → Reviews → Offer → FAQ → Final CTA → Sticky mobile CTA.

## Tech

- Single static `index.html` (inline CSS + minimal vanilla JS)
- SEO meta, Open Graph / Twitter cards, JSON-LD Product structured data
- Lazy-loaded images, `IntersectionObserver` reveal animations, accessible FAQ (`<details>`)
- Buy Now CTAs tracked via `window.dataLayer.push({ event: 'cta_click', ... })`

## Deployment

Hosted with **GitHub Pages** from the `main` branch (root).

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```
