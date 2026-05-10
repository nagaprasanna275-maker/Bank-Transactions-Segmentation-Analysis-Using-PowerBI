Problem Statement
Banks manage massive volumes of customer and transaction data, but without proper segmentation, it becomes difficult to identify high-value customers and design targeted strategies.

This project analyzes demographics and transaction patterns of 1.04 million+ records using Power BI to improve customer loyalty, acquisition, and retention.
Dataset Overview
Source: Bank transaction dataset
Raw Records: 1,048,568
Cleaned Records: 1,045,170
Key Fields: CustomerID, DOB, Gender, Location, Account Balance, Transaction Date/Amount.
🧹 Data Cleaning & Preparation (Power Query)
Type Conversion: Formatted CustomerDOB, TransactionDate, and TransactionTime.
Handling Nulls: Replaced missing gender and location values with "Unknown".
Validation: Removed invalid records and enforced consistent numeric formats.
🧮 Data Modeling & DAX
Calculated Columns
Customer Age / Age Group: (18–24, 25–34, 35–44, 45–54, 55+)
State: Derived from location data.
Key Measures
Measure	Description
Total Revenue	Sum of all transaction amounts
Loyalty Status	Categorized as Loyal, Regular, New, or Lost
Retention Rate	Analysis of new vs. lost customers
Avg Balance	Mean account balance per segment
📈 Key Insights
The Core User: Male customers dominate (~71%), and the 35–44 age group is the most valuable segment.
Geography: Maharashtra has the highest customer concentration and revenue.
Peak Activity: Transactions peak at 7 PM, generating total revenue of ₹14.8 crores.
Retention Warning: Lost customers significantly outnumber new customers, and loyal customers are extremely low (~50).
💡 Strategic Recommendations
Loyalty: Launch personalized rewards for the 35–44 age group in Maharashtra.
Acquisition: Run digital campaigns targeting the 18–34 demographic with referral bonuses.
Retention: Trigger re-engagement alerts for low-activity users before they are "lost."
Expansion: Launch regional campaigns in low-penetration states like Assam and Bihar.
🛠 Tools Used
Power BI (Visualization)
DAX (Measures & Logic)
Power Query (ETL)
📌 Conclusion
This project demonstrates how customer segmentation can uncover hidden "leaks" in a business (like the retention gap) and provide data-driven solutions for growth
