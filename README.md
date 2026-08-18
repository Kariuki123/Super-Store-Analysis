# 🏬 Super Store Analysis | Sales & Profit Intelligence Dashboard

An end-to-end Business Intelligence solution designed to analyze retail sales performance, customer behavior, product profitability, and regional market trends using Power BI.

This project demonstrates advanced data modeling, business-focused KPI design, DAX measures, data transformation with Power Query, and interactive dashboard development to support executive decision-making.

---

# 📌 Table of Contents

- Project Overview & Business Problem
- Data Architecture & Modeling
- Data Preparation & Transformation
- Power BI Dashboards
- Key Business Insights
- Strategic Recommendations
- Tools & Technologies
- Repository Structure
- Future Improvements

---

# 🏢 Project Overview & Business Problem

Retail organizations generate large volumes of transactional data daily, yet transforming that data into meaningful business insights remains a challenge.

Management required a centralized reporting solution to answer critical business questions regarding:

### Sales Performance
- Which regions generate the highest revenue?
- What products and categories drive sales growth?
- How are sales trending over time?

### Profitability Analysis
- Which products contribute the highest profits?
- Which categories operate at lower margins?
- Are high-sales products also profitable?

### Customer Analytics
- Which customer segments contribute the most revenue?
- What purchasing patterns exist across different markets?

### Regional Performance
- Which states and regions present growth opportunities?
- Where are sales underperforming?

To address these challenges, an interactive Power BI dashboard was developed to transform raw sales records into actionable business intelligence.

---

# 🗄️ Data Architecture & Modeling

To improve performance, scalability, and reporting efficiency, the dataset was modeled using a Star Schema approach.

## Fact Table

### Fact_Sales
**Grain:** One record per order transaction.

**Key Fields**
- Order ID
- Order Date
- Ship Date
- Customer ID
- Product ID
- Sales
- Quantity
- Discount
- Profit

---

## Dimension Tables

### Dim_Customer
Contains unique customer information.

**Attributes**
- Customer ID
- Customer Name
- Segment
- Region
- State
- City

### Dim_Product

Stores product-level information.

**Attributes**
- Product ID
- Product Name
- Category
- Sub-Category

### Dim_Date

Built using a dynamic calendar table.

**Attributes**
- Date
- Month
- Quarter
- Year
- Month Name
- Year-Month

### Dim_Geography

Supports geographic reporting and visualization.

**Attributes**
- Country
- Region
- State
- City

---

# 🛠 Data Preparation & Transformation

Several data preparation processes were completed using Power Query:

### Data Cleaning

- Removed duplicates
- Handled missing values
- Standardized data formats
- Corrected inconsistent categorical values

### Data Transformation

- Created date hierarchies
- Optimized data types
- Established table relationships
- Calculated business metrics

### Data Modeling

- Implemented star schema architecture
- Created relationship keys
- Optimized filtering behavior
- Improved report performance

---

# 📊 Power BI Dashboards

## Page 1: Executive Sales Performance Dashboard

Provides a high-level overview of business performance through key metrics and trend analysis.

### KPIs

- Total Sales
- Total Profit
- Profit Margin
- Total Orders
- Quantity Sold
- Average Order Value

### Visual Analysis

- Monthly Sales Trend
- Monthly Profit Trend
- Regional Performance
- Category Contribution
- Segment Analysis

### Business Value

Allows executives to quickly evaluate overall company performance and identify areas requiring attention.

---

## Page 2: Product & Profitability Analysis

Focuses on understanding which products and categories create the most business value.

### Analysis Includes

- Sales by Category
- 


