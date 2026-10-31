# 📊 Sample Superstore Sales & Profit Analysis Dashboard

![Excel](https://img.shields.io/badge/Data-Excel-green?style=for-the-badge&logo=microsoftexcel)
![Tableau](https://img.shields.io/badge/Visualization-Tableau-blue?style=for-the-badge&logo=tableau)
![Analytics](https://img.shields.io/badge/Domain-Data%20Analytics-orange?style=for-the-badge)

## 📌 Project Overview

This project focuses on analyzing the **Sample Superstore Sales Dataset** to understand sales performance, profitability, customer segments, regional contributions, and product category trends.

An interactive dashboard was developed using **Tableau** to transform raw sales data into meaningful business insights and support data-driven decision-making.

The project identifies profitable business areas, underperforming regions, and opportunities for improving overall business performance.

## 🎯 Project Objectives

- Analyze overall sales and profit performance.
- Identify the most profitable regions.
- Understand customer segment performance.
- Evaluate product category and sub-category sales.
- Analyze monthly order quantity trends.
- Identify loss-making products and business areas.
- Generate actionable business recommendations.

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Dataset storage, inspection and preparation |
| Tableau Desktop | Dashboard development and data visualization |
| Python | Supporting dataset analysis and report generation |
| PDF | Dashboard and project report documentation |
| GitHub | Project documentation and version control |

## 📂 Dataset Description

**Dataset:** Sample Superstore Sales Dataset

The Excel workbook contains three sheets:

| Sheet Name | Description |
|---|---|
| Orders | Main transactional sales dataset |
| Returns | Returned order information |
| Users | Regional manager information |

### 📋 Orders Dataset Fields

The Orders sheet contains 8,399 records and 23 original fields.

**Customer & Location Information**
- Customer Name
- Customer Segment
- City
- State
- Zip Code
- Region

**Order Information**
- Row ID
- Order ID
- Order Date
- Ship Date
- Ship Mode
- Order Priority

**Product Information**
- Product Category
- Product Sub-Category
- Product Name
- Product Container

**Sales & Financial Information**
- Sales
- Profit
- Order Quantity
- Discount
- Unit Price
- Shipping Cost
- Product Base Margin

**Analysis Period:** 2009–2012

## 📈 Key Performance Indicators (KPIs)

The project analyzes the following business metrics:

| KPI | Value |
|---|---:|
| Total Sales | 14,915,600.82 |
| Total Profit | 1,521,767.96 |
| Total Orders | 5,496 |
| Total Order Records | 8,399 |
| Profit-to-Sales Ratio | 10.20% |

*Note: Financial values are presented in the dataset's recorded units; the workbook does not explicitly specify a currency.*

## 📊 Dashboard Analysis

### 1. 🌍 Regional Sales Analysis
- Central is the highest sales-contributing region.
- Central also generates the highest total profit.
- South has the highest regional profit margin.
- West has the lowest regional profit margin.

### 2. 👥 Customer Segment Analysis
- Corporate is the leading customer segment by sales and profit.
- Consumer and Home Office segments also contribute significantly.
- Regional segment comparisons help identify differences in customer profitability.

### 3. 📦 Product Category Analysis
- Technology generates the highest sales and profit.
- Furniture has a comparatively lower profit margin.
- Office Supplies contributes significantly to order quantity.

### 4. 📅 Monthly Sales Trend Analysis
- May records the highest total order quantity.
- November records the lowest total order quantity.
- Monthly analysis helps understand demand patterns and plan inventory.

### 5. 💰 Profit vs Sales Analysis
- Sales and profit generally show a positive relationship.
- Several order lines generate negative profit.
- High sales do not always guarantee high profitability.

### 6. 🚚 Shipping Analysis
- Regular Air generates the highest absolute sales and profit among shipping modes.
- Delivery Truck has the lowest profit margin.
- Shipping performance can help identify opportunities for cost optimization.

## 🔍 Key Business Insights

1. Central is the strongest region in terms of sales and total profit.
2. South demonstrates the highest regional profit margin.
3. Technology is the most profitable product category.
4. Corporate customers contribute the largest share of sales and profit.
5. Furniture requires attention due to its comparatively low profitability.
6. Tables and Bookcases are important loss-making sub-categories to investigate.
7. May is the peak month for order quantity.
8. A significant proportion of order lines generate negative profit.

## 💡 Business Recommendations

- Focus on improving profitability in the West region.
- Review pricing and discount strategies for Furniture products.
- Investigate loss-making sub-categories such as Tables and Bookcases.
- Maintain strong relationships with high-performing customer segments.
- Optimize shipping costs and delivery methods.
- Use monthly demand trends to improve inventory planning.
- Monitor negative-profit transactions regularly.
- Collect return reasons and returned product quantities for deeper analysis.

## 📊 Dashboard Features

The Tableau dashboard provides visual analysis of:

- Profit by Region and Customer Segment.
- Sales Contribution by Region.
- Profit vs Sales Relationship.
- Order Quantity by Month.
- Regional and product performance comparisons.

## 📁 Project Structure

```text
Sample-Superstore-Sales-Analysis/
│
├── Dataset/
│   └── Sample-Superstore-Sales.xls
│
├── Tableau/
│   └── Tableau-Dashboard-1.twbx
│
├── Dashboard/
│   └── Dashboard.pdf
│
├── Report/
│   └── Sample_Superstore_Sales_Project_Report.pdf
│
└── README.md
```

## 🚀 How to Use This Project

1. Clone or download this repository.
2. Open the Excel dataset to explore the raw sales information.
3. Open the `.twbx` file using Tableau Desktop.
4. Explore the dashboard visualizations and business insights.
5. Read the PDF report for detailed analysis and conclusions.

## 📌 Conclusion

This project demonstrates how data analytics and visualization tools can transform raw business data into meaningful insights.

Using Excel and Tableau, the project analyzes sales, profit, regional performance, customer segments, product categories, and monthly trends.

The findings help identify business opportunities, understand profitability challenges, and support better strategic decisions.

## 👨‍💻 Author

**Agam**

📊 Aspiring Data Analyst | Data Visualization | Business Intelligence

---

⭐ If you find this project useful, consider giving this repository a star!

#DataAnalytics #Tableau #Excel #BusinessIntelligence #DataVisualization #SalesAnalysis
