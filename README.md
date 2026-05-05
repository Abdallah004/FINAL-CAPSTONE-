# WarehouseMS — Web-Based Warehouse & Sales Management System

A full-stack system for supermarket suppliers to manage inventory, process sales, and generate PDF business intelligence reports. Live on Vercel, backed by a Neon Postgres database.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, custom CSS, vanilla JS (SPA-style controller) |
| Backend | Node.js + Express.js |
| Database | PostgreSQL (Neon in production, local Postgres in dev) |
| Auth | JWT access + refresh tokens, optional Google sign-in |
| PDFs | PDFKit (invoices + sales reports) |
| Jobs | node-cron (daily expiry/low-stock scanner) |
| Logging | Winston |
| Hosting | Vercel (serverless) + Neon (Postgres) |
