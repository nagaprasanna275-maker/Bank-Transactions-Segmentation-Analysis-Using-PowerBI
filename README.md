# Bank Customer Segmentation & Transaction Analysis using Power BI

Bank Customer Segmentation & Transaction Analysis using Power BI | Analyzed 1M+ records to identify retention gaps and revenue drivers | DAX, Power Query & Data Modeling

---

# 🏦 Bank Customer Segmentation Analysis

## 📌 Problem Statement

Banks manage massive volumes of customer and transaction data, but without proper segmentation, it becomes difficult to identify high-value customers and design targeted strategies.

This project analyzes demographics and transaction patterns of **1.04 million+ records** using **Power BI** to improve customer loyalty, acquisition, and retention.

---

## 📊 Dataset Overview

- **Source:** Bank transaction dataset  
- **Raw Records:** 1,048,568  
- **Cleaned Records:** 1,045,170  
- **Transaction Volume:** ₹1.64 Billion+  
- **Key Fields:** CustomerID, DOB, Gender, Location, Account Balance, Transaction Date/Amount  

---

## 🧹 Data Cleaning & Preparation (Power Query)

- **Type Conversion:** Formatted CustomerDOB, TransactionDate, and TransactionTime  
- **Handling Nulls:** Replaced missing gender and location values with `"Unknown"`  
- **Validation:** Removed invalid records and enforced consistent numeric formats  
- **Feature Engineering:** Created Age Groups and Loyalty Status columns  

---

## 🧮 Data Modeling & DAX

### Calculated Columns

- Customer Age  
- Age Group (18–24, 25–34, 35–44, 45–54, 55+)  
- State (Derived from location data)  
- Loyalty Status  

### Key Measures

- **Total Revenue:** Sum of all transaction amounts  
- **Loyalty Status:** Loyal, Regular, New, or Lost  
- **Retention Rate:** Analysis of retained vs lost customers  
- **Avg Balance:** Average account balance per segment  
- **Avg Transaction Value:** Average transaction amount  

---

## 📈 Key Insights

- Male customers dominate (~71%) of total transactions  
- Customers aged **35–44** generated the highest revenue  
- Maharashtra had the highest customer concentration and revenue  
- Peak transaction activity occurred around **7 PM**, generating ₹14.8 crores  
- Lost customers significantly outnumbered loyal customers, highlighting retention gaps  

---

## 💡 Strategic Recommendations

### 🎯 Loyalty
Launch personalized rewards for high-value customers aged 35–44.

### 🚀 Acquisition
Run digital campaigns targeting the 18–34 demographic with referral bonuses.

### 🔄 Retention
Trigger re-engagement alerts for inactive customers before churn.

### 🌍 Expansion
Launch regional campaigns in low-penetration states like Assam and Bihar.

---

## 🛠 Tools Used

- Power BI (Visualization & Dashboard Development)  
- DAX (Measures & Business Logic)  
- Power Query (ETL & Data Cleaning)  
- Excel/CSV (Dataset Handling)  

---

## 📌 Conclusion

This project demonstrates how customer segmentation and transaction analysis can uncover retention gaps, identify revenue-driving customer segments, and support data-driven business decisions using interactive Power BI dashboards.
