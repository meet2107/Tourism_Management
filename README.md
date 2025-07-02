# 🗃️ Tourism Management System – DBMS Project

![Made With](https://img.shields.io/badge/Made%20With-FFFFFF?style=for-the-badge&color=gray)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)



## Overview

The **Tourism Management System** is a database-centric project designed to simulate real-world data operations in the tourism industry. It supports core operations for managing tour packages, customers, bookings, and payments using a relational database (PostgreSQL). This project showcases entity relationships, normalization, and SQL-based operations essential for backend data management in travel agencies or tour platforms.

---

## 🧱 Features

🏝️ Tour Package Management – Add, update, and query tour details.

👤 Customer Information Management – Maintain personal and contact details.

📅 Booking System – Manage bookings linked to tours and customers.

💰 Payments & Transactions – Track transactions, payment status, and revenue.

📝 Feedback Mechanism – Record and analyze customer feedback.

---

## 🛠️ How to Run

1. Install PostgreSQL.
2. Create the database:
   ```sql
   CREATE DATABASE tourism_db;
   USE tourism_db;
   ```
3. Run the following script:
   - `T209_Database_Seeding.sql`

4. Test queries from `T209_Queries.pdf`.

---

## 🔍 Sample Use Cases

- Retrieve all bookings for a specific customer
- List most popular tour packages
- Get total revenue by month
- Find customers who never gave feedback

---

## 🔄 Normalization

- All tables follow **Boyce Codd Normal Form (BCNF)**
- Redundancy minimized using foreign keys

---

## 📊 ER Diagram

Available in the file `T209_ERD.pdf` for better understanding of entity relationships.

---

## 📚 Academic Purpose

This project is a submission for a **Database Management Systems (DBMS)** course. It demonstrates:

- Relational schema design
- Querying with SQL
- Data integrity via constraints

---

## 💡 Future Enhancements

* Add stored procedures and triggers
* Integrate with a frontend using Flask or React
* Implement report generation (PDF/CSV exports)
* Apply real-world constraints (e.g., max group size, date validations)
