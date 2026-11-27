# 🚲 Europe Bike Store Sales & Profitability Analysis (2011–2016)

An end-to-end data auditing, feature engineering, and interactive business intelligence dashboard built in **Microsoft Excel** analyzing **112,036** retail transactions across six countries from **2011 to 2016**.

![Europe Bike Store Dashboard](dashboard.png)

---

## 🎯 Business Problem & Objectives
Between **2011 and 2016**, a multi-country cycling retailer experienced strong top-line growth alongside seasonal fluctuations and varying profit margins across its three core product lines (**Bikes, Accessories, and Clothing**). This project answers four core business questions:

1. **Multi-Year Growth & Trends (2011–2016):** How have annual revenue and net profit evolved over six years, and which years drove peak performance?
2. **Product Category & Sub-Category Profitability:** Which categories and sub-categories generate the highest net profit versus high-volume accessory sales?
3. **Regional Market Performance:** How do total revenue and profit compare across the six operating markets (*United States, Australia, United Kingdom, Germany, France, and Canada*)?
4. **Customer Demographics:** How does purchasing revenue distribute across customer age brackets (*Adults, Young Adults, Youth, Seniors*) and gender segments?

---

## 🧹 Data Auditing & Feature Engineering
Before constructing PivotTables and interactive visuals, the raw dataset (`112,036` records) underwent rigorous validation:
* **Duplicate & Completeness Audit:** Verified data integrity across all `112,036` records (`0` duplicate rows; `0` missing values across date, demographic, and financial fields).
* **Financial Verification (`Verified_Profit`):** Audited pre-existing profit figures by engineering `Verified_Profit = Revenue - Cost` (`$84,826,772` total revenue; `$32,046,239` verified net profit).
* **Profitability Ratio (`Profit_Margin`):** Created a calculated column (`Verified_Profit / Revenue`), establishing an overall company profit margin of **37.8%**.
* **Date & Currency Standardization:** Standardized transaction dates (`Date`) and formatted all monetary fields in US Dollars (`$`).

---

## 💡 Key Business Insights
* **Strong Multi-Year Expansion:** Total revenue reached **$84.83M** with **$32.05M** in verified profit (**37.8% margin**), surging sharply in **2013** and peaking in **2015** (**$19.95M** revenue) and **2016** (**$17.72M** in half-year volume).
* **Product Profit Drivers:** **Bikes** generated the vast majority of profit—led by **Road Bikes** and **Mountain Bikes**—while **Tires and Tubes** and **Helmets** anchored high-frequency **Accessories** profitability.
* **Geographic Concentration:** The **United States** (**$27.78M** revenue) and **Australia** (**$21.30M** revenue) served as the primary growth engines, generating over **57%** of total company sales, followed by the **United Kingdom**, **Germany**, **France**, and **Canada**.
* **Core Demographic Segment:** **Adults (35–64)** and **Young Adults (25–34)** accounted for the overwhelming majority of revenue, with balanced spending across both **Male** and **Female** customers.

---

## 🛠️ Excel Skills & Features Demonstrated
* **Data Auditing & Formulas:** `SUM`, `COUNTA`, Financial Verification (`Revenue - Cost`), and `Profit Margin %` calculations across 112k+ rows.
* **Interactive Dashboarding:** Dynamic PivotTables, Multi-Series Line Charts, Grouped Horizontal Bar Charts, Clustered Column Charts, KPI Summary Cards, and **Multi-Chart Connected Slicers** (`Year`, `Product_Category`, `Country`, `Customer_Gender`).

---

## 📁 Repository Structure
* `Europe-Bike-Sales.xlsx` — Cleaned dataset, PivotTables, and interactive Dashboard.
* `dashboard.png` — High-resolution preview of the completed Excel dashboard.
* `README.md` — Project documentation, data audit log, and strategic insights.
