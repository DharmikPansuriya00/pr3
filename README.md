## 📌 Project Description

This project focuses on building a **clean, optimized, and well-structured data model** and transforming raw data into **meaningful insights** through interactive dashboards.

The main goal is to showcase:
- Proper **data modeling techniques**
- Usage of **DAX measures**
- Understanding of **star schema**
- Creation of **business-ready dashboards**

---

## 🎯 Project Objectives

✔ Convert raw data into a structured format  
✔ Apply **data cleaning & transformation** techniques  
✔ Build **fact and dimension tables**  
✔ Create relationships with correct **cardinality**  
✔ Write optimized **DAX calculations**  
✔ Design insightful Power BI dashboards  

---

## 🧠 Business Problem Statement

Organizations often struggle with:
- Unstructured data
- Poor data relationships
- Incorrect calculations
- Slow performance dashboards

This project solves these issues by implementing:
- A normalized data model  
- Centralized fact table  
- Optimized DAX measures  
- Clean visual storytelling  

---

## 🗂️ Dataset Information

The project uses multiple datasets, each serving a specific purpose in the data model.

### 📁 Fact Table
**Sales_Fact**
- SalesID (Primary Key)
- CustomerID (Foreign Key)
- ProductID (Foreign Key)
- RegionID (Foreign Key)
- DateKey (Foreign Key)
- Quantity
- Revenue
- Discount

### 📁 Dimension Tables
**Customer_Dim**
- CustomerID
- Full Name
- Age
- Gender
- Segment

**Product_Dim**
- ProductID
- Product Name
- Category
- Sub-Category
- Price

**Region_Dim**
- RegionID
- Country
- State
- City

**Date_Dim**
- Date
- Year
- Quarter
- Month
- Day

---

## 🔄 Data Transformation (Power Query)

All transformations are performed using **Power Query**, including:

- 🧹 Removing null and duplicate values
- 🔄 Changing data types
- ✂ Splitting and merging columns
- 🗓 Creating a custom Date table
- 🔑 Renaming columns for consistency

---

## 🧩 Data Modeling Approach

⭐ **Star Schema Design**

- One **central fact table** (Sales)
- Multiple **dimension tables**
- One-directional relationships
- Optimized filtering paths

### 🔗 Relationships
- One-to-Many cardinality
- Active & inactive relationships
- No circular dependencies

---

## 🧮 DAX Measures Used

Key DAX calculations implemented in this project:

- 💰 **Total Sales**
- 📦 **Total Quantity Sold**
- 📉 **Total Discount**
- 🧾 **Average Sales Value**
- 📊 **Year-over-Year Growth**
- 📅 **Monthly & Quarterly Trends**

All measures follow **best practices** for performance optimization.

---

## 📊 Dashboard & Visualizations

The Power BI report includes:

✨ KPI Cards (Sales, Quantity, Profit)  
✨ Bar Charts & Column Charts  
✨ Line Charts for trends  
✨ Slicers for Date, Region, Product  
✨ Drill-down and cross-filtering  





