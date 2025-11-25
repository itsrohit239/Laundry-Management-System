<div align="center">

  <h1 align="center">🧺 Laundry Management System</h1>

  <p align="center">
    A comprehensive, responsive web application to streamline laundry business operations, order tracking, and billing.
    <br />
    <a href="https://github.com/itsrohit239/Laundry-Management-System/issues"><strong>Report Bug</strong></a>
    ·
    <a href="https://github.com/itsrohit239/Laundry-Management-System/pulls"><strong>Request Feature</strong></a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
    <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
    <img src="https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
    <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery" />
    <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
  </p>
</div>

---

## 📖 About The Project

The **Laundry Management System (LMS)** is a web-based solution designed to digitize the daily operations of a laundry service. From managing customer data to tracking the lifecycle of a garment from "Pending" to "Delivered," this system provides a seamless experience for administrators.

It includes an automated billing system that generates printable invoices, helping businesses move away from manual paperwork.

### 🌟 Key Features

* **📊 Admin Dashboard:** Real-time overview of total orders, revenue, and pending deliveries.
* **📦 Order Management:** Full lifecycle tracking with status updates (Pending ➝ Processing ➝ Ready ➝ Delivered).
* **👕 Service Management:** CRUD (Create, Read, Update, Delete) functionality for laundry services (e.g., Dry Clean, Wash & Iron) and pricing.
* **📈 Sales Reports:** Generate monthly reports to track business performance.
* **📱 Responsive Design:** Fully functional on mobile, tablets, and desktops using Bootstrap 5.

---

## 🛠️ Technologies Used

* **Backend:** PHP
* **Database:** MySQL
* **Frontend:** HTML5, CSS3, Bootstrap 5 
* **Scripting:** JavaScript, jQuery
* **Icons:** FontAwesome

---


## 🚀 Getting Started

Follow these instructions to set up the project locally on your machine.

### Prerequisites

* **XAMPP** or **WAMP** server (for PHP & MySQL).
* A web browser.

### Installation Steps

1.  **Clone the Repository**
    ```sh
    git clone [https://github.com/itsrohit239/Laundry-Management-System.git](https://github.com/itsrohit239/Laundry-Management-System.git)
    ```
2.  **Move to Server Directory**
    * Copy the project folder to your `htdocs` folder (if using XAMPP) or `www` folder (if using WAMP).

3.  **Database Setup**
    * Open **phpMyAdmin** (`http://localhost/phpmyadmin`).
    * Create a new database named: `laundry_db`
    * Import the `database.sql` file provided in the root directory of this project.

4.  **Configure Connection**
    * Go to `config/db.php`.
    * Ensure the credentials match your local setup:
        ```php
        $servername = "localhost";
        $username = "root";
        $password = ""; // Default XAMPP password is empty
        $dbname = "laundry_db";
        ```

5.  **Run the Application**
    * Open your browser and visit: `http://localhost/Laundry-Management-System`

### 🔐 Default Login Credentials

| Role | Username | Password |
| :--- | :--- | :--- |
| **Administrator** | `admin` | `admin123` |

---


## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 👤 Author

**Rohit**
* GitHub: [@itsrohit239](https://github.com/itsrohit239)

<div align="center">
  <br />
  <i>If you found this project helpful, please give it a ⭐️!</i>
</div>
