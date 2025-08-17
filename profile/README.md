# Silah — Connecting Businesses

> **Silah** (Arabic: صِلَة)  
> *[noun]* Connection, bond, link; often used to describe the ties between people, family, or communities.

**Silah** is an AI-augmented full-stack B2B web platform that connects suppliers and buyers.
Suppliers can showcase their products and services, while buyers can place orders or submit requests for proposals (RFPs).

---

## Tech Stack

- **Frontend:** React, Axios, Socket.IO, Jest 
- **Backend:** NestJS, Prisma, PostgreSQL, Jest
- **AI Integration:** FastAPI, LaBSE (semantic search), Facebook Prophet (demand forecasting)
- **Deployment & Storage:** DigitalOcean, Cloudflare R2 (for image storage)
- **Authentication:** Wathq API (Commercial Registration verification)
- **Multilingual:** Google Translate API (auto-translate product info)
- **Payment Gateway:** Tap Payments

---

## Features

### For All Users

- Secure account creation with Commercial Registration (CR) verification via Wathq API
- Role-based access (Buyer/Supplier switchable anytime)
- Real-time notifications
- Internal chat with image sharing
- Clean, RTL/LTR multilingual UI with auto-translations

### For Buyers

- Smart product & supplier search with semantic AI (LaBSE)
- Place orders based on supplier rules (MOQ, case quantity)
- Participate in group orders to benefit from bulk discounts and easier MOQ fulfillment
- Submit and manage Request for Proposals (RFPs)
- Track orders, review suppliers, receive invoices

### For Suppliers

- Create and manage product & service listings
- Storefront customization (banner, bio)
- Receive and manage real-time orders, bids, and invoices
- Enable group purchases with countdown and special pricing
- Access AI-powered sales forecasts and stock recommendations
- Subscribe to Premium Plan for advanced features (with free trial)


---

> Built with care as part of a graduation project by an amazing team.
