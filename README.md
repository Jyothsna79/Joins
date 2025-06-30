# Joins
# Task 5: SQL Joins (Inner, Left, Right, Full)

## 📌 Objective

The goal of this task is to understand and practice combining data from multiple tables using different types of SQL joins: INNER, LEFT, RIGHT, and FULL.

---

## 🛠 Tools Required

- *DB Browser for SQLite* (for .sqlite DB files)
- *MySQL Workbench* (if using MySQL)

---

## 🧱 Table Structure

We use two related tables:

### Customers

| Column      | Type   | Description       |
|-------------|--------|-------------------|
| CustomerID  | INT    | Primary key       |
| Name        | TEXT   | Customer's name   |
| Email       | TEXT   | Customer's email  |

### Orders

| Column      | Type   | Description          |
|-------------|--------|----------------------|
| OrderID     | INT    | Primary key          |
| CustomerID  | INT    | Foreign key          |
| Product     | TEXT   | Ordered product name |
| OrderDate   | DATE   | Date of order        |

---

