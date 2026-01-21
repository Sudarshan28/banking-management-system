# Banking Management System (MySQL)

A relational database project built using **MySQL** to simulate core banking operations such as customer management, account handling, and transaction tracking.  
The project demonstrates practical use of **DBMS concepts** including schema design, constraints, joins, indexing, and analytical queries.

---

## 📌 Features

- Customer management with unique customer records
- Multiple bank accounts per customer
- Transaction history tracking (Deposit / Withdrawal)
- Relational schema using primary and foreign keys
- JOIN-based queries for reporting and analysis
- Aggregation queries for customer balance insights

---

## 🛠️ Tech Stack

- **Database:** MySQL
- **Tool:** MySQL Workbench
- **Concepts Used:**  
  - Relational schema design  
  - Primary & Foreign keys  
  - Indexing  
  - JOIN operations  
  - GROUP BY & aggregate functions  

---

## 🗂️ Database Schema

The database consists of the following tables:

- **Customers**
  - Stores customer details (name, email, phone)
- **Accounts**
  - Stores account type and balance for each customer
- **Transactions**
  - Stores transaction history linked to accounts

Schema relationships are implemented using foreign keys to maintain data integrity.

---

## 🔍 Sample Queries Implemented

- Fetch transaction history for each account
- Retrieve customer-wise account details
- Calculate total balance per customer using aggregation
- Sort transactions by date

---

## 📷 Screenshots

Screenshots of:
- Database schema
- Table data
- Query execution and result output  

are available in the **screenshots/** folder.

---

## 🚀 How to Run

1. Open **MySQL Workbench**
2. Create a new SQL tab
3. Run the SQL script from the `sql/` folder
4. Execute the provided queries to view results

---

## 📌 Learning Outcome

This project strengthened my understanding of:
- Real-world database modeling
- Writing optimized SQL queries
- Using joins and aggregations for data analysis
- Working with MySQL Workbench in a structured way

---

## 🔗 Author

**Sudarshan Gupta**  
GitHub: https://github.com/Sudarshan28

##ScreenShots
## Customers & Accounts Table
<img width="1440" height="900" alt="Screenshot 2026-01-21 at 3 19 13 PM" src="https://github.com/user-attachments/assets/7e90f5e7-a75c-4187-9666-4a6ae06d240a" />

## Transactions & Query Results
<img width="1440" height="900" alt="Screenshot 2026-01-21 at 3 19 59 PM" src="https://github.com/user-attachments/assets/d17fa389-14eb-42f6-b6d5-62c1a91abbe0" />

## Balance Summary Report
<img width="1440" height="900" alt="Screenshot 2026-01-21 at 3 56 04 PM" src="https://github.com/user-attachments/assets/a02afa72-3077-431a-bd55-4ae36d78a93f" />


