# 🎓 Student Registration System

A web-based **Student Management System** built with **PHP**, **MySQL**, and **HTML5/CSS3**. This application allows users to register new students into a database and view the list of registered students in a clean table view.

---

## ✨ Features

* 📝 **Student Registration: ** Add new students with details including Name, Email, Phone Number, and Course.
* 📊 **View Records: ** Fetch and display all registered students dynamically from the database.
* 🗂️ **Course Selection: ** Dropdown menu supporting multiple fields (ICT, Engineering, Business, English).
* 🎨 **Simple Navigation & UI: ** Includes home navigation and clean form/table layouts.

---

## 🛠️ Tech Stack & Prerequisites

| Technology | Usage |
| :--- | :--- |
| **PHP** (v7.4 / v8.x) | Backend Processing & Database Connection |
| **MySQL** | Relational Database System |
| **HTML5 & CSS3** | User Interface & Styling |
| **XAMPP / WAMP / MAMP** | Local Development Server |

---

## 📂 Project Structure

| File Name | Description |
| :--- | :--- |
| `home.html` | Landing / Welcome page with navigation links |
| `index.html` | Student registration form |
| `INSERT.php` | Handles form submission and inserts data into MySQL |
| `VIEW.php` | Queries the database and displays student listings |
| `db.php` | MySQL database connection setup |

---

## 🚀 Installation & Setup

### 1. Database Setup

1. Open **phpMyAdmin** (`http://localhost/phpmyadmin`).
2. Create a new database named **`student_registation_db`**.
3. Create a table named **`students`** by running this SQL query:

```SQL
CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR (100) NOT NULL,
    email VARCHAR (100) NOT NULL,
    phone VARCHAR (20) NOT NULL,
    course VARCHAR (50) NOT NULL
);
