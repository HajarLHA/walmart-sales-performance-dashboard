# 🛒 Walmart Sales Performance Dashboard

## 📌 Project Overview 

This Power BI dashboard provides an **interactive analysis of Walmart’s weekly sales performance (2010–2012)**.  
It helps explore how different factors such as store location, year, and holiday status impact total and average sales over time.

---

## 📁 Repository Structure

```
├── dashboard/      #Power BI file & exported dashboard
├── dataset/           #dataset
└── README.md       #Project documentation
```

---

## 📊 Dataset

The dashboard was built using the **Walmart Weekly Sales Dataset**, a publicly available dataset from Kaggle that contains historical sales data for multiple Walmart stores across the U.S.  

- **Rows:** 6,435  
- **Columns:** 8  
- **Time Period:** 2010–2012  
- **Main Fields:**  
  - `Store` – Store ID number  
  - `Date` – Week of sales record  
  - `Weekly_Sales` – Total sales revenue for the given store and week  
  - `Holiday_Flag` – Indicates if the week includes a major holiday (1 = Holiday, 0 = Non-Holiday)  
  - `Temperature` – Average temperature for the week (°F)  
  - `Fuel_Price` – Average fuel cost for the week  
  - `CPI` – Consumer Price Index for the region  
  - `Unemployment` – Unemployment rate for the region   
📥 The dataset can be downloaded from: (https://www.kaggle.com/datasets/yasserh/walmart-dataset).

---

## 🔑 Key Features

- **KPIs** for Total Sales, Average Weekly Sales, Average Sales per Store, and Holiday Impact  
- **Top 10 Stores by Total Sales** (Treemap)  
- **Sales Trend Over Time** (Line Chart)  
- **Holiday vs Non-Holiday Sales** (Donut Chart)  
- **Interactive Filters:**  
  - Year   
  - Store 
  - Holiday Status (Holiday / Non-Holiday)
    
---

## 🧠 Tools & Techniques

- **Power BI Desktop**  
- **Data Modeling** and DAX Calculations  
- **KPI Cards** for visual storytelling  
- **Custom Formatting** and consistent color theme  

---

## 📊 Key Insights

- **Total Sales:** 6.74 Billion  
- **Average Weekly Sales:** 1.05 Million  
- **Average Sales per Store:** 149.72 Million  
- **Holiday Impact:** -91.9% (lower sales during holidays compared to non-holidays)

---
👩‍💻 Created by *Hajar Lhamyani* – Data Scientist & Analyst | Machine Learning Engineer



