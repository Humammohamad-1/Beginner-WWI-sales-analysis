# Beginner Power BI Project 📌

## 📌 Project Overview
This repository contains a **Power BI project** demonstrating **business intelligence analysis** using a **star schema dataset**. The goal is to showcase skills in **data modeling, visualization, and reporting**.

## 📊 Dataset Description
The dataset follows a **star schema**, which consists of **1 fact table** and **4 dimension tables**.

The data comes from the **imaginary company Wide World Importers (WWI)**.

### **Dataset Files**
- **Fact Table (Sales Information)**: `FactSales.csv`
- **Dimension Tables (Supporting Transaction Details)**:
  - `DimCustomer.csv`
  - `DimEmployee.xlsx`
  - `DimStockItem.csv`
  - `DimDate.csv`
  - `DimCity.csv`

### **Fact Table: `FactSale`**
The **FactSale** table contains **transactional sales data**, including:
- `Bill To Customer Key`
- `City Key`
- `Customer Key`
- `Delivery Date Key`
- `Invoice Date Key`
- `Description`
- `Package`
- `Profit`
- `Quantity`

### **Dimension Tables**
#### 📅 `DimDate` - Stores date-related attributes:
- `Calendar Year`
- `Calendar Month Label`
- `Day Number`
- `Fiscal Year`

#### 🛍️ `DimCustomer` - Contains customer information:
- `Customer Key`
- `Buying Group`
- `Category`
- `Credit Limit`
- `Postal Code`

#### 🌍 `DimCity` - Provides geographical details:
- `City Key`
- `State Province`
- `Country`
- `Sales Territory`

#### 👥 `DimEmployee` - Holds employee-related data:
- `Employee Key`
- `Is Salesperson`
- `Preferred Name`

---

## 📈 Analysis Conducted
The **Power BI report** includes the following insights:

### 1️⃣ **Sales Performance Analysis**
- A **bar chart** displaying the **quantity of items sold** over different years.
- Breakdown of **dry items vs. chiller items** in total sales.

### 2️⃣ **Employee-Based Profit Analysis**
- A **table visualization** showing:
  - **Employee-wise sales**, listing item descriptions, quantity sold, and total profit.
  - **Grand totals** for total quantity sold and overall profit.

### 3️⃣ **Geographical Profit Analysis**
- A **map visualization** that plots **profit by state/province**, helping to identify the most profitable regions.
- A **key metric card** showing the **average total including tax**.
- A **bar chart** displaying the **minimum total including tax by buying group**, offering insight into different customer segments.

---


