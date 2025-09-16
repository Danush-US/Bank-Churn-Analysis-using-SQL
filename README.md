# Bank Churn Analysis using SQL  

## Business Problem  
Customer churn is a critical challenge in the banking industry.  
- Acquiring a new customer is significantly more expensive than retaining an existing one.  
- Customers with high credit utilization often indicate financial distress and a higher risk of default.  
- Banks need to retain long-tenure VIP customers and identify opportunities for cross-selling financial products.  

The problem to solve: How can customer demographics and financial behavior be analyzed to reduce churn, manage risk, and improve profitability?  

---

## Solution  
This project uses Microsoft SQL Server to analyze customer data and provide actionable insights for retention, risk management, and profitability.  

Key steps:  
- Data preparation: Imported, cleaned, and standardized customer data.  
- KPI development: Total customers, average age, average utilization ratio, average credit limit.  
- Segmentation: Customers grouped by demographics (age, income, marital status, education, card type).  
- Risk profiling: Classified customers into Low, Moderate, and High Risk using utilization thresholds.  
- Customer insights:  
  - High-risk customers identified through high utilization.  
  - VIP customers identified through long tenure and strong balances.  
  - Cross-sell opportunities identified for customers with high credit limits but low balances.  

---

## Key Insights  
- Basic and Silver cardholders dominate, while Platinum cardholders are fewer but more profitable.  
- Customers with utilization above 80% are at high risk of default.  
- High-income customers maintain larger balances, making them suitable cross-sell targets.  
- Long-tenure customers with strong balances represent loyal VIPs who require retention efforts.  
- Customers with high credit limits but low balances represent untapped opportunities.  

---

## Business Impact  
- Credit Risk Management: Early identification of high-risk customers.  
- Retention Strategies: Re-engagement of churn-prone or dormant customers.  
- Personalized Banking: Tailored services for high-income, low-risk customers.  
- Marketing Optimization: Improved targeting of customer segments.  
- Loyalty Programs: Rewarding long-term VIP customers to strengthen relationships.  

---



## Visuals  

### 1. KPI Overview  
Shows Total Customers, Average Age, Credit Limit, and Utilization Ratio.  
![KPI Overview](https://github.com/Danush-US/Bank-Churn-Analysis-using-SQL/blob/main/kpi_overview.png)  

---

### 2. Customer Distribution by Card Category  
Number of customers in each Card Category.  
![Card Distribution](https://github.com/Danush-US/Bank-Churn-Analysis-using-SQL/blob/main/card_distribution.png)  

---

### 3. Average Balance by Income Level  
Average balance grouped by Income Levels.  
![Income vs Balance](https://github.com/Danush-US/Bank-Churn-Analysis-using-SQL/blob/main/income_balance.png)  

---

### 4. Customers by Marital Status  
Distribution of customers by Marital Status.  
![Marital Status](https://github.com/Danush-US/Bank-Churn-Analysis-using-SQL/blob/main/marital_status.png)  

---

### 5. Age Group Segmentation  
Segmentation of customers by Age Ranges.  
![Age Segmentation](https://github.com/Danush-US/Bank-Churn-Analysis-using-SQL/blob/main/age_segmentation.png)  

---

### 6. Top 10 Customers by Utilization Ratio  
High-risk customers with the highest utilization ratio.  
![Top 10 Utilization](https://github.com/Danush-US/Bank-Churn-Analysis-using-SQL/blob/main/top10_utilization.png)  

---

### 7. VIP Customers — Tenure vs Balance  
Customers with longest relationships and higher balances.  
![VIP Customers](https://github.com/Danush-US/Bank-Churn-Analysis-using-SQL/blob/main/vip_customers.png)  

---

## Insights  

- Most customers fall in the 26–45 age group.  
- High-income groups maintain higher average balances.  
- Customers with utilization above 80% are at higher churn risk.  
- VIP customers have tenure longer than 53 months.  



## Conclusion  
This project demonstrates how SQL can be applied beyond reporting to generate business-driven insights. It showcases skills in data cleaning, query optimization, KPI development, segmentation, and risk profiling, while connecting technical results with real-world banking strategies.  
  
