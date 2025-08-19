<div align="center">

  # **Full-Stack E-Commerce Platform (MEAN Stack)**

  **A complete, feature-rich e-commerce application built with Angular (Frontend) and a Node.js/Express RESTful API (Backend), featuring distinct portals for users and administrators.**

  <img src="https://i.imgur.com/example.png" alt="E-Commerce Application Interface"/>

  [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
  [![Angular](https://img.shields.io/badge/Angular-v17-DD0031?logo=angular&logoColor=white)](https://angular.io/)
  [![Node.js](https://img.shields.io/badge/Node.js-v18-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
  [![Express.js](https://img.shields.io/badge/Express.js-4.x-000000?logo=express&logoColor=white)](https://expressjs.com/)
  [![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb&logoColor=white)](https://www.mongodb.com/)

  [ **View Live Demo (Coming Soon)** ]("#") · [ **Report Bug** ](https://github.com/ahmedtoba74/Ecommerce-Project/issues) · [ **Request Feature** ](https://github.com/ahmedtoba74/Ecommerce-Project/issues)

</div>

---

## 📖 Table of Contents

- [About The Project](#-about-the-project)
- [Key Features](#-key-features)
- [Tech Stack & Tools](#️-tech-stack--tools)
- [Project Architecture](#️-project-architecture)
- [Getting Started](#-getting-started)
- [Project Roadmap](#️-project-roadmap)
- [Author](#-author)
- [License](#-license)

---

## 🧐 About The Project

This project is a comprehensive e-commerce solution built on the **MEAN stack** (MongoDB, Express.js, Angular, Node.js). It provides a seamless shopping experience for users and a powerful management interface for administrators, all connected via a robust RESTful API.

The application follows modern development principles, focusing on a modular and scalable architecture with a clear separation between the **Angular front-end** and the **Node.js/Express back-end**.

---

## ✨ Key Features

### 🛍️ Customer-Facing Portal

-   **Intuitive Product Navigation:** Browse, search, and view detailed product pages.
-   **Seamless Cart Management:** Easily add, view, and manage items in the shopping cart.
-   **Secure Authentication:** User registration and login functionality with protected routes.
-   **Order Placement & Tracking:** A streamlined checkout process and a dedicated page to track order history.
-   **User-Friendly Notifications:** Toast notifications for actions like adding to cart or login success.

### 🧑‍💼 Admin Dashboard

-   **Full Product Management (CRUD):** Admins can add, update, and delete products, including image uploads.
-   **Order Management:** View all customer orders and update their status (e.g., Pending, Shipped, Delivered).
-   **User Management:** View and manage all registered users.
-   **Protected Routes:** Dedicated admin routes are secured to prevent unauthorized access.

---

## 🛠️ Tech Stack & Tools

This project leverages a modern full-stack ecosystem to deliver a high-performance application.

| Category | Technologies & Tools |
| :--- | :--- |
| **Frontend** | ![Angular](https://img.shields.io/badge/Angular-v17-DD0031?logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5.2-3178C6?logo=typescript&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-v5-7952B3?logo=bootstrap&logoColor=white) ![RxJS](https://img.shields.io/badge/RxJS-B7178C?logo=rxjs&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-v18-339933?logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![Mongoose](https://img.shields.io/badge/Mongoose-880000?logo=mongoose&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white) |
| **Dev Tools**| ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?logo=visualstudiocode&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-CB3837?logo=npm&logoColor=white) |

---

## 🏛️ Project Architecture

The project is structured as a **monorepo** with two distinct applications: `frontend` and `backend`, ensuring a clean separation of concerns.

### Frontend Architecture (Angular)
The Angular front-end follows best practices for creating scalable applications.
-   **`components/`**: Reusable UI elements (navbar, product cards, etc.).
-   **`pages/`**: Main application views (Home, Products, Login, Admin Dashboard).
-   **`services/`**: Manages API communication and shared state.
-   **`guards/`**: Implements route protection logic (`AuthGuard`, `AdminGuard`).
-   **`models/`**: Defines TypeScript interfaces for data structures.

### Backend Architecture (Node.js)
The Node.js back-end is built using the **MVC (Model-View-Controller)** pattern.
-   **`models/`**: Defines Mongoose schemas for the database.
-   **`controllers/`**: Contains the business logic for each route.
-   **`routes/`**: Defines the API endpoints and connects them to controller functions.
-   **`middleware/`**: Handles authentication, authorization, and error handling.

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### **Prerequisites**

-   Node.js (v18.x or later)
-   Angular CLI (`npm install -g @angular/cli`)
-   MongoDB (either a local instance or a free [Atlas](https://www.mongodb.com/cloud/atlas) cluster)
-   Git

### **Installation & Setup**

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/ahmedtoba74/Ecommerce-Project.git](https://github.com/ahmedtoba74/Ecommerce-Project.git)
    cd Ecommerce-Project
    ```
2.  **Install Backend Dependencies:**
    ```sh
    cd backend
    npm install
    ```
3.  **Install Frontend Dependencies:**
    ```sh
    cd ../frontend
    npm install
    ```
4.  **Set Up Backend Environment:**
    - Navigate back to the `backend` folder.
    - Create a `.env` file and add the necessary environment variables (use `.env.example` as a guide).
    ```env
    # .env.example
    PORT=3000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    ```
    
### **Running the Application**

You will need two terminals running concurrently.

1.  **Run the Backend Server:**
    - In your first terminal, inside the `backend` folder:
    ```sh
    npm start
    ```
    - The server should now be running on `http://localhost:3000`.

2.  **Run the Frontend Application:**
    - In your second terminal, inside the `frontend` folder:
    ```sh
    ng serve
    ```
    - Open your browser and navigate to `http://localhost:4200/`.

---

## 🗺️ Project Roadmap

-   [ ] **Payment Gateway Integration:** Integrate Stripe or another provider for real transactions.
-   [ ] **Advanced Product Filtering:** Add functionality to filter products by category, price range, etc.
-   [ ] **State Management:** Implement a state management library like NgRx for more complex client-side state.
-   [ ] **Testing:** Add unit tests (Jest) for the back-end and front-end (Jasmine/Karma).
-   [ ] **CI/CD:** Implement a CI/CD pipeline using GitHub Actions for automated testing and deployment.

---

## 👨‍💻 Author

**Ahmed Toba Mahmoud**
- **LinkedIn:** [@ahmed-toba](https://www.linkedin.com/in/ahmed-toba-135287239)
- **GitHub:** [@ahmedtoba74](https://github.com/ahmedtoba74)

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

````
