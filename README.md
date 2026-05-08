# Pizza Sales Performance Analysis (SQL & Power BI) 🍕

---

## 🖼 Dashboard Preview
<img width="3265" height="1814" alt="Capture d’écran 2026-05-08 à 20 05 02" src="https://github.com/user-attachments/assets/b42f0bec-26fd-4e81-b07a-e5c0ea01747b" />
<img width="3265" height="1814" alt="Capture d’écran 2026-05-08 à 20 05 10" src="https://github.com/user-attachments/assets/3361d12d-d059-4982-ac74-6c3ce85ec559" />


## 📌 Project Overview
This project aims to analyze the operational and financial performance of a pizza restaurant chain. Using **SQL** for data extraction and **Power BI** for visualization, I transformed raw sales data into a strategic dashboard to help optimize the menu and identify peak sales periods.

## ⚙️ The Data Pipeline
1. **Data Exploration (SQL):** - Created a dedicated database and imported transactional data (over 48,000 rows).
   - Developed complex queries to calculate critical KPIs: Total Revenue, Average Order Value, and Total Pizzas Sold.
   - Analyzed sales trends by day and month using `DATE_FORMAT` and `STR_TO_DATE`.
2. **Data Visualization (Power BI):** - Designed a multi-page interactive dashboard.
   - Page 1: **Executive Summary** (Sales trends, Category distribution).
   - Page 2: **Best & Worst Sellers** (Deep dive into product performance).

## 📊 Key Business Insights
- **Total Revenue:** Generated approximately **$817.86K** with a total of **21,350 orders**.
- **Sales Trends:** Weekends (Friday and Saturday evenings) show the highest order volume, suggesting a need for increased staffing.
- **Product Performance:** - **Top Seller:** "The Classic Deluxe Pizza" is a leader in both quantity and total orders.
    - **Bottom Seller:** "The Brie Carre Pizza" contributes the least to revenue, indicating a potential menu update.
- **Category Analysis:** The "Classic" category accounts for nearly **27%** of total sales.

## 💻 Technical Highlights
- **Advanced SQL Queries:** Use of aggregate functions, subqueries for percentage calculations (`PCT_Sales`), and `LIMIT` clauses for Top/Bottom 5 analysis.
- **Power BI Skills:** Data modeling, DAX measures for dynamic KPIs, and advanced visual formatting (Donut charts, Stacked Bar charts).

## 📂 Project Resources
- **All files and Data:** [Pizza_Sales_Report](https://drive.google.com/drive/folders/13RBrk2o6bp-fWsI6Rg_6F1xvayTVPnvy?usp=sharing)
