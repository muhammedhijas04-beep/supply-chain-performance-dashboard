📦 Supply Chain Performance Dashboard

📊 Project Overview

This project analyzes supply chain operations to uncover delivery delays, logistics inefficiencies, regional risks, and product profitability patterns.
The goal is to transform raw operational data into actionable insights that support better logistics planning and business decision-making.


🎯 Business Questions Answered

Are deliveries happening on time?

Which shipping modes are causing delays?

Which countries have logistics risk?

How is order demand trending over time?

Which product categories are profitable or operationally challenging?

🛠 Tools Used

| Tool                | Purpose                           |
| ------------------- | --------------------------------- |
|   Python (Pandas)   | Data cleaning & feature creation  |
|   SQL               | KPI validation & business queries |
|   Power BI          | Dashboard & visualization         |


📁 Dataset Summary

~180,000 records

Order-line level data

~66,000 unique customer orders

Includes shipping, delivery, geography, product, and profit information


📊 Dashboard Structure

🟦 Page 1 — Executive Overview

High-level health check of operations

Late Delivery %

Average Delay Days

Average Profit per Order

Monthly Demand Trend

🟧 Page 2 — Logistics Performance

Operational deep dive

Delay by Shipping Mode

On-Time Delivery %

Delay Distribution

Shipping Mode: Profit vs Delay Trade-off

🟥 Page 3 — Regional Risk Analysis

Geographic performance insights

Countries with highest delays

Late delivery rate by country

Country vs Shipping Mode performance

🟩 Page 4 — Category Performance

Business + supply chain strategy

Category profitability ranking

Category delivery delays

Profit vs Delay trade-off by category

Top performing products


🔍 Operational & Customer Behavior Insights

Second Class shipping shows the highest delay rates but continues to generate strong order volume and solid profit per order. This indicates a trade-off between delivery reliability and business profitability.

Although delays are frequent, the average delay is relatively small (around 1–2 days). This suggests the delivery experience may be inconvenient but not severe enough to significantly reduce demand.

First Class shipping carries higher customer expectations, meaning even small delays in this mode may impact customer satisfaction more strongly than in economy shipping options.

The dataset does not include shipping cost or customer preference information. Therefore, while continued usage of slower shipping options suggests customers may accept longer delivery times, this remains a behavioral hypothesis rather than a confirmed conclusion.

From an operational perspective, improving reliability—especially for Second Class shipping—represents a major opportunity to enhance customer trust while maintaining profitability.

💡 Business Impact

The dashboard helps stakeholders:

Improve logistics planning

Optimize shipping method selection

Identify high-risk regions and delivery bottlenecks

Align inventory strategy with profitability and delivery performance
