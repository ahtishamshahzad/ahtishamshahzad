# Project Case Studies

Detailed case studies for production projects led or built by **Ahtisham Shahzad** — Senior React Native &amp; Full-Stack JavaScript Engineer.

All details below are drawn from real project records. Where a detail isn't available, it's marked **Not specified**.

---

## 1. Blaia

**Shop Local, Online — Marketplace for Neighbourhood Shops**

### Overview
An online marketplace built around a simple idea: help small, local shops sell online while keeping the personal, "shop around the corner" feel. Instead of nationwide shipping, customers reserve and pay for items online, then collect them in person from a nearby store.

### My Role
Full-Stack Lead — delivered the platform end to end: the customer-facing website, the shop-owner and admin dashboard, and the backend that ties it all together (payments, orders, notifications, and email).

### Tech Stack
TypeScript · Turborepo · NestJS 10 · Prisma 6 · PostgreSQL · Next.js 15 · React 19 · Redux Toolkit · HeroUI · Tailwind CSS v4 · Stripe Connect · Resend · Playwright

### Platforms
Web (customer storefront + seller/admin dashboard)

### Key Features
- Complete marketplace built end to end — customer site, seller dashboard, and backend
- Flexible product system: standard, sold-by-weight, and multi-option items, with validation rules that keep listings accurate before they go live
- Secure payments with automatic seller payouts, refunds, and a built-in dispute process
- Location-based discovery — customers see shops genuinely near them
- Discount codes, bulk catalogue import from a spreadsheet, and time-limited offers
- Automatic branded email notifications for orders, payouts, and account activity
- Multi-language support throughout, with SEO-friendly pages so shops get found
- Every release tested on the live site before going out (end-to-end checks with Playwright)

### Scale
- **19** feature modules · **35** data models · **25** validation rules · **3** locales

### Business Value
Gives small, local shops a trustworthy online sales channel without losing the in-person relationship — complete with secure payments, automatic payouts, refunds, and dispute handling, so both shoppers and shop owners can transact with confidence.

