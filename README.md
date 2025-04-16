

# Student Management System

A simple console-based Student Management System built using Python and MySQL. This project enables you to perform CRUD operations such as adding, viewing, updating, and deleting student records.

---

## Features

- Add new student
- View a specific student's data
- Update existing student information
- Delete a student record
- View all student records
- Menu-driven interface for easy interaction

---

## Technologies Used

- Python 3.x
- MySQL (pymysql connector)

---

## Installation & Setup

1. Install Required Python Package
   Open a terminal and run:
   ```bash
   pip install pymysql

2. Ceate the MySQL Database:
   Log into your MySQL server and create the database.

3. Execute the python file:
   python student_mgmt_system.py

   
## Database schema:
   
   Column    | Data Type | Description
   stud_id   | INT       | Primary key
   name      | VARCHAR   | Student name
   email     | VARCHAR   | Email address
   contact   | BIGINT    | Contact number
   
   
## Sample output:
   
   ----- Welcome to Student Management System -----
   
   1. Add Student  
   2. Display Student Data  
   3. Modify Existing Student Record  
   4. Remove Student  
   5. Fetch All Student Records  
   6. Exit  
