# 📚 Library Management System – SQL Project

This project is a relational database design and implementation of a **Library Management System** using SQL. It aims to simulate the management of books, members, employees, branches, and transactions such as issuing and returning books.

## 📂 Project Structure

The project contains a single SQL script file:
- `Library Management System.sql`: Includes SQL statements to create tables, insert sample data, and perform various operations.

## 🛠️ Features Implemented

- 📁 **Database & Table Creation**:
  - `branch`, `employees`, `members`, `books`, `issued_status`, `return_status`
- 🧾 **Data Insertion**:
  - Pre-populated sample data for testing and demonstration
- 🔄 **Transactions**:
  - Issue and return books with tracking
- 🔧 **Modifications**:
  - Insert new records, update member info, delete issued records
- 📊 **Reports & Queries**:
  - Most issued books
  - Total rental income by category
  - Members with multiple issues
  - Books not returned
  - Employees with manager details
  - Summary tables (CTAS)

## 📌 Sample SQL Tasks

- **Insert** new book and member records
- **Update** a member's address
- **Delete** issued records
- **Joins** and **aggregations** for reporting
- **CTAS**: Create tables with derived data
- **Date filtering**: Recent registrations, issues

## ✅ Tasks

### Task 1:INSERT INTO books(isbn, book_title, category, rental_price, status, author, publisher)
VALUES
('978-1-60129-456-2', 'To Kill a Mockingbird', 'Classic', 6.00, 'yes', 'Harper Lee', 'J.B. Lippincott & Co.');

