# ECOMMERCE-SALES-DASHBOARD

## 🛒 Madhav E-commerce Sales Dashboard (Power BI)

An interactive and insightful Power BI dashboard developed for Madhav Store to monitor and analyze their online sales across India.
The dashboard offers a comprehensive view of key business metrics including profit/loss trends, sales distribution by category and region, and customer behavior by payment mode.
It enables the store owner to make data-driven decisions that improve operational efficiency, boost revenue, and enhance customer satisfaction.

## Purpose

The primary goal of this project is to provide the owner of Madhav Store with a clear and actionable visual representation of sales data, helping them:
- Monitor profit and loss trends
- Identify top-performing products and regions
- Analyze customer behavior by category and payment mode
- Make data-driven decisions to boost profitability



## 🧰 Tech Stack

- **Power BI** – For data modeling and visual analytics  
- **Excel** – As the source of raw order and detail data tables  
- **DAX** – Used to create calculated columns (e.g., Average Order Value)
- **Data Modeling** – Relationships established among tables



## ✨ Key Features

- **Stacked Column Chart**:  
  - Visualizes **Profit by Order Date**
  - Profit (Blue) and Loss (Orange) are highlighted with clear color coding  

- **Stacked Bar Chart**:  
  - Displays **Profit by Subcategory**
  - Filters applied to show only **Top 5 profitable subcategories**

- **Donut Charts**:
  - Quantity sold by **Category**
  - Quantity distributed across **Payment Modes**

- **Top 5 States Analysis**:
  - Stacked bar chart showing **Amount by Top 5 States**

- **Custom Measure** –  
  - **AOV (Average Order Value)** calculated using:
    ```
    AOV = Amount / Quantity
    ```

- **Interactive Filters & Slicers**:  
  - Allow users to dynamically explore specific states, categories, subcategories, or payment types

---

## 🚧 Challenges Addressed

- Simplified a large dataset into clear, executive-level visual insights
- Enabled fast and accurate profit/loss detection per order date
- Made category-level performance instantly understandable
- Provided state-wise and payment mode analysis for better market targeting
- Built AOV as a custom performance metric to measure order efficiency
