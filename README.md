# 💊 Pharmacy Management System

A web-based **Pharmacy Management System** designed to help manage medicines, inventory, customers, employees, and sales efficiently.

The system provides a centralized platform for handling common pharmacy operations through an easy-to-use interface.

---

## 🚀 Features

* 🔐 User Authentication
* 👥 Role-based access for Admin, Pharmacist, and Cashier
* 💊 Medicine Management
* 📦 Inventory Management
* ⚠️ Low Stock Alerts
* 📅 Medicine Expiry Tracking
* 👨‍⚕️ Employee Management
* 👤 Customer Management
* 🛒 Sales and POS Management
* 📊 Dashboard with sales summary
* 💰 Automatic 10% Tax Calculation
* 🗄️ MySQL Database Integration
* 📱 Bootstrap Responsive Interface

---

## 🛠️ Technologies Used

* **PHP**
* **Laravel**
* **MySQL**
* **Bootstrap**
* **HTML**
* **CSS**
* **JavaScript**
* **Blade Templates**
* **Eloquent ORM**
* **XAMPP**

---

## 👥 User Roles

### 👨‍💼 Admin

* Manage medicines
* Manage employees
* Manage customers
* View sales information
* Manage pharmacy operations

### 💊 Pharmacist

* Manage medicines
* Check inventory
* Monitor stock levels
* Handle pharmacy-related operations

### 💵 Cashier

* Manage customers
* Process sales
* Generate bills
* Handle POS operations

---

## 📦 Medicine Management

The system allows pharmacy staff to:

* Add new medicines
* Update medicine information
* Delete medicines
* Track available stock
* Monitor expiry dates
* Identify low-stock medicines

---

## 🛒 Sales & POS

The Sales/POS module allows users to:

* Select medicines
* Enter quantities
* Calculate the total price
* Apply **10% tax**
* Process customer sales
* Maintain sales records

---

## 📊 Dashboard

The dashboard provides an overview of important pharmacy information, including:

* Total medicines
* Total customers
* Total employees
* Sales summary
* Recent sales
* Stock information

---

## 🗄️ Database

The project uses **MySQL** for storing application data.

### Database Name

```text
pharmacy_db
```

The database contains information related to medicines, users, employees, customers, and sales.

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/ahsanali52757-blip/Pharamacy-management-System.git
```

### 2. Open the Project

Open the project folder in **VS Code** or another code editor.

### 3. Install Dependencies

```bash
composer install
```

### 4. Create Environment File

```bash
copy .env.example .env
```

### 5. Generate Application Key

```bash
php artisan key:generate
```

### 6. Configure Database

Create a MySQL database named:

```text
pharmacy_db
```

Then update the database settings in `.env`.

### 7. Run Migrations

```bash
php artisan migrate
```

### 8. Start Laravel Server

```bash
php artisan serve
```

Open the application in your browser using the local URL provided by Laravel.

---

## 📁 Project Structure

```text
Pharamacy-management-System/
│
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
│   └── views/
├── routes/
├── storage/
├── .env.example
├── artisan
├── composer.json
└── README.md
```

---

## 🎯 Project Purpose

The purpose of this project is to provide a digital solution for managing common pharmacy operations.

It demonstrates the use of **Laravel, PHP, MySQL, Bootstrap, MVC architecture, Eloquent ORM, authentication, CRUD operations, and database management**.

---

## 🔮 Future Improvements

* Online medicine ordering
* Prescription management
* Supplier management
* Invoice printing
* Advanced sales reports
* Email notifications
* Medicine barcode scanning
* Automated expiry notifications

---

## 👨‍💻 Developer

**Ahsan Ali**

Software Engineering Student

GitHub: [@ahsanali52757-blip](https://github.com/ahsanali52757-blip)

---

⭐ Feel free to explore this project and check out my other repositories.
