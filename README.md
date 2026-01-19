# Online Retail Analytics

End-to-End Sales, Customer, and Geographic Revenue Analysis (2011)

## Project Overview

This project analyzes transactional data from a real-world online retail business to uncover revenue drivers, customer concentration, seasonal trends, and geographic performance.
The analysis focuses on answering business-critical questions:

- When does revenue peak and why?
- Which customers and countries drive the majority of revenue?
- How does unit volume differ from revenue contribution?
- Where is revenue concentrated outside the UK?

The project combines data cleaning, metric engineering, and interactive dashboards to move from raw transactions to decision-ready insights.

## Data Preparation

Before analysis, the dataset was cleaned to ensure accuracy and relevance:

- Removed cancelled and invalid transactions
- Excluded records with missing customer IDs
- Filtered out non-positive quantities and prices
- Created a Revenue metric using:
  Revenue = Quantity × UnitPrice

Only clean, meaningful transactions were used for downstream analysis.

## Key Business Insights (2011)

- Revenue peaks in November, reflecting strong seasonal demand.
- Customer revenue is highly concentrated, with a small number of customers contributing a disproportionate share.
- Revenue outside the UK is concentrated in Western Europe, led by the Netherlands and EIRE.
- Unit volume and revenue do not always align, highlighting pricing and product-mix effects.
- December revenue appears lower due to partial-month data availability, not a demand collapse.

# Dashboards & Analysis
  ## Power BI Dashboard
  The Power BI dashboard provides an interactive view of:
  - Monthly revenue trends (2011)
  - Top 10 customers by total revenue
  - Revenue concentration via KPI cards
  - Geographic revenue distribution (excluding the UK)
  
  File location:
  powerbi/online_retail_powerbi_dashboard.pbix

  ## Customer Overview Dashboard:
  <img width="1314" height="744" alt="Screenshot 2026-01-19 235844" src="https://github.com/user-attachments/assets/6db94835-20cc-40b7-9a85-fd05c189479d" /> 
  
  ## Geographic Overview Dashboard:
  <img width="1327" height="745" alt="Screenshot 2026-01-20 000156" src="https://github.com/user-attachments/assets/ed3ad092-c8af-4f05-9636-d50b58d54d88" />



  ## Tableau Dashboard
  Tableau was used for comparative visual analysis, including:
  - Top 10 countries by revenue and quantity (excluding UK)
  - Revenue vs. unit volume comparison
  - Geographic sales distribution

    File location:
    tableau\online_retail_dashboard_2011.twb

    ## Sales Overview Dashboard:
    <img width="1320" height="798" alt="online_retail_Dashboard" src="https://github.com/user-attachments/assets/b59e0cae-9cb6-45cb-883f-f40a0355aa9a" />

    
## Tools & Technologies

1. Jupyter Notebook(python) – Data cleaning and feature engineering
2. Power BI – Interactive dashboards and KPIs
3. Tableau – Comparative visual analytics
4. Excel – Source dataset and validation

## Project Objective
The goal of this project is not just visualization, but business interpretation:
- To identify who, where, and when value is created, and to highlight revenue concentration risks and opportunities for growth.
- Analyze sales performance over time to identify seasonal trends and peak revenue periods.
- Measure customer revenue concentration to understand dependency on high-value customers.
- Identify top-performing customers and countries contributing to overall revenue.
- Compare unit sales vs revenue contribution to reveal pricing and product-mix effects.
- Evaluate geographic distribution of revenue, excluding the UK, to highlight international market strength.
- Build interactive dashboards that enable business users to explore insights dynamically.
- Translate raw transactional data into actionable business insights that support strategic decision-making.

## Conclusion
- This analysis reveals that online retail revenue in 2011 is driven by strong seasonality, customer concentration, and regional performance differences.
- A small subset of customers contributes a significant share of total revenue, highlighting both opportunity and risk in customer dependency. International revenue outside the UK is largely concentrated in Western Europe, with the Netherlands and EIRE emerging as key markets. While unit volume is globally distributed, higher revenue is driven by pricing and product mix rather than quantity alone.
- Overall, this project demonstrates how structured data cleaning, metric engineering, and interactive dashboards can transform raw transactional data into insights that support revenue optimization, customer strategy, and geographic expansion decisions.
