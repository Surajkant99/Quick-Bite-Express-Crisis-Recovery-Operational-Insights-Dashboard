# Quick Bite Express: Crisis Recovery & Operational Insights Dashboard
A comprehensive Power BI solution designed to analyze a critical operational failure at a food-tech startup. This dashboard quantifies the impact on revenue, identifies high-value customer churn, correlates delivery performance with negative sentiment, and provides actionable insights for business recovery strategies.

## 🧾 Project Overview
This project is an interactive data analytics dashboard built using Power BI to analyze a severe crisis period at "Quick Bite Express," a food delivery company. Facing a dual challenge of food safety violations and a massive delivery outage in June 2025, the company needed a unified view of the damage. This dashboard integrates disparate data sources—sales transactions, delivery logs, customer reviews, and partner data—to provide a comprehensive post-mortem. It is designed for executive leadership and operational managers to understand what happened, why it happened, and who was most impacted, enabling data-driven recovery decisions.

## ❓ Problem Satatement
Quick Bite Express experienced a catastrophic drop in order volumes and revenue starting in June 2025. Data was fragmented across operational, financial, and customer feedback systems, making it difficult to pinpoint the root causes and scale of the impact. This project addresses the need for a consolidated analytical solution to:
- Quantify the exact financial loss comparing pre-crisis (Jan-May) and crisis (Jun-Sep) periods.
- Measure the extent of operational failure regarding delivery times and SLA compliance.
- Identify high-value, loyal customers who churned as a result of the crisis.
- Correlate negative customer sentiment directly with operational performance metrics.
- Assess the impact on key restaurant partners to prioritize relationship management.

## 📈 Dashboards & Features
#### Navigation
The report is structured into five distinct analytical views:
- Executive Summary: High-level KPIs and trends showing the overall crisis impact.
- Delivery Performance Analysis: Deep dive into SLA compliance, delivery times, and operational bottlenecks.
- Customer Loyalty & Churn Analysis: Identifying retained vs. churned customers, focusing on high-value segments.
- Customer Sentiment Analysis: Analyzing review scores, keyword trends (Word Cloud), and the link between delivery time and ratings.
- Restaurant Partner Analysis: Evaluating the performance and decline of top restaurant partners across cities.
#### Key Visualizations & Analysis
- Trend Analysis: Pre-crisis vs. Crisis comparison charts highlighting the sharp decline in Revenue, Orders, and Active Customers.
- Operational KPIs: Tracking the dramatic drop in SLA Compliance % and the corresponding spike in Average Delivery Time (minutes).
- Churn Quantification: DAX measures calculating the exact number of "Loyal Customers" (e.g., 5+ pre-crisis orders) who stopped ordering during the crisis.
- Sentiment Drivers: Scatter plots correlating average delivery time with average rating, and Word Clouds visualizing common negative feedback themes (e.g., "Late," "Cold").
- Partner Impact: Top N analysis identifying high-volume restaurants with the steepest percentage decline in orders.
#### Interactive Filters
- Period Selector (Pre-Crisis / Crisis)
- City / Region
- Customer Segment (New / Returning / Loyal)
- Restaurant Name

## 💻 Tech Stack
- Power BI Desktop: For data visualization, interactive reporting, and data modeling.
- Excel/CSV Files: Raw source data for orders, customers, deliveries, and ratings.
- Power Query (M Language): For data extraction, transformation, and loading (ETL) to clean and prepare the datasets.
- DAX (Data Analysis Expressions): For creating complex measures regarding churn, SLA compliance, and period-over-period comparisons.

## 🔑 Key Insights
- The Operational Collapse: The primary driver of revenue loss was a massive failure in logistics; SLA compliance dropped from a stable ~44% pre-crisis to under 12% during the crisis peak, with average delivery times exceeding 60 minutes.
- Financial Cliff: Revenue and order volumes saw an immediate and sharp decline ($7.4M down to $2.9M) as soon as the crisis hit in June.
- Loyalty Drain: The operational failures directly resulted in the churn of over 3,400 high-value, loyal customers, representing a significant long-term revenue risk.
- Sentiment Correlation: Customer sentiment flipped from positive to negative, with analysis proving a direct strong correlation between increased delivery times and plummeting star ratings.
- Partner fallout: Key high-volume partners in major cities experienced order declines of over 90%, requiring immediate account management intervention.

## 🔗 Important links
- [Live PowerBI dashboard](https://app.powerbi.com/view?r=eyJrIjoiMGYwODg2OTAtNzUwMi00YTA2LTgxNmYtMTQwN2UwOTc0NDNlIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
- [Linkedin Post](https://www.linkedin.com/feed/update/urn:li:activity:7392902188844580864/)

## 📞 Contacts
- [Protfolio](https://codebasics.io/portfolio/Suraj-Kant)
- [Linkedin](https://www.linkedin.com/in/surajkant9/)
- [Email](mailto:surajkant264@gmail.com)
