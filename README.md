# Hotel-Management-System

# Hotel Management System
## Overview
The Hotel Management System is a comprehensive web-based application designed to streamline hotel operations. Built using HTML, CSS, PHP, and MySQL, it integrates frontend and backend functionalities, supports payment processing using APIs, and includes an admin dashboard for efficient management of rooms, bookings, and guests.

## Features
## 1. Payment Processing
Implemented Square Pay API for seamless and secure payment processing.
## 2. Enhanced Performance
Optimized API integration, reducing response time by 40%, enhancing the overall user experience.
## 3. Database Management
Designed efficient database schemas using SQL on XAMPP, ensuring smooth data handling and retrieval.
## 4. Admin Dashboard
Developed a powerful admin interface for:
Managing rooms and their availability.
Handling bookings efficiently.
Monitoring and managing guest information.
Technologies Used
Frontend: HTML, CSS
Backend: PHP
Database: MySQL (on XAMPP)
API: Square Pay API for payment integration
Installation and Setup
Prerequisites
Install XAMPP for running the server and database.
A modern web browser to test the system.
Steps to Install
Clone the Repository

## bash
Copy code
git clone https://github.com/AyushRaut01/Hotel-Management-System.git
cd Hotel-Management-System
Setup Database

## Open phpMyAdmin in XAMPP.
## Create a database named hotel_management.
## Import the provided SQL script (database.sql) to set up tables and initial data.
## Configure the Application

## Update the database configuration in config.php:
php
Copy code
$db_host = 'localhost';
$db_user = 'root';
$db_password = '';
$db_name = 'hotel_management';
Start the Application

## Place the project folder inside XAMPP's htdocs directory.
## Start MySQL services from the XAMPP control panel.
## Access the system at http://localhost/Hotel-Management-System.

# Usage
## User Side:
Search and book available rooms.
Process payments securely via Square Pay API.
View booking history.
## Admin Side:
Manage room availability and pricing.
Oversee guest and booking details.
Generate reports for business insights.
