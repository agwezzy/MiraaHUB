# 🌿 MiraaMtaani — Fresh Miraa Delivery App

> **Order premium miraa from the comfort of your home. Fast, discreet delivery straight to your door.**

---

## 📸 Overview

MiraaMtaani is a fully client-side web application that lets users browse, order, and track miraa deliveries in Nairobi. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no backend required.

The app features a vibrant, Kenya-inspired design with smooth animations, a live order tracker, and a complete ordering flow from product selection to doorstep delivery.

---

## ✨ Features

- **📍 Location Input** — Enter your delivery area (e.g. Eastleigh, CBD, Westlands)
- **🛍️ Product Catalogue** — Browse miraa by category with filtering
- **🛒 Shopping Cart** — Add items, adjust quantities, view running total
- **📋 Order Form** — Enter name, phone number, delivery address, and preferred delivery time
- **✅ Order Confirmation** — Unique order ID generated per order
- **🏍️ Live Delivery Tracker** — Animated status updates: Confirmed → Packing → On the Way → Delivered
- **🔔 Toast Notifications** — Instant feedback on every action
- **📱 Responsive Design** — Works on mobile and desktop

---

## 🌿 Product Catalogue

| Product | Origin | Price | Category |
|---|---|---|---|
| Meru Green (Muguka) | Meru County | KSh 150 / bundle | Standard |
| Nyambene Premium | Nyambene Hills | KSh 300 / bundle | Premium |
| Tigania Select | Tigania West | KSh 250 / bundle | Premium |
| Standard Bundle x3 | Meru County | KSh 400 / 3 bundles | Bundles |
| Premium Bundle x2 | Nyambene Hills | KSh 550 / 2 bundles | Bundles |
| Mixed Bag (3 types) | Various | KSh 650 / 3 bundles | Bundles |
| Thermos Flask | — | KSh 800 / piece | Accessories |
| Karai (Chewing Plate) | — | KSh 200 / piece | Accessories |

---

## 🚀 Getting Started

No installation needed. This is a single-file HTML app.

### Run Locally

```bash
# Clone the repository
git clone https://github.com/yourusername/miraa-mtaani.git

# Open in browser
cd miraa-mtaani
open miraa-delivery.html
```

Or simply double-click `miraa-delivery.html` to open it in your browser.

### Deploy to GitHub Pages

1. Push the file to your repository
2. Go to **Settings → Pages**
3. Set source to `main` branch
4. Your app will be live at `https://yourusername.github.io/miraa-mtaani/`

---

## 🗂️ Project Structure

```
miraa-mtaani/
├── miraa-delivery.html   # Complete app (HTML + CSS + JS in one file)
└── README.md             # This file
```

---

## 🔄 How the Ordering Flow Works

```
1. Enter delivery location
        ↓
2. Browse & filter products by category
        ↓
3. Add items to cart (adjust quantities anytime)
        ↓
4. Click "View Order Details" → fill in name, phone, address & time
        ↓
5. Click "Place Order Now"
        ↓
6. Confirmation screen with order ID + live tracker
        ↓
   [Confirmed] → [Packing] → [On the Way] → [Delivered]
```

---

## 🎨 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, flexbox, grid, animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Playfair Display + Jost |
| Hosting | Any static host (GitHub Pages, Netlify, Vercel) |

No npm. No build step. No dependencies. Just open and use.

---

## 🗺️ Roadmap / Potential Enhancements

- [ ] **M-Pesa Integration** — STK push payment via Safaricom Daraja API
- [ ] **SMS Confirmation** — Order alerts via Africa's Talking API
- [ ] **Rider Tracking Map** — Live GPS map view using Leaflet.js
- [ ] **Admin Dashboard** — Manage orders and update delivery status
- [ ] **Backend API** — Node.js/Express + MongoDB for persistent orders
- [ ] **User Accounts** — Login, order history, saved addresses
- [ ] **PWA Support** — Install as mobile app, offline support

---

## 🕐 Operating Hours

Open daily **6:00 AM – 10:00 PM**
Delivery time: **30–60 minutes** within Nairobi

---

## 📍 Coverage Area

Currently serving **Nairobi, Kenya**.
Primary delivery zones: Eastleigh, CBD, Westlands, South B, Embakasi, Kasarani.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

```bash
# Fork the repo, then:
git checkout -b feature/your-feature-name
git commit -m "Add your feature"
git push origin feature/your-feature-name
# Open a Pull Request
```

---

## 📄 License

[MIT](LICENSE) — free to use, modify, and distribute.

---

<div align="center">
  <strong>🌿 MiraaMtaani</strong> · Fresh from Meru & Nyambene Hills · Nairobi, Kenya<br>
  <em>Built with ❤️ for the community</em>
</div>
