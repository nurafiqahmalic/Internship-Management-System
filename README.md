# Internship-Management-System

This GitHub repository contains the code for the database management system (DBMS) used in the ISIM (Information Systems for Internship Management) project. The DBMS is implemented using PHP and MySQL, with PHPMyAdmin as the database management tool.

## Overview

The DBMS is responsible for managing the database operations required for the ISIM project. It handles database connections, query execution, and data manipulation tasks.

## Technologies Used

- PHP
- MySQL
- PHPMyAdmin

## Features

1. **DBController Class:** Manages database connections and executes SQL queries.
   - `connectDB()`: Establishes a connection to the MySQL database.
   - `runQuery($query)`: Executes a SELECT query and returns the result set.
   - `numRows($query)`: Returns the number of rows returned by a SELECT query.
   - `updateQuery($query)`: Executes an UPDATE query.
   - `insertQuery($query)`: Executes an INSERT query.
   - `deleteQuery($query)`: Executes a DELETE query.

## Configuration

To use the DBMS, follow these steps:

1. Ensure that Xampp, PHP and MySQL are installed on your server.
2. Import the database schema into PHPMyAdmin.
3. Update the database connection details in the `DBController` class (`host`, `user`, `password`, `database`).

## Usage

# Step 1 (Homepage)
<div id="header" align="center">
 <img src="https://imgtr.ee/images/2024/04/02/a014e1b4edcc16c4642c71c88320a8a2.png" alt="a014e1b4edcc16c4642c71c88320a8a2.png" />
</div>
