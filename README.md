# 🏗️ SSIS Data Warehouse Project

## 📌 Project Overview
This project demonstrates the design and implementation of a **Data Warehouse using SQL Server Integration Services (SSIS)**.  
It focuses on building a complete **ETL pipeline (Extract, Transform, Load)** to prepare data for analytics and reporting.

---

## 🎯 Objectives
- Build a structured Data Warehouse
- Automate ETL processes using SSIS
- Clean and transform raw data
- Enable efficient analytical querying

---

## ⚙️ Technologies Used
- Microsoft SQL Server
- SSIS (SQL Server Integration Services)
- Visual Studio
- SQL (Queries & Scripting)

---

## 🔄 ETL Pipeline

### 1️⃣ Extract
- Data is extracted from source databases/files

### 2️⃣ Transform
- Data cleaning (handling NULLs, duplicates)
- Data formatting and type conversion
- Derived columns creation

### 3️⃣ Load
- Loading processed data into fact and dimension tables

---

## 🧱 Data Warehouse Design
A **Star Schema** architecture is used:

- ⭐ Fact Table:
  Stores quantitative data (e.g., sales, transactions)

- 📊 Dimension Tables:
  Store descriptive attributes (e.g., customer, date, product)

---

## ⚙️ SSIS Components Used
- Control Flow (Workflow management)
- Data Flow Tasks
- Derived Column Transformation
- Data Conversion
- Error Handling

---

## 📊 Project Highlights
- End-to-end ETL pipeline built using SSIS
- Designed a scalable Data Warehouse model
- Applied real-world data cleaning techniques
- Structured data for reporting & analysis

---

## 🚀 How to Run the Project
1. Open the project in **Visual Studio**
2. Configure database connection strings
3. Build the solution
4. Execute SSIS package

---

## 🔮 Future Improvements
- Implement Incremental Loading
- Add Logging & Monitoring system
- Optimize performance for large datasets
- Add scheduling using SQL Server Agent

---

## 👩‍💻 Author
**Aya Eltahan**
