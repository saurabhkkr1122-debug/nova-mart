# NOVAMART — Premium Online Shopping Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**NOVAMART** is a lightweight, responsive, single-page application (SPA) e-commerce web platform built using pure Vanilla JavaScript, CSS, and HTML5. It offers a smooth shopping experience complete with product browsing, real-time filtering, wishlist management, a cart system, dynamic coupon support, and checkout validation.

---

## 🌟 Key Features

* **⚡ Single Page Architecture (SPA):** Fast hash-based routing (`#/`, `#/shop`, `#/cart`, `#/checkout`, etc.) with zero page reloads.
* **📱 Fully Responsive UI:** Tailored layout for Desktop, Tablet, and Mobile devices with mobile navigation menus.
* **🛒 Dynamic Cart & Wishlist System:** Add/remove items, update quantities, persist items using browser storage, and manage wishlists in real-time.
* **🔍 Advanced Filtering & Search:** Search products by keyword, filter by categories, rating, maximum price range, or toggle on-sale items.
* **🏷️ Coupon Code Engine:** Built-in discount engine supporting promo codes (e.g., `NOVA20` for 20% off).
* **🔒 Form Validation Checkout:** Interactive checkout page with dynamic payment method options (Card, UPI, Cash on Delivery) and input validation.
* **🌙 Interactive UX Elements:** Custom toast notifications, product quick view modals, interactive rating displays, scroll animations, and back-to-top buttons.

---

## 📁 Project Structure

```text
├── index.html       # Single-file bundled application (HTML, CSS, JS)
└── README.md        # Project documentation
```

---

## 🚀 Getting Started

No build tools, bundlers, or node modules are required to run this project.

### Quick Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/novamart.git
   ```

2. **Navigate to the directory:**
   ```bash
   cd novamart
   ```

3. **Open the application:**
   - Double-click `index.html` to open it directly in any modern web browser.
   - Alternatively, serve it using VS Code's **Live Server** extension or any standard static file server:
     ```bash
     npx serve .
     ```

---

## 🛠️ Built With

* **HTML5:** Semantic markup structure.
* **CSS3:** Custom properties (CSS variables), CSS Grid, Flexbox, keyframe animations, and glassmorphism styling.
* **JavaScript (ES6+):** DOM manipulation, event listeners, Hash routing, custom state handling.
* **Google Fonts:** Inter & Sora typography.

---

## 📦 Features & Page Overview

| Route | View | Description |
| :--- | :--- | :--- |
| `#/` | **Home** | Hero section, featured products, category highlights, trust indicators, and newsletter signup. |
| `#/shop` | **Shop** | Product listing with multi-level filters (price slider, category checkboxes, rating, deals tag). |
| `#/product` | **Detail** | Comprehensive product page with image previews, stock status, ratings, and related items. |
| `#/cart` | **Cart** | Cart item summary, line item calculations, shipping calculators, and coupon code handler. |
| `#/wishlist` | **Wishlist** | Dedicated view displaying saved items with easy one-click transfer to cart. |
| `#/checkout` | **Checkout** | Full billing form, payment option switches, real-time input error handling, and order summary. |
| `#/about` | **About** | Brand story, company statistics, and platform mission. |

---

## 🤝 Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.