# Apartment Booking & Rent Tracking System

## Overview

The Apartment Booking & Rent Tracking System is a MySQL-based database project designed to organize apartment management, tenant information, rental bookings, rent payments, and property maintenance.

The system provides a centralized relational database for managing property operations and generating useful reports through SQL queries.

## Features

- **User Management:** Maintain user profiles and account information.
- **Apartment Management:** Store apartment details, locations, and property status.
- **Unit Management:** Track individual units, rental prices, and availability.
- **Tenant Management:** Maintain tenant profiles and related information.
- **Booking Management:** Record rental bookings, lease dates, and booking status.
- **Rent Tracking:** Store payment records, payment methods, and late fees.
- **Staff Management:** Maintain staff details, roles, and salaries.
- **Maintenance Tracking:** Record maintenance requests, priorities, and statuses.
- **Property Inspections:** Maintain inspection records and results.
- **Audit Logging:** Track administrative activities for accountability.
- **SQL Reporting:** Generate reports for vacancies, revenue, bookings, staff expenses, and maintenance tasks.

## Database Structure

The database contains ten main relational tables:

1. Users
2. Apartments
3. Units
4. Tenants
5. Bookings
6. Rent_Payments
7. Staff
8. Maintenance_Requests
9. Inspections
10. Audit_Log

The project uses primary keys, foreign keys, relational constraints, and normalization up to Third Normal Form (3NF), as described in the project documentation.

## Technologies Used

- MySQL
- SQL (DDL and DML)
- Relational Database Design
- Entity-Relationship Diagrams (ERD)
- SQL JOINs and reporting queries

## Reports and Analysis

The database supports queries for:

- Apartment availability and vacant units
- Apartment locations and rental prices
- Tenant contact information
- Booking status and lease tracking
- Rent payment status and revenue summaries
- Staff salary expenditure
- High-priority maintenance requests
- Revenue by payment method

## Project Files

- `apartment rental system.sql` — SQL database schema, data, and queries.
- `final documentation apartment rental system.docx` — Detailed project documentation.

## How to Use

1. Install MySQL Server and a compatible SQL client, such as MySQL Workbench.
2. Open the SQL file in your SQL client.
3. Review the script and execute it in the appropriate MySQL environment.
4. Run the included queries to explore the database and generate reports.

**Note:** Review the SQL script before execution and ensure that the required database privileges are available.

## Future Improvements

- Develop a web-based interface for property managers and tenants.
- Integrate online rent payments and payment notifications.
- Add automated utility tracking and predictive maintenance features.

## Academic Project

**Course:** Database Management System  
**Department:** Computer Science  
**University:** University of South Asia