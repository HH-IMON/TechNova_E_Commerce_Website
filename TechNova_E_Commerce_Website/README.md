<img width="1904" height="953" alt="Admin Home Page" src="https://github.com/user-attachments/assets/8acad595-4295-4734-9610-e6e701fac5b4" />
<img width="1900" height="943" alt="Admin Product Page" src="https://github.com/user-attachments/assets/01231a62-4394-40d0-b634-80187291632c" />
<img width="1906" height="955" alt="Admin user page" src="https://github.com/user-attachments/assets/bccc0fb1-d18d-4d24-bb9b-abd43d6a12ae" />
<img width="1890" height="932" alt="admin contrat" src="https://github.com/user-attachments/assets/ebd662bc-0c66-4b37-a52b-53ffac119619" />
# 🚀 TechNova E-Commerce Website

A modern, fully functional **PHP & MySQL-based e-commerce platform** designed for selling technology products. TechNova offers a seamless shopping experience with a powerful admin panel, secure authentication system, and efficient product and order management features.

---

## 🌐 Overview

TechNova is built to simulate a real-world online shopping system. It includes both **user-side functionalities** and a **robust admin dashboard**, making it ideal for learning full-stack web development concepts.

---

## ✨ Features

### 👤 User Features

* 🔐 Secure user registration and login system
* 🛍️ Browse products by categories (Laptops, Mobiles, PCs, Monitors)
* 🛒 Add, update, and remove items from cart
* ❤️ Wishlist functionality for saving products
* 📦 View order history and status
* 👤 Profile management with image support
* 📩 Contact form for user queries
* 📱 Fully responsive design

---

### 🛠️ Admin Features

* 📊 Dashboard with system overview
* 📦 Product management (Add, Edit, Delete)
* 🗂️ Category management
* 📑 Order tracking and status updates
* 👥 User management system
* 💬 Message handling system

---

## 📸 Screenshots

> ⚠️ Replace these placeholders with your actual project screenshots.

* 🏠 Home Page
* 📊 Admin Dashboard
* 📦 Product Management
* 👥 User Management

---

## 🧰 Technologies Used

* **Backend:** PHP (7.x+)
* **Database:** MySQL / MariaDB
* **Frontend:** HTML5, CSS3, JavaScript
* **Database Access:** PDO
* **Image Processing:** PHP GD Library
* **Session Handling:** PHP Sessions

---

## 📋 Requirements

* PHP 7.0 or higher
* MySQL 5.7+ / MariaDB 10.2+
* Apache / Nginx Server
* PDO Extension Enabled
* GD Library Enabled

---

## ⚙️ Installation Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/technova-ecommerce.git
```

---

### 2️⃣ Setup Database

```sql
CREATE DATABASE shop_db;
```

```bash
mysql -u root -p shop_db < shop_db.sql
```

---

### 3️⃣ Configure Database

Edit `config.php`:

```php
<?php
$db_name = "mysql:host=localhost;dbname=shop_db";
$username = "root";
$password = "";
$conn = new PDO($db_name, $username, $password);
?>
```

---

### 4️⃣ Set Folder Permissions

```bash
chmod 755 uploaded_img/
```

---

### 5️⃣ Run the Project

```
http://localhost/technova-ecommerce/home.php
```

---

## 🔑 Default Credentials

### 👨‍💼 Admin

* Email: [admin@gmail.com](mailto:admin@gmail.com)
* Password: admin

### 👤 Test User

* Email: [user@test.com](mailto:user@test.com)
* Password: 123456

---

## 📁 Project Structure

```
technova-ecommerce/
├── admin_page.php
├── admin_products.php
├── admin_orders.php
├── admin_users.php
├── home.php
├── shop.php
├── category.php
├── cart.php
├── wishlist.php
├── checkout.php
├── orders.php
├── login.php
├── register.php
├── config.php
├── css/
│   └── style.css
├── uploaded_img/
├── components/
│   ├── header.php
│   └── footer.php
└── shop_db.sql
```

---

## 🎯 Core Functionalities

### 🛍️ Product Management

* Add products with details
* Upload images
* Edit & delete products
* Category filtering

### 🛒 Cart System

* Add/remove items
* Update quantity
* Calculate total
* Checkout system

### 📦 Order System

* Place orders
* Track order history
* Admin status updates

### 🔐 Authentication System

* Session-based login
* Role-based access (Admin/User)
* Basic password security

---

## 🔒 Security Notes

* ⚠️ Uses MD5 hashing (for learning purposes only)
* ✔️ PDO prepared statements used (SQL Injection protection)
* ✔️ Basic input validation implemented
* ✔️ Session-based authentication

> 💡 Recommendation: Use `password_hash()` and `password_verify()` in production.

---

## 🚀 Future Improvements

* 🔐 Advanced password encryption (bcrypt/Argon2)
* 💳 Payment gateway integration
* 🔍 Product search functionality
* ⭐ Reviews & ratings system
* 📦 Order tracking system
* 🎟️ Coupon/discount feature
* 📧 Email notifications
* ⚡ AJAX-based UI improvements

---

## 🤝 Contributing

Contributions are welcome!

```bash
git checkout -b feature/new-feature
git commit -m "Added new feature"
git push origin feature/new-feature
```

Then open a Pull Request 🚀

---

## 📄 License

This project is created for **educational purposes**. You are free to use, modify, and distribute it.

---

## 👨‍💻 Author

**Md. Methun Hossain**
📧 methun.khan01@gmail.com

🎓 Green University of Bangladesh
💻 Computer Science & Engineering

---

⭐ *If you like this project, don't forget to give it a star on GitHub!*


