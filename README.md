# ecommerce-funnel-olist
# E-Commerce Funnel, Revenue & Retention Analysis (Tableau + Python)

## Executive Summary
This project analyzes the end-to-end order lifecycle, revenue performance, and customer retention of a multi-seller e-commerce marketplace using real transactional data.  
The goal was to identify where orders drop off, what drives revenue growth, and how operational performance (especially delivery delays) impacts cancellations and repeat purchases.

Using Python for data preparation and Tableau for visualization, I built an analytics-ready dataset, defined core business KPIs, performed cohort retention analysis, and delivered an interactive dashboard with actionable insights.

---

## Business Problem
E-commerce platforms often focus heavily on customer acquisition, while under-analyzing:
- Where customers drop off after placing orders
- How delivery performance impacts cancellations and customer experience
- Whether revenue growth is driven by new customers or repeat purchases

Key questions addressed:
- What is the order funnel from purchase to delivery?
- How do cancellations and late deliveries affect realized revenue?
- Are customers returning after their first purchase?
- Which cohorts generate higher long-term value?

---

## Methodology

### 1. Data Preparation (Python / Pandas)
- Loaded raw transactional CSV files (orders, order items, payments, customers)
- Cleaned and parsed timestamps
- Engineered business metrics such as:
  - Delivery time (days)
  - Late delivery flag
  - Order-level revenue (GMV)
  - Purchase month and cohort month
- Aggregated item-level and payment-level data to the correct order grain
- Exported analytics-ready tables for visualization

### 2. Metrics & Analysis
- Funnel metrics: total orders, delivered orders, cancellations
- Revenue metrics: GMV, Average Order Value (AOV)
- Operational metrics: late delivery rate, average delivery time
- Customer analytics:
  - Cohort retention matrix
  - Repeat purchase rate
  - Cohort-level Lifetime Value (LTV)

### 3. Visualization (Tableau Public)
- Built KPI tiles for executive-level monitoring
- Created trend analyses for orders, revenue, and operations
- Designed a cohort retention heatmap to visualize customer behavior over time
- Assembled a multi-section interactive dashboard for business stakeholders

---

## Results & Key Insights
- A significant portion of orders are canceled before delivery, representing lost revenue.
- Late deliveries are strongly associated with higher cancellation rates.
- Revenue growth is driven primarily by order volume rather than increases in AOV.
- Customer retention drops sharply after the first purchase, with a relatively low repeat purchase rate.
- Later customer cohorts show lower retention and LTV, suggesting declining customer quality or experience over time.

---

## Next Steps
- Segment sellers or regions by late delivery risk and prioritize operational improvements.
- Introduce post-purchase engagement strategies to improve first-to-second purchase conversion.
- Analyze product categories and sellers to identify high-risk cancellation drivers.
- Extend the analysis with A/B testing data to measure the impact of delivery or messaging improvements.
- Rebuild key metrics in SQL to support production-scale analytics pipelines.

---

## Tools Used
- Python (pandas, numpy)
- Tableau Public (web)
- Jupyter Notebook
- Real-world e-commerce transactional dataset

---

## Dashboard
📊 **Interactive Tableau Dashboard:**  
*(Add your Tableau Public link here)*

