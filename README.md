# 🗃️ Tourism Management System – DBMS Project

![Made With](https://img.shields.io/badge/Made%20With-FFFFFF?style=for-the-badge&color=gray)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)



## Overview

The **Tourism Management System** is a database-centric project designed to simulate real-world data operations in the tourism industry. It supports core operations for managing tour packages, customers, bookings, and payments using a relational database (PostgreSQL). This project showcases entity relationships, normalization, and SQL-based operations essential for backend data management in travel agencies or tour platforms.

---

## 🧱 Features

- **Tour Package Management**
- **Customer Information Management**
- **Booking System**
- **Payments & Transactions**
- **Feedback Mechanism**

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

- All tables follow **Third Normal Form (3NF)**
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
