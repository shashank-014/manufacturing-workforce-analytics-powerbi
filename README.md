# Manufacturing & Workforce Analytics Dashboard (Power BI)

## Overview
This project presents an end-to-end manufacturing and workforce analytics solution built using **Power BI**.
It integrates production, cost, and employee performance data to deliver actionable insights for operational efficiency, cost control, and workforce planning.

The dashboard is designed for **decision-makers**, combining clean data modeling, advanced DAX measures, and interactive visuals.

---

## Business Problem
Manufacturing efficiency, production cost, and employee performance are deeply interconnected.
This project aims to answer:
- Which products and countries drive higher production costs?
- How efficiently are warehouses and manufacturing locations utilized?
- How is the workforce distributed, and does salary correlate with performance?
- Are there operational anomalies that require attention?

---

## Datasets Used
**Manufacturing Production Data**
- ProductID, ProductType, ProductionDate
- ProductionCost, QuantityProduced
- CountryOfOrigin, WarehouseLocation

**Employee Performance Data**
- EmployeeID, Department, HireDate
- Salary, PerformanceRating
- CountryOfOperation, ProductID
- Employee Training Records

---

## Key Features & Analysis
- Cleaned and standardized **500K+ production records**
- Built a **relational data model** using ProductID (one-to-many)
- Created **25+ DAX measures**, including:
  - Cost per Unit
  - Average Performance Rating
  - Employee Tenure
- Time-based analysis using Year-Month derived date columns
- Advanced analytics:
  - Salary vs Performance correlation
  - Production & cost trend forecasting
  - Explainable anomaly detection (high cost & low quantity)

---

## Dashboard Pages
### 1. Executive Overview
- Total Production, Cost, Cost per Unit
- Production vs Cost trends
- Cost efficiency by product and country

### 2. Employee & Performance Analysis
- Workforce distribution by department
- Performance ratings by department
- Salary vs performance analysis
- Salary trends over time

### 3. Risk & Anomaly Analysis
- High-cost and low-quantity anomaly detection
- Warehouse efficiency comparison
- Operational risk indicators

---

## Key Insights
- Production costs remain stable despite volume fluctuations
- Higher salary does not guarantee higher performance
- Workforce distribution is balanced across departments
- Operational anomalies are isolated, not systemic

---

## Tools & Technologies
- **Power BI**
- Power Query
- DAX
- SQL-style data modeling
- Time-series analysis
- Business Intelligence best practices

---

## How to Use
1. Download the `.pbix` file from the `dashboard/` folder
2. Open in Power BI Desktop
3. Interact with filters for department, country, product type, and time

---

## Author
**Shashank Kumar**  
Data Analyst | AI & ML Enthusiast  
