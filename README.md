Here’s a clean and professional **README.md** for your project 👇

---

# ⌚ TimeCraft – Premium Watches Website

TimeCraft is a modern, responsive eCommerce-style website for showcasing and selling premium watches. It features a clean UI, interactive shopping cart, product filtering, and multiple pages — all built using **HTML, CSS, Bootstrap, and JavaScript**.

---

## 🚀 Features

* 🏠 **Multi-page Layout (SPA style)**

  * Home
  * Shop
  * About
  * Contact
  * Cart

* 🛍️ **Product Listing**

  * Dynamic watch rendering using JavaScript
  * Filter by:

    * Men's Watches
    * Women's Watches

* 🛒 **Shopping Cart**

  * Add to cart
  * Remove items
  * Update quantity
  * Auto price calculation (Subtotal, Tax, Shipping, Total)

* 🎨 **Modern UI/UX**

  * Bootstrap 5 design
  * Animations & hover effects
  * Responsive layout for all devices

* 🔔 **Notifications**

  * Add-to-cart alerts
  * Contact form success message

* 📩 **Contact Form**

  * Simple frontend validation
  * User-friendly design

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **Bootstrap 5**
* **JavaScript (Vanilla)**
* **Font Awesome Icons**
* **Google Fonts**

---

## 📁 Project Structure

```
TimeCraft/
│── index.html   # Main project file (all-in-one SPA)
│── README.md    # Project documentation
```

---

## ⚙️ How It Works

### 1. Navigation

* Uses JavaScript to switch between pages without reloading.
* Each section is wrapped in a `.page` class.

### 2. Products

* Watches are stored in a JavaScript array:

```js
const watches = [ ... ];
```

* Dynamically rendered using `displayWatches()`.

### 3. Cart System

* Cart stored in:

```js
let cart = [];
```

* Functions:

  * `addToCart()`
  * `removeFromCart()`
  * `updateCartQuantity()`
  * `updateCart()`

### 4. Filtering

* Buttons filter watches by gender using:

```js
data-filter="men" / "women"
```

---

## ▶️ How to Run

1. Download or clone the project
2. Open `index.html` in your browser

No server or installation required ✅

---

## 📸 Screens Included

* Hero Section
* Product Cards
* Cart Page
* About & Contact Pages

---

## 🔮 Future Improvements

* 🔐 User authentication (Login/Signup)
* 💳 Payment integration (Stripe / PayPal)
* 🗄️ Backend (Node.js / Firebase)
* ❤️ Wishlist feature
* 🔍 Search functionality

---
## Live Website

https://hooriasadiq.github.io/watch_website/


## 👨‍💻 Author

Developed by **Hooria Sadiq**

---

## 📄 License

This project is open-source and free to use.

---

If you want, I can also:

* convert this into **GitHub README (with badges & images)**
* or **add screenshots + live demo section**
* or **separate files (HTML/CSS/JS)** for cleaner structure
