# 📊 Superstore Sales Analytics — Power BI Project

**Institute:** Red & White Skill Education  
**Course:** Data Analytics (Power BI Practical Report 1)  
**Student Name:** Sandesh  
**Tools Used:** Power BI Desktop • Power Query Editor • DAX • Microsoft Excel  

---

## 📌 Project Overview

This project is an end-to-end retail sales analytics solution built in **Power BI Desktop** using the **Sample Superstore Dataset**. The primary goal is to help executive management analyze retail sales performance, profitability trends, customer purchasing behavior, and regional disparities across the United States.

The project covers the entire business intelligence workflow:
1. **Data Ingestion & Cleaning:** Connecting to the raw data and performing 8+ transformation steps in **Power Query Editor** to resolve dirty date formats, nulls, and duplicate values.
2. **Data Modeling & DAX Measures:** Defining key performance metrics including Total Sales, Total Profit, Profit Margin %, and Order Quantities.
3. **Interactive Reporting:** Designing a clean, professional 2-page dashboard with an executive brand color palette (`#CC0000` Crimson Red and `#4A4A4A` Charcoal Gray), interactive slicers, and cross-filtering.

---

## 🎥 Project Presentation Video

🎬 **Walkthrough Video:** [`Superstore_Sales_Presentation_Edited.mp4`](Superstore_Sales_Presentation_Edited.mp4)  
* **Format:** MP4 (1080p Full HD)  
* **Duration:** 4 Minutes 30 Seconds  
* **Description:** A screen recording walkthrough demonstrating the Power BI dashboard, interactive slicer filtering, key sales and profit metrics, Power Query data cleaning transformations, and business insights.

---

## 📸 Dashboard Previews

### Page 1: Executive Sales & Profit Performance Dashboard
A high-level view designed for business leaders to monitor top-line sales, bottom-line profitability, and territory performance.

![Page 1 Executive Dashboard](screenshots/Dashboard_Page1_Executive.png)

* **Key KPI Cards:** Total Sales ($2.30M), Total Profit ($286.40K), Total Quantity Sold (37.87K), and Profit Margin (12.47%).
* **Monthly Trends:** Line chart visualizing monthly sales trajectories and profitability fluctuations.
* **Regional Contribution:** Donut chart breaking down sales volume across West, East, Central, and South regions.
* **Category Breakdown:** Bar chart comparing revenue and profit margins across Technology, Furniture, and Office Supplies.
* **Interactive Slicers:** Region filter, Segment filter (Consumer, Corporate, Home Office), and Order Date range slider.

---

### Page 2: Detailed Order Data (Audit Table)
A granular data table enabling operational teams to audit individual transactions and inspect order-level profitability.

![Page 2 Detailed Table](screenshots/Dashboard_Page2_Detailed_Table.png)

* **Tabular Columns:** Order ID, Order Date, Customer Name, Segment, Region, Category, Sub-Category, Sales, and Profit.
* **Conditional Formatting:** Highlighting high-margin profitable orders in green and loss-making transactions in red.
* **Cross-Filtering:** Selecting any customer segment or category instantly filters the granular transactional records.

---

## 🛠️ Data Cleaning & Transformations (Power Query)

The raw Superstore dataset contained formatting inconsistencies and dirty records that were resolved before visualization:

1. **Date Format Normalization:** Converted mixed date formats (`DD/MM/YYYY` and `YYYY-MM-DD`) into standardized Date data types.
2. **Data Type Standardization:** Enforced explicit numeric data types (Fixed Decimal for Sales/Profit, Whole Number for Quantity/Postal Code).
3. **Missing Value Handling:** Audited and resolved missing entries across geographical fields.
4. **Custom Column Engineering:** Created calculated helper columns for delivery duration (Days to Ship) and profit status flags.
5. **Applied Custom Brand Theme:** Imported a corporate Red and Charcoal color theme file to ensure visual consistency across all visuals.

---

## 📈 Key Business Insights

* **Top Performing Region:** The **West Region** generated the highest overall sales (over $725K) and the strongest net profit margin.
* **Most Profitable Category:** **Technology** is the primary profit driver for the company, delivering a healthy 17.4% net profit margin led by Phones and Copiers.
* **Loss-Making Sub-Categories:** The **Tables** sub-category within Furniture operates at a net loss due to excessive promotional discounts (up to 70%).
* **Customer Segment Dominance:** The **Consumer Segment** represents over 50% of total revenue, making it the most critical audience for retail marketing campaigns.

---

## 🗂️ Project Deliverables

* 📊 **`Super Store.pbix`** — The complete interactive Power BI Desktop report file.
* 🎥 **`Superstore_Sales_Presentation_Edited.mp4`** — Master presentation video walkthrough (4.5 min, 1080p Full HD).
* 📁 **`Sample - Superstore.csv`** — Cleaned source dataset.
* 🎨 **`RedWhite_Brand_Theme.json`** — Custom Power BI color theme file.
* 🖼️ **`screenshots/`** — High-resolution dashboard image exports.
