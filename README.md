College Lab Booking System
Overview

The Lab Booking System is a web-based application developed for colleges to manage and streamline the process of booking computer labs and classrooms.
It allows teachers to book available labs, view existing schedules, and avoid scheduling conflicts. The system also includes features for administrators to manage lab timetables, view bookings, and ensure efficient utilization of institutional resources.

Objective

To automate the manual lab booking process in colleges by creating a centralized online platform that ensures efficient lab utilization, avoids double bookings, and provides transparency for all users.

Features

Teacher login with authentication.

Real-time availability of labs and time slots.

Organized block and lab selection (Blocks A–F with multiple labs).

Supports both fixed timetable slots and flexible bookings.

Automatic deletion of expired bookings.

Email notifications to HODs using PHPMailer when a booking is made.

Smart search functionality to find available labs based on block, type, day, and time.

Admin dashboard for full control over bookings and timetables.

Database integration to store user details, bookings, and schedules.

Technologies Used

Frontend: HTML, CSS, JavaScript, AJAX

Backend: PHP (XAMPP environment)

Database: MySQL

Email Integration: PHPMailer

Server Environment: Apache (via XAMPP)

Installation & Setup

Download or clone the repository:

git clone https://github.com/yourusername/labbooking.git


Extract the files into your local server directory (for example, htdocs in XAMPP).

Create a MySQL database named lab_booking.

Import the provided SQL file (lab_booking.sql) into phpMyAdmin.

Configure email settings (sender address and app password) inside PHPMailer files.

Start Apache and MySQL using XAMPP Control Panel.

Open the application in your browser:

http://localhost/labbooking/

Usage

For Teachers:

Log in using valid credentials.

Check lab availability and make bookings.

Receive email confirmation after booking.

For Admins:

Manage labs, blocks, and timetables.

View, modify, or delete bookings.

Send email notifications to HODs.

Database Structure

users – Stores teacher credentials and department details.

hods – Contains HOD email and department data for notifications.

bookings – Records lab booking details.

fixed_bookings – Contains predefined timetable slots.

Future Enhancements

Student portal for viewing lab availability.

Integration for classroom and interactive room bookings.

Calendar-based view for easier schedule visualization.

AI-based system for conflict detection and automated suggestions.

Developer Information

Project Title: College Lab Booking System
Developed by: Dhruva D
College Name: Vidya Vardhaka College of Engineering 
Role: Full Stack Web Developer
Technologies Used: PHP, MySQL, HTML, CSS, JavaScript
Year: 2025
