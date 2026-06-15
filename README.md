# Security Market Performance Analysis Dashboard

- Project Overview

This project analyzes security trading activity across multiple exchanges using Power BI. The objective was to identify trading patterns, exchange popularity, geographic distribution of securities, and performance trends over time.

The dashboard was developed using a star schema model consisting of fact and dimension tables and includes DAX measures for performance and time-based analysis.

- Business Questions

The dashboard answers the following questions:

1. Which exchange do securities come from?
2. Where are securities located geographically?
3. Which exchanges are most popular in terms of trading volume?
4. What relationships between securities provide insights into higher performance?
5. How does security performance change over time?
6. Which securities perform best?

## Data Model
1 Fact Table
- FactActivity

2 Dimension Tables
- DimDate
- DimExchange
- DimSecurity

Model Structure

A star schema design was implemented to improve model performance and simplify analysis.

