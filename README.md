# Customer Churn Analytics

<p>
This project focuses on identifying patterns and behaviors that lead to customer churn in a leading online E-commerce company.
By analyzing customer behavior, preferences, and engagement metrics, we aim to uncover key churn indicators and suggest data-driven strategies to improve customer retention.
</p>

<h2>Business Challenge</h2>
<p>
Customer churn is a critical problem for online retailers, as losing active customers can significantly impact revenue and profitability.
This project aims to help the business identify customers who are likely to churn, understand the reasons behind churn, and propose strategies to retain valuable customers using data-driven insights.
</p>

<h2> Dataset Overview</h2>
<p>
The dataset belongs to a prominent E-commerce company and includes information about customer demographics, behavior, and transaction history.
</p>

<h3>Key Features:</h3>
<table>
  <thead>
    <tr>
      <th>Column</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>CustomerID</td><td>Unique customer identifier</td></tr>
    <tr><td>Churn</td><td>Target variable indicating if a customer has churned</td></tr>
    <tr><td>Tenure</td><td>Duration of customer relationship with the platform</td></tr>
    <tr><td>PreferredLoginDevice</td><td>Customer’s login device</td></tr>
    <tr><td>CityTier</td><td>Tier of the customer's city</td></tr>
    <tr><td>WarehouseToHome</td><td>Distance between warehouse and customer’s home</td></tr>
    <tr><td>PreferredPaymentMode</td><td>Most used payment method</td></tr>
    <tr><td>Gender</td><td>Customer's gender</td></tr>
    <tr><td>HourSpendOnApp</td><td>Hours spent on the app or website</td></tr>
    <tr><td>NumberOfDeviceRegistered</td><td>Devices registered by the customer</td></tr>
    <tr><td>PreferedOrderCat</td><td>Most ordered category in the last month</td></tr>
    <tr><td>SatisfactionScore</td><td>Customer's satisfaction score</td></tr>
    <tr><td>MaritalStatus</td><td>Customer's marital status</td></tr>
    <tr><td>NumberOfAddress</td><td>Number of addresses added by the customer</td></tr>
    <tr><td>Complain</td><td>If a complaint was raised in the last month</td></tr>
    <tr><td>OrderAmountHikeFromlastYear</td><td>% increase in order amount from last year</td></tr>
    <tr><td>CouponUsed</td><td>Coupons used in the last month</td></tr>
    <tr><td>OrderCount</td><td>Number of orders placed in the last month</td></tr>
    <tr><td>DaySinceLastOrder</td><td>Days since the last order</td></tr>
    <tr><td>CashbackAmount</td><td>Average cashback in the last month</td></tr>
  </tbody>
</table>

<h2> Analysis Scope</h2>
<ul>
  <li><strong>Objective:</strong> Analyze customer churn behavior to identify key drivers and support retention efforts.</li>
  <li><strong>Inclusion Criteria:</strong> All customers with complete records on churn and behavioral features.</li>
  <li><strong>Exclusion Criteria:</strong> Customers with missing or inconsistent values after preprocessing.</li>
  <li><strong>Time Frame:</strong> Data is assumed to represent customer behavior for a recent month/year.</li>
  <li><strong>Tools Used:</strong> Python (Pandas, NumPy, Matplotlib, Seaborn), Jupyter Notebook</li>
</ul>

<h2> Key Business Questions</h2>
<ul>
  <li>Can the number of days since the last order help design targeted marketing campaigns?</li>
  <li>Are there differences in buying behavior between male and female customers?</li>
  <li>What are the key indicators that lead to customer churn?</li>
  <li>Does warehouse-to-home distance correlate with customer complaints?</li>
  <li>Is the number of saved addresses related to customer churn?</li>
</ul>

<h2>Analysis & Insights</h2>
<ul>
  <li>Identified behavioral patterns of churned vs. retained customers.</li>
  <li>Discovered strong correlations between churn and low satisfaction scores, high complaint frequency, and long gaps since last order.</li>
  <li>Gender-based behavior differences revealed in order frequency and device preferences.</li>
  <li>Customers living farther from warehouses tend to raise more complaints.</li>
  <li>A higher number of registered addresses may indicate more active or loyal users.</li>
</ul>
<p><strong> See full visualizations and detailed insights in the Jupyter Notebook</strong></p>

<h2> Recommendations</h2>
<ul>
  <li>Implement personalized re-engagement campaigns for users with high <code>DaySinceLastOrder</code>.</li>
  <li>Address root causes of complaints from distant customers by optimizing delivery experience.</li>
  <li>Launch loyalty incentives for users with low order counts or satisfaction scores.</li>
  <li>Consider gender-based promotions based on observed buying patterns.</li>
  <li>Encourage address registration as it may indicate deeper platform engagement.</li>
</ul>

<h2> Data Preprocessing</h2>
<ul>
  <li>Handled missing values and outliers</li>
  <li>Encoded categorical variables</li>
  <li>Normalized relevant numerical features</li>
  <li>Feature selection based on correlation and domain knowledge</li>
</ul>
