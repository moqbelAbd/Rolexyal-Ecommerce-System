# Rolexyal - Luxury Watches & Accessories E-Commerce Platform

Rolexyal is a modern, full-stack e-commerce web application centered around luxury watches and premium accessories. Built with a robust backend architecture and a sleek user interface, it provides a seamless shopping experience for customers and a comprehensive management dashboard for administrators.

## 🚀 Live Demo & Access
* **Live Website:** [http://rolexyal.runasp.net/](http://rolexyal.runasp.net/)
* **GitHub Repository:** [https://github.com/moqbelAbd/Rolexyal-Ecommerce-System](https://github.com/moqbelAbd/Rolexyal-Ecommerce-System)

### Demo Admin Credentials:
* **Email:** `Admin@gmail.com`
* **Password:** `#Admin123`

---

## ✨ Key Features

### For Customers:
* **Hybrid Shopping Cart:** Seamlessly handles guest shopping sessions and automatically syncs/merges cart items into the user's database cart upon login or registration.
* **Secure Authentication & Account Management:** Powered by ASP.NET Core Identity with role-based access control, profile management, and order history tracking.
* **Advanced Product Discovery:** Filter products by categories, subcategories, price ranges, and real-time search keywords.
* **Wishlist & Reviews:** Add products to a wishlist and submit customer testimonials or reviews.
* **Secure Payment & Checkout:** Supports multi-step checkout processes with encrypted saved payment card handling using the ASP.NET Data Protection API.

### For Administrators:
* **Admin Dashboard & Analytics:** Comprehensive overview tracking total revenue, monthly sales trends, order status breakdowns, and category-wise revenue distribution.
* **Inventory & Product Management:** Monitor stock levels with low-stock alerts, manage product catalogs, images, and categories.
* **Order Oversight:** View, update, and manage customer orders efficiently.

---

## 🛠️ Tech Stack

* **Framework:** ASP.NET Core MVC (.NET)
* **Language:** C#
* **Database & ORM:** SQL Server, Entity Framework Core (EF Core)
* **Authentication & Security:** ASP.NET Core Identity, ASP.NET Data Protection API
* **Frontend:** Razor Views, HTML5, CSS3, Bootstrap, JavaScript, AJAX, jQuery

---

## 📂 Project Structure Overview

```text
Rolexyal/
│
├── Areas/Identity/          # Authentication pages (Login, Register, Logout)
├── Controllers/             # MVC Controllers (Customer, Admin, Home, Cart)
├── Models/                  # Entity models and ViewModels
├── Data/                    # ApplicationDbContext and database configurations
├── Views/                   # Razor views (Shop, Cart, Checkout, Dashboard, etc.)
└── wwwroot/                 # Static assets (CSS, JS, images, vendor libraries)
