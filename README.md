# powerbi-sales-financial-analytics
An interactive and end-to-end Power BI dashboard analyzing global sales trends, profitability, and regional performance using DAX and Power Query.
# End-to-End Sales & Financial Performance Analytics Dashboard

An interactive corporate-grade Business Intelligence solution developed using **Microsoft Power BI** to analyze global sales trends, profitability, and multi-regional corporate performance. 

## 📊 Project Overview
This project transforms raw financial datasets into an executive-ready analytics platform. It focuses on driving business growth by identifying high-value customer segments, tracking seasonal revenue patterns, and conducting deep-dive root-cause analyses on corporate profit margins.

---

## 🛠️ Key Technical Features & Workflow

### 1. Data Transformation (Power Query)
* Conducted advanced data cleaning, handling formatting issues, and ensuring structural integrity.
* Developed custom data types and structurally optimized the schema for analytical processing.

### 2. Analytical Data Modeling & DAX Formulas
* Modeled data using a structured **Star Schema** approach to establish clean relationships between facts and dimensions.
* Developed multi-tiered metrics using advanced **DAX (Data Analysis Expressions)**, including:
  * **Total Sales:** `SUM('financials'[ Sales])`
  * **Total Profit:** `SUM('financials'[Profit])`
  * **Year-over-Year (YoY) Growth %:** Time intelligence metrics utilizing `CALCULATE` and `SAMEPERIODLASTYEAR`.

### 3. Executive Dashboard Design (Multi-Page Architecture)
* **Page 1: Executive Summary**
  * High-level KPI Cards tracking core metrics (Revenue, Profitability).
  * Time-series Line Charts capturing cyclical and seasonal sales trends.
  * Clustered Bar Charts highlighting top-performing revenue-generating products.
* **Page 2: Product & Segment Deep-Dive**
  * Matrix Visualizations profiling profit margins across diverse customer segments.
  * Scatter Charts acting as product performance matrices to segregate high-performing items.
  * AI-driven Decomposition Trees for multi-dimensional root-cause and regional contribution analysis.

---

## 📸 Dashboard Screenshots
*(Tip: Take screenshots of your 2 pages, upload them to your repository, and put their links below!)*

### Page 1: Executive Summary
![Executive Summary](path_to_your_screenshot_page1.png)

### Page 2: Product & Segment Analysis
![Segment Analysis](path_to_your_screenshot_page2.png)

---

## 🚀 How to Run the Project
1. Download and install [Power BI Desktop](https://microsoft.com).
2. Clone or download this repository.
3. Open the `End_to_End_Sales_Analytics_Project.pbix` file to interact with the live dashboard.
