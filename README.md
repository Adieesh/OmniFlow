# 🚀 OmniFlow – Business Workflow Automation System

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange?logo=mysql)
![CustomTkinter](https://img.shields.io/badge/GUI-CustomTkinter-darkgreen)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey)
![PDF](https://img.shields.io/badge/Reports-PDF%20Generator-red)

*A Modern Desktop Application for Order & Customer Management (Python + MySQL + CustomTkinter)*

---

## 📌 Overview
**OmniFlow** is a customizable business workflow automation software built using **Python**, **CustomTkinter**, and **MySQL**.  
It helps manage:

- Customer information  
- Order creation & tracking  
- Invoice + job card generation  
- Dashboard analytics  
- Secure MySQL-backed storage  

Although demonstrated with tailoring workflows, OmniFlow can be adapted to **any service-based or product-based industry**.

---

## 🎯 Key Features

### ✔ Modern Dark UI (CustomTkinter)
A minimal, elegant interface with responsive components and organized navigation.

### ✔ Order Management
- Add, update, delete orders  
- Track status (Pending → In Progress → Ready → Delivered)  
- View details via interactive cards  

### ✔ Customer Management
- Centralized customer database  
- Smart autocomplete search  
- Auto-fill customer details during new orders  

### ✔ PDF Generation (ReportLab)
- Professionally formatted **Invoices**  
- Printable **Job Cards** with measurements  

### ✔ Dashboard Analytics (Matplotlib)
- Garment-wise distribution (Pie Chart)  
- Status breakdown (Bar Chart)  
- Automatic monthly revenue calculation  

### ✔ MySQL Database Storage
Reliable and structured storage for users, customers, orders, and settings.

---

## 🛠 Technologies Used

- **Python 3.x**  
- **CustomTkinter**  
- **MySQL**  
- **mysql-connector-python**  
- **ReportLab**  
- **Matplotlib**  
- **tkcalendar**  
- **JSON**, **datetime**

---

## ⚙️ Installation & Setup

### 1️⃣ Install Dependencies
```
pip install -r requirements.txt
```
### 2️⃣ Configure MySQL
Ensure MySQL is installed and running.
Update database credentials in main.py
```
connection = mysql.connector.connect(
    host='localhost',
    user='root',
    password='yourpassword',
    database='omniflow'
)
```
### 3️⃣ Run the Application
```
python main.py
```
### 4️⃣ Default Login Credentials
```
Username: admin
Password: admin123
```
---

## 📸 Screenshots

### 🔐 Login Screen

### 🏠 Dashboard

### 📝 New Order Form

### 📄 Invoice Output

---

## 🔮 Future Enhancements

- Role-based user accounts
- Cloud database integration
- Encrypted passwords (bcrypt)
- Multi-branch syncing
- Mobile / Web version

---

## 🤝 Contributing

Contributions are always welcome!
For major changes, please open an issue first to discuss improvements.

---
## 📜 License

Released under the MIT License.

---

## ❤️ Author

Adieesh V.K
Creator & Developer of OmniFlow

---
