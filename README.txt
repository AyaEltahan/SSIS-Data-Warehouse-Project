# 📊 Data Warehouse ETL Pipeline using SSIS

## 📌 Introduction
In this project, a complete Data Warehouse pipeline is developed using SSIS to transform raw data into meaningful and structured information for analysis.

---

## 🎯 Problem Statement
Raw data from different sources is often inconsistent and not ready for analysis.  
This project solves this problem by building an ETL pipeline to clean, transform, and organize the data into a Data Warehouse.

---

## 🧠 Solution Approach
The solution is implemented using SSIS through:
- Extracting data from source files (Excel / Database)
- Transforming data (cleaning, handling nulls, formatting)
- Loading data into structured tables

---

## 🏗️ Data Model
A Star Schema design is used:

- **Fact Table** → stores measurable data (e.g., transactions, count)
- **Dimension Tables** → store descriptive attributes (e.g., date, customer)

---

## ⚙️ ETL Implementation
- Control Flow: manages workflow execution
- Data Flow: handles data transformation
- Derived Columns & Data Conversion
- Data Validation and Error Handling

---

## 📊 Project Highlights
- Built ETL pipeline using SSIS
- Designed Data Warehouse schema
- Applied data cleaning techniques
- Organized data for efficient querying

---

## 🚀 Execution Steps
1. Open the project in Visual Studio  
2. Configure database connections  
3. Run the SSIS package  

---

## 🔮 Future Enhancements
- Implement Incremental Load  
- Add Logging & Monitoring  
- Improve performance optimization  

---

## 👩‍💻 Author
Aya Eltahan