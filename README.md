# Customer_Churn_Analysis
E-commerce Customer Churn Analytics
This project focuses on identifying patterns and behaviors that lead to customer churn in a leading online E-commerce company. By analyzing customer behavior, preferences, and engagement metrics, we aim to uncover key churn indicators and suggest data-driven strategies to improve customer retention.

📌 Business Challenge
Customer churn is a critical problem for online retailers, as losing active customers can significantly impact revenue and profitability. This project aims to help the business identify customers who are likely to churn, understand the reasons behind churn, and propose strategies to retain valuable customers using data-driven insights.

📊 Dataset Overview
The dataset belongs to a prominent E-commerce company and includes information about customer demographics, behavior, and transaction history.

Key Features:
Column	Description
CustomerID	Unique customer identifier
Churn	Target variable indicating if a customer has churned
Tenure	Duration of customer relationship with the platform
PreferredLoginDevice	Customer’s login device
CityTier	Tier of the customer's city
WarehouseToHome	Distance between warehouse and customer’s home
PreferredPaymentMode	Most used payment method
Gender	Customer's gender
HourSpendOnApp	Hours spent on the app or website
NumberOfDeviceRegistered	Devices registered by the customer
PreferedOrderCat	Most ordered category in the last month
SatisfactionScore	Customer's satisfaction score
MaritalStatus	Customer's marital status
NumberOfAddress	Number of addresses added by the customer
Complain	If a complaint was raised in the last month
OrderAmountHikeFromlastYear	% increase in order amount from last year
CouponUsed	Coupons used in the last month
OrderCount	Number of orders placed in the last month
DaySinceLastOrder	Days since the last order
CashbackAmount	Average cashback in the last month
🧭 Analysis Scope
Objective: Analyze customer churn behavior to identify key drivers and support retention efforts.

Inclusion Criteria: All customers with complete records on churn and behavioral features.

Exclusion Criteria: Customers with missing or inconsistent values after preprocessing.

Time Frame: Data is assumed to represent customer behavior for a recent month/year.

Tools Used: Python (Pandas, NumPy, Matplotlib, Seaborn), Jupyter Notebook

🔍 Key Business Questions
Can the number of days since the last order help design targeted marketing campaigns?

Are there differences in buying behavior between male and female customers?

What are the key indicators that lead to customer churn?

Does warehouse-to-home distance correlate with customer complaints?

Is the number of saved addresses related to customer churn?

📈 Analysis & Insights
Identified behavioral patterns of churned vs. retained customers.

Discovered strong correlations between churn and low satisfaction scores, high complaint frequency, and long gaps since last order.

Gender-based behavior differences revealed in order frequency and device preferences.

Customers living farther from warehouses tend to raise more complaints.

A higher number of registered addresses may indicate more active or loyal users.

(👉 See full visualizations and detailed insights in the Jupyter Notebook)

💡 Recommendations
Implement personalized re-engagement campaigns for users with high DaySinceLastOrder.

Address root causes of complaints from distant customers by optimizing delivery experience.

Launch loyalty incentives for users with low order counts or satisfaction scores.

Consider gender-based promotions based on observed buying patterns.

Encourage address registration as it may indicate deeper platform engagement.

🧹 Data Preprocessing
Handled missing values and outliers

Encoded categorical variables

Normalized relevant numerical features

Feature selection based on correlation and domain knowledge
