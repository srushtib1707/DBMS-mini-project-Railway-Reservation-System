Railway Reservation System - DBMS Mini Project

Project Overview

The Railway Reservation System is a database management project designed to automate train ticket reservations. This system allows users to book, cancel, and check ticket status while enabling administrators to manage train details efficiently.

Features

1. Train Information Management

Stores train names, schedules, and availability.

Admins can update train details such as numbers, schedules, and routes.

2. Ticket Booking & Reservation

Users can check seat availability and book tickets.

Each booking is assigned a unique PNR number.

Generates a reservation ticket with travel details.

3. Reservation Status & Cancellation

Passengers can check PNR status (Confirmed, RAC, or Waiting List).

Cancel tickets and receive a cancellation receipt with fare deductions.

4. Report Generation

Generates reservation charts and reports for admin use.

Technology Stack

Frontend:

HTML, CSS, Bootstrap - For a responsive and user-friendly interface.

JavaScript - Enhances interactivity.

Backend:

PHP - Server-side processing.

MySQL - Database to store user and train information.

Project Structure

railway-reservation/
│
├── src/                      # PHP backend files
│   ├── booking.php           # Handles booking logic
│   ├── cancel.php            # Handles cancellations
│   ├── check_status.php      # PNR status check
│
├── web/                      # Frontend files
│   ├── index.html            # Homepage
│   ├── booking.html          # Booking portal
│   ├── status.html           # PNR status check
│
├── static/                   # Static files (CSS, JS, images)
├── railres.sql               # Database schema

Usage

Users can book tickets, check PNR status, and cancel reservations.
Admins can manage train schedules and seat availability.


Conclusion
The Railway Reservation System is an effective DBMS-based project that simplifies train ticket booking and management. By integrating PHP and MySQL, it provides a seamless experience for both passengers and administrators, ensuring an efficient and automated railway reservation process.
