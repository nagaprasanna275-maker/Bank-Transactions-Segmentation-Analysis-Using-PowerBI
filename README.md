Bank Customer Segmentation & Transaction Analysis using Power BI

Analyzed 1M+ banking transaction records to identify customer retention gaps, revenue-driving segments, and transaction behavior patterns using Power BI, DAX, and Power Query.

🏦 Bank Customer Segmentation Analysis
📌 Problem Statement

Banks generate massive volumes of customer and transaction data daily. Without proper customer segmentation and transaction analysis, it becomes difficult to identify high-value customers, improve retention, and optimize business strategies.

This project analyzes customer demographics, transaction behavior, and revenue trends to uncover actionable business insights that support customer acquisition, loyalty, and operational planning.

📊 Dataset Overview
Source: Bank Transaction Dataset
Raw Records: 1,048,568
Processed Records: 1,045,170
Transaction Volume: ₹1.64 Billion+
Key Fields:
Customer ID
DOB
Gender
Location
Account Balance
Transaction Date & Time
Transaction Amount

🧹 Data Cleaning & Preparation (Power Query)
✔ Data Transformation
Converted date and time fields into proper formats
Standardized transaction and balance values
Extracted state information from location data

✔ Data Quality Handling
Replaced missing gender/location values with "Unknown"
Removed duplicate and invalid transaction entries
Handled inconsistent data types and null values

✔ Feature Engineering
Created
Customer Age
Age Groups
Loyalty Segments
Time-based transaction categories

🧮 Data Modeling & DAX
📌 Calculated Columns
Customer Age
Age Group (18–24, 25–34, 35–44, 45–54, 55+)
Transaction Hour
State
Customer Segment

📌 Key Measures
Measure	Description
Total Revenue	Sum of all transaction amounts
Total Customers	Distinct customer count
Avg Transaction Value	Average revenue per transaction
Avg Account Balance	Mean customer account balance
Loyal Customers	Highly active retained customers
Lost Customers	Inactive customers over time
Retention Rate	Loyal vs Lost customer analysis

📈 Dashboard Insights
👥 Customer Insights
Male customers contributed nearly 71% of total transactions.
Customers aged 35–44 formed the highest-value segment.
Loyal customer percentage was significantly lower compared to lost customers.

🌍 Geographic Analysis
Maharashtra generated the highest customer concentration and revenue.
Mumbai and New Delhi emerged as key transaction hubs.
States like Assam and Bihar showed lower market penetration.

⏰ Transaction Trends
Peak transaction activity occurred around 7 PM.
High transaction periods helped identify operational load timings.
Time-based analysis supported service and staffing optimization.

💰 Revenue Analysis
Processed over ₹1.64 Billion in transaction value.
Average transaction behavior highlighted high-value customer clusters.

💡 Business Recommendations
🎯 Retention Strategy
Create personalized reward programs for high-value customers.
Trigger inactivity alerts before customers become “Lost.”

🚀 Acquisition Strategy
Launch referral and cashback campaigns for younger demographics (18–34).
Improve engagement with digital-first marketing campaigns.

📍 Geographic Expansion
Increase campaigns in underperforming states.
Focus on regional customer acquisition strategies.
⚙ Operational Improvements
Allocate resources during peak transaction hours.
Optimize staffing and service planning based on transaction trends.

📊 Dashboard Features
Interactive KPI Cards
Customer Segmentation Analysis
Revenue & Transaction Trend Analysis
Geographic Heatmaps
Peak Hour Transaction Analysis
Retention & Loyalty Insights

🛠 Tools & Technologies Use
Power BI — Dashboard Development & Visualization
Power Query — Data Cleaning & ETL
DAX — Calculated Measures & KPIs
Excel/CSV — Raw Dataset Handling

📌 Conclusion

This project demonstrates how customer segmentation and transaction analytics can help banks identify retention gaps, optimize operational planning, and improve revenue-focused decision-making through interactive Power BI dashboards.
