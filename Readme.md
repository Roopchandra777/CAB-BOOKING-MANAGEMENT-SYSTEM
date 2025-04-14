# CAB-BOOKING-MANAGEMENT-SYSTEM
This Online Cab Booking System provides a seamless platform for customers to search, book, and manage cab rides. The system includes three main panels: Admin Panel, Driver Panel, and Customer Panel. Customers can register, book rides, cancel bookings, and view booking history. 


# 🚖 Online Cab Booking System in PHP MySQL

A simple web-based Cab Booking System developed using **PHP** and **MySQL**, designed to help users book cabs online. This project features client-side interactions along with fully functional **Admin** and **Driver** dashboards. Ideal for beginner developers and IT students looking to understand real-life project implementations using PHP.
The Online Cab Booking System is a web-based application developed using PHP and MySQL, aimed at digitizing and streamlining the process of booking cabs online. It allows customers to register, search for available cabs, book rides, and manage their trip history. Meanwhile, drivers can manage their assigned trips, update the trip status, and view their booking history. The admin panel provides full control over system settings, cab and driver management, customer records, and ongoing bookings.

This project is designed to mimic real-world cab booking platforms like Uber or Ola in a simplified format. It offers a hands-on learning experience for students and beginner developers looking to understand web-based CRUD operations, user role management, and dynamic database interaction using PHP and MySQL.

🎯 Objectives
To create a centralized cab booking system for customers, drivers, and administrators.

To automate the cab assignment and booking confirmation process.

To provide real-time trip status updates to users.

To manage driver profiles, cab details, and system configurations from a single admin dashboard.

🌐 Live System Workflow
Customer registers and logs in to book a cab.

Admin assigns drivers and manages the fleet of vehicles.

Driver accepts or rejects booking requests and updates trip statuses.

The system keeps all users informed through real-time dashboard updates and status tracking.

## 🧾 Features

- Customer Registration & Login
- View & Cancel Booking History
- Search Available Cabs
- Book Cabs (Pickup & Drop-off)
- Driver Panel: Accept & Update Trip Status
- Admin Panel: Full Control Over Drivers, Cabs & Bookings
- Manage Vehicle Categories
- System Settings & Branding
- Responsive UI with Bootstrap

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: PHP (v7.4 recommended)
- **Database**: MySQL
- **Local Server**: XAMPP

---

## 📂 How to Run the Project

1. **Install XAMPP**  
   Ensure PHP version is 7.4.

2. **Setup the Project**
   - Extract the ZIP file.
   - Copy the extracted folder into `C:\xampp\htdocs\`.

3. **Import the Database**
   - Start Apache & MySQL from XAMPP Control Panel.
   - Visit `http://localhost/phpmyadmin`.
   - Create a new database (use the name from `01 LOGIN DETAILS & PROJECT INFO.txt`).
   - Import the `.sql` file located inside the `DATABASE FILE` folder.

4. **Launch the Application**
   - Open your browser and go to:  
     `http://localhost/cms/`  
     Replace `cms` with the actual name of the folder.

5. **Login Details**
   - All login credentials are in `01 LOGIN DETAILS & PROJECT INFO.txt`.

---

## 👤 Panels Overview

### Admin Panel
- Manage Cabs, Drivers & Categories
- Monitor All Bookings
- Set Trip Status
- Update System Settings & Branding

### Driver Panel
- Login with Driver Credentials
- Accept Booking Requests
- Set Trip Status (Picked / Dropped)
- View Booking History

### Customer Panel
- Register/Login
- Search & Book Cabs
- Cancel Pending Bookings
- View Booking History

---

## 📄 Project Information

- **Project Name**: Online Cab Booking System PHP
- **Language Used**: PHP
- **Database**: MySQL
- **Recommended PHP Version**: 7.4
- **Type**: Web Application
- **Developer**:  Roopchandra ([@roopchandra06](https://github.com/roopchandra777))

---

## 🔑 Login Credentials Format

**Admin Login**
- **Username**: admin
- **Password**: 12345

**Driver Login**
- **Username**: DRIVER001 (Example registration code)
- **Password**: driver123

**Customer Login**
- **Username**: Registered Email
- **Password**: Created at registration
## 📘 License
For correct passwaord cantact me -: roopchandrapal06@gmail.com , roopchandrapalr@gmail.com, roopchandra777@gmail.com
This project is intended for **educational purposes only**. Feel free to use, learn, and modify it. Please credit the original developer.

---


## 📦 Folder Structure

```bash
CabBookingSystem/
├── admin/                  # Admin dashboard
├── customer/               # Customer portal
├── driver/                 # Driver portal
├── assets/                 # CSS/JS/images
├── includes/               # PHP functions and database connection
├── DATABASE FILE/          # MySQL .sql file
├── 01 LOGIN DETAILS & PROJECT INFO.txt
├── index.php
└── README.md

##📎 Sample Use Case
A customer signs up and books a ride.

The admin gets notified and assigns a driver.

The driver logs in, accepts the ride, picks up the customer, and marks the trip as "Dropped Off".

The system records all trip history for all users.


📜 License
This project is open-source and free to use for learning, personal, and academic purposes. Commercial redistribution is prohibited without permission.

✅ Notes
Customers cannot book a cab already marked as "Booked" or "On Trip"

Drivers require an admin-generated login (Registration Code + Password)

Admin has the power to deactivate any user or driver

Designed for clarity, responsiveness, and ease of use using Bootstrap

Best of Luck all of you.
