# 📊 Credit Card Transaction & Customer Report – Power BI Dashboard
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

Profitability of Card category by Gender

## Business question: Which card tiers or segments drive revenue?

<img width="1516" height="1116" alt="image" src="https://github.com/user-attachments/assets/a255b112-10e4-4fbf-bc96-a6b77094e0bb" />

This tree map shows 

- Blue card is the top revenue driver for both males (25.7M) and females (20.45M)

- Male customers generate more revenue across all card tiers.

- Blue cards account for nearly 85% of total revenue; Silver and Gold contribute less than 15%.

## Action: Focus upsell/retention on high-revenue segments; reconsider product features for low-revenue tiers

Credit Score Distribution (Histogram)
## Why: Understand distribution of creditworthiness; spot large low-score clusters.

<img width="1292" height="818" alt="image" src="https://github.com/user-attachments/assets/4462e388-a1dc-4a17-8010-3ca2ee0f0137" />

This Histogram shows

- Majority of customers have satisfaction scores between 3 and 4

- Highest customer count is at score 3 (3,068 people)

- Fewest customers at scores 1 and 2 (1,173 and 1,792)

- Scores 4 and 5 have similar customer numbers (2,099 and 1,976)

## Business action: Tighten credit policies or create monitoring for low-score clusters.

# Credit Utilization Trend (Line chart)

Why: Tracks how utilization evolves — rising utilization may precede defaults

<img width="2010" height="1106" alt="image" src="https://github.com/user-attachments/assets/38cdbf65-ba9c-4e3b-a7a8-5d0f30ff180b" />

This line charts shows-: 

- Blue card consistently has the highest average utilization ratio (between 0.286 and 0.305) throughout the year.

- Gold and Platinum cards show more variability, with Platinum peaking in August (0.2975) and October (0.3056).

- Silver card remains stable and lowest in utilization (around 0.08–0.10 all year).

- Gold card peaks early in the year (0.1738 in Feb) but drops below 0.05 in June, November, and December.

## Action: Identify customers for limit increases (low-risk high-utilization) or intervention for high-risk.

---

## 🔹 Key Insights
### **Credit Card Transaction Report**
1. **Revenue Trend**: Revenue fluctuates weekly, showing peaks at certain weeks.
2. **Top Card Type**: Blue cards generate the highest revenue.
3. **Transaction Type**: Swipe transactions account for the largest share of revenue.
4. **Expenditure Categories**: Bills, Entertainment, Fuel, Grocery, Food, and Travel are the highest contributors to total revenue.

### **Customer Report**
1. **Gender Analysis**: Male customers contribute higher total revenue compared to females.
2. **Top Job Roles**: Businessmen and White-Collar employees are the top revenue-generating customer segments.
3. **Education Impact**: Graduates and Post-Graduates form the majority of high-revenue customers.
4. **Income Groups**: High-income customers contribute the most to total revenue.
5. **Customer Satisfaction**: The majority of customers fall within the 3-4 satisfaction score range, indicating room for improvement in customer experience.

### **TreeMap Insights**
The treemap visual breaks down revenue by expenditure type (Bills, Entertainment, Fuel, Grocery, Food, Travel). Key observations:
- **Bills**: Largest expenditure category, contributing the highest revenue.
- **Entertainment & Fuel**: Significant contributors, with steady transaction volumes.
- **Grocery & Food**: Essential spending areas showing consistent revenue generation.
- **Travel**: Moderate revenue, with potential for growth in the travel credit card segment.

---

## 🔹 Dashboard Snapshots
### **Credit Card Transaction Report**
![Credit Card Transaction Report](https://github.com/sandyb8860/Credit_card_tranaction_Dashboard-Power-BI/blob/main/Credit%20card%20transation.png?raw=true)

### **Customer Report**
![Customer Report](https://github.com/sandyb8860/Credit_card_tranaction_Dashboard-Power-BI/blob/main/Credit%20card%20customer%20report.png?raw=true)

---

## 🔹 Technologies Used
- **Power BI Desktop**: For data modeling, visualization, and dashboard creation.
- **DAX (Data Analysis Expressions)**: For custom calculations and measures.
- **Power Query**: For data cleaning and transformation.
- **Data Sources**: CSV files for Credit Card Transactions and Customer Details.

---

## 🔹 Conclusion
This Power BI dashboard provides a comprehensive view of credit card usage patterns and customer behavior. It enables data-driven decision-making for marketing strategies, product offerings, and customer satisfaction improvement. The insights derived can help businesses optimize revenue streams and enhance customer engagement.
