<img width="894" height="881" alt="image" src="https://github.com/user-attachments/assets/f7ce4baf-3d4f-41eb-a77a-c70faddc3114" />

# 🎬 End-to-End Data Integration & Analytics Project  
### (MySQL → Snowflake → MongoDB)

## 📘 1. Project Overview
This project demonstrates a complete **data lifecycle** — from relational storage in **MySQL**, to cloud data warehousing in **Snowflake**, and finally to document-based modeling in **MongoDB**.  

Using the **Sakila** sample database (a film rental system), you will:
- Perform **data modeling** (ERD & Star Schema)
- Build and run an **ETL pipeline**
- Execute **analytical queries and reporting**
- Model data in a **NoSQL environment**

This workflow simulates a **real-world data engineering pipeline** used in modern organizations.

---

## 🎯 2. General Objective
Migrate and transform the Sakila dataset across **MySQL**, **Snowflake**, and **MongoDB**, while developing skills in:
- Database design  
- ETL (Extract, Transform, Load)  
- Cloud data management  
- NoSQL data modeling & analytics  

---

## 🏗️ 3. Project Architecture
```text
MySQL (Relational) → Export CSV → Snowflake (Cloud DW) → Transform & Query → MongoDB (NoSQL)

🔹 4. Project Phases
Phase 1 – MySQL Environment

Objective: Install and explore the Sakila database, build ERD, and perform SQL queries.

Tasks:

Install MySQL Workbench and import:

sakila-schema.sql

sakila-data.sql

Inspect tables and relationships (SHOW TABLES;)

Create an ERD diagram showing entity relationships

Write at least 5 SQL queries:

Top 10 films

Top 10 customers

Total rentals by country

Export selected tables (customer, rental, payment) to CSV format

Deliverables:

ERD diagram (PNG/PDF)

5 SQL queries with screenshots

Exported CSV files

Phase 2 – Snowflake Data Warehouse

Objective: Load CSV files into Snowflake and design a Star Schema for analytics.

Tasks:

Create a Snowflake account, warehouse, and schema

Use STAGE and COPY INTO commands to load CSV files

Design a Star Schema (fact + dimension tables)

Run analytical queries:

Monthly revenue

Top countries

Customer behavior trends

Deliverables:

Star Schema diagram

Snowflake SQL commands and screenshots

3 analytical query results

Phase 3 – MongoDB NoSQL Modeling

Objective: Model data as documents and perform aggregations using MongoDB Atlas.

Tasks:

Create a MongoDB Atlas free cluster

Download and use MongoDB Compass

Import CSV files (customer, rental, payment)

Design collections (customers, rentals) using embedded or referenced structures

Define indexes for efficient querying

Write 3 Aggregation Pipeline queries:

Rentals per country

Total payments per customer

Average rental duration

Deliverables:

JSON document structure

3 aggregation pipeline queries and results

🧰 5. Tools & Resources
Platform	Tool	Link
MySQL	MySQL Workbench	Download

Snowflake	Web UI / Worksheets	Sign Up

MongoDB	MongoDB Atlas	Atlas

MongoDB	MongoDB Compass	Compass
📦 6. Final Deliverables

Your final project portfolio should include:

ERD and Star Schema diagrams

SQL and NoSQL scripts

CSV files

Screenshots of all key steps

A short reflection (5–6 sentences) comparing MySQL, Snowflake, and MongoDB

All documents uploaded to GitHub and shared on LinkedIn

🧠 7. Learning Outcomes

By completing this project, you will be able to:

Design and document relational and NoSQL databases

Execute ETL workflows between multiple platforms

Write analytical and aggregation queries

Understand key differences between OLTP, OLAP, and NoSQL systems

🧑‍🏫 8. Instructor Note

This project simulates a real-world data engineering pipeline used in analytics environments.
You are encouraged to:

Work collaboratively

Document each step clearly

Reflect on how data flows across different architectures

✨ Example Reflection (Optional)

Working with MySQL, Snowflake, and MongoDB revealed the distinct roles of each technology.
MySQL handled structured transactional data efficiently, while Snowflake enabled scalable analytics and fast aggregation.
MongoDB provided flexibility for semi-structured data and rapid document retrieval.
This project demonstrated how modern data pipelines integrate multiple systems to deliver end-to-end insights.

📁 Repository Structure (Suggested)
End-to-End-Data-Integration-Project/
│
├── Phase1_MySQL/
│   ├── ERD_Diagram.png
│   ├── Queries.sql
│   └── CSV_Exports/
│
├── Phase2_Snowflake/
│   ├── Star_Schema.png
│   ├── Snowflake_Scripts.sql
│   └── Query_Results/
│
├── Phase3_MongoDB/
│   ├── Document_Structure.json
│   ├── Aggregation_Queries.js
│   └── Screenshots/
│
└── README.md
