EDDICTED — Gear 5 Streetwear Website

A high-energy, defiant e-commerce web application inspired by the chaotic freedom of Sun God Nika Gear 5 and modern Shibuya cyberpunk anime streetwear.

Built strictly according to the Gear 5 Streetwear Design System (DESIGN.md).

⚡ Architecture & Pages

index.html — Flagship Homepage

High-impact kinetic typography hero (AWAKEN YOUR FREEDOM)
Live drop countdown clock (18:42:19)
Gear 5 Awakened Edition spotlight showcase with direct size selection & quick-add
Curated Capsule grid featuring Zoro, Sanji, Trafalgar Law, Joy Boy, and Onigashima pieces
"Anatomy of the Awakening" engineering & craft technical bento grid
Shibuya Lookbook 2026 teaser
Verified customer reviews & rating badge (4.8/5.0)
"Awakened Syndicate" VIP access newsletter with instant 15% coupon

product.html — Complete Product Detail Page (PDP)

Supports dynamic URL query parameters (e.g. product.html?id=gear5, product.html?id=zoro, product.html?id=sanji)
High-resolution multi-view gallery with active thumbnail selector & hover zoom
Swatch color selection with active status rings
Interactive Size Matrix (S - XXL) with live stock warnings ("Only 14 items left in this size!")
Interactive Size Guide modal with measurement matrix
Quantity counter with stock limits
Animated "Add to Cart" interaction + slide-out cart drawer trigger
Instant "Buy Now with Express Checkout" routing
Interactive "Write a Review" modal with star rating picker that dynamically appends verified reviews

catalog.html — Full Drops & Catalog

Multi-faceted filter sidebar: Anime Arc / Hero, Category, Available Sizes, In-Stock Only
Real-time sort dropdown (Featured, Price: Low to High, Price: High to Low, Rating)
Product cards equipped with Quick View modals, Wishlist hearts, and Quick Add buttons

lookbook.html — Shibuya Editorial 2026

Tokyo street photography spreads
Interactive hotspot pins on models with instant hover previews and quick-shop actions

checkout.html — Express Checkout Flow

One-click express payment buttons (Apple Pay, Google Pay, PayPal)
Multi-step address and payment information forms
Live calculation with promotional discounts (GEAR5, FREESHIP, DRUMS20)
Order completion with generated Order Number (ED-2026-NIKA-XXXX) and printable confirmation receipt
🎨 Design System Compliance (DESIGN.md)
Color Palette:
Background & Surface: #121414 (Deep Charcoal Void)
Accents: #ddb8ff / #7c03d3 (Electric Purple & Secondary Container)
Text: #e2e2e2 (High Contrast White) and #c9c5cc (Subdued Muted)
Ambient Glows: rgba(147, 51, 234, 0.45) kinetic purple aura
Typography:
Headlines: Anton (uppercase, tight tracking)
Body & UI: Space Grotesk
Shapes & Depth:
Industrial 0px hard corners, tech clipped diagonal edges, edge-to-edge product framing
🚀 How to Run / Preview
Option 1: Open in Any Web Browser (No installation needed)

Double-click index.html in Windows Explorer or open it directly in Google Chrome or Microsoft Edge.

Option 2: Run Local Lightweight Server

Double-click start-server.bat or run in PowerShell:

powershell
powershell -ExecutionPolicy Bypass -File .\start-server.ps1

Then visit: http://localhost:8080
