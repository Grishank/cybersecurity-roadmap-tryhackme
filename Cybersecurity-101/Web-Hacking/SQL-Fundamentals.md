# 🗄️ SQL Fundamentals — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/SQL-Fundamentals-banner.png?raw=true" alt="SQL Fundamentals Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Web Hacking Fundamentals  
**Difficulty:** Easy  
**Date Completed:** May 2026  
**Room Link:** https://tryhackme.com/room/sqlfundamentals  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

The **SQL Fundamentals** room introduces the foundations of databases and SQL queries used in modern applications.

The room focuses on:
- Databases and tables
- SQL syntax
- CRUD operations
- Clauses and operators
- Functions
- Query structure
- Database interaction basics

This room builds the foundation required for:
- Database analysis
- SQL Injection understanding
- Web application security
- Backend data interaction
- SOC investigation workflows

---

# 🎯 Learning Objectives

- Understand how databases work
- Learn SQL syntax basics
- Create and manage tables
- Perform CRUD operations
- Use clauses and operators
- Work with SQL functions
- Understand how applications interact with databases

---

# 🌍 Task 1 — Introduction

Introduced SQL and relational databases.

## Key Takeaways

- SQL stands for Structured Query Language
- Databases store structured information
- Applications use SQL to interact with data

---

# 🗄️ Task 2 — Databases 101

Learned the structure of relational databases.

## Core Concepts

| Concept | Description |
|---|---|
| Database | Collection of organized data |
| Table | Stores rows and columns |
| Row | Single record |
| Column | Specific attribute |

---

# 💻 Task 3 — SQL

Introduced SQL query syntax and database interaction.

## Basic Query Example

```sql
SELECT * FROM users;
```

## Common SQL Actions

- Retrieve data
- Insert records
- Update information
- Delete records

---

# 📦 Task 4 — Database and Table Statements

Learned how databases and tables are created and managed.

## Example Statements

### Create Database

```sql
CREATE DATABASE company;
```

### Create Table

```sql
CREATE TABLE employees (
    id INT,
    name VARCHAR(100)
);
```

---

# 🔄 Task 5 — CRUD Operations

Covered the four main database operations.

| Operation | Purpose |
|---|---|
| CREATE | Add data |
| READ | Retrieve data |
| UPDATE | Modify data |
| DELETE | Remove data |

---

## CRUD Examples

### Insert Data

```sql
INSERT INTO users VALUES (1, 'admin');
```

### Read Data

```sql
SELECT * FROM users;
```

### Update Data

```sql
UPDATE users SET name='administrator' WHERE id=1;
```

### Delete Data

```sql
DELETE FROM users WHERE id=1;
```

---

# 📑 Task 6 — Clauses

Learned how SQL clauses filter and organize results.

## Common Clauses

| Clause | Purpose |
|---|---|
| WHERE | Filter results |
| ORDER BY | Sort results |
| LIMIT | Restrict output |
| GROUP BY | Group records |

---

## Example

```sql
SELECT * FROM users
WHERE role='admin'
ORDER BY id DESC
LIMIT 5;
```

---

# ⚙️ Task 7 — Operators

Explored SQL comparison and logical operators.

## Common Operators

| Operator | Purpose |
|---|---|
| = | Equal |
| != | Not equal |
| > | Greater than |
| < | Less than |
| AND | Both conditions true |
| OR | One condition true |

---

# 🧮 Task 8 — Functions

Learned how SQL functions process and manipulate data.

## Common SQL Functions

| Function | Purpose |
|---|---|
| COUNT() | Count rows |
| AVG() | Calculate average |
| MAX() | Highest value |
| MIN() | Lowest value |

---

## Example

```sql
SELECT COUNT(*) FROM users;
```

---

# 🛡️ SOC / Blue Team Perspective

Understanding SQL is important because:
- Many attacks target databases
- Analysts investigate database-related breaches
- SQL Injection is one of the most common web vulnerabilities
- Logs often contain SQL-related indicators

Common attacks involving SQL:
- SQL Injection
- Database enumeration
- Unauthorized data access
- Credential dumping
- Data manipulation

---

# 🧾 Key Concepts Learned

- Database structure
- SQL syntax
- CRUD operations
- Clauses
- Operators
- SQL functions
- Query execution
- Data management basics

---

# 💬 Key Takeaway

> “Understanding SQL is essential in cybersecurity because databases store critical organizational data and are frequent targets during attacks.”

---

# 🚀 Next Steps

- Learn SQL Injection basics
- Study database security concepts
- Practice SQL queries hands-on
- Learn Burp Suite database testing
- Explore OWASP Top 10 database vulnerabilities
- Continue Web Hacking fundamentals
