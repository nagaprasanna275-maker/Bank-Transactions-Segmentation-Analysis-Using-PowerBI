# Bank Customer Segmentation & Transaction Analysis using Power BI

Analyzed 1M+ customer transaction records to identify customer segments, retention gaps, revenue trends, and transaction behavior using Power BI, DAX, and Power Query.

---

# 🏦 Bank Customer Segmentation Analysis

## 📌 Problem Statement

Banks manage massive volumes of customer and transaction data, but without proper segmentation, it becomes difficult to identify high-value customers and develop targeted business strategies.

This project analyzes customer demographics and transaction behavior across 1.04M+ records to improve customer retention, acquisition, and revenue optimization.

---

# 📊 Dataset Overview

| Attribute | Details |
|---|---|
| Source | Bank Transaction Dataset |
| Raw Records | 1,048,568 |
| Cleaned Records | 1,045,170 |
| Transaction Volume | ₹1.64 Billion+ |
| Tools Used | Power BI, DAX, Power Query |

### Key Fields

| Field Name | Description |
|---|---|
| CustomerID | Unique customer identifier |
| DOB | Customer date of birth |
| Gender | Customer gender |
| Location | Customer city/state |
| Account Balance | Current account balance |
| Transaction Date | Date of transaction |
| Transaction Amount | Transaction value |

---

# 🧹 Data Cleaning & Preparation (Power Query)

| Process | Description |
|---|---|
| Type Conversion | Formatted DOB, Date, and Time columns |
| Null Handling | Replaced missing values with "Unknown" |
| Data Validation | Removed invalid and duplicate records |
| Feature Engineering | Created Age Group and State columns |

---

# 🧮 Data Modeling & DAX

## 📌 Calculated Columns

| Column | Description |
|---|---|
| Customer Age | Calculated from DOB |
| Age Group | 18–24, 25–34, 35–44, 45–54, 55+ |
| State | Derived from location |
| Loyalty Status | Loyal, Regular, New, Lost |

---

## 📌 Key Measures

| Measure | Description |
|---|---|
| Total Revenue | Sum of all transaction amounts |
| Retention Rate | Loyal vs Lost customer analysis |
| Avg Balance | Average account balance |
| Total Customers | Distinct customer count |
| Avg Transaction Value | Average transaction amount |

---

# 📈 Key Insights

| Area | Insight |
|---|---|
| Customer Demographics | Male customers contributed ~71% of transactions |
| Valuable Segment | Age group 35–44 generated highest revenue |
| Geography | Maharashtra had highest customer concentration |
| Peak Activity | Transactions peaked around 7 PM |
| Retention Analysis | Lost customers outnumbered loyal customers |

---

# 💡 Strategic Recommendations

| Strategy Area | Recommendation |
|---|---|
| Loyalty Programs | Personalized rewards for high-value customers |
| Acquisition | Referral campaigns targeting 18–34 age group |
| Retention | Re-engagement alerts for inactive customers |
| Expansion | Regional campaigns in low-penetration states |

---

# 🛠 Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Power BI | Dashboard development & visualization |
| DAX | Measures and business logic |
| Power Query | Data cleaning & ETL |
| Excel/CSV | Dataset handling |

---

# 📌 Conclusion

This project demonstrates how customer segmentation and transaction analysis can uncover customer retention gaps, identify revenue-driving segments, and support data-driven business decisions using interactive Power BI dashboards.
