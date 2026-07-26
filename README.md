# Retail Performance Analytics Dashboard

## Business Problem
Retail businesses generate thousands of transactions daily across multiple product categories, regions, and customer segments. Decision-makers often struggle to identify profitability drivers, customer churn risks, and the true impact of discounts on overall business performance.

This project addresses these challenges by building an interactive Business Intelligence solution that transforms raw transactional data into actionable insights for executives and operational teams.

---

## Executive Summary
This project provides an end-to-end data analytics solution designed to analyze e-commerce retail performance, customer behavior, product profitability, and discount impacts. Using an enriched e-commerce dataset, a multi-page Power BI dashboard was engineered alongside Python data pipelines to extract actionable business insights, optimize revenue streams, and mitigate churn and return risks.

---

## Project Architecture
Raw Dataset
  ↓
Python Cleaning & Preprocessing
  ↓
Feature Engineering & RFM Segmentation
  ↓
Machine Learning Risk Modeling
  ↓
Cleaned Dataset Export (CSV)
  ↓
Power BI Data Modeling & DAX Measures
  ↓
Business Insights & Strategic Recommendations

---

## Project Repository Files
- **Dataset:** [`enriched_ecommerce_dataset.csv`](./enriched_ecommerce_dataset.csv) – Cleaned transactional dataset containing order details, customer segments, sales, and profit metrics.
- **Python Pipeline:** [`Retail_Analytics_Pipeline.ipynb`](./Retail_Analytics_Pipeline.ipynb) – Python notebook used for data preprocessing, feature engineering, exploratory data analysis (EDA), and machine learning modeling.
- **Power BI Report File:** [`Retail Performance Analytics.pbix`](./Retail Performance Analytics.pbix) – The primary interactive multi-page Power BI dashboard.
- **Dashboard Preview (PDF):** [`Retail Performance Analytics-Image .pdf`](./Retail Performance Analytics-Image%20.pdf) – High-resolution export of all dashboard pages.
- **Video Walkthrough:** [`Retail Performance Analytics-video.MP4`](./Retail Performance Analytics-video.MP4) – Complete video demonstration of interactive features and page navigation.

---

## Key Business Metrics
- **Total Sales:** $5.87M
- **Total Net Profit:** $7.53M
- **Total Orders:** 35K
- **Total Quantity Sold:** 51K units
- **Total Customers:** 8K
- **Average Order Value (AOV):** $170.01
- **Total Discount Amount Given:** $308.52K
- **Average Discount Rate:** 4.93%
- **Customer Return Rate:** 4.41%

---

## Dashboard Preview

### Page Screenshots & Video Demonstration
- **Executive Summary:** Overview of high-level KPIs, revenue drivers, and top-line trends.
- **Sales Performance:** Regional breakdown and temporal sales distribution.
- **Products:** SKU volume analysis and identification of slow-moving inventory.
- **Customers:** RFM customer segmentation and churn risk analysis.
- **Profitability:** Discount impact on net margins across product categories.
- **Recommendations:** Data-driven strategic actions and machine learning insights.

*(Please refer to [`Retail Performance Analytics-Image .pdf`](./Retail Performance Analytics-Image%20.pdf) for page previews and [`Retail Performance Analytics-video.MP4`](./Retail Performance Analytics-video.MP4) for the complete interactive walkthrough).*

---

## Business Insights & Dashboard Walkthrough

### Page 1: Executive Performance Overview
- **Objective:** High-level summary of key performance indicators for leadership.
- **Key Findings:**
  - `Electronics` leads overall revenue among categories.
  - Sales and net profit showed consistent trend variations across 2023, 2024, and 2025.
  - Customer base is heavily driven by `Loyal Customers` followed by `At Risk` segments.

### Page 2: Sales Performance & Temporal
- **Objective:** Regional and time-series sales analysis.
- **Key Findings:**
  - Regional distribution ranks sales highest in `South` ($1.4M+), followed by `North`, `West`, `East`, and `Central`.
  - Monthly trends highlight demand spikes across mid-year and Q4 periods.
  - Sales analysis across days of the week shows peak transaction volume on `Wednesday` and `Thursday`.

### Page 3: Product & Category Performance
- **Objective:** Item-level volume analysis and slow-moving product tracking.
- **Key Findings:**
  - Top category: `Electronics` (Sales: $3.32M | Net Profit: $5.07M).
  - Isolated top revenue-generating SKUs (e.g., `P217031`, `P242326`, `P224743`).
  - Identified bottom 10 slow-moving items to optimize warehouse inventory turnover.

### Page 4: Customer Behavior & RFM
- **Objective:** Customer segmentation, risk profiling, and purchasing preferences.
- **Key Findings:**
  - **At Risk Customers Count:** 2K out of 8K total customers (~25%).
  - Preferred Payment Method: `Credit Card` dominates total transactions, followed by `Debit Card`, `COD`, `UPI`, `PayPal`, and `Wallet`.
  - Customer age demographic analysis reveals highest sales concentration in the 22–30 age bracket.

### Page 5: Profitability & Discount Impact
- **Objective:** Analyzing net profit performance against discount strategies.
- **Key Findings:**
  - Top 5 Most Profitable Categories: `Electronics`, `Home`, `Sports`, `Fashion`, `Beauty`.
  - Margin & Discount Correlation: Heavy discounting on certain categories erodes net profit without generating proportional volume increases.
  - Isolated low-margin and negative-profit items for pricing re-evaluation.

### Page 6: Strategic Business Recommendations & ML Integration
- **Objective:** Actionable data-driven strategies and predictive risk insights.
- **Key Recommendations:**
  1. **Profitability & Discount Optimization:** Enforce a strict 15% discount cap on low-margin products; transition to product bundling rather than direct price cuts.
  2. **Return Risk Mitigation:** Deploy machine learning classification models to flag high-probability return orders; implement pre-shipment quality checks for flagged orders.
  3. **Customer Retention:** Launch automated win-back marketing campaigns with targeted coupon thresholds for the 2,000 `At Risk` customers.
  4. **Inventory Management:** Reallocate regional inventory based on localized demand trends and initiate clearance bundling for bottom 10 slow-moving products.

---

## Skills Demonstrated
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Customer Segmentation (RFM)
- Business Intelligence Reporting
- KPI Design
- Data Modeling
- DAX Measures
- Power Query
- Predictive Analytics
- Business Recommendations

---

## Business Value
This dashboard enables decision-makers to:
- Monitor overall business performance and revenue streams in real time.
- Identify high-performing and underperforming products to optimize inventory turnover.
- Optimize discount strategies to protect net profitability.
- Reduce return risks using predictive analytics.
- Improve customer retention through targeted RFM segmentation strategies.
- Support data-driven strategic decision-making across executives and operational teams.
