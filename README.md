# Auto-Taxi Stand Management System

This project is a **PHP-based application** designed to manage and streamline the operations of an auto/taxi stand. It provides an efficient way to handle bookings, allocate vehicles, and manage drivers and passengers. The system aims to simplify stand management, improve efficiency, and provide better services to passengers.

---

## Features

- **User Management**: 
  - Registration and login for drivers, passengers, and administrators.
- **Booking Management**:
  - Passengers can book autos or taxis.
  - View booking history and status.
- **Vehicle Allocation**:
  - Automates the allocation of vehicles to passengers based on availability.
- **Driver Management**:
  - Tracks driver availability and schedules.
- **Admin Panel**:
  - Manage users, bookings, and vehicle data.
  - Generate reports for analytics and decision-making.
- **Real-Time Updates**:
  - Keeps track of vehicle availability and booking statuses in real time.

---

## Prerequisites

Before running this project, ensure the following software is installed:

1. **Web Server**: XAMPP, WAMP, or any PHP-supported server.
2. **PHP**: Version 7.4 or higher.
3. **Database**: MySQL.

---

## Installation

1. **Download or Clone the Repository**:
   ```bash
   git clone https://github.com/Adarash13/Taxi-Management.git
   cd Taxi-Management
   ```

2. **Move Files to Server**:
   - Copy the project folder to your web server's root directory (e.g., `htdocs` for XAMPP).

3. **Import the Database**:
   - Open **phpMyAdmin**.
   - Create a database (e.g., `auto_taxi_stand`).
   - Import the provided SQL file (likely named `database.sql` or similar) into the database.

4. **Update Configuration**:
   - Open the `config.php` file (if available).
   - Set the database connection parameters:
     ```php
     $host = 'localhost';
     $user = 'root';
     $password = '';
     $database = 'auto_taxi_stand';
     ```

5. **Run the Application**:
   - Start your web server and navigate to the project directory in your browser:
     ```
     http://localhost/Auto-Taxi-Stand-Management-System/
     ```

---

## Usage

1. **Admin**:
   - Log in to the admin panel to manage users, vehicles, and bookings.
2. **Drivers**:
   - View assigned bookings and update availability.
3. **Passengers**:
   - Book autos/taxis and check booking statuses.

---

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Server**: Apache (XAMPP/WAMP)

---

## Future Enhancements

- **Online Payment Integration**.
- **GPS Tracking for Vehicles**.
- **Mobile App Compatibility**.
- **Multi-Language Support**.

---

## Contributing

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

---

## Contact
**Adarsh Sainath H**

For any queries, reach out to [sainathadarsh13@gmail.com].
