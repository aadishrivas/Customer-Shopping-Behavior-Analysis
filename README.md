# Customer-Shopping-Behaviour-Analysis

Explore shopping patterns across **3,900 customer records** with Python, PostgreSQL, and Power BI. This project cleans the data, analyzes customer and product trends, and presents findings in a dashboard.

## Contents

- [Project overview](#project-overview)
- [Key findings](#key-findings)
- [Files](#project-files)
- [Getting started](#getting-started)

<details>
<summary><strong>Project overview</strong></summary>

The analysis covers spending by customer group, product ratings and category performance, discounts, shipping methods, subscriptions, and purchase history. In Python, missing review ratings are filled with category medians, columns are standardized, and age and purchase-frequency fields are prepared. SQL queries explore the cleaned data, while the Power BI dashboard summarizes customer and revenue patterns.

</details>

<details>
<summary><strong>Selected findings</strong></summary>

- Clothing generated the highest category revenue: **$104,264**.
- Average purchase amounts were similar for subscribers (**$59.49**) and non-subscribers (**$59.87**).

These are descriptive results from this dataset; they do not establish causation.

</details>

## Project files

| File | Description |
|---|---|
| [`customer_shopping_behavior.csv`](customer_shopping_behavior.csv) | Source dataset |
| [`customer_behaviour_analysis.ipynb`](customer_behaviour_analysis.ipynb) | Python data preparation and analysis |
| [`customer_behavior_sql_queries.sql`](customer_behavior_sql_queries.sql) | PostgreSQL analysis queries |
| [`customer_behavior_dashboard.pbix`](customer_behavior_dashboard.pbix) | Power BI dashboard |
| [`Customer Shopping Behavior Analysis.pdf`](Customer%20Shopping%20Behavior%20Analysis.pdf) | Project report |

## Getting started

1. Run the notebook with the CSV in the same folder.
2. Use the SQL file with the prepared data loaded into PostgreSQL.
3. Open the PBIX file in Power BI Desktop to explore the dashboard.

<details>
<summary><strong>Tools used</strong></summary>

Python · Pandas · PostgreSQL · SQL · Power BI

</details>

