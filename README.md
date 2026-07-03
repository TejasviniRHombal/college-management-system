# College Management System

A backend **College Management System** built using **Node.js** and **MySQL**. This project demonstrates MySQL database connectivity with Node.js and performs essential database operations such as creating databases, managing faculty, library, and student marks records, and executing SQL queries using the `mysql2` package.

---

##  Overview

The College Management System is a simple backend application that showcases the integration of Node.js with MySQL. It performs database creation, table creation, data insertion, retrieval, and deletion for different college entities.

This project is intended for learning and understanding basic database management and backend development concepts.

---

##  Features

* Connect to a MySQL database
* Create a college database
* Create Faculty, Library, and Marks tables
* Insert records into each table
* Retrieve faculty, library, and student marks data
* Delete records based on specified conditions
* Display query results in the terminal

---

##  Tech Stack

| Technology       | Purpose              |
| ---------------- | -------------------- |
| Node.js          | Backend Runtime      |
| JavaScript (ES6) | Programming Language |
| MySQL            | Relational Database  |
| mysql2           | MySQL Driver         |

---

##  Project Structure

```text
College-Management-System/
│
├── dbcollege.js          # Main application file
├── .gitignore
├── README.md
└── outputs.pdf         # Sample output (Optional)
```

---

## Database Schema

### Faculty

| Column      | Type        |
| ----------- | ----------- |
| FacultyName | VARCHAR(25) |
| Subject     | VARCHAR(25) |
| Experience  | VARCHAR(25) |

### Library Details

| Column      | Type        |
| ----------- | ----------- |
| LID         | INT         |
| LibraryName | VARCHAR(25) |

### Marks

| Column      | Type        |
| ----------- | ----------- |
| StudentName | VARCHAR(25) |
| English     | INT         |
| Maths       | INT         |
| Science     | INT         |

---

##  Prerequisites

Before running the project, ensure you have:

* Node.js
* MySQL Server
* npm

---

##  Database Configuration

Update your MySQL credentials in the project file.

```javascript
const mysql = require("mysql2");

const connection = mysql.createConnection({
    host: "localhost",
    user: "root",
    password: "YOUR_PASSWORD",
    database: "college2"
});
```

---

##  Run the Project

```bash
node college.js
```

---

##  SQL Operations Performed

### Database Operations

* Create College Database

### Table Operations

* Create Faculty Table
* Create Library Details Table
* Create Marks Table

### Data Operations

* Insert Faculty Records
* Insert Library Records
* Insert Student Marks
* Retrieve Data
* Delete Records
* Display Updated Records

---

## Concepts Demonstrated

* MySQL Database Connectivity
* SQL Queries
* Database Creation
* Table Creation
* INSERT Operations
* SELECT Operations
* DELETE Operations
* CRUD Fundamentals
* Callback Functions
* Backend Development with Node.js

---

##  Future Enhancements

* Update existing records
* Search students by name
* Calculate total and average marks
* Add student and faculty management
* Implement login and authentication
* Build REST APIs using Express.js
* Develop a web-based frontend

---

##  Author

**Tejasvini R Hombal**
