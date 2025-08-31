# Profit-Loss-Supply-Analytics-
Analytics dashboard built with SQL Server and Power Bi to visualize profit, loss, supply shortages, and demand-availability trends

# Data Visualization for Business Optimization  

## Overview  
This project demonstrates the use of Power BI, SQL Server, and DAX to transform raw demand and availability data into meaningful business insights. The focus is on tracking profit, loss, demand, supply shortages, and daily averages through an interactive dashboard.  

---

## Problem Statement  
Businesses face challenges such as:  
- Limited visibility into demand vs. availability.  
- Difficulty tracking profit, losses, and shortages.  
- Raw data stored in databases without clear visualization for decision-making.  

---

## Solution  
The project provides:  
- Data Integration from SQL Server into Power BI.  
- Data Cleaning & Joins to prepare structured datasets.  
- DAX Measures to calculate business KPIs.  
- Interactive Dashboards to display performance metrics.  

---

## Data Model  

### Measure Table  
- Average Availability Per Day  
- Average Demand Per Day  
- Average Loss Per Day  
- Total Availability  
- Total Demand  
- Total Loss  
- Total Number of Days  
- Total Profit  
- Total Supply Shortage  

### Demand/Availability Data  
- Availability  
- Demand  
- Order Date (DD-MM-YYYY)  
- Product ID  
- Product Name  
- Profit/Loss  
- Unit Price  

---

## Workflow  
1. Install and configure SQL Server.  
2. Import data into test environment.  
3. Apply joins and transformations in SQL Server.  
4. Import data into Power BI Desktop.  
5. Create DAX Measures & KPIs.  
6. Import data into production environment.  
7. Clean data using SQL transformations.  
8. Publish and validate reports in Power BI Service.  

---

## Dashboard Insights  

### Financial Metrics  
| Metric              | Value  |  
|---------------------|--------|  
| Total Profit        | 22K    |  
| Total Loss          | 97K    |  
| Average Daily Loss  | 88.84  |  

### Supply & Demand Metrics  
| Metric                       | Value |  
|------------------------------|-------|  
| Average Demand per Day       | 3.40  |  
| Average Availability per Day | 2.87  |  
| Total Supply Shortage        | 579   |  

---

## Outcome  
The dashboards provide a clear view of profitability, losses, demand trends, and shortages, supporting data-driven business optimization.

<img width="1741" height="845" alt="Screenshot 2025-08-31 130443" src="https://github.com/user-attachments/assets/85b77b61-b2ac-43a0-a050-db6d514f4d39" />

