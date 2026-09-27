Fitness Subscription Analytics

Project Overview

This project analyzes fitness subscription data to understand customer retention, forecast future subscription revenue, and compare Customer Lifetime Value (LTV) with Customer Acquisition Cost (CAC). The analysis was completed in Tableau.

Customer Cohort Analysis

The cohort analysis groups customers by their cohort month and year so that customers who joined in the same month but in different years are analyzed separately.

The analysis shows a significant decline in active customers around Month 2, suggesting that customers typically begin canceling their subscriptions around two months after joining.

Key Finding: Customers typically cancel around Month 2.

Revenue Forecast

The revenue forecast uses subscription transactions only and forecasts monthly subscription revenue for the next 12 months.

The forecast begins at approximately $186,694 in February 2026 and reaches approximately $267,483 by January 2027.

Overall, the forecast shows an upward trend in subscription revenue over the next 12 months. The forecast does not show strong evidence of seasonality, as there is no clear repeating seasonal pattern in the forecasted revenue.

Key Findings:

February 2026 forecast: $186,694

January 2027 forecast: $267,483

Overall trend: Increasing

Strong evidence of seasonality: No

CAC vs. LTV Analysis

The CAC vs. LTV analysis compares cumulative Customer Lifetime Value with the total Customer Acquisition Cost for the 2024 and 2025 customer cohorts.

Total CAC is calculated separately for each cohort year so that the reference line represents the acquisition cost of customers in the selected cohort.

The 2024 cohort reaches the CAC break-even point at approximately Month 4.

The 2025 cohort reaches the CAC break-even point between Months 5 and 6, meaning cumulative LTV has recovered CAC by approximately Month 6.

Key Findings:

2024 cohort CAC break-even: Month 4

2025 cohort CAC break-even: Month 6

The 2024 cohort therefore reaches its CAC break-even point earlier than the 2025 cohort.

Repository Contents

README.md — Summary of the analysis and key findings

Tableau Workbook — Interactive Tableau analysis

data/ — Fitness subscription dataset

screenshots/ — screenshots of the cohort analysis, revenue forecast, CAC vs. LTV analysis, and data model
