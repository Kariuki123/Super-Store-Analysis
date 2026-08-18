# 📊 Super Store Analysis | Sales & Profit Intelligence Dashboard

An end-to-end Business Intelligence solution built in Power BI to analyze retail sales performance, profitability, customer behavior, and regional trends across a Super Store business.

This project transforms transactional sales data into actionable insights through interactive dashboards, KPI monitoring, profitability analysis, and customer intelligence reporting, enabling stakeholders to make data-driven decisions.

---

## 📸 Dashboard Preview

### Executive & Sales Overview

Images/Executive.png

The Executive Dashboard provides a high-level overview of business performance through sales KPIs, category analysis, regional performance, and product-level sales tracking.

### Profitability & Customer Insights

Images/Insights.png

The Insights Dashboard focuses on profitability drivers, customer contribution analysis, profit margin performance, and segment-level business insights.

---

# 📌 Table of Contents

- Project Overview & Business Problem
- Business Objectives
- Data Modeling
- Dashboard Features
- Key Performance Indicators
- Key Business Insights
- Strategic Recommendations
- Tools & Technologies
- Repository Structure

---

# 🏢 Project Overview & Business Problem

Retail organizations generate large volumes of sales and customer data every day. However, identifying the factors driving revenue growth, profitability, and customer performance can be challenging without a centralized analytics platform.

This project was developed to help decision-makers answer critical business questions regarding:

### Sales Performance
- Which categories generate the most revenue?
- Which products drive overall sales performance?
- How do sales trends change throughout the year?

### Profitability Analysis
- Which products create the greatest profit?
- What is the company's overall profit margin?
- Which customer segments contribute most to profitability?

### Regional Performance
- Which regions generate the highest sales?
- Where are expansion opportunities available?

### Customer Analytics
- Who are the most valuable customers?
- Which customer segments contribute the largest share of profit?

---

# 🎯 Business Objectives

The dashboard was designed to:

- Monitor overall sales and profitability performance.
- Track monthly business growth.
- Identify best-performing products and categories.
- Analyze regional sales distribution.
- Evaluate customer profitability.
- Support strategic decision-making through interactive reporting.

---

# 📈 Key Performance Indicators (KPIs)

The Executive Dashboard tracks the following key metrics:

| KPI | Value |
|-------|---------|
| Total Sales | $2.29M |
| Total Profit | $286.8K |
| Total Orders | 5,009 |
| Profit Margin | 12.49% |

Additional metrics analyzed include:

- Sales by Category
- Sales by Region
- Monthly Sales Trends
- Customer Profitability
- Profit by Segment
- Top Products by Sales
- Top Sub-Categories by Profit

---

# 🗄️ Data Modeling

The data model follows a Star Schema approach to improve performance and reporting efficiency.

### Fact Table

#### Fact_Sales
Contains transactional order data including:

- Order ID
- Order Date
- Customer
- Product
- Sales
- Quantity
- Discount
- Profit

### Dimension Tables

#### Dim_Product
- Product Name
- Category
- Sub-Category

#### Dim_Customer
- Customer Name
- Segment
- Region

#### Dim_Date
- Year
- Month
- Quarter

#### Dim_Geography
- Region
- State

---

# 📊 Dashboard Features

## Page 1: Executive & Sales Overview

The Executive Dashboard provides a comprehensive summary of company performance.

### Key Highlights

✅ Total Sales of **$2.29M**

✅ Total Profit of **$286.8K**

✅ Profit Margin of **12.49%**

✅ Total Orders of **5,009**

### Analyses Included

- Monthly Sales Trend
- Sales by Category
- Sales by Region
- Top 5 Products by Sales
- Interactive Filters by:
  - Year
  - Region
  - Category
  - Product

---

## Page 2: Profitability & Customer Insights

This dashboard focuses on understanding profit drivers and customer contribution.

### Key Highlights

✅ Total Profit of **$286.82K**

✅ Profit Margin of **12.49%**

✅ Total Customers of **793**

✅ Average Sales per Customer of approximately **$3K**

### Analyses Included

- Monthly Sales vs Profit Trend
- Top 5 Sub-Categories by Profit
- Profit by Customer
- Profit Distribution by Segment
- Interactive Filtering
- Customer Performance Analysis

---

# 💡 Key Business Insights

## Technology Leads Sales Performance

Technology is the highest revenue-generating category, outperforming Furniture and Office Supplies.

### Implication
Increased focus on technology inventory and marketing campaigns can drive additional revenue growth.

---

## Western Region Drives Revenue

The West region contributes the highest sales volume, followed closely by the East region.

### Implication
These regions represent the strongest markets and may offer the greatest opportunity for expansion.

---

## Copier Products Generate Strong Profitability

Copiers are the most profitable sub-category, followed by Phones and Accessories.

### Implication
Management should prioritize high-margin product categories when planning inventory investments.

---

## Consumer Segment Dominates Profit Contribution

The Consumer segment contributes approximately 46.76% of total profit, making it the largest customer segment by profitability.

### Implication
Customer retention and loyalty programs should primarily target consumer customers.

---

## Sales Peak Towards Year-End

Monthly sales performance increases significantly during the final quarter of the year, especially in November and December.

### Implication
Seasonal inventory planning and promotional campaigns should be aligned with year-end demand.

---

# 🎯 Strategic Recommendations

### Increase Investment in High-Profit Categories

Prioritize Copiers, Phones, and Accessories due to their strong profit contribution.

### Expand Presence in High-Performing Regions

Focus growth initiatives within the West and East regions while identifying opportunities to improve performance in lower-performing markets.

### Improve Profitability Monitoring

Track products that generate strong sales but lower profit margins to optimize pricing and discount strategies.

### Strengthen Customer Loyalty Programs

Develop targeted marketing campaigns for Consumer and Corporate customers to increase retention and lifetime value.

### Leverage Forecasting Models

Introduce predictive analytics to improve sales forecasting, inventory planning, and resource allocation.

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|--------|----------|
| Power BI Desktop | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | Business Calculations & KPIs |
| Excel / CSV | Data Source |
| GitHub | Version Control & Documentation |

---

# 📂 Repository Structure

```text
Super-Store-Analysis/
│
├── Data/
│   └── Source datasets
│
├── Images/
│   ├── Executive.png
│   └── Insights.png
│
├── Superstore.pbix
│
└── README.md
```

---

# 👨‍💻 Author

## John Kariuki

** | Data Analyst | Power BI Developer**

📍 Nairobi, Kenya

GitHub: https://github.com/Kariuki123

---

## ⭐ Project Goal

The objective of this project is to transform retail transaction data into meaningful business intelligence that supports strategic decision-making, improves profitability, identifies growth opportunities, and delivers actionable insights through interactive Power BI dashboards.
