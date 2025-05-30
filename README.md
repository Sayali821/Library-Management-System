# 📚 Library Management System – SQL Project

![BannerLMS]()

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

![Insert new record](https://github.com/Sayali821/Library-Management-System/blob/af7548f4f90089f7fcd5d28bbd0e072a45b24d6f/Images/Insert%20new%20record.png)

### Task 2: Update an Existing Member's Address

![Update new record](https://github.com/Sayali821/Library-Management-System/blob/34874060768a1a12fcecc070b326fc665473b137/Images/Update%20new%20record.png)

### Task 3: Delete a Record from the Issued Status Table. Objective: Delete the record with issued_id = 'IS121' from the issued_status table.

![Deleting record](https://github.com/Sayali821/Library-Management-System/blob/34874060768a1a12fcecc070b326fc665473b137/Images/Deleting%20record.png)

### Task 4: Retrieve All Books Issued by a Specific Employee -- Objective: Select all books issued by the employee with emp_id = 'E101'.

![Retrive data of user](https://github.com/Sayali821/Library-Management-System/blob/34874060768a1a12fcecc070b326fc665473b137/Images/Retrive%20data%20of%20user.png)

### Task 5: List Members Who Have Issued More Than One Book -- Objective: Use GROUP BY to find members who have issued more than one book.

![Count more then 1](https://github.com/Sayali821/Library-Management-System/blob/34874060768a1a12fcecc070b326fc665473b137/Images/Count%20more%20then%201.png)

### Task 6: Create Summary Tables: Used CTAS to generate new tables based on query results - each book and total book_issued_cnt**

![Book issued count](https://github.com/Sayali821/Library-Management-System/blob/34874060768a1a12fcecc070b326fc665473b137/Images/Book%20issued%20count.png)

### Task 7. Retrieve All Books in a Specific Category

![Book of specific category](https://github.com/Sayali821/Library-Management-System/blob/34874060768a1a12fcecc070b326fc665473b137/Images/Book%20of%20specific%20category.png)

### Task 8: Find Total Rental Income by Category:

![Income by category](https://github.com/Sayali821/Library-Management-System/blob/34874060768a1a12fcecc070b326fc665473b137/Images/Income%20by%20category.png)


## 🧰 Technologies Used

- SQL (compatible with MySQL)
- SQL DDL, DML, DQL, and JOIN operations
