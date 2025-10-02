# 🍔 TastyAF - Online Food Ordering Website

TastyAF is a modern online food ordering platform built with **PHP**, **MySQL**, **HTML/CSS**, and **JavaScript**.  
It allows customers to browse the menu, add items to their basket, customize toppings, and place orders online.  
Admins can manage orders through a secure admin panel.

---

## 🚀 Features

### Customer Side
- 🛒 Add food items to basket with toppings  
- 🔄 Manage basket (update, remove, clear)  
- 💳 Fake payment simulation (checkout flow)  
- 📱 Responsive design with mobile-friendly navigation  
- 👤 User authentication (Login/Register/Profile)  

### Admin Side
- 📋 Manage all customer orders  
- ✅ Accept, complete, or cancel orders  
- 📊 Track order status in real time  
- 🔒 Secure access for admins only  

---

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript (vanilla)  
- **Backend:** PHP 8+  
- **Database:** MySQL  
- **Server:** XAMPP / Apache  

---

## 📂 Project Structure

```
tastyaf/
│── css/ # Stylesheets
│── img/ # Images & logos
│── php/ # PHP backend scripts
│ ├── db.php # Database connection
│ ├── process_payment.php # Checkout & fake payment
│ ├── update_status.php # Update order status
│ └── logout.php
│── index.php # Homepage
│── profile.php # User profile
│── admin.php # Admin panel
│── login.php # Login page
│── register.php # Register page
```

---

## ⚙️ Installation

1. Clone the repository:
```
git clone https://github.com/YOUR_USERNAME/tastyaf.git
```

or

2. Move Project to XAMPP
```
move tastyaf C:\xampp\htdocs\tastyaf
```

3. Import Database from project folder to phpMyAdmin
```
https://localhost/phpmyadmin
```


4. Start Apache & MySQL in XAMPP
# (Run this from XAMPP Control Panel)
```
Start Apache
Start MySQL
```

5. Open in Browser
# Navigate to:
```
http://localhost/tastyaf/
```

