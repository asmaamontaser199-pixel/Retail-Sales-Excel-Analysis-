# 📊 Retail Sales Performance & Profitability Analysis (Excel)

An end-to-end data analytics project focused on evaluating sales performance, identifying profitability bottlenecks, and analyzing customer purchasing trends using Advanced Excel, Power Query, Power Pivot, and DAX.

---

## 📌 Executive Summary & Business Problem

Despite generating strong top-line revenue, the retail operations faced margin compression due to high product return rates and unoptimized discount strategies. 

This project aims to address these core business challenges:
1. **Profit Leakage via Returns:** Identifying high-return categories and products that dilute overall profitability ($125.9K total returns).
2. **Discount vs. Margin Imbalance:** Evaluating the financial impact of aggressive discounting across regional markets.
3. **Customer & Product Concentration:** Uncovering top-performing sales drivers and regional trends to guide inventory and marketing focus.

---

## 🛠️ Tech Stack & Methodology

* **Data Cleaning & ETL:** Used **Power Query** for data transformation, handling missing values, standardizing column data types, and structuring raw orders data.
* **Data Modeling:** Modeled relational data in **Power Pivot** utilizing a Star Schema structure.
* **Calculations & DAX:** Wrote dynamic **DAX Measures** for KPI tracking, including:
  * `Total Sales`
  * `Net Sales`
  * `Total Returns`
  * `Net Profit`
  * `Profit Margin %`
* **Interactive Dashboard:** Built a dynamic Excel dashboard featuring interactive Slicers (Category, Region, Order Date), KPI Cards, Top 5/10 Charts, and Sales Trends.
* **Executive Reporting:** Authored a structured Word/PDF business report detailing strategic recommendations for stakeholders.

---

## 📈 Key Insights & Business Findings

* **Return Metrics:** Total returns amounted to **$125,970**, noticeably impacting net profitability. Specific technology and office supply sub-categories experienced the highest return volumes.
* **Profit Margin Alignment:** While overall Sales reached **$1.11M**, the overall Profit Margin settled at **29%**, indicating room for margin expansion by restructuring discount caps.
* **Regional Performance:** The **West** region outperformed in sales volume, whereas targeted regional marketing is needed for lower-performing territories like the **South**.
* **Top Customer & Product Concentration:** The top 10 customers contribute significantly to gross margin, highlighting the need for tailored loyalty retention strategies.

---

## 💡 Strategic Recommendations

1. **Optimize Return Policies:** Conduct a vendor/quality audit on sub-categories with high return rates and refine product listings to set accurate customer expectations.
2. **Revise Discount Thresholds:** Set strict discount limits on low-margin products to prevent unnecessary profit erosion.
3. **Targeted Regional Campaigns:** Reallocate marketing budget toward high-margin regions (West & East) while running targeted promotions in the South.

---

## 📁 Repository Structure

* `Retail Sales Analytics Project.xlsx` - Master Excel workbook containing Power Query ETL, Power Pivot Data Model, Pivot Tables, and Interactive Dashboard.
* `Retail Sales Analytics Report.pdf` - Full executive business report with detailed findings, root-cause analysis, and strategic recommendations.
* `/screenshots` - High-resolution images of the interactive dashboard and key report sections.
