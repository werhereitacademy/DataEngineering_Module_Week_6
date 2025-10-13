<img width="894" height="881" alt="image" src="https://github.com/user-attachments/assets/f7ce4baf-3d4f-41eb-a77a-c70faddc3114" />

# 🎬 Azure Data Engineering & Analytics – Week 7  
## End-to-End Data Integration & Analytics Project  
### *(MySQL → Snowflake → MongoDB)*

---

## 📌 Project Overview

This project explores the full data lifecycle using the **Sakila** film rental database. You'll experience how data flows across three major platforms:

- **MySQL** (Relational Database)
- **Snowflake** (Cloud Data Warehouse)
- **MongoDB** (NoSQL Document Store)

You'll perform:

- 📐 Data modeling (ERD & Star Schema)  
- 🔄 Data migration (ETL process)  
- 📊 Analytical queries and reporting  
- 📄 Document modeling in NoSQL  

This simulates a real-world data engineering pipeline used in modern analytics environments.

---

## 🎯 General Objective

Migrate and analyze the Sakila dataset across three platforms while developing skills in:

- Database design  
- ETL workflows  
- Cloud data warehousing  
- NoSQL analytics  

---

## 🏗️ Project Architecture

```text
MySQL (Relational) 
   ↓ Export CSV 
Snowflake (Cloud DW) 
   ↓ Transform & Query 
MongoDB (NoSQL)
```

---

## 🚦 Project Phases

### 🔹 Phase 1 – MySQL Environment

**Objective:** Install and explore Sakila, build ERD, and run SQL queries.

**Tasks:**
- Install MySQL Workbench  
- Import `sakila-schema.sql` & `sakila-data.sql`  
- Inspect tables and relationships  
- Create ERD diagram  
- Write 5+ SQL queries (e.g., top 10 films, rentals by country)  
- Export `customer`, `rental`, `payment` tables to CSV  

**Deliverables:**
- ERD diagram (PNG/PDF)  
- SQL query screenshots  
- Exported CSV files  

---

### 🔹 Phase 2 – Snowflake Data Warehouse

**Objective:** Load CSVs into Snowflake and design a Star Schema.

**Tasks:**
- Create Snowflake account, warehouse, and schema  
- Use `STAGE` and `COPY INTO` to load data  
- Design Star Schema (fact + dimension tables)  
- Run analytical queries (monthly revenue, top countries, trends)  

**Deliverables:**
- Star Schema diagram  
- Snowflake SQL scripts and screenshots  
- 3 analytical query results  

---

### 🔹 Phase 3 – MongoDB NoSQL Modeling

**Objective:** Model data as documents and run aggregations in MongoDB Atlas.

**Tasks:**
- Create MongoDB Atlas cluster  
- Download MongoDB Compass  
- Import CSVs into collections  
- Design embedded/referenced document structures  
- Define indexes  
- Write 3 aggregation queries (e.g., rentals per country, total payments)  

**Deliverables:**
- JSON document structure  
- Aggregation queries and results  

---

## 🧰 Tools & Resources

| Platform | Tool               | Link                                                                 |
|----------|--------------------|----------------------------------------------------------------------|
| MySQL    | MySQL Workbench    | [Download](https://dev.mysql.com/downloads/workbench)               |
| Snowflake| Web UI / Worksheets| [Sign Up](https://signup.snowflake.com)                             |
| MongoDB  | Atlas & Compass    | [Atlas](https://www.mongodb.com/atlas) • [Compass](https://www.mongodb.com/products/tools/compass) |

---

## 📦 Final Deliverables

- ✅ ERD and Star Schema diagrams  
- ✅ SQL and NoSQL scripts  
- ✅ CSV files  
- ✅ Screenshots of all key steps  
- ✅ Short reflection (5–6 sentences) comparing MySQL, Snowflake, and MongoDB  
- ✅ All materials uploaded to GitHub and shared on LinkedIn  

---

## 🎓 Learning Outcomes

By completing this project, you will:

- Design and document relational & NoSQL databases  
- Execute ETL workflows across platforms  
- Write analytical and aggregation queries  
- Understand OLTP, OLAP, and NoSQL architectures  

---

## 🧑‍🏫 Instructor Note

This project simulates a real-world data engineering pipeline.  
Work collaboratively, document each step, and reflect on how data flows across architectures.

---
