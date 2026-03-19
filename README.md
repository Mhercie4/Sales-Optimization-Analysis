# Retail Sales Performance Analysis (1,000+ Transactions)

## 📌 Project Overview
This project features a comprehensive end-to-end data analysis of a retail company’s sales data using **Microsoft Excel**. The primary objective was to transform a raw, fragmented dataset of 1,000+ transactions into a dynamic, interactive "Business Intelligence" (BI) dashboard. The analysis provides actionable insights into regional performance, product profitability, and customer buying patterns to support data-driven decision-making.

## 🛠️ Tools & Technologies Used
* **Microsoft Excel:** Advanced Data Cleaning, PivotTables, and Dashboard Design.
* **Data Cleaning:** Leveraged `TRIM`, `PROPER`, and `UPPER` to handle inconsistent text and formatting.
* **Advanced Formulas:** Implemented `VLOOKUP` for data enrichment and `IFS` for multi-tier logical categorization.
* **Statistical Analysis:** Used `SUMIFS`, `COUNTIFS`, and `AVERAGEIFS` for targeted KPI reporting on the Summary Sheet.

## 📂 Project Structure
* **Raw_Data:** The original dataset containing noise and unformatted records.
* **Cleaned_Data:** Processed data with helper columns (Year, Month, Profit, Order Tiers).
* **Summary_Sheet:** Detailed calculations and business metrics.
* **Dashboard:** The final interactive interface featuring slicers and visual KPIs.

## 🧹 Data Cleaning & Transformation
To ensure the accuracy of the insights, the following steps were performed:
1.  **Standardization:** Removed leading/trailing spaces and standardized naming conventions for Regions and Categories.
2.  **Data Enrichment:** Integrated a Product Cost lookup table to calculate net **Profit** per transaction.
3.  **Logical Categorization:** Implemented a **Three-Tier Order Status** column:
    * **High Value:** Orders > $1,000
    * **Medium Value:** Orders between $500 - $1,000
    * **Low Value:** Orders < $500
4.  **Time Intelligence:** Extracted Month and Year from order dates to visualize growth trends.

## 📊 Dashboard Visuals
  **[Dashboard Screenshot]**
<img width="762" height="403" alt="Project 4 Dashboard" src="https://github.com/user-attachments/assets/72d93e33-1f19-4890-b5c1-8c19977f0684" />

* **Interactive Slicers:** Allows users to filter the entire report by Region, Segment, and Product Category.
* **KPI Scorecard:** Real-time tracking of Total Sales, Total Profit, and Total Order counts.
* **Revenue Trends:** A line chart visualizing monthly fluctuations and significant seasonal peaks.
* **Regional Performance:** A breakdown of profitability by geographic location.
* **Top 5 Products:** A sorted bar chart identifying the highest revenue-generating items.

## 💡 Key Insights
* **Regional Leader:** The **North Region** is the strongest market, contributing approximately **26%** of total revenue.
* **High-Value Impact:** Despite being fewer in number, **"High Value" orders (>$1,000)** contribute disproportionately to the total profit margin.
* **Hero Products:** The **Air Fryer** and **Stapler** are the top-grossing products, consistently outperforming other stock units.
* **Seasonality:** A sharp revenue increase is observed in **June**, followed by a dip in **September**, suggesting a mid-year peak that requires targeted inventory preparation.
* **Bulk Buying:** Analysis reveals that **Corporate** segments tend to have a higher **Average Quantity Sold** per order compared to individual consumers.

## 🚀 Strategic Recommendations
* **Tier-Based Marketing:** Develop loyalty rewards or exclusive offers for "High Value" customers to ensure retention of the most profitable segment.
* **Bulk-Order Strategy:** Implement volume-based discounts for the **Corporate** segment to encourage even larger order sizes.
* **Regional Scaling:** Replicate successful sales tactics from the North region in the East and West regions to capture more market share.
* **Inventory Optimization:** Prioritize stock for the "Top 5" products ahead of the identified June peak to avoid stockouts.

---
###**Project Resources**

Raw Dataset used [Project 4 Dataset.xlsx](https://github.com/user-attachments/files/26116338/Project.4.Dataset.xlsx)

Live Dashboard [Project 4 xl file.xlsx](https://github.com/user-attachments/files/26116352/Project.4.xl.file.xlsx)

---
---

**Author:** Mercy Enujuba (M.E Analytics) 

**Data Analyst**

