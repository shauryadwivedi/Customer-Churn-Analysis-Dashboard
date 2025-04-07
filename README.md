# 📊Customer-Churn-Analysis-Dashboard
🔍 Project Overview

The Customer Churn Dashboard is an interactive business intelligence tool developed to help companies understand and reduce customer churn. Built using Power BI, with data pre-processed in Python (Pandas, NumPy) on Google Colab, this dashboard provides both high-level trends and detailed customer-level analysis.

The dashboard enables stakeholders to explore key patterns in customer behavior, identify high-risk segments, and take proactive decisions to improve customer retention.

🎯 Objectives

Analyze and visualize customer churn across demographics, services, and billing factors.

Identify common trends among churned customers.

Provide a customer-level lookup tool for churn analysis.

Enable actionable insights for business teams using an intuitive interface.

🛠️ Tools and Technologies Used

Component	Tools/Technologies
Data Source	CSV File (Telco Customer Churn Dataset)
Data Cleaning	Python (Pandas, NumPy) via Google Colab
Visualization	Power BI Desktop

📁 Dataset

Source: Telco Customer Churn Dataset – Kaggle

Features Include:

Demographics (Gender, Age, SeniorCitizen)

Services (Phone, Internet, Streaming)

Billing (MonthlyCharges, TotalCharges, ContractType)

Churn Label (Yes/No)

📄 Dashboard Pages Overview

📌 Page 1: Churn Analysis Overview

KPIs: Total Customers, Churned Customers, Churn Rate

Filters: Gender, Contract Type, Internet Service, Tenure Group, etc.

Visuals: Pie Charts, Bar Graphs, Clustered Columns, and Time Trends

Comparative Insights: Churn vs Non-Churn

🔎 Page 2: Individual Customer Lookup

Enter Customer ID to view churned customer details

Information Includes:

Personal and Demographic Details

Contract and Billing Info

Services Subscribed


Helps support teams understand why a specific customer may have left

📊 Key Features

Dynamic filters and slicers for interactive exploration

Drill-downs for deeper insights

Real-time lookup of customer records

Clean and business-ready visual design

📝 How to Use
Open Google Colab and run data_cleaning.ipynb to preprocess the dataset.

Download the cleaned CSV and open Power BI Desktop.

Load the dataset and open customer_churn_dashboard.pbix.

Explore the dashboard:

Use filters to view churn insights.

Go to Page 2 and input a Customer ID for individual analysis.

📷 Dashboard Preview
![image](https://github.com/user-attachments/assets/cb284560-ea64-4e29-85ee-373a966a0315)




![image](https://github.com/user-attachments/assets/3a4bd707-0383-45a9-9b71-a3bce170090d)


📌 Use Cases

Identify customer segments most likely to churn.

Enable support teams to understand individual churn cases.

Inform retention strategies based on data-driven insights.

🤝 Contributions

Have suggestions or want to contribute? Fork the repository, make your changes, and submit a pull request.
