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

### **3. Dashboard Design**
- Developed two interactive dashboards:
  - **Credit Card Transaction Report**: Focuses on revenue, transaction count, and interest by card type, transaction type, and expenditure category.
  - **Customer Report**: Analyzes customer segmentation based on demographics, income, job, and satisfaction scores.

### **4. Data Visualization**
Used Power BI visualizations such as:
- Cards for KPIs (Total Revenue, Total Interest, Total Transactions, Total Amount).
- Line Charts for weekly revenue trends.
- Stacked Bar Charts to compare revenue by Gender, Education Level, Job Type.
- Donut Charts for card usage by Card Category.
- Tables for top customers by revenue.
- TreeMap for revenue breakdown by expenditure categories.

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
