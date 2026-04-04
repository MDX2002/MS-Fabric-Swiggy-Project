# 🚀 Swiggy Data Analytics Project (End-to-End using Microsoft Fabric)

📌 Project Overview
This project focuses on transforming Swiggy’s raw, complex operational data into a streamlined visual intelligence system using Microsoft Fabric.

The Problem
Swiggy generates massive amounts of data every second from orders, restaurants, and deliveries. Because this data is raw and scattered across different sources, it is nearly impossible for decision-makers to quickly see which cities are performing best, identify peak order times, or understand customer food preferences.

The Solution
I built an end-to-end data pipeline that automates the journey from "messy data" to "clear insights." By centralizing the data into a Lakehouse, cleaning it with SQL, and modeling it into a Star Schema, I created a single source of truth. The result is an interactive Power BI dashboard that allows stakeholders to monitor KPIs like Total Sales ($53M) and regional performance in real-time, turning raw numbers into actionable business strategy.

## 🧠 Business Problem

Swiggy generates large volumes of data daily from:

* Customers
* Restaurants
* Orders
* Deliveries

The challenge is to:

* Analyze business performance
* Improve delivery efficiency
* Understand customer behavior

---

## 🎯 Objectives

* Build a scalable data pipeline using Microsoft Fabric
* Clean and validate raw data using SQL
* Design a **Star Schema** data model
* Create a **semantic layer** for reporting
* Develop an interactive Power BI dashboard

---

## 🏗️ Architecture Overview

### 🔹 Data Pipeline Flow

```
Raw Data → Lakehouse → Data Cleaning (SQL) → Data Warehouse → Semantic Model → Power BI Dashboard
```

---

## 🛠️ Tools & Technologies

* Microsoft Fabric (Lakehouse, Data Warehouse, Data Pipelines)
* Microsoft Power BI
* SQL (Data Cleaning & Validation)
* DAX (Measures & KPIs)

---

## 📂 Data Architecture

### 📥 1. Data Ingestion (Lakehouse)

* Stored raw datasets:

  * customers
  * restaurants
  * orders
  * delivery partners
  * deliveries

---

### 🧹 2. Data Cleaning (SQL)

Performed:

* Removing duplicates
* Handling missing values
* Fixing invalid date formats
* Validating order amounts
* Ensuring referential integrity

---

### 🏢 3. Data Warehouse Modeling

Implemented a **Star Schema**:

**Fact Table**

* fact_orders

**Dimension Tables**

* dim_date
* dim_restaurants
* dim_dish
* dim_location

---

### 📊 4. Semantic Model

Created measures such as:

* Total Orders
* Total Revenue
* Average Order Value
* Average Delivery Time
* Orders per Restaurant

---

### 📈 5. Dashboard (Power BI)

Developed an interactive dashboard with:

* KPI cards
* Time-based analysis (daily, monthly trends)
* City-wise performance
* Restaurant insights
* Customer behavior analysis

---

## 📸 Dashboard Preview

![Dashboard](screenshots/dashboard_overview.png)

---

## 🧠 Key Insights

* Peak order volumes occur during weekends
* High-performing cities contribute major revenue share
* Delivery delays impact customer satisfaction
* Repeat customers drive consistent revenue

---

## 💡 Skills Demonstrated

* Data Engineering (Fabric Lakehouse & Pipelines)
* SQL Data Cleaning & Validation
* Data Modeling (Star Schema)
* DAX Calculations
* Data Visualization & Storytelling

---

## ⚙️ How to Use

1. Download the `.pbix` file
2. Open using Power BI Desktop
3. Explore dashboard using filters and slicers

---

## 👤 Author

**Malindu Dilmin**

---
Inspired by: Data Tutorials YouTube channel

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
