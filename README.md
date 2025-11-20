# Healthcare-project
This project focuses on analyzing a healthcare dataset using SQL to uncover insights related to hospital performance, patient volume, and revenue trends. The SQL scripts include data exploration, aggregation, time-series analysis, and YoY/MoM growth calculations to support data-driven decision-making in the healthcare sector.
 Healthcare Data Analysis using SQL

This project performs an in-depth analysis of healthcare organizational data using SQL. It explores hospital performance, patient volumes, and revenue trends across different time periods and categories. The goal is to extract meaningful insights that support data-driven decision-making within the healthcare sector.

 Project Overview

The SQL script analyzes key metrics such as:

Total discharges

Patient days

Net patient revenue

Hospital counts by control type

County-level revenue distribution

Quarterly and monthly revenue growth

Year-to-Date (YTD) and Year-to-Go (YTG) revenue

The analysis leverages advanced SQL functions, window operations, and date transformations to produce clear insights.

 SQL Techniques Used

Aggregations: SUM(), COUNT(), grouping by hospital type, year, quarter, and county

Date Handling: YEAR(), MONTH(), QUARTER(), STR_TO_DATE()

String Operations: LEFT(), RIGHT(), CONCAT()

Window Functions: LAG() for comparative time-series analysis

CTEs (Common Table Expressions): Used for modular and readable data pipelines

Growth Metrics: Quarter-over-Year (QoY) and Month-over-Month (MoM) revenue growth

 Key Insights Generated

 Hospital Category Analysis
Breakdown of discharges, patient days, total hospitals, and net patient revenue by hospital type.

 County-Level Revenue Insights
Total net patient revenue aggregated by county.

 Time Series Revenue Analysis

Yearly Revenue

Quarterly Revenue with same-quarter-on-year comparisons

Monthly Revenue with same-month-on-year comparisons

 Growth Metrics

QoY growth percentage

MoM growth percentage

 YTD & YTG Metrics
Segmentation of revenue for the latest year based on the latest available month.

 File Included
Healthcare.sql

Contains all SQL queries for:

Data exploration

Aggregation metrics

Quarterly & monthly revenue growth

YTD/YTG analysis

 How to Use

Import or connect your SQL environment to the healthcare dataset (table: org_data).

Run the queries in Healthcare.sql step-by-step or as needed.

Review outputs to analyze performance across hospitals, counties, and time periods.

 License

This project is open-source. Feel free to use, modify, or extend the SQL logic for your own analytics projects.
