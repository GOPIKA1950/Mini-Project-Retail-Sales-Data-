# Mini-Project-Retail-Sales-Data-
Retail Sales Data Analysis project using Excel &amp; Power BI. Performed data cleaning, null value handling, transformation, Pivot Tables, DAX measures, and interactive dashboards for sales insights.
# 🛒 Retail Store Sales Analysis Dashboard

## 📌 Project Overview
This project focuses on cleaning, transforming, analyzing, and visualizing a Retail Store Sales dataset using **Microsoft Excel** and **Power BI**. The dataset contained missing values, duplicate records, inconsistent text formats, and required additional calculated fields for meaningful business analysis. After data preparation, interactive dashboards were developed to generate insights into sales performance, customer behavior, product trends, and payment preferences.

## 🎯 Project Objectives
* Clean and preprocess raw retail sales data
* Handle missing values and duplicate records
* Standardize inconsistent data entries
* Create calculated columns for enhanced analysis
* Perform exploratory data analysis using Pivot Tables
* Build interactive Power BI dashboards
* Generate business insights and recommendations

## 🛠️ Tools & Technologies
### Microsoft Excel
* Data Cleaning
* Data Transformation
* Pivot Tables
* Pivot Charts
* Excel Functions & Formulas

### Power BI
* Data Modeling (Star Schema)
* DAX Measures
* Interactive Dashboards
* KPI Cards
* Drill-Down Analysis
* Cross Filtering

## 📂 Dataset Information
The dataset contains retail transaction data including:
* Transaction ID
* Customer ID
* Transaction Date
* Category
* Item
* Quantity
* Price Per Unit
* Total Spend
* Payment Method
* Location
* Discount Applied
* Customer Spending Tier

## 🧹 Data Cleaning & Transformation
### Data Quality Improvements
✔ Removed duplicate records
✔ Handled missing values
✔ Standardized inconsistent category names
✔ Applied data validation and formatting
✔ Created calculated columns
✔ Organized supporting calculations and analysis sheets

### Missing Value Treatment

| Column         | Method Used                    |
| -------------- | ------------------------------ |
| Item           | Replaced with "Item_0_Unknown" |
| Price Per Unit | Average Imputation             |
| Quantity       | Median Imputation              |
| Total Spend    | Median Imputation              |

### Calculated Columns Created
* Item Category
* Item Number / ID
* Transaction Month
* Day of Week
* Net Total (After Discount)
* Spend Tier

## 📊 Excel Analysis

### Pivot Tables & Charts

#### Revenue by Location and Payment Method

* Clustered Column Chart

#### Monthly Revenue & Volume Trends

* Line Chart

#### Product Performance by Category

* Stacked Bar Chart

#### Day-of-Week Purchasing Habits

* Column Chart

#### Discount Impact Analysis

* Doughnut Chart

#### Customer Spend Tier Breakdown

* Horizontal Bar Chart


# 📈 Power BI Dashboard

## Dashboard 1: Retail Sales Overview

### KPI Cards

* Total Sales
* Average Sales
* Total Transactions
* Total Quantity Sold

### Visualizations

* Line Chart – Sales by Month
* Column Chart – Sales by Category
* Donut Chart – Sales by Payment Method
* Donut Chart – Sales by Location
* Gauge Chart – Sales Performance

### Analysis Methods

* Trend Analysis
* KPI Monitoring
* Category Comparison
* Channel Analysis
* Payment Analysis


## Dashboard 2: Product & Category Analysis

### KPI Cards

* Average Price
* Average Sales
* Total Sales
* Total Quantity

### Visualizations

* Donut Chart – Quantity by Category
* Column Chart – Item Count by Category
* Treemap – Sales by Category
* Bar Chart – Sales by Item
* Matrix Table – Category vs Payment Method
* Funnel Chart – Category Ranking

### Analysis Methods

* Product Performance Analysis
* Category Analysis
* Revenue Contribution Analysis
* Ranking Analysis


## Dashboard 3: Time, Location & Customer Analysis

### KPI Cards

* Total Sales
* Total Transactions
* Total Quantity
* Average Sales

### Visualizations

* Line Chart – Sales by Month
* Column Chart – Transactions by Month
* Donut Chart – Payment Method Analysis
* Scatter Chart – Sales vs Quantity
* Bar Chart – Sales by Customer
* 100% Stacked Bar Chart – Location & Payment Method
* Pie Chart – Sales by Day of Week

### Analysis Methods

* Time-Series Analysis
* Customer Analysis
* Location Analysis
* Payment Behavior Analysis
* Correlation Analysis


## 📐 Data Model
A **Star Schema** data model was implemented in Power BI to improve performance and reporting efficiency.

### Dimension Tables
* Dim_Date
* Dim_Category
* Dim_Payment
* Dim_Location

### Relationships
* One-to-Many (1:*)
* Single Direction Filtering

## 📊 DAX Measures

```DAX
Total Sales = SUM(Sales[Total Spend])

Total Quantity = SUM(Sales[Quantity])

Total Transactions =
DISTINCTCOUNT(Sales[Transaction ID])

Average Sales =
AVERAGE(Sales[Total Spend])

Average Price =
AVERAGE(Sales[Price Per Unit])


## 🔍 Key Insights

* Total sales exceeded ₹1.6M across approximately 13K transactions.
* Customer purchasing behavior varied across payment methods and locations.
* Certain product categories generated significantly higher revenue.
* Monthly sales trends highlighted peak and low-performing periods.
* Discount strategies influenced customer spending patterns.
* Customer spend tiers helped identify high-value customers.

## 🚀 Business Recommendations

* Focus marketing efforts on high-performing categories.
* Increase inventory for top-selling products.
* Optimize discount campaigns to maximize revenue.
* Improve sales performance during low-performing months.
* Strengthen customer retention strategies for high-value customers.
* Promote preferred payment methods to improve customer experience.


## 📷 Dashboard Preview

Add screenshots of:

* Dashboard 1: Retail Sales Overview
* Dashboard 2: Product & Category Analysis
* Dashboard 3: Time, Location & Customer Analysis


## 👩‍💻 Author

**Gopika A.S.**

B.Com Finance Graduate

Aspiring Data Analyst

Skills: Excel | Power BI | SQL | Python | AI-Driven Data Analytics

LinkedIn: www.linkedin.com/in/gopika-anil-319352416

## 📌 Conclusion
This project demonstrates practical skills in data cleaning, transformation, business analysis, and dashboard development using Excel and Power BI. The interactive dashboards provide valuable insights into sales performance, customer behavior, category profitability, and business growth opportunities.
