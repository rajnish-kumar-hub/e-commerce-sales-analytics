# E-Commerce Sales & Customer Analytics Dashboard | Power BI

An interactive Power BI project analyzing e-commerce sales, profitability, customer behavior, product performance, marketing effectiveness, operational efficiency, and geographic trends across 2021–2025.

## Project Overview

This project transforms e-commerce data into an interactive business intelligence dashboard to support data-driven decision-making. It combines sales, customer, product, marketing, and operational metrics to help identify performance drivers, understand customer purchasing behavior, and evaluate business growth opportunities.

The dashboard consists of **7 analytical pages**, supported by a relational data model, a dedicated Date Table, and DAX-based KPIs.

## Business Objectives

- Evaluate sales growth, profitability, and monthly performance trends.
- Identify high-performing products, categories, and customer segments.
- Analyze customer acquisition, retention, and lifetime value.
- Compare marketing channels based on sales, profitability, and customer value.
- Assess order fulfillment, delivery performance, cancellations, and returns.
- Examine geographic variations in sales and profitability.

## Dashboard Pages & Analysis

### 1. Executive Overview
Provides a high-level summary of business performance through KPI cards, sales trends, profit trends, and country-level comparisons.

**Metrics analyzed:**
- Net Sales and Profit
- Profit Margin
- Total Transactions and Total Orders
- Average Order Value (AOV)
- Year-over-Year (YoY) Sales Growth
- Return Rate and Cancellation Rate

**Business value:** Enables stakeholders to assess overall performance and identify areas requiring deeper investigation.

### 2. Sales & Profitability
Examines revenue generation, cost structure, profit trends, and the relationship between discounts and profitability.

**Analysis includes:**
- Gross Sales versus Net Sales
- Product Cost, Shipping Cost, and Tax
- Discount impact on sales and profit
- Monthly sales and profit trends
- Product-category profitability comparisons
- Discount Rate versus Profit Margin

**Business value:** Helps evaluate margin pressure, understand cost drivers, and assess whether discounting is associated with stronger sales but weaker profitability.

### 3. Product Performance
Evaluates product and category performance using revenue, profit, sales volume, order volume, and customer ratings.

**Analysis includes:**
- Top-performing products by revenue and profit
- Product-category comparisons
- Quantity sold and order volume
- Product revenue versus product profit
- Product ratings and profit margins

**Business value:** Supports product portfolio evaluation and helps identify products that generate strong revenue, healthy margins, or potential performance concerns.

### 4. Customer Analytics
Analyzes customer value, purchasing patterns, demographic segments, and geographic customer distribution.

**Analysis includes:**
- Total Customers and New Customers
- Repeat Customers and Repeat Customer Percentage
- Customer Lifetime Value (CLV)
- Customer Acquisition Cost (CAC)
- Sales and profit by customer segment
- Customer analysis by age group, city, region, and country
- Customer-level revenue and order comparisons

**Business value:** Helps distinguish customer groups by commercial value and investigate opportunities to improve retention, repeat purchases, and acquisition efficiency.

### 5. Marketing & Channel Performance
Compares marketing channels using sales contribution, profit, order volume, customer value, and acquisition costs.

**Analysis includes:**
- Marketing-attributed Sales
- Sales and profit by marketing channel
- Channel-level order volume and AOV
- Profit margin comparisons
- Customer Lifetime Value versus Customer Acquisition Cost
- Channel-level performance comparisons

**Business value:** Helps assess which channels contribute to revenue and profit and whether customer value justifies acquisition costs.

### 6. Operations & Customer Experience
Examines order fulfillment, delivery reliability, cancellations, returns, and customer feedback.

**Analysis includes:**
- Order status and delivery status
- Delayed Orders Percentage
- On-Time Delivery Percentage
- Average Delivery Days
- Cancellation Rate and Return Rate
- Return reasons
- Customer ratings versus delivery time
- Negative Review Percentage

**Business value:** Helps identify operational bottlenecks and investigate how fulfillment performance may relate to customer satisfaction and product returns.

### 7. Geographic Analysis
Compares business performance across countries using a map visualization and supporting performance table.

**Analysis includes:**
- Net Sales by Country
- Profit and Profit Margin by Country
- Total Orders and Average Order Value
- Total Customers by Country

**Business value:** Supports geographic performance comparisons and helps identify markets for further investigation, investment, or operational improvement.

## Key Performance Indicators (KPIs)

