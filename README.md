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

# Student Homepage
<div id="header" align="center">
 <img src="https://imgtr.ee/images/2024/04/02/fc798a77e522fd9ed0b18636583a5851.png" alt="fc798a77e522fd9ed0b18636583a5851.png" border="0" />
</div>

1. Click on Register Button and fill in the information
2. Proceed on Login and upload the resumes
3. Your resumes has succesfully sent to your desired company

# Admin Homepage
<div id="header" align="center">
 <img src="https://imgtr.ee/images/2024/04/02/baf9d6ddb160057e5ab17b372df2b198.png" alt="baf9d6ddb160057e5ab17b372df2b198.png" border="0" />
</div>

1. Click "Admin" button and insert "admin" as both username and password
2. The sidebar consists of: Home, Accounts, Upload Internships, Student Profile, Options

## Database (db_issm)

<div id="header" align="center">
 <img src="https://imgtr.ee/images/2024/04/02/3387dee5cb1167651988a93452bef51c.png" alt="3387dee5cb1167651988a93452bef51c.png" border="0" />
</div>
