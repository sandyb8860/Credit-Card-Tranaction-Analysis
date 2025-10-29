# 📊 Credit Card Tranaction Analysis
## 🔹 Project Objective
The objective of this project is to analyze credit card transactions and customer behavior to generate actionable business insights.
  
The dashboard helps financial institutions and stakeholders:
-  Track revenue, transactions, and interest earned.
-  Understand customer demographics (age, gender, education, job, income groups).
-  Identify credit card usage patterns by category, expenditure type, and customer satisfaction.
-  Monitor weekly and quarterly revenue trends for performance tracking.
---
## 🔹 Steps Followed
### **1. Data Preparation**
- Gathered data from Credit Card Transactions and Customer Details tables.
- Cleaned and transformed raw data using Power Query in Power BI.
- Ensured relationships between Client Number (common key).
### **2. Data Modeling & Calculations**
- Created new calculated columns and measures using DAX:
  
- Categorized Age Groups and Income Groups using `SWITCH`.
  
- Created Week Number calculations for weekly trends using `WEEKNUM`.
  
- Defined metrics like Total Revenue, Total Transactions, Total Interest Earned, and Total Amount.
### **4. Data Visualization**
## Business Summarywidth="1650" height="366" alt="image" src="https://github.com/user-attachments/assets/edb1d43c-2702-43b8-85cb-916e6969ec34" />Profitability of Card category by Gender
## Business question: Which card tiers or segments drive revenue?width="1516" height="1116" alt="image" src="https://github.com/user-attachments/assets/a255b112-10e4-4fbf-bc96-a6b77094e0bb" />This tree map shows 
- Blue card is the top revenue driver for both males (25.7M) and females (20.45M)
- Male customers generate more revenue across all card tiers.
- Blue cards account for nearly 85% of total revenue; Silver and Gold contribute less than 15%.
## Action: Focus upsell/retention on high-revenue segments; reconsider product features for low-revenue tiers
Credit Score Distribution (Histogram)
## Why: Understand distribution of creditworthiness; spot large low-score clusters.width="1292" height="818" alt="image" src="https://github.com/user-attachments/assets/4462e388-a1dc-4a17-8010-3ca2ee0f0137" />This Histogram shows
- Majority of customers have satisfaction scores between 3 and 4
