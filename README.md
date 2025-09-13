# 🏠 Real Estate Management System (PHP + MySQL)

A web-based application built with **PHP and MySQL** that allows users and admins to manage real estate listings efficiently.  
The system provides a responsive interface for browsing, adding, editing, and deleting property details.

---

## ✨ Features
### User Module:
- User registration & login system
- Browse property listings with details
- View property grid and detailed pages
- Contact form integration
- Mortgage/loan calculator

### Admin Module:
- Admin login & management
- Manage property details (add, edit, delete)
- Manage agents, cities, and states
- Dashboard for quick operations
- Profile and user management

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript (Bootstrap)
- **Backend:** PHP
- **Database:** MySQL
- **Server:** XAMPP / WAMP / LAMP

---

## 📂 Project Structure
- `index.php` → Homepage with property listings
- `property.php`, `propertydetail.php`, `propertygrid.php` → Property browsing
- `submitproperty.php` → Add property form
- `admin/` → Admin panel (manage properties, agents, cities, states)
- `config.php` → Database configuration
- `login.php`, `register.php` → Authentication system

---

## ⚙️ Setup Instructions
1. Install [XAMPP](https://www.apachefriends.org/) or WAMP server.
2. Copy the project folder into the `htdocs` directory.
3. Create a database in **phpMyAdmin** (e.g., `realestate_db`).
4. Import the provided SQL file (if available) into the database.
5. Update `config.php` with your database credentials.
6. Start Apache and MySQL from XAMPP/WAMP.
7. Open the project in browser:  
   `http://localhost/RealEstate-PHP/`

---

## 🔑 Default Login (check `01 LOGIN DETAILS & PROJECT INFO.txt`)
- **Admin Username:** admin  
- **Admin Password:** admin123  
- (You can change these in the database)

---

## 📌 Future Improvements
- Add role-based access control
- Implement search & filter for listings
- Integrate Google Maps API for property locations
- Add image upload for properties

---

## 👨‍💻 Author
Developed as part of a Computer Science project for managing real estate properties.
