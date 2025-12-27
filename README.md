Overview
Power BI and SQL project that models utility style rate design and revenue performance. Goal is to move from raw usage and rate components to clear views of revenue trends, variance drivers, and bill comparisons.

Full write up with screenshots sits in docs/RateDataProject_Summary.docx.

At a glance
Dataset: sample utility rate data (monthly usage plus rate components)
Rows: 24 monthly periods across 2025 to 2026, 1 customer class, 1 rate schedule
Tech stack: PostgreSQL, pgAdmin, Excel, Power BI
Focus: revenue trend, driver variance (volume, rate, fixed charge), bill comparison under current vs prior rates
Key insights in one line:
Rates and fixed charges drive the 2026 revenue lift, while usage seasonality drives month to month swings

What this repo shows
- How raw CSVs are staged and validated in Excel
- How CSVs load into PostgreSQL using pgAdmin
- How SQL joins usage to rate components to produce analysis ready tables
- How variance logic decomposes revenue change into driver effects
- How those outputs feed a multi page Power BI dashboard with slicers and navigation

Why this project matters
This project shows end to end work:
- Working with rate and usage data similar to utility analytics
- Building analysis ready tables with SQL and data validation checks
- Using variance decomposition to explain revenue change in a way leaders can use
- Delivering a clean Power BI report built for monitoring and rate review
