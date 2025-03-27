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

## Database Setup

1. **Create the Database**:
   ```sql
   CREATE DATABASE emp;
