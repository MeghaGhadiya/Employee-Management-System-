# Employee Management System

A Python-based **Employee Management System** that uses a **MySQL database** for performing CRUD operations (Create, Read, Update, Delete). The system allows users to manage employee records with ease.

## Features

- **Add Employee**: Insert a new employee's details into the database.
- **Remove Employee**: Delete an employee's record from the database.
- **Promote Employee**: Update an employee's salary based on a promotion.
- **Display Employees**: View all employee records from the database.

## Tech Stack

- **Python**: Programming language for the application logic.
- **MySQL**: Relational database to store employee records.
- **MySQL Connector**: Python library to interact with the MySQL database.

## Requirements

Before running the project, ensure you have the following installed:

1. **Python 3.x**: [Download Python](https://www.python.org/)
2. **MySQL Server**: [Download MySQL](https://dev.mysql.com/downloads/mysql/)
3. **Required Python Libraries**:
   - Install `mysql-connector-python`:
     ```bash
     pip install mysql-connector-python
     ```

Database Setup
Follow these steps to set up the database:

Open MySQL Workbench or any MySQL client.

Create the database using the following command:

sql
CREATE DATABASE emp;
Use the database:

sql
USE emp;
Create the employees table:

sql
CREATE TABLE employees (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    position VARCHAR(255) NOT NULL,
    salary DECIMAL(10, 2) NOT NULL
);
How to Run
Clone or download the repository.

Open the project in a Python IDE or Jupyter Notebook.

Update the connection details in the Python script to match your MySQL setup:

Host: Your MySQL server address (e.g., localhost).

User: Your MySQL username.

Password: Your MySQL password.

Database: emp

Run the Python script and interact with the menu-driven application.