### Links
- Web: [blaia.shop](https://blaia.shop/)
- Web: [blaia.app](https://blaia.app/)

---

## 2. STEMQuiz

**Competitive STEM Quiz Platform**

### Overview
A cross-platform (iOS / Android / web) app for timed, competitive quizzing across Science, Technology, Engineering, and Math — roughly 33.5k lines of TypeScript across a React Native client and an Express backend, with server-authoritative monetization, anti-fraud billing, and a full admin CMS.

### My Role
Full-Stack Lead — client, backend, monetization, and admin panel.

### Tech Stack
React Native · Expo SDK 54 · Expo Router · React Query · Reanimated · Express 5 · Node/TypeScript · PostgreSQL · Drizzle ORM · RevenueCat · JWT · Tailwind CSS

### Platforms
iOS · Android · Web

### Key Features
- Server-authoritative 3-tier system (Guest / Free / Premium) enforced entirely server-side, each gated path returning a distinct 403 code (`GUEST_LIMIT`, `LOCKED_24H`, `LEVEL_LOCKED`…)
- Anti-fraud billing reconciliation: cross-checks the JWT tier against the DB on every request and silently self-heals stale client tokens, with log sentinels separating auto-healed cases from real billing desyncs
- Deep gamification — XP, coins, daily streaks with milestone rewards, weekly-XP leagues, coin-based lifelines (50:50, Hint, Pause, Double Attempt), 14 auto-awarded badges, exam mode, and a 3-tier explanation system
- Growth/conversion engineering — paywall A/B copy experiment, free-tier interstitial + rewarded ads, and a first-4-days retention banner loop
- Production ops — request correlation IDs, slow-request + p95 latency tracking with `[DEGRADED]` alerts, feature flags, and a 38-check regression gate before deploy
- Admin CMS — role-based permissions, content/event/leaderboard management, a badge studio, fraud monitoring, Excel bulk question import, bulk user actions, and email campaigns

### Scale
- **~33.5k** lines of TypeScript · **3** platforms · **14** auto-awarded badges

### Business Value
Monetization and entitlements are protected against client tampering, while deep gamification and conversion experiments drive engagement and upgrade rate — all observable and operable through a production-grade admin panel.

### Links
- iOS: [App Store](https://apps.apple.com/us/app/stemquiz/id6759861972)
- Android: [Google Play](https://play.google.com/store/apps/details?id=app.stemquizapp.com)

---

## 3. My Mind Bestie

**Cross-Platform Wellness SaaS**

### Overview
A unified wellness experience across Web, Mobile (iOS + Android), and Desktop (Electron). One user, one account, three surfaces — all sharing the same backend and design system.

### My Role
Full-Stack Lead — architecture, monorepo, serverless backend, and payments.

### Tech Stack
React Native · Next.js · NestJS · PostgreSQL · AWS Lambda · Stripe · Electron · TurboRepo

### Platforms
Web · iOS · Android · Desktop (4 platforms)

### Key Features
- Unified Web + Mobile + Desktop experience
- TurboRepo monorepo with shared packages (UI primitives, API client, types, validation schemas)
- Serverless NestJS backend on AWS Lambda with modular features for auth, payments, and content
- Stripe subscriptions + recurring billing end-to-end
- Audio/video streaming, push notifications, and offline-first content on mobile
- Admin dashboard for users, content, and subscriptions

### Scale
- **4** platforms · **3** subscription tiers

### Business Value
One codebase strategy lets a small team ship and maintain a consistent wellness product across four platforms, with subscription billing built in from day one.

### Links
- Not specified

---

## 4. Obenan

**AI-Powered Digital Marketing Platform**

### Overview
A multi-product, multilingual platform helping businesses manage their digital presence with AI-driven insights — Obenan Dashboard, Landing Platform, and OmniPulse, all sharing UI primitives via a TurboRepo monorepo.

### My Role
Frontend Lead — frontend architecture across the product suite.

### Tech Stack
Next.js · React · Redux · Strapi CMS · TurboRepo · Tailwind CSS · Framer Motion · i18n

### Platforms
Web

### Key Features
- Multi-product platform for business clients
- SEO-friendly, multilingual SSR/SSG experiences with i18n
- Strapi CMS powering dynamic content for the marketing surface
- Centralized dashboard surfacing digital-presence metrics and AI-driven insights
- Reusable UI library keeping every product on-brand

### Business Value
A shared design system and monorepo keep three products consistent and fast to evolve, while SEO-friendly multilingual delivery expands reach across markets.

### Links
- Web: [obenan.ai](https://www.obenan.ai/)

---

## 5. Pedlar

**Creator Commerce Storefronts**

### Overview
Lets creators connect with followers and sell curated collections of their favourite brands and products through a personal Pedlar storefront.

### My Role
Frontend Engineer

### Tech Stack
React · Next.js · Tailwind CSS · REST APIs

### Platforms
Web

### Key Features
- Per-creator storefront experience
- Curated brand &amp; product collections
- High-conversion product detail pages

### Business Value
Turns a creator's audience and taste into a monetizable storefront with conversion-focused product pages.

### Links
- Web: [pedlar.store](https://pedlar.store/)

---

## 6. SenSights

**Telehealth &amp; Senior Remote Monitoring**

### Overview
A cloud-based platform delivering remote monitoring, personal emergency response (PERS), and telehealth services for seniors and senior-care workers.

### My Role
Mobile Engineer

### Tech Stack
React Native · Redux · REST APIs · Push Notifications

### Platforms
iOS · Android

### Key Features
- Remote monitoring &amp; PERS for seniors
- Risk monitoring for senior-care staff
- iOS + Android shipped to stores

### Business Value
Helps seniors stay safe and independent while giving care staff timely risk visibility through a connected mobile experience.

### Links
- iOS: [App Store](https://apps.apple.com/us/app/sensights/id1522446657)
- Android: [Google Play](https://play.google.com/store/apps/details?id=com.sensights&hl=en&gl=US&pli=1)

---

## 7. uDress

**Fashion Marketplace**

### Overview
A cross-platform mobile marketplace for buying and selling fashion products, with advanced search, filtering, and real-time chat.

### My Role
Mobile Engineer

### Tech Stack
React Native · Redux · REST APIs · Reanimated

### Platforms
iOS · Android

### Key Features
- Advanced search + filtering
- Real-time chat between buyers and sellers
- Reanimated micro-interactions
- iOS + Android shipped to stores

### Business Value
Connects buyers and sellers in a fast, chat-enabled marketplace experience built for mobile.

### Links
- iOS: [App Store](https://apps.apple.com/us/app/udress/id1485435709)
- Android: [Google Play](https://play.google.com/store/apps/details?id=com.app.udress)

---

## 8. Etihad Town

**Real Estate &amp; Community Management**

### Overview
A full-stack mobile app for property and community management — listings, announcements, and real-time updates for residents.

### My Role
Mobile Lead

### Tech Stack
React Native · Node.js · REST APIs · Push Notifications

### Platforms
iOS · Android

### Key Features
- Full-stack mobile app for property + community
- CMS for listings, announcements, and user data
- Push notifications + real-time updates
- Coordinated delivery across multiple modules

### Business Value
Gives a residential community a single mobile hub for listings, announcements, and resident communication.

### Links
- iOS: [App Store (developer)](https://apps.apple.com/us/developer/etihad-town-pvt-limited/id1690750920)
- Android: [Google Play](https://play.google.com/store/apps/details?id=com.etihadtown.app)

---

## 9. CompanyNeeds

**Office Supplies E-commerce**

### Overview
An e-commerce platform for office supplies — web storefront and Android app with a full product catalog and ordering flow.

### My Role
Full-Stack Engineer

### Tech Stack
Next.js · React Native · REST APIs · Tailwind CSS

### Platforms
Web · Android

### Key Features
- Web + Android app for office supplies
- Full catalog + filtering
- Order workflow with cart and checkout

### Business Value
Provides a B2B office-supplies catalogue and ordering flow across web and mobile.

### Links
- Web: [company-needs.vercel.app](https://company-needs-front-end.vercel.app/)
- Android: [Google Play](https://play.google.com/store/apps/details?id=com.companyneeds.app)

---

## 10. Live Urdu News

**News Aggregator**

### Overview
Aggregates news from leading Pakistani and international newspapers into a clean, easy-to-read mobile experience.

### My Role
Mobile Engineer

### Tech Stack
React Native · REST APIs · Redux

### Platforms
iOS

### Key Features
- Aggregates multiple news sources
- Clean reading experience
- iOS shipped to App Store

### Business Value
Brings multiple news sources into one clean, fast reading experience for mobile readers.

### Links
- iOS: [App Store](https://apps.apple.com/us/app/live-urdu-news/id1565184003)

---

> Source of truth: portfolio project data. Store links and live URLs are taken directly from the portfolio and are safe to share publicly. No private client source code or credentials are included.
