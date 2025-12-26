🔍 Project Overview

This project analyzes telecom customer churn using Power BI to identify key factors that influence customer attrition.
The analysis helps businesses reduce churn, improve customer satisfaction, and make data-driven decisions.

❗ Business Problem

Telecom companies face high customer churn, leading to revenue loss and increased acquisition costs.
However, without proper analysis, it is difficult to understand:

Why customers leave

Which customers are at high risk

Which services or pricing models cause churn

✅ Solution Approach

Cleaned and transformed raw customer data

Built churn-related KPIs using DAX

Analyzed churn across demographics, tenure, services, and billing

Created interactive Power BI dashboards for insights and decision-making

📁 Dataset Information

Total Records: 7,043 customers

Key Columns:

CustomerID

Gender, SeniorCitizen, Partner, Dependents

Tenure

PhoneService, InternetService, OnlineSecurity, TechSupport

Contract, PaymentMethod, MonthlyCharges, TotalCharges

Churn

🧹 Data Cleaning Steps

✔ Removed null values (TotalCharges)
✔ Converted TotalCharges from text to numeric
✔ Standardized categorical values (Yes/No)
✔ Removed duplicate records
✔ Created derived fields:

Tenure Groups

Total Services Subscribed

📐 Key DAX Measures

Churn Rate

Total Customers

Churned Customers

Average Monthly Charges

Average Tenure

Total Revenue

📈 Key Insights

Customers with month-to-month contracts have the highest churn

Low-tenure (0–12 months) customers are more likely to churn

Fiber optic users show higher churn due to higher charges

Customers with more subscribed services tend to be more loyal

Auto-payment methods reduce churn rate

🧠 Business Applications

🎯 Marketing: Target high-risk customers with retention offers

🛠 Customer Support: Improve services for high-churn segments

📊 Management: Track churn KPIs and trends

📦 Product Teams: Optimize pricing and service bundles

💰 Finance: Forecast revenue loss due to churn

📊 Power BI Dashboard

The dashboard includes:

Overall churn KPIs

Churn by tenure, contract, and payment method

Customer demographic analysis

Interactive filters for deep analysis

(Add screenshots here)

🚀 Tools & Technologies

🟡 Power BI

📗 Excel

📘 DAX

🧹 Power Query

🏁 Conclusion

This project demonstrates how data analytics and visualization can help telecom companies:

Reduce customer churn

Improve customer experience

Increase revenue stability

