# Project Overview
Analyzing Delivery Performance and Order Trends in E-Commerce using dataset from Kaggle. (Brazilian E-Commerce Public Dataset by Olist)

This dataset comes from the Brazilian e-commerce platform **Olist**. It contains information on approximately **100,000** orders from **2016 to 2018**, made across multiple marketplaces in Brazil. 

This project analyzes order and delivery performance between 2016 and 2018, focusing on speed, reliability, and regional trends.
It combines SQL queries for data preparation with a Tableau dashboard for visualization.
The dashboard highlights:
- Total Orders (2016–2018)
- Average Order Cycle Time (Days)
- On‑Time Delivery Rate (%)
- Segment‑level comparisons (High: >200, Medium: 50-199, Low: <50)
- Regional monthly order trends (Top 3 regions in 2018)


## Project Goals

1. **Evaluate seller delivery performance**  
   Compare slow vs fast sellers using delivery time metrics to identify potential inefficiencies in supplier fulfillment or warehouse operations.

2. **Assess delivery reliability and its impact on customer experience**  
   Measure the on-time delivery rate to understand how consistently delivery promises are met, which may influence customer satisfaction and retention.

3. **Identify high-demand shipping regions**  
   Analyze order distribution by region to support logistics planning, resource allocation, and strategic inventory placement.

## Tech Stack
- Python (Kaggle Notebook) → data cleaning, preprocessing, and exploratory analysis
- SQL → queries, joins, aggregations, and KPI calculations
- Tableau → dashboard design and visualization
- GitHub → project hosting, documentation, and version control


/sql          → SQL scripts (queries, schema, ETL steps)
/python       → Kaggle notebook (.ipynb)
/tableau      → Tableau workbook (.twb)
/screenshots  → Dashboard screenshots
/docs         → Documentation and notes
README.md     → Project overview
