# Salon Management Database

This repository contains a PostgreSQL database dump for a salon management system. The dump includes the schema definition as well as sample data.

## Database Overview

The database consists of three main tables:

1. **Appointments**: Stores information about appointments made by customers.
2. **Customers**: Contains details about salon customers.
3. **Services**: Lists the various services offered by the salon.

Each table is designed with appropriate columns and constraints to maintain data integrity.

## Usage

1. **Database Setup**:
   - Ensure PostgreSQL is installed on your system.
   - Create a new database named "salon".

2. **Import Database Dump**:
   - Use the provided SQL script to create tables and insert sample data into the "salon" database.

3. **Exploring Data**:
   - Once imported, you can query the tables to view appointments, customer information, and available services.

## Sample Queries

Here are some example queries you can run:

```sql
-- View all appointments
SELECT * FROM appointments;

-- Get details of all customers
SELECT * FROM customers;

-- List available services
SELECT * FROM services;
