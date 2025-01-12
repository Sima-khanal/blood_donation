Here's a `README.md` file for your Blood Donation System. This file provides a comprehensive guide to the project, its setup, usage, and features.

---

# Blood Donation System

## Overview

The **Blood Donation System** is a web-based application designed to manage blood requests and cancellations. It allows users to make blood requests, view available stock, and cancel requests if needed. Admins have access to manage blood stock, view all blood requests, and approve or reject requests. The system is built using **HTML**, **CSS**, **JavaScript**, and **PHP** with a **MySQL** database.

---

## Features

### User Features:

- **User Registration**: Sign up as a blood requester with personal details and create a unique account.
- **Blood Request**: Make a blood request by selecting blood type and quantity.
- **Request Cancellation**: Cancel a previously made request (if applicable).
- **Login**: Secure login for users to manage their requests.

### Admin Features:

- **Admin Login**: Admins can securely log into the admin panel.
- **Manage Blood Stock**: Add, update, or delete blood stock.
- **View Blood Requests**: View all requests from users, approve/reject requests, or cancel them.

---

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **AJAX**: For dynamic requests without reloading the page

---

## Installation

### Prerequisites

1. A server running PHP (e.g., XAMPP, WAMP, or any PHP-compatible server).
2. MySQL database for storing data.
3. Basic knowledge of web development.

### Steps to Install

1. **Download the Project**:

   - Clone or download the repository to your local machine.

2. **Set Up the Database**:
   - Create a new MySQL database named `blood_donation` using the provided SQL script (`blood_donation.sql`).
   - Import the SQL file to set up the tables.
3. **Configure Database Credentials**:

   - Open the `db.php` file.
   - Update the database connection settings (host, username, password, and database name) according to your environment.

4. **Start the Server**:

   - Launch your PHP server (e.g., via XAMPP/WAMP or command line if you're using PHP's built-in server).

5. **Access the Application**:
   - Open a web browser and navigate to `localhost/blood_donation` (or the corresponding URL if hosted online).

---

## Usage

### User Registration and Login

1. **Sign Up**: Register a new user by filling out the registration form (name, email, phone, password, etc.).
2. **Login**: Use the registered email and password to log in to the system.
3. **Blood Request**: After logging in, users can make a blood request by specifying the blood type and quantity.
4. **Request Cancellation**: If needed, users can cancel their blood request.

### Admin Panel

1. **Login as Admin**: Admins can log in with their credentials to access the admin dashboard.
2. **Manage Blood Stock**: Admins can update the blood stock, adding new blood types and quantities.
3. **View and Manage Requests**: Admins can see all requests from users, approve or reject them, or cancel the requests.

---

## File Structure

```
/blood_donation
    /admin                - Admin-specific pages
    /css                  - Stylesheets (CSS)
    /js                   - JavaScript files (scripts)
    /shared               - Common components and pages
    db.php                - Database connection file
    functions.php         - Common PHP functions
    index.php             - Landing page
    login.php             - Login page
    register.php          - Registration page
    create_blood_request.php - Handle blood request creation
    cancel_request.php    - Handle blood request cancellation
    manage_stock.php      - Admin page to manage blood stock
    view_requests.php     - Admin page to view and manage blood requests
    blood_donation.sql    - SQL file to set up the database
    script.js             - Client-side JavaScript for handling interactivity
```

---

## How to Contribute

1. **Fork the repository** to your GitHub account.
2. **Clone the forked repository** to your local machine.
3. **Create a new branch** for your feature or bug fix.
4. **Make your changes** and commit them.
5. **Push your changes** to your forked repository.
6. **Submit a pull request** for review.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- **XAMPP/WAMP** for local development.
- **PHP and MySQL** for the backend development.
- **AJAX** for dynamic content updates.

---

This README provides an overview of the project, its features, and instructions for setup and usage. Let me know if you need any further modifications or additions!
