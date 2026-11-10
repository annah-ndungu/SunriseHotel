# Sunrise Hotel Booking System

## 📌 Project Overview

The **Sunrise Hotel Booking System** is a web-based hotel room booking project developed to allow customers to view available rooms and make hotel reservations online.

The system was developed as part of a practical web development project using **PHP, MySQL, HTML, CSS, and JavaScript**.

## ✨ Features

- 🏨 Hotel room booking
- 👤 Customer booking details
- 📧 Customer email and phone number collection
- 🛏️ Room type selection
- 🌙 Number of nights selection
- 👥 Number of guests selection
- ✅ JavaScript form validation
- 💾 Booking information stored in a MySQL database
- 📋 View existing bookings
- 🏠 Home page navigation
- 💻 Simple and user-friendly interface

## 🛠️ Technologies Used

- **HTML** - Structure of the web pages
- **CSS** - Styling and page layout
- **JavaScript** - Form validation
- **PHP** - Server-side processing
- **MySQL** - Database management
- **XAMPP** - Local development server
- **VS Code** - Code editor

## 📂 Project Structure

```text
Sunrise-Hotel-Booking/
│
├── index.php
├── book_room.php
├── view_bookings.php
├── db.php
├── style.css
├── script.js
│
└── database/
    └── hotel_booking.sql
```

> The exact files may vary depending on the final project folder structure.

## ⚙️ How to Run the Project

### 1. Install XAMPP

Download and install XAMPP if it is not already installed.

### 2. Start XAMPP

Open the XAMPP Control Panel and start:

- Apache
- MySQL

### 3. Copy the Project

Place the project folder inside the XAMPP `htdocs` directory.

Example:

```text
C:\xampp\htdocs\Sunrise-Hotel-Booking
```

### 4. Create the Database

Open **phpMyAdmin** through XAMPP and create the required database.

Import the provided SQL file:

```text
hotel_booking.sql
```

### 5. Check Database Connection

Make sure the database connection details in `db.php` match your local MySQL configuration.

### 6. Open the Project

Open a browser and visit:

```text
http://localhost/Sunrise-Hotel-Booking/
```

The Sunrise Hotel Booking System should now be available locally.

## 📝 Booking Validation

The booking form uses JavaScript validation to ensure that the required customer and booking information is provided before the form is submitted.

The validation includes:

- Customer name
- Email address
- Phone number
- Number of nights
- Number of guests
- Room type

## 🎯 Purpose of the Project

The purpose of this project is to demonstrate practical understanding of:

- Web application development
- PHP programming
- Database connectivity
- MySQL database management
- JavaScript form validation
- HTML and CSS
- CRUD-related database operations
- Running a PHP application using XAMPP

## 👩‍💻 Author

**Annaf Ndung'u**

Bachelor of Information Technology  
Kirinyaga University

## 📄 License

This project was developed for educational purposes.
