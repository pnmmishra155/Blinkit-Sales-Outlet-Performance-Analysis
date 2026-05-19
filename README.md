# Blinkit-Sales-Outlet-Performance-Analysis
Developed an interactive Blinkit Sales Analysis Dashboard in Power BI to analyze outlet performance, product categories, sales trends, and customer ratings using business KPIs and data visualization techniques.


# Blinkit Sales Analysis Dashboard using Power BI

## Project Overview

This project focuses on analyzing Blinkit's sales performance, customer satisfaction, and inventory distribution using an interactive Power BI dashboard.

The dashboard provides actionable business insights by analyzing:
- Sales performance
- Product categories
- Outlet establishment trends
- Outlet size & location performance
- Customer ratings
- Inventory distribution

The goal of this project is to help stakeholders make data-driven business decisions through effective visualization and KPI analysis.

---

# Business Requirement

To conduct a comprehensive analysis of Blinkit's sales data in order to identify key insights, optimize outlet performance, improve customer satisfaction, and support business growth using Power BI.

---

# KPIs Requirements

The following key performance indicators (KPIs) were used in this dashboard:

| KPI | Description |
|---|---|
| Total Sales | Overall revenue generated from all products sold |
| Average Sales | Average revenue per sale |
| Number of Items | Total number of items sold |
| Average Rating | Average customer rating |
| Item Visibility | Visibility score of products |

---

# Dashboard Features

## Sales Analysis
- Total Sales by Fat Content
- Total Sales by Item Type
- Sales Trend by Outlet Establishment

## Outlet Analysis
- Sales by Outlet Size
- Sales by Outlet Location
- Outlet Type Performance

## Interactive Features
- Dynamic Filters
- Slicers
- KPI Cards
- Interactive Charts
- Drill-down Analysis

---

# Charts Used

| Chart Type | Purpose |
|---|---|
| Donut Chart | Sales contribution analysis |
| Bar Chart | Category comparison |
| Line Chart | Trend analysis |
| Stacked Column Chart | Segmented comparison |
| Matrix Table | Detailed KPI reporting |

---

# Tools & Technologies Used

- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Excel / CSV Dataset

---

# DAX Measures Used

```DAX
Total Sales = SUM(Blinkit[Sales])

Average Sales = AVERAGE(Blinkit[Sales])

No of Items = COUNT(Blinkit[Item Identifier])

Average Rating = AVERAGE(Blinkit[Rating])
```

---

# Key Business Insights

- Tier 3 outlets generated the highest sales
- Medium-sized outlets showed better performance
- Supermarket Type 1 contributed maximum revenue
- Low-fat products had strong customer demand
- Fruits and snack categories were top-performing items

---

# Dashboard Preview

## Main Dashboard
![Dashboard](https://github.com/pnmmishra155/Blinkit-Sales-Outlet-Performance-Analysis/blob/main/Blinkit-Sales-Outlet-Performance-Analysis-Dashboard.png)

---

# Project Workflow

1. Requirement Gathering
2. Data Walkthrough
3. Data Connection
4. Data Cleaning / Quality Check
5. Data Modeling
6. Data Processing
7. DAX Calculations
8. Dashboard Layout Designing
9. Charts Development & Formatting
10. Dashboard Development
11. Insights Generation

---

# Learning Outcomes

Through this project, I gained hands-on experience in:
- Data Cleaning
- Data Modeling
- DAX Calculations
- Dashboard Designing
- Business Intelligence Reporting
- Data Visualization
- Retail Sales Analysis

---

# Folder Structure

```text
Blinkit-Sales-Analysis-PowerBI/
│
├── Dataset/
│   └── blinkit_data.csv
│
├── Dashboard/
│   └── Blinkit_Dashboard.pbix
│
├── Screenshots/
│   └── dashboard_overview.png
│
└── README.md
```

---

# Conclusion

The Blinkit Sales Analysis Dashboard successfully transforms raw retail data into meaningful business insights using Power BI. The dashboard enables better understanding of customer behavior, outlet performance, and sales trends to support strategic business decisions.

---

# Author

Poonam Mishra

---


# Tags

`Power BI` `Data Analytics` `Business Intelligence` `Dashboard` `DAX` `Retail Analytics` `Data Visualization`
