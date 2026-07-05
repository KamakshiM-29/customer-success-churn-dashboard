# Customer Success Churn Dashboard

An interactive Power BI dashboard designed to analyze customer churn, identify key churn drivers, monitor customer health, and recommend customer success strategies to improve retention and protect recurring revenue.
## Project Overview

Customer retention is a critical business challenge for subscription-based businesses. Losing valuable customers directly impacts recurring revenue, acquisition costs, and long-term business growth.

This project demonstrates how business intelligence can support Customer Success teams by transforming customer data into actionable insights. Using Power BI and DAX, the dashboard analyzes customer behavior, identifies churn risk, evaluates customer health, estimates revenue exposure, and provides strategic recommendations to improve customer retention.
## Business Problem

Organizations often have large volumes of customer data but lack visibility into the factors contributing to customer churn. Without a structured approach to monitor customer health, businesses struggle to identify at-risk customers before they leave.

The objective of this project is to build an interactive dashboard that enables Customer Success teams to:

- Monitor customer churn trends
- Identify key churn drivers
- Evaluate customer health
- Estimate revenue exposure
- Prioritize customer success initiatives
## Project Objectives

- Analyze customer churn across multiple customer segments.
- Identify the primary factors influencing churn.
- Build a customer health scoring framework.
- Segment customers into Healthy, Watchlist, and Critical groups.
- Estimate revenue exposure associated with customer health.
- Recommend customer success actions to improve retention.
## Tools & Technologies

| Category | Tools Used |
|----------|------------|
| Business Intelligence | Power BI Desktop |
| Data Transformation | Power Query |
| Data Modeling | Power BI Data Model |
| Calculations | DAX (Data Analysis Expressions) |
| Data Source | Customer Churn Dataset |
| Version Control | GitHub |
## Dashboard Overview

The dashboard is organized into four interactive pages, each focusing on a different stage of customer analysis and decision-making.

| Dashboard Page | Purpose |
|---------------|---------|
| Executive Overview | High-level KPIs, revenue metrics, and customer distribution |
| Customer Churn Driver Analysis | Identify the major factors influencing churn |
| Customer Health & Revenue Risk Analysis | Monitor customer health, revenue exposure, and customer segments |
| Recommendations & Action Plan | Translate insights into actionable customer success strategies |
## Dashboard Preview

The dashboard provides an end-to-end view of customer churn, customer health, revenue exposure, and strategic customer success recommendations.

## Dashboard Pages
### 1. Executive Overview

Provides a high-level summary of customer churn, revenue performance, customer distribution, and subscription trends through interactive KPI cards and visualizations.

![Executive Overview](Images/Executive%20Overview.png)
### 2. Customer Churn Driver Analysis

Analyzes the primary factors contributing to churn, including payment risk, product usage, customer support interactions, customer engagement, tenure, age group, and gender.

![Customer Churn Driver Analysis](Images/Customer%20Churn%20Driver%20Analysis.png)
### 3. Customer Health & Revenue Risk Analysis

Introduces a customer health scoring model to classify customers into Healthy, Watchlist, and Critical segments while highlighting revenue exposure and health trends.

![Customer Health & Revenue Risk Analysis](Images/Customer%20Health%20%26%20Revenue%20Risk%20Analysis.png)
### 4. Recommendations & Action Plan

Converts analytical findings into practical customer success strategies, including executive recommendations, strategic focus areas, intervention planning, and a structured 90-day action roadmap.

![Recommendations & Action Plan](Images/Recommendations%20%26%20Action%20Plan.png)
## Key Business Insights

The dashboard highlights several customer behaviors that contribute to churn risk and revenue exposure.

- Customers with **High Payment Risk** exhibit the highest churn rate compared to other payment segments.
- **Low Usage** customers are more likely to churn, indicating lower product adoption.
- Customers requiring **High Support** also demonstrate higher churn, suggesting potential service or product experience issues.
- The Customer Health Score successfully segments customers into **Healthy**, **Watchlist**, and **Critical** groups, enabling proactive intervention.
- A significant share of revenue is associated with **Critical** and **Watchlist** customers, making them the highest priority for retention efforts.
- Customer health trends provide an opportunity to prioritize retention initiatives before customers reach the point of churn.
## Customer Success Recommendations

Based on the analysis, the following customer success initiatives are recommended:

- Prioritize outreach for Critical customers with High Payment Risk.
- Improve onboarding and feature adoption for Low Usage customers.
- Monitor Watchlist customers through regular health reviews.
- Strengthen customer support processes for accounts with recurring service issues.
- Use Customer Health Score as an early warning indicator for proactive retention planning.
- Track Revenue Exposure alongside customer health to prioritize high-value retention efforts.
## Skills Demonstrated

Through this project, I demonstrated skills in:

- Power BI Dashboard Development
- Data Cleaning using Power Query
- Data Modeling
- DAX Calculations and Measures
- Customer Churn Analysis
- Customer Segmentation
- Customer Health Scoring
- Business Intelligence Reporting
- Customer Success Analytics
- Revenue Risk Analysis
- Data Visualization
- Business Recommendation Framework
## Repository Structure

```text
customer-success-churn-dashboard
│
├── Dashboard
│   └── Customer Churn Dashboard.pbix
│
├── Dataset
│   └── Customer_Churn.csv
│
├── Images
│   ├── Executive Overview.png
│   ├── Customer Churn Driver Analysis.png
│   ├── Customer Health & Revenue Risk Analysis.png
│   └── Recommendations & Action Plan.png
│
├── README.md
└── LICENSE
```
## How to Use

1. Download the Power BI dashboard (`.pbix`) file from the `Dashboard` folder.
2. Open the file using Microsoft Power BI Desktop.
3. Navigate through the four dashboard pages to explore customer churn, customer health, and revenue risk.
4. Use the interactive slicers to filter the analysis by customer attributes and business segments.
5. Review the recommendations page for suggested customer success initiatives based on the analysis.
## Project Highlights

- Designed a four-page interactive Power BI dashboard focused on Customer Success analytics.
- Developed custom DAX measures for customer health scoring and revenue exposure analysis.
- Built customer segmentation to prioritize retention efforts.
- Converted analytical findings into actionable customer success recommendations.
