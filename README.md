# 📚 Online Bookstore Database Analysis (PostgreSQL)

![image alt](https://github.com/Ayan-baksi/Online-Bookstore-SQL-project/blob/main/ONLINE%20BOOKSTORE%20VIEWS.png?raw=true)
This project showcases a well-structured **relational database design** and a set of **real-world SQL queries** built for an **online bookstore** platform. It covers everything from basic retrievals to complex aggregations, CTEs, and business logic insights — developed using **PostgreSQL**.

---

## 📌 Project Objective

To simulate a working e-commerce bookstore backend and extract key **business insights** using advanced SQL queries, such as:

- Sales trends
- Inventory status
- Customer behavior
- Revenue analysis
- Product performance

---

## 🗂️ Dataset Overview

The project uses three CSV files representing database tables:

| Table      | Description                                |
|------------|--------------------------------------------|
| `Books`    | Book ID, Title, Genre, Author, Price, Stock, Published Year |
| `Customers`| Customer ID, Name, Country, City           |
| `Orders`   | Order ID, Book ID, Customer ID, Quantity, Order Date, Total Amount |

---

## 🧩 Database Design

- All data was **imported and normalized** into relational tables.
- **Primary/foreign key** relationships were established:
  - `Orders.book_id` → `Books.book_id`
  - `Orders.customer_id` → `Customers.customer_id`

---

## 🧠 Key SQL Queries

A total of **22 queries** were written to extract business insights:

| #  | Query Purpose |
|----|---------------|
| 1  | Retrieve all Fiction books |
| 5  | Total stock of books |
| 6  | Most expensive book |
| 11 | Total revenue from all orders |
| 12 | Total books sold per genre |
| 14 | Customers with ≥2 orders |
| 15 | Most frequently ordered book |
| 17 | Books sold by each author |
| 20 | Remaining stock after sales |
| 21 | Top 3 highest-spending customers (CTE) |
| 22 | Highest priced book per genre (CTE) |
  
... and many more!

> 🧪 Full SQL scripts are included in the repository for replication and testing.

---

## 📈 Tools & Skills Applied

- **PostgreSQL**
- **SQL** (Joins, Aggregations, CTEs, Filtering, Sorting, Grouping)
- **Data Modeling**
- **Business Logic Implementation**
- **E-commerce & Retail Analytics Simulation**

---

## 🧠 What I Learned

- Structuring a normalized relational database for business data  
- Writing complex queries to extract practical and visualizable insights  
- Using SQL to support decision-making in sales and inventory management  

---

## 🚀 How to Use

1. Import the provided CSV files into a PostgreSQL database.
2. Run the SQL queries in your favorite IDE (pgAdmin, DBeaver, etc.).
3. Customize queries to explore further insights!

---

## 📎 Files Included

- `Books.csv`  
- `Customers.csv`  
- `Orders.csv`  
- `online_bookstore_queries.sql` 

---

## 🔗 Connect with Me

**Ayan Baksi**  
[LinkedIn](https://www.linkedin.com/in/ayan-baksi)  
📧 ayanbaksi11@gmail.com  

---