| KPI | Purpose |
|---|---|
| Net Sales | Measures sales after applicable deductions |
| Profit | Evaluates financial performance |
| Profit Margin | Measures profit relative to sales |
| Total Orders | Tracks order volume |
| Total Transactions | Tracks recorded transactions |
| Average Order Value | Measures average sales value per order |
| YoY Sales Growth | Tracks annual sales growth |
| Customer Lifetime Value | Estimates the value generated by a customer |
| Customer Acquisition Cost | Measures customer acquisition expenditure |
| Repeat Customer % | Measures the share of customers who purchase repeatedly |
| Return Rate | Tracks returned orders or items according to the implemented definition |
| On-Time Delivery % | Measures delivery reliability |

*The precise calculation of each metric depends on its DAX definition and the underlying data grain.*

## Key Analytical Findings

The dashboard is designed to investigate the following business questions:

1. **Sales performance:** How do monthly sales and profits change over time, and are there periods of growth or decline?
2. **Profitability:** Which product categories and markets contribute most to profit, and where are margins under pressure?
3. **Discount effectiveness:** How do discount rates relate to net sales and profit margins?
4. **Product performance:** Which products lead in sales, profit, and order volume, and do customer ratings differ across products?
5. **Customer value:** Which customer segments generate higher sales, profit, and lifetime value?
6. **Customer retention:** How do new and repeat customers contribute to the business, and how does repeat purchasing change over time?
7. **Marketing efficiency:** How do channels compare in sales, profitability, and customer acquisition cost relative to lifetime value?
8. **Operational efficiency:** How do delivery delays, cancellations, returns, and customer ratings vary?
9. **Geographic performance:** Which countries contribute the most sales and profit, and where are further growth opportunities worth investigating?

### Business Recommendations Framework

Use the observed results to develop evidence-based recommendations:

- **Sales and profitability:** Investigate declining margins, rising costs, or discount-heavy categories and prioritize actions based on their profit contribution.
- **Product strategy:** Review high-revenue and high-margin products separately to avoid confusing sales volume with profitability.
- **Customer retention:** Compare repeat-purchase behavior and lifetime value across segments to identify opportunities for targeted retention campaigns.
- **Marketing allocation:** Evaluate channel profitability alongside acquisition cost and customer lifetime value before reallocating budgets.
- **Operations:** Prioritize recurring causes of delivery delays, cancellations, and returns where the data indicates meaningful operational impact.
- **Geographic expansion:** Investigate markets with strong profitability and sustainable demand rather than relying on revenue alone.

## Technical Implementation

### Tools & Technologies
- **Power BI Desktop** — Dashboard development and interactive reporting
- **DAX** — KPI calculations and analytical measures
- **Data Modeling** — Relational data model connecting five datasets and a Date Table
- **Data Visualization** — KPI cards, line charts, bar charts, scatter plots, tables, and map visuals

### Implementation Workflow

1. **Data integration:** Combined five datasets with a dedicated Date Table.
2. **Data modeling:** Established relationships to support analysis across orders, customers, products, and related business dimensions.
3. **KPI development:** Implemented DAX measures for sales, profit, margins, orders, customer metrics, and operational performance.
4. **Dashboard design:** Organized the report into seven pages aligned with distinct business functions.
5. **Business analysis:** Used interactive visualizations to compare trends, segments, products, channels, and geographic performance.

## Repository Structure

```text
e-commerce-sales-analytics/
│
├── README.md
├── e-commerce.pbix
└── E-commerce dashboard/
    ├── executive-overview.png
    ├── sales-profitability.png
    ├── product-performance.png
    ├── customer-analytics.png
    ├── marketing-channel-performance.png
    ├── operations-customer-experience.png
    └── geographic-analysis.png
```

## How to Explore the Project

1. Download or clone this repository.
2. Open `e-commerce.pbix` in Power BI Desktop.
3. Navigate through the seven report pages.
4. Interact with available slicers and filters to explore performance across time periods, products, customer segments, marketing channels, and countries.

## Project Outcomes

- Built a **7-page interactive BI dashboard** covering seven business analysis areas.
- Integrated **five datasets and a Date Table** into a relational data model.
- Developed DAX-based KPIs to measure sales, profitability, customer value, marketing performance, and operational efficiency.
- Created a structured analytical framework to support evidence-based commercial and operational decisions.

## Future Improvements

- Add a verified executive summary with actual KPI values and quantified findings.
- Incorporate cohort analysis and customer retention trends.
- Evaluate channel profitability using clearly defined acquisition and lifetime-value calculations.
- Add forecasting or scenario analysis to support sales and profitability planning.
- Document data sources, transformation steps, and DAX measure definitions.

## Author

**Rajnish Kumar**

Aspiring Data Analyst | Power BI | DAX | Data Modeling | Business Intelligence

[LinkedIn](https://www.linkedin.com/in/rajnishks1605/) · [Github](https://github.com/rajnish-kumar-hub)
