# Background-Verification-Risk-Dashboard-.powe-bi-excel-power-query


📊 Background Verification Risk Analyzer
🧠 Project Overview

The Background Verification Risk Analyzer is a data analytics project designed to identify risks in the hiring process by analyzing candidate verification data. It helps organizations detect discrepancies, evaluate vendor performance, and improve overall verification efficiency.

🎯 Business Problem

Organizations rely on background verification to ensure candidate authenticity. However:

Candidates may provide incorrect information
Vendors may have inconsistent verification quality
Delays in verification can increase hiring risks

This project aims to solve these issues using data-driven insights.

📁 Dataset Description

A synthetic dataset was created to simulate real-world verification scenarios.

🔑 Features:
Candidate_ID – Unique identifier
Education_Verified – Yes/No
Employment_Verified – Yes/No
Address_Verified – Yes/No
Criminal_Record – Clear / Record Found
Delay_Days – Verification time in days
Vendor_Name – Verification provider
Final_Status – Clear / Discrepancy
🧹 Data Preparation

Performed in Excel:

Cleaned missing and inconsistent values
Standardized categorical data
Created derived columns:
Risk_Flag → High Risk / Low Risk
Delay_Category → Fast / Moderate / Delayed
📊 Power BI Analysis
📌 Key Metrics (DAX Measures)
Total Candidates
Discrepancy Count
Discrepancy Rate (%)
Average Delay
High Risk Count
📈 Dashboard Features
🔹 Executive Summary
Quick overview using KPI cards
🔹 Vendor Risk Analysis
Discrepancy count by vendor (Bar Chart)
🔹 Risk Distribution
High Risk vs Low Risk (Pie Chart)
🔹 Delay Analysis
Distribution of verification delays (Column Chart)
🔹 Detailed Analysis
Matrix showing vendor-wise verification outcomes
Interactive slicers (Vendor, Delay Category)
🔍 Key Insights
Certain vendors show higher discrepancy rates → potential process gaps
Delayed verifications often correlate with higher discrepancies
A significant portion of candidates fall into high-risk category
💼 Business Impact

This solution helps organizations:

Identify high-risk candidates
Improve vendor selection and monitoring
Reduce fraud and bad hiring decisions
Enhance verification efficiency
🛠️ Tools Used
Excel → Data cleaning & preprocessing
Power BI → Data modeling, DAX, dashboard creation
🚀 Future Improvements
Integrate real-time verification data
Add predictive model for risk scoring
Automate alerts for high-risk candidates
👤 Author

Tausif Raza
Aspiring Data Analyst | Power BI | Excel
