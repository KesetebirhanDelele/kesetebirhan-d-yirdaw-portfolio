# RCM

## Project Overview

Analyzes healthcare revenue cycle data to identify inefficiencies and provides insights through an interactive dashboard.

---

## Business Problem

Healthcare organizations often struggle with inefficiencies in their revenue cycle, leading to claim denials and payment delays. This project addresses these challenges by providing actionable insights through data analysis, helping healthcare providers optimize their financial processes.

---

## Objective

- Analyze healthcare revenue cycle data to identify claim denials and payment delays.
- Integrate multiple data sources, including EMR and claims data, for comprehensive insights.
- Deliver visual analytics through a Power BI dashboard to support decision-making.

---

## Tools & Technologies

- Microsoft SQL Server
- Power BI
- Medallion Architecture
- Python
- Excel/CSV

---

## Project Workflow

- Load raw data from CSV/Excel into staging tables in SQL Server.
- Clean and transform the data by joining EMR and claims datasets and handling null values.
- Aggregate the cleaned data into analytics-ready views for dashboard consumption.
- Create a Power BI dashboard to visualize key metrics and trends.
- Refresh the dashboard to display updated insights for stakeholders.

---

## Key Insights

- Utilized Medallion Architecture to efficiently manage data ingestion and transformation, enhancing scalability.
- Identified key performance indicators (KPIs) such as denial rate and average days in accounts receivable to drive actionable insights.
- Recommended procedural improvements based on detailed analysis of denial trends at the CPT code level.

---

## Final Dashboard / Project Preview

![Final Dashboard](https://raw.githubusercontent.com/KesetebirhanDelele/RCM/main/image.png)

---

## Business Impact

- Enabled healthcare providers to benchmark performance and identify areas for improvement.
- Facilitated data-driven decision-making through interactive visualizations.
- Provided insights into top denial reasons, allowing for targeted interventions.

---

[← Back to portfolio](../README.md)
