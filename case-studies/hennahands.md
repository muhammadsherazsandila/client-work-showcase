# ✋ HennaHands.K — Premium Mehndi Artist

> **Client:** HennaHands.K  
> **Location:** Islamabad & Rawalpindi, Pakistan  
> **Status:** 🔧 In Development  
> **Role:** Full Stack Developer (via [Sandila Digix](https://sandiladigix.com))  

---

## 📋 Project Overview

HennaHands.K is a premium mehndi (henna) artist serving clients in the Islamabad and Rawalpindi area. They specialize in bridal mehndi, party henna designs, and home-service sessions. They needed a professional online presence to showcase their artistry, attract clients through search and social media, and streamline the booking process.

---

## 🎯 The Challenge

| Challenge | Details |
|-----------|--------|
| **Portfolio Showcase** | Henna is a visual art — the website must beautifully display intricate design work |
| **Booking System** | Need to handle bridal, party, and home-service appointments efficiently |
| **Local SEO** | Must rank for "mehndi artist in Islamabad" and related local search queries |
| **Instagram Integration** | Most clients discover mehndi artists via Instagram — website must complement that |
| **Mobile-First** | Target audience primarily browses on mobile devices |

---

## 💡 My Solution

### Architecture

```
┌───────────────────────────────────────────────────┐
│                    FRONTEND                        │
│       Next.js + TypeScript + Tailwind CSS          │
│                                                    │
│  ┌──────────┐  ┌───────────┐  ┌────────────────┐  │
│  │  Design  │  │ Service & │  │   Booking &    │  │
│  │ Gallery  │  │  Pricing  │  │    Contact     │  │
│  └──────────┘  └───────────┘  └────────────────┘  │
│                                                    │
│  ┌──────────┐  ┌───────────┐  ┌────────────────┐  │
│  │  Client  │  │   About   │  │   Instagram    │  │
│  │Testimony │  │  & Story  │  │     Feed       │  │
│  └──────────┘  └───────────┘  └────────────────┘  │
│                                                    │
│          Mobile-First Responsive Design            │
│         Deployed on Vercel (Custom Domain)         │
└───────────────────────────────────────────────────┘
```

### Key Features Being Built

1. **Design Gallery**
   - High-resolution photo gallery of henna designs
   - Category filtering: Bridal, Party, Arabic, Indo-Arabic, Finger/Hand, Full Arm
   - Image optimization for fast loading with large photo sets
   - Lightbox viewing for detail inspection

2. **Service Packages & Pricing**
   - Clear pricing tiers: Bridal packages, Party rates, Home service fees
   - Package comparison for easy decision-making
   - Seasonal/event-specific packages (Eid, Wedding Season)

3. **Booking & Inquiry System**
   - Appointment request form with date/time selection
   - Event type selection (bridal, party, personal)
   - Location input for home service visits
   - WhatsApp quick-booking integration

4. **Social Proof**
   - Client testimonials section
   - Before/after showcase
   - Real wedding/event photo features

5. **Local SEO Optimization**
   - Structured data markup for local business
   - Optimized for "mehndi artist Islamabad" and related keywords
   - Google Maps integration
   - Mobile-first design for Instagram-to-website traffic

---

## 🛠️ Tech Stack

| Layer | Technology | Why |
|-------|-----------|-----|
| **Framework** | Next.js, TypeScript | SSR for SEO, image optimization for gallery |
| **Styling** | Tailwind CSS | Responsive design, elegant typography |
| **Deployment** | Vercel | Fast, reliable, custom domain support |

---

## 🔑 Key Technical Decisions

| Decision | Rationale |
|----------|----------|
| **Next.js Image Optimization** | Gallery-heavy site needs automatic image resizing and lazy loading |
| **Mobile-first design** | 80%+ traffic expected from Instagram links on mobile devices |
| **Local SEO focus** | Service-area business depends on local search visibility |
| **WhatsApp booking** | Target demographic prefers WhatsApp for communication over web forms |

---

*Being developed by [Muhammad Sheraz](https://github.com/muhammadsherazsandila) via [Sandila Digix](https://sandiladigix.com)*
