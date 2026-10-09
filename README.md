# WebProject-BH-STORE

# 🛒 BH STORE

## 📌 Description

BH STORE is a modern E-Commerce platform developed for the sale of smartphones, accessories, and spare parts.

The website allows users to browse available products, quickly search for items, add products to their shopping cart, create an account, and place orders online.

This project was developed as part of a Full Stack Web Development learning experience using PHP, MySQL, HTML, CSS, and JavaScript.

---

## ✨ Main Features

### 👤 User Management
- New user registration
- Secure login
- Logout functionality
- User session management

### 📱 Product Catalog
- Smartphones
- Accessories
- Spare parts

### 🔎 Smart Search
- Dynamic product search
- Fast display of search results

### 🛍️ Shopping Cart
- Add products to cart
- Modify product quantities
- Automatic total calculation

### 📦 Order Management
- Order validation
- Order storage in the database
- Order history management

### ⚙️ Administration
- Administrator dashboard
- Product management
- Order tracking and management

### 📱 Responsive Design
- Desktop compatible
- Tablet compatible
- Mobile compatible

---

## 🛠️ Technologies Used

### Front-End
- HTML5
- CSS3
- JavaScript

### Back-End
- PHP

### Database
- MySQL

---

## 🗄️ Database Structure

### `users`

User account management:

- `id`
- `name`
- `email`
- `password`
- `created_at`
- `updated_at`

### `products`

Product storage:

- `id`
- `name`
- `brand`
- `category`
- `specs`
- `price`
- `old_price`
- `image`

### `commandes`

Order management:

- `id`
- `user_id`
- `items`
- `total`
- `status`
- `created_at`

---

## 📂 Project Structure

```text
BHSTORE/
│
├── index.html
├── style.css
├── login.php
├── register.php
├── logout.php
├── save_commande.php
├── get_products.php
├── config.php
│
├── admin.html
├── admin.php
├── admin.css
├── admin.js
│
├── DATABASE.sql
│
└── Product Images/
```

---

## 🚀 Installation

### 1. Clone the Project

```bash
git clone https://github.com/YOUR-USERNAME/BHSTORE.git
```

### 2. Import the Database

Import the following file:

```text
DATABASE.sql
```

into phpMyAdmin.

### 3. Configure the MySQL Connection

Edit the following file:

```text
config.php
```

Configure your database information:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "bh_store";
```

### 4. Run the Project

Place the project folder inside:

```text
C:\xampp\htdocs\
```

Start Apache and MySQL from the XAMPP Control Panel.

Then open your browser and navigate to:

```text
http://localhost/BHSTORE
```

---

## 🎯 Project Objectives

- Apply Full Stack Web Development concepts in practice.
- Understand Front-End and Back-End integration.
- Use PHP and MySQL in a real-world application.
- Develop a functional E-Commerce platform.

---

## 📍 Location

BH STORE – Ajim, Djerba, Tunisia

---

## 👨‍💻 Author

**BH YASSER**

Computer Science Student – Software Engineering

E-Commerce project developed as part of a Web Development learning experience.

---

## 📄 License

Educational and academic project.
