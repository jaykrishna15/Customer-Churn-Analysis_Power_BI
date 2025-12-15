# 📊 Customer Churn Analysis – Power BI Project

## 🔍 Overview

This Power BI project analyzes customer churn behavior in a telecom company to identify key factors influencing customer retention and revenue.
The dashboard provides insights into demographics, service subscriptions, contract types, billing patterns, and churn prediction drivers — helping stakeholders make data-driven decisions to reduce churn and improve customer satisfaction.

🧾** Dataset Description**  

Source: Telecom Customer Dataset
Rows: 7,043
Columns: 21

| Column                                                                                         | Description                                               |
| ---------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| customerID                                                                                     | Unique ID for each customer                               |
| gender                                                                                         | Male or Female                                            |
| SeniorCitizen                                                                                  | Indicates senior citizen (1 = Yes, 0 = No)                |
| Partner                                                                                        | Whether the customer has a partner                        |
| Dependents                                                                                     | Whether the customer has dependents                       |
| tenure                                                                                         | Number of months the customer has stayed with the company |
| PhoneService                                                                                   | Indicates if phone service is active                      |
| MultipleLines                                                                                  | Multiple phone lines or not                               |
| InternetService                                                                                | Type (DSL, Fiber optic, or No Internet)                   |
| OnlineSecurity / OnlineBackup / DeviceProtection / TechSupport / StreamingTV / StreamingMovies | Add-on service subscriptions                              |
| Contract                                                                                       | Month-to-month, One year, or Two year                     |
| PaperlessBilling                                                                               | Yes or No                                                 |
| PaymentMethod                                                                                  | Payment mode used by the customer                         |
| MonthlyCharges                                                                                 | Monthly fee charged                                       |
| TotalCharges                                                                                   | Total billed amount                                       |
| Churn                                                                                          | Indicates whether the customer has churned (Yes/No)       |


🧠 **Objectives**

Identify customer segments with high churn risk.

Analyze tenure, service, and contract patterns.

Understand billing methods and churn relationship.

Compare revenue impact of lost vs retained customers.

Provide data-driven recommendations for retention strategies.

📈 **Key Insights**
🧍‍♂️ **Customer Demographics**

Overall churn rate: 27%

Senior citizens have a higher churn tendency.

Customers in their first year show the highest churn.

Average monthly charges rise with higher tenure.

🌐** Service Subscription Analysis**

Fiber Optic users churn the most (42%).

Customers with more add-on services churn less.

Most churned customers used streaming services.

💳 **Contract & Billing Insights**

Month-to-month contracts cause 75% of total churn.

Two-year contracts have the lowest churn rate (~5%).

Electronic check payments show the highest churn.

Auto-payment (bank/credit card) users are more loyal.

🤖** Churn Prediction & Key Drivers**

Highest churn risk: Fiber Optic + Month-to-Month customers.

Lack of Tech Support or Online Security increases churn (~42%).

Lost Revenue: ₹139K | Retained Revenue: ₹316K

⚙️ **Tools & Techniques Used**

Power BI Desktop – Dashboard creation & data visualization

Power Query – Data cleaning & transformation

DAX – KPI & measure calculations

SQL – Data extraction and preprocessing

Data Modeling – Star schema relationships

🧩 **Dashboard Pages**

Customer Demographics Analysis

Service Subscription Analysis

Contract & Billing Insights

Churn Prediction & Key Drivers

🧭** Business Recommendations**

✅ Encourage customers to move to long-term contracts
✅ Offer bundled packages with add-on services
✅ Improve Fiber Optic service quality
✅ Promote auto-payment options
✅ Enhance digital experience for paperless billing users
