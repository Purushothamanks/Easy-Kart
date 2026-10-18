# Easy Kart — Multi-Store Product Aggregator Pro (EK)

A high-performance, responsive multi-store product aggregator and e-commerce price comparison web application. Built with modern web standards, adhering to the **60-30-10** color rule, **WCAG 2.1 AAA** contrast accessibility, and mobile-first responsiveness (320px to 4K displays).

---

## 🌐 Live Application
- **Live URL**: [https://easy-kart-d6d3a.web.app](https://easy-kart-d6d3a.web.app)
- **Alternate URL**: [https://easy-kart-d6d3a.firebaseapp.com](https://easy-kart-d6d3a.firebaseapp.com)
- **Firebase Project ID**: `easy-kart-d6d3a`

---

## 🛍️ Features & Architectural Highlights
- 🔍 **Live Debounced Global Search**: Instantly matches keywords across product titles, categories, and marketplace retailers.
- 🏷️ **Categorical Deal Navigation**: Fast category switching across Electronics, Fashion, Books, Home & Kitchen, Grocery, and Gaming.
- ⚖️ **Interactive Comparison Matrix**: Compare up to 4 items simultaneously across verified retailers (Amazon, Flipkart, Croma, Nike, Apple), prices, and ratings.
- 📈 **Price Trend Visualizer**: Embedded dynamic HTML5 canvas charting historical lowest, highest, and latest prices.
- 🤍 **Wishlist Drawer**: Save favorite items across sessions with one-click "Move All to Cart".
- 🛒 **Shopping Cart & Checkout Simulation**: Real-time subtotal estimation, quantity adjustments, and simulated order generation.
- 📦 **Order History Log**: Persistent records of simulated past purchases.
- 🌗 **Dark / Light Theme Modes**: Synchronous token switching with system and user persistence.
- 📱 **Mobile-First Ergonomics**: Fixed frosted-glass bottom navigation bar, off-canvas drawers, and >=48px touch targets.
- 💾 **State Import & Export**: One-click JSON backup and restoration.

---

## 🚀 Running Locally

### Method 1: Python Built-in HTTP Server (Instant)
```bash
cd /home/purushothaman/Videos/Projects/EK/Project_file
python3 -m http.server 3000
```
Open [http://localhost:3000/public/](http://localhost:3000/public/) in any modern browser.

### Method 2: Node.js Serve
```bash
cd /home/purushothaman/Videos/Projects/EK/Project_file
npx serve public
```

---

## 🛠️ Deployment
To deploy updates to Firebase Hosting:
```bash
cd /home/purushothaman/Videos/Projects/EK/Project_file
firebase deploy --only hosting
```
