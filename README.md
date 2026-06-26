# MOTH-APP

**The Subscription Engine for the MOTH Empire**

MOTH-APP is the central platform powering all subscriptions, memberships, and recurring access for the MOTH streetwear brand and its growing empire.

This is not just billing software. This is the system that turns one-time buyers into **owners** — giving the right people exclusive access, status, and a direct line to the Empire.

## Vision

MOTH was born from the silhouette of a neck tattoo — raw, personal, and transformed into a symbol of rebirth and power.

MOTH-APP exists to protect and scale that energy. It manages:

- Recurring revenue through tiered memberships
- Exclusive product access and early drops for members
- Member lifecycle (onboarding → engagement → retention)
- Admin tools for ELEVEN to run the business cleanly and vertically

The goal is simple: build a real, ownable membership platform that feels as premium and rebellious as the clothes.

## Core Features (Planned)

- **Membership Tiers** — Multiple levels with different access, pricing, and perks
- **Stripe Integration** — Subscriptions, one-time payments, customer portal, and webhook handling
- **Member Dashboard** — View orders, exclusive drops, membership status, and benefits
- **Admin Dashboard** — Full control over users, subscriptions, products, and analytics
- **Drop & Access Control** — Gate products, digital content, or experiences behind membership
- **Notifications & Lifecycle Emails** — Smart communication when someone joins, upgrades, or their payment fails
- **Analytics** — Revenue, churn, cohort performance, and Empire health metrics

## Tech Stack (Recommended)

| Layer          | Technology                          | Why |
|----------------|-------------------------------------|-----|
| Frontend       | Next.js 15 (App Router) + TypeScript + Tailwind + shadcn/ui | Fast, beautiful dashboards + great DX |
| Backend        | Next.js Server Actions + API Routes | One codebase, no separate backend needed yet |
| Database       | Supabase (Postgres + Auth)          | Fast auth, real-time, easy to scale |
| Payments       | Stripe (Subscriptions + Webhooks)   | Industry standard, powerful customer portal |
| Deployment     | Vercel                              | Zero-config, excellent for Next.js |
| Styling        | Tailwind + custom design system     | Matches the raw, premium MOTH aesthetic |

This stack lets one person (you) move extremely fast while still building something that can scale into a real business system.

## Getting Started (Local Development)

```bash
git clone https://github.com/hellodiormurakami-ctrl/MOTH-APP.git
cd MOTH-APP
