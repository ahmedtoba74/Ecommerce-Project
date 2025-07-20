# 🛒 MEAN-STACK E-Commerce App

A full-featured e-commerce system built using **Angular**, **Bootstrap**, and **TypeScript**, designed for both **users** and **admins**. It includes authentication, product management, cart functionality, and order tracking.

---

## 🌐 Live Demo

🚀 Coming soon...

---

## 📸 Screenshots

-   Home Page
-   Products Section
-   Admin Dashboard
-   Cart & Order Page  
    _(Add screenshots here if available)_

---

## 📁 Features

### 🛍️ User Features

-   🔎 Browse and search products.
-   🛒 Add to Cart & View Cart.
-   🧾 Place orders and track them.
-   🔐 Login / Signup (auth protected).
-   📦 View **Out of Stock** status clearly.
-   📄 View individual product details.

### 🧑‍💼 Admin Features

-   ➕ Add new products with image upload.
-   ✏️ Update or delete products.
-   📋 View all user orders.
-   📌 Change order status (e.g. pending, shipped).
-   🔐 Admin routes are protected.

### 🌐 UI & Navigation

-   📌 Sticky Navbar (Home, Products, About, Login/Signup).
-   👣 Footer displayed on all pages.
-   🖼️ Hero section with call-to-action button.
-   🧩 Responsive Cards showing product info.
-   💬 Toast notifications for actions (add to cart, login success/failure, etc.)

---

## 🛠️ Tech Stack

| Frontend       | Tools                     |
| -------------- | ------------------------- |
| Angular        | `v17+`                    |
| Bootstrap      | UI styling and components |
| TypeScript     | Strongly typed code       |
| RxJS           | Reactive programming      |
| Angular Router | Page navigation           |
| Font Awesome   | Icons                     |

---

## 🧠 Architecture

src/
├── app/
│ ├── components/ # Reusable components like Navbar, Footer, Card, Toast
│ ├── pages/ # Home, Products, Login, Signup, My Orders, Admin pages
│ ├── services/ # API, Auth, Cart, Toast
│ ├── guards/ # Route protection
│ ├── models/ # Interfaces and types
│ └── app-routing.module.ts
├── assets/
│ └── images/
└── environments/
└── environment.ts

yaml
Copy
Edit

---

## 🔗 API Integration

> **Note:** The backend is ready but not yet connected. Once backend APIs are deployed, update `environment.ts` with your API base URL and integrate the HTTP services.

---

## 📦 Installation & Run

```bash
# Clone the repo
git clone https://github.com/your-username/angular-ecommerce.git
cd angular-ecommerce

# Install dependencies
npm install

# Run the app
ng serve
Then go to: http://localhost:4200

🧾 Future Improvements
Connect with real backend (Node.js / Express / MongoDB).

Add JWT authentication with access/refresh tokens.

Add product filters (by price/category).

Payment gateway integration (e.g. Stripe).

Responsive mobile-first redesign.

🧑‍💻 Author
Ahmed Toba
📧 ahmed.toba.mahmoud@gmail.com
🌐 LinkedIn

📄 License
This project is licensed under the MIT License.
```
