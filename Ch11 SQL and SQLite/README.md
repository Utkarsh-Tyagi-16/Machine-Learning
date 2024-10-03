# 🗄️ SQL and SQLite

### Overview
SQL (Structured Query Language) is a powerful standard language designed for managing and manipulating relational databases. It is essential for querying, updating, and managing databases. SQLite, on the other hand, is a lightweight, self-contained, serverless, and zero-configuration database engine, often used in mobile devices and embedded systems. It's perfect for projects where ease of use, simplicity, and portability are important.

---

### 🔍 What This Repository Covers

- **SQL Basics**:  
  - What is SQL?  
  - Data definition and manipulation.  
  - Common SQL commands like `SELECT`, `INSERT`, `UPDATE`, and `DELETE`.
  
- **SQLite Overview**:  
  - How to set up SQLite.  
  - Differences between SQLite and other relational databases.  
  - Example of creating, querying, and managing an SQLite database.

- **SQL + SQLite in Practice**:
  - Sample database and table creation in SQLite.
  - Writing SQL queries to interact with SQLite databases.
  - Best practices when working with SQL and SQLite together.

---

### 🛠️ How to Set Up

1. **Install SQLite**:  
   SQLite doesn't require a separate server, so just download it from the official [SQLite website](https://sqlite.org/download.html).
   
2. **Database Setup**:  
   Use the following SQL script to create your first database:
   ```sql
   CREATE TABLE students (
      id INTEGER PRIMARY KEY,
      name TEXT NOT NULL,
      grade INTEGER
   );
3. **Start Querying**:
Use SQL commands like SELECT, INSERT, and UPDATE to manage your database.


### 🧠 Concepts You’ll Learn

- **Data Management**:
  Learn how to create, update, and delete data.

- **Relational Concepts**:
  Understand the relationships between different data points using foreign keys.

- **Efficient Querying**:
  Writing optimized queries using JOIN, GROUP BY, and HAVING.

