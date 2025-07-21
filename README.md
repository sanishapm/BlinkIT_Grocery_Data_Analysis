# 📊 BlinkIT Grocery Data Analysis — Power BI Project

This repository presents an end-to-end data analysis and visualization project using **Power BI**, based on grocery data from **BlinkIT**. The project includes **data cleaning, transformation, modeling, and dashboard creation**, all executed entirely within Power BI — **no Excel or external tools used**.

---

## 🧾 Project Overview

The objective is to uncover insights from grocery retail data using an interactive and well-designed Power BI dashboard. This includes examining:
- Product performance
- Outlet characteristics
- Sales trends
- Consumer metrics

---

## 📁 Files Included
- `blinkit_grocery_data.xlsx`- Raw Data

- `blinkit.pbix` – Power BI file containing:
  - Raw data ingestion
  - Power Query transformations
  - DAX-based measures
  - Fully interactive report pages

---

## 📊 Dashboard Highlights

The dashboard includes the following visuals and KPIs:

- **KPI Cards**:  
  - **Total Sales**: ₹788K  
  - **Average Sales**: ₹141  
  - **Average Rating**: 3.92  
  - **Total Items**: 6K  

- **Visualizations**:  
  - Sales by Outlet Establishment Year  
  - Sales by Item Type  
  - Item Fat Content Breakdown  
  - Sales by Outlet Size and Location Type  
  - Filter by Outlet Type (Grocery Store, Supermarket) and Tier (1, 2, 3)

- **Filters & Slicers**:  
  - Outlet Type  
  - Outlet Tier  
  - Page-level and visual-level filtering enabled

---

## ⚙️ Technologies Used

- **Power BI Desktop**
  - Power Query for data cleaning
  - DAX for custom measures  
    Example:  
    ```DAX
    Total Sales = SUM('BlinkIT Grocery Data'[Sales])
    ```
  - Built-in visuals and slicers
  - Responsive page layout

---
