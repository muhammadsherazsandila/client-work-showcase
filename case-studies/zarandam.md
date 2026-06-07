# 🛍️ Zarandam — Premium Fashion E-Commerce

> **Client:** Zarandam Fashion Brand  
> **Location:** Lahore, Pakistan  
> **Live URL:** [zarandam.com](https://zarandam.com)  
> **Status:** ✅ Live & Active  
> **Role:** Full Stack Developer (via [Sandila Digix](https://sandiladigix.com))  

---

## 📋 Project Overview

Zarandam is a premium Pakistani women's fashion brand based in Lahore, specializing in embroidered collections, western wear, and formal dresses. They needed a modern, high-performance e-commerce platform to serve customers across Pakistan.

---

## 🎯 The Challenge

| Challenge | Details |
|-----------|--------|
| **No Online Presence** | The brand had no digital storefront and relied entirely on physical retail and social media |
| **Product Showcase** | Needed to elegantly display embroidered suits with detailed imagery and size options |
| **Payment Flexibility** | Pakistani market requires Cash on Delivery (COD) and mobile wallet support |
| **Mobile-First** | 70%+ of target audience shops from mobile devices |
| **Shipping Logic** | Needed tiered shipping with free delivery threshold |

---

## 💡 My Solution

### Architecture

```
┌──────────────────────────────────────────────────┐
│                   FRONTEND                        │
│         Next.js + TypeScript + Tailwind CSS       │
│                                                   │
│  ┌─────────┐  ┌──────────┐  ┌─────────────────┐  │
│  │ Product  │  │  Cart &  │  │  User Account   │  │
│  │ Catalog  │  │ Checkout │  │  & Orders       │  │
│  └────┬─────┘  └────┬─────┘  └────────┬────────┘  │
│       │              │                 │           │
├───────┼──────────────┼─────────────────┼───────────┤
│       │         REST API               │           │
├───────┼──────────────┼─────────────────┼───────────┤
│                   BACKEND                         │
│           Node.js + Express.js                    │
│                                                   │
│  ┌─────────┐  ┌──────────┐  ┌─────────────────┐  │
│  │ Product  │  │  Order   │  │   Shipping &    │  │
│  │ Service  │  │ Service  │  │   Payment       │  │
│  └────┬─────┘  └────┬─────┘  └────────┬────────┘  │
│       │              │                 │           │
│       └──────────────┼─────────────────┘           │
│                      │                             │
│              ┌───────┴────────┐                    │
│              │    MongoDB     │                    │
│              └────────────────┘                    │
│                                                   │
│  ┌─────────────────────────────────────────────┐  │
│  │            Cloudinary (Image CDN)            │  │
│  └─────────────────────────────────────────────┘  │
└──────────────────────────────────────────────────┘
```

### Key Features Built

1. **Product Catalog System**
   - Multi-category browsing (Embroidered 3-Piece, Western Wear, Formal Dresses)
   - High-resolution image galleries with zoom functionality
   - Size and color variant selection
   - Product filtering and search

2. **Shopping Cart & Checkout**
   - Persistent cart with real-time price calculation
   - 5-step checkout flow: Browse → Select → Cart → Checkout → Delivery
   - Cash on Delivery (COD) integration
   - Mobile wallet payment support
   - Free shipping on orders over PKR 6,000

3. **Order Management**
   - Order tracking and status updates
   - Returns and exchange workflow (7-day policy)
   - Order history for registered customers

4. **Customer Experience**
   - WhatsApp integration for real-time customer support
   - Responsive design optimized for mobile-first browsing
   - Fast page loads with Next.js SSR and image optimization
   - SEO-optimized product pages

---

## 🛠️ Tech Stack

| Layer | Technology | Why |
|-------|-----------|-----|
| **Frontend** | Next.js, TypeScript | SSR for SEO, type safety, fast page loads |
| **Styling** | Tailwind CSS | Rapid UI development, consistent design system |
| **Backend** | Node.js, Express.js | REST API for product, cart, and order management |
| **Database** | MongoDB (Mongoose) | Flexible schema for product variants and orders |
| **Image CDN** | Cloudinary | Optimized image delivery, transformations |
| **Deployment** | Vercel | Auto-deployment, edge caching, custom domain |

---

## 📊 Results & Impact

- ✅ **Launched successfully** with full e-commerce functionality
- ✅ **Nationwide coverage** with delivery across all of Pakistan
- ✅ **Mobile-optimized** — responsive design for 70%+ mobile traffic
- ✅ **SEO-ready** — product pages indexed and ranking in search results

---

## 🔑 Key Technical Decisions

| Decision | Rationale |
|----------|----------|
| **Next.js over plain React** | Server-side rendering critical for e-commerce SEO and faster initial page loads |
| **MongoDB over PostgreSQL** | Product catalogs benefit from flexible document schema (variants, attributes) |
| **Cloudinary for images** | Automatic image optimization and responsive sizing reduces bandwidth by ~60% |
| **COD-first payment** | Pakistan's e-commerce market is 65%+ COD — supporting it was essential |

---

*Developed by [Muhammad Sheraz](https://github.com/muhammadsherazsandila) via [Sandila Digix](https://sandiladigix.com)*
