# Customer Analytics

EDA and SQL-powered pipeline to analyse customer lifetime value, retention cohorts, and regional distribution.

## Overview

| Detail | Info |
| --- | --- |
| Tools | Python, Pandas, SQL, SQLAlchemy, Seaborn, Jupyter |
| Database | Relational database queried via SQLAlchemy |
| Focus | Lifetime value, retention, regional distribution |

## Key Findings

- Top customer by lifetime revenue: Sean Miller at $5,043
- Customer retention rate: 92.9% (New vs Returning cohort analysis)
- South region (512 customers) underperforms vs West (686) — geographic growth opportunity
- Reusable SQL queries using GROUP BY and aggregation run directly from Jupyter

## How to Run

pip install pandas sqlalchemy seaborn jupyter
jupyter notebook customer_analytics.ipynb
