# db-manager-crud

A simple CRUD web application for managing a pharmacy database.  
The system allows users to create, read, and delete records for clients, suppliers, products, pharmacies, and payments using a PHP + MySQL backend.

---

## Features

- Full CRUD operations for database tables
- Client management system
- Supplier management system
- Product catalog management
- Pharmacy management
- Payment tracking system
- MySQL relational database with foreign keys
- Simple web interface for each table
- Data stored and managed through phpMyAdmin / MySQL

---

## Development Tools

![VS Code](https://img.shields.io/badge/VS%20Code-blue?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![OpenServer](https://img.shields.io/badge/OpenServer-black?style=for-the-badge&logo=windows&logoColor=white)
![phpMyAdmin](https://img.shields.io/badge/phpMyAdmin-red?style=for-the-badge&logo=phpmyadmin&logoColor=white)
![Git](https://img.shields.io/badge/Git-black?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## Technologies

![HTML5](https://img.shields.io/badge/HTML5-orange?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-purple?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-lightblue?style=for-the-badge&logo=mysql&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?style=for-the-badge&logo=javascript&logoColor=black)

---

## Database

The project uses a MySQL database named `pharmacy`.

### Main Tables

- `клієнт` (clients)
- `постачальник` (suppliers)
- `продукт` (products)
- `аптека` (pharmacies)
- `замовлення` (orders)
- `оплата` (payments)

Each table supports basic CRUD operations through the web interface.

---

## Screenshots

### Home Page
![Home Page](Screenshot/1.png)

### Clients Management
![Clients](Screenshot/11.png)

### Products Management
![Products](Screenshot/8.png)

---

## Installation

### 1. Clone repository
```bash
git clone https://github.com/your-username/db-manager-crud.git
```

---

### Run Project

1. Start OpenServer or XAMPP
2. Import database into phpMyAdmin
3. Move project to `htdocs` or OpenServer `/domains`
4. Open in browser:
http://localhost/db-manager-crud/
