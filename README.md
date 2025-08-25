# Python Summer Party Notebooks

Project Overview
This repository contains a collection of data analysis solutions to common business problems from Interview Master's Python Summer Party challenge., implemented in both SQL and Python (Pandas). The project demonstrates a comprehensive approach to data analysis, from initial data cleaning and exploration to advanced aggregation and predictive modeling.

## Key Skills Demonstrated

**Data Cleaning:** dropna(), drop_duplicates(), fillna(), pd.to_numeric(errors='coerce'), TRIM, COALESCE.

**Data Transformation:** pd.to_datetime, .assign(), .map(), CASE statements.

**Aggregation:** groupby(), agg(), pivot_table(), SQL GROUP BY.

Advanced Techniques:

**SQL**: Common Table Expressions (CTEs), Window Functions (AVG() OVER (PARTITION BY ...)).

**Pandas:** .transform(), .idxmax(), pd.cut(), method chaining.

**Metrics & KPIs:** Calculating CTR, average order value, sales lift, and growth rates.

## Some of the key business questions I answered include:
**Which combination of rider count and distance leads to the highest driver earnings?

What is the predicted sales lift of introducing a new payment option?

Which days of the week have the highest number of high-risk transactions?
**
## How to use

1. Create and activate a Python environment (venv or conda).
2. Install dependencies:
   
   pip install jupyterlab pandas numpy
   
3. Launch Jupyter Lab or Notebook and open any `day-XX.ipynb` file.

## About Interview Master

These challenges are hosted by Interview Master -- a platform for preparing for Data Science & Analytics interviews. Learn more at [interviewmaster.ai](https://www.interviewmaster.ai).
