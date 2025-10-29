# 
 📊 Credit Card Transaction & Customer Report – Power BI Dashboard
## 
 🔹 Project Objective
The objective of this project is to analyze credit card transactions and customer behavior to generate actionable business insights.
  
The dashboard helps financial institutions and stakeholders:
- 
 Track revenue, transactions, and interest earned.
- 
 Understand customer demographics (age, gender, education, job, income groups).
- 
 Identify credit card usage patterns by category, expenditure type, and customer satisfaction.
- 
 Monitor weekly and quarterly revenue trends for performance tracking.
---
## 
 🔹 Steps Followed
### 
 
**
1. Data Preparation
**
- 
 Gathered data from Credit Card Transactions and Customer Details tables.
- 
 Cleaned and transformed raw data using Power Query in Power BI.
- 
 Ensured relationships between Client Number (common key).
### 
 
**
2. Data Modeling & Calculations
**
- 
 Created new calculated columns and measures using DAX:
  
- 
 Categorized Age Groups and Income Groups using 
`
SWITCH
`
 function.
  
- 
 Created a new column:
  
    
`
Revenue = Total Transaction Amount + Interest + Annual Fee
`.
  
- 
 Built measures for 
`
Current Week Revenue
` 
 and 
`
Previous Week Revenue
` 
 to calculate growth.
### 
 
**
3. Dashboard Design
**
- 
 Designed two dashboards:
  
- 
 
**
Credit Card Transaction Report
** 
 – Focused on transaction performance.
  
- 
 
**
Credit Card Customer Report
** 
 – Focused on customer demographics and segmentation.
- 
 Used a mix of charts (bar, line, donut, cards, slicers) for better visualization.
---
## 
 🔹 Visuals Insights 
Customer Segment Profitability (Treemap)
Business question: Which card tiers or segments drive revenue?width
=
"1410" 
height
=
"804" 
alt
=
"image" 
src
=
"https://github.com/user-attachments/assets/3bfc6db8-fbd5-4457-ae82-9d1c6f0af804" 
/>

- Blue card is the top revenue driver for both males (25.7M) and females (20.45M).
- Male customers generate more revenue across all card tiers.
- Blue cards account for nearly 85% of total revenue; Silver and Gold contribute less than 15%.

**Insight:**
Focus on male Blue cardholders for maximum profitability.

### 
 
**
Revenue Performance
**
- 
 Total Revenue generated: 
**
23M
**
- 
 Total Transactions: 
**
19M
**
, with 
**
3.32M interest
** 
 and 
**
278K transaction count
**
### 
 
**
Customer Segmentation
**
- 
 Majority of revenue is generated from 
**
middle-aged groups (30–50 yrs)
**
.
- 
 
**
High-income groups
** 
 and 
**
graduates
** 
 contribute significantly to revenue.
- 
 
**
Male customers
** 
 dominate transactions compared to female customers.
### 
 
**
Credit Card Usage
**
- 
 
**
Gold and Platinum card categories
** 
 contribute higher revenue.
- 
 
**
Travel and grocery expenditures
** 
 are top contributors to spending.
### 
 
**
Trends
**
- 
 Seasonal spikes observed in 
**
Q2 and Q4 revenues
**
.
---
## 
 🔹 Action Items
Based on insights, the following actions are recommended:
- 
 
**
Customer Retention
** 
 – Focus marketing campaigns on high-value customer groups (30–50 yrs, graduates, high-income).  
- 
 
**
Product Strategy
** 
 – Promote Platinum and Gold cards to maximize revenue.  
- 
 
**
Revenue Growth
** 
 – Encourage more transactions in low-performing categories (like utilities).  
- 
 
**
Customer Satisfaction
** 
 – Track satisfaction scores and reduce delinquent accounts to improve loyalty.  
- 
 
**
Seasonal Planning
** 
 – Leverage Q2 and Q4 peaks with targeted offers and cashback schemes.  
---
## 
 🔹 Tools & Technologies
- 
 
**
Power BI
** 
 – Data cleaning, modeling, DAX measures, and visualization.  
- 
 
**
DAX (Data Analysis Expressions)
** 
 – Custom calculations and measures.  
