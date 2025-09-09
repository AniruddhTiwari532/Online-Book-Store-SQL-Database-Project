# Online-Book-Store-SQL-Database-Project
This project is a SQL-based database system designed for managing an online book store. It handles various operations like storing book details, managing customers, tracking orders, handling inventory, and processing payments. The database is designed with optimized queries and normalized tables to ensure efficient data storage and retrieval.

## 📂 Project Structure
| **File Name**     | **Description**           | **Key Columns**                                                                |
| ----------------- | ------------------------- | ------------------------------------------------------------------------------ |
| **Books.csv**     | Stores book details       | `Book_ID`, `Title`, `Author`, `Genre`, `Price`, `Stock`                        |
| **Customers.csv** | Contains customer details | `Customer_ID`, `Name`, `Email`, `City`, `Country`                              |
| **Orders.csv**    | Tracks customer purchases | `Order_ID`, `Book_ID`, `Customer_ID`, `Quantity`, `Order_Date`, `Total_Amount` |

## 🛠️ Database Schema

#### Tables Used:

Books

Customers

Orders

#### Relationships:

Books.Book_ID ↔ Orders.Book_ID

Customers.Customer_ID ↔ Orders.Customer_ID

This design ensures data normalization and avoids redundancy.
