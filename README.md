# Pharmacy Sales & Profitability Performance

## Executive Summary

This project delivers an end-to-end sales and profitability performance analysis for a multi-location pharmacy business. The dashboard is designed to support executive, operational, and commercial decision-making by translating transactional data into actionable insights across financial performance, regional efficiency, and product profitability.

The solution emphasizes KPI governance, trend analysis, and performance benchmarking, aligning with best practices expected at a Senior Data Analyst level.

---

## Business Problem
### Pharmacy leadership requires timely and reliable insight to:

- Understand overall financial health

- Identify profit leakage driven by cost inefficiencies or low-margin products

- Evaluate regional and store-level performance disparities

- Assess the true impact of promotional activities on profitability

- Raw transactional data alone is insufficient for strategic decisions without structured modeling and performance metrics.

---

## Analytical Objectives

- Establish a single source of truth for revenue, cost, profit, and volume KPIs

- Compare Year-to-Date (YTD) performance against Last Year (LY) benchmarks

- Identify top and bottom contributors across pharmacies, regions, and products

- Quantify promotion effectiveness beyond revenue, with margin context

- Enable drill-down analysis from executive summary to operational detail

  ---
  
## Dashboard Architecture
### The dashboard is structured into three analytical layers:

### 1. Executive Overview
### A high-level performance snapshot designed for senior stakeholders:
- Revenue, Total Cost, Profit, Units Sold, and Average Selling Price (ASP)
- YTD vs LY variance analysis
- Monthly revenue and profit trend analysis
- Top 5 pharmacies by revenue contribution
- Promotion profit comparison by year

### 2. Regional & Location Performance
### Focused on geographic efficiency and scale:
- Revenue contribution by country
- Cost vs profit comparison by city
- Top revenue-generating regions
- Geographic visualization of cost distribution

### 3. Product & Commercial Performance
### Evaluates product strategy and promotional effectiveness:
- Revenue and profit by product category
- High-performing vs underperforming categories
- Promoted vs non-promoted revenue and profit
- Top 5 and bottom 5 brands by profit contribution
- Revenue and cost comparison by pharmacy type (Urban, Suburban, Rural)
- Top products by units sold, profit, and margin

---

## KPI (Governance)
- Revenue: Total sales value generated from product transactions
- Total Cost: Aggregated procurement and operational cost
- Profit: Revenue minus total cost
- Average Selling Price (ASP): Revenue divided by total units sold
- YTD / LY Metrics: Standardized time intelligence measures for performance comparison

--- 

## Methodology
- Data modeling using a star schema (fact sales with supporting dimension tables)
- DAX-based calculations for time intelligence and profitability metrics
- Data validation through cross-checks between totals, trends, and drill-down views
- Performance optimization for responsive filtering and slicing

---

## Key Insights
- Prescription products are the primary revenue and profit drivers, while medical devices underperform
- Promotions increase revenue but require tighter margin controls to avoid profit dilution
- Urban pharmacies consistently outperform suburban and rural locations
- Certain regions exhibit high revenue but disproportionately high costs, indicating efficiency gaps

---

## Recommendations
- Optimize pricing and cost structure in underperforming regions
- Focus promotional campaigns on high-margin products rather than volume-only growth
- Reassess low-performing product categories and brands
- Strengthen inventory planning based on top-selling and high-profit items
- Use regional performance insights to guide expansion and resource allocation

---

## Tools & Technologies
- **Power BI** – Data modeling, DAX calculations, and visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures for sales, profit, and performance metrics

---

## About Me
- Opeyemi Arabambi
- Data Analyst (Healthcare & Business Analytics)
