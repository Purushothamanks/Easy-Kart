# Easy Kart — Aggregator Pro (EK) - Run Instructions

## 🌐 Active Live URL (Firebase Hosting)
- **Primary Live URL**: https://easy-kart-d6d3a.web.app
- **Alternate Live URL**: https://easy-kart-d6d3a.firebaseapp.com
- **Firebase Project ID**: `easy-kart-d6d3a`

---

## Project Overview
**Easy Kart (EK)** is a feature-rich, multi-store product aggregator e-commerce web platform. It includes live search, interactive filters, product comparison matrix, cart and wishlist management, checkout flow simulation, dark/light mode toggle, and keyboard shortcuts.

---

## Local Run Instructions

### Method 1: Python Built-in Server (Recommended & Instant)
1. Open your terminal and navigate to the project directory:
   ```bash
   cd /home/purushothaman/Videos/Projects/EK/Project_file
   ```
2. Start the local server:
   ```bash
   python3 -m http.server 3000
   ```
3. Open your browser and navigate to:
   ```
   http://localhost:3000/public/
   ```
   *(or `http://localhost:3000/`)*

---

### Method 2: Node.js `serve` / `npx`
1. Navigate to the project directory:
   ```bash
   cd /home/purushothaman/Videos/Projects/EK/Project_file
   ```
2. Run using `npx`:
   ```bash
   npx serve public
   ```
3. Open the URL shown in the terminal (default: `http://localhost:3000`).

---

### Method 3: Direct Browser Open
Open `Project_file/public/index.html` (or `Project_file/index.html`) directly in Google Chrome, Brave, Firefox, or Edge.

---

### Method 4: Firebase Hosting Deployment
1. Install Firebase CLI:
   ```bash
   npm install -g firebase-tools
   ```
2. Deploy to Firebase Hosting:
   ```bash
   firebase login
   firebase deploy
   ```
