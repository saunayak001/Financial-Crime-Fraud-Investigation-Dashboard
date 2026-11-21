# Fraud Investigation & Financial Crime Intelligence Dashboard

An Excel-based financial crime analytics project featuring interactive dashboards for transaction fraud monitoring, risk analysis and investigation outcomes.

---

## 1. Project Overview

This project focuses on analysing financial transactions, fraud alerts and investigation cases through an interactive Excel dashboard.

The objective is to demonstrate how data analytics can support fraud detection, transaction monitoring, risk assessment and financial crime investigation processes.

The project combines data cleaning, data modelling, analytical calculations and interactive visualisation to transform structured datasets into meaningful insights.

The reporting period covered by the dashboards is **1 November 2025 – 31 October 2026**.

## 2. Business Problem

Financial institutions process large volumes of transactions across multiple payment methods and channels. Identifying suspicious patterns, prioritising fraud alerts and managing investigation cases efficiently can be challenging.

Without structured analysis, it may be difficult to:

- Identify unusual transaction patterns.
- Monitor fraud alerts across different payment methods.
- Understand customer, account and device-related risks.
- Prioritise high-risk alerts and investigations.
- Analyse confirmed fraud and false-positive cases.
- Monitor investigation outcomes and investigator workloads.

This project addresses these analytical challenges through interactive dashboards and structured data analysis.

## 3. Project Objectives

The key objectives of this project are to:

- Analyse transaction activity across different payment methods and channels.
- Examine fraud alerts based on priority and alert type.
- Identify customer, account and device-related risk patterns.
- Analyse investigation outcomes, including confirmed fraud and false positives.
- Monitor investigation status, escalation patterns and risk categories.
- Evaluate investigator workload and case distribution.
- Present actionable insights through interactive Excel dashboards.

## 4. Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Microsoft Excel | Dashboard development and data analysis |
| Power Query | Data cleaning and transformation |
| Power Pivot | Data modelling and relationships |
| DAX | Calculated measures and KPIs |
| PivotTables | Data summarisation and analysis |
| PivotCharts | Interactive data visualisation |
| Slicers & Timeline | Interactive filtering and reporting |

## 5. Dataset Overview

The project uses structured datasets covering transaction activity, customer information, accounts, fraud alerts and investigation records.

### Principal Data Tables

1. **Customers:** Customer-related information and risk attributes.
2. **Accounts:** Account information and associated risk indicators.
3. **Transactions:** Transaction-level records covering different payment methods and channels.
4. **Fraud Alerts:** Alerts generated for potentially suspicious activities, including alert priority and alert type.
5. **Investigation Cases:** Investigation records containing case status, risk category, investigation type and final decisions.

### Supporting Data Tables

- Beneficiaries
- Devices
- Calendar / Date Table

These supporting tables provide additional analytical context and help establish relationships across the data model.

## 6. Dashboard 1 – Fraud & Transaction Intelligence

This dashboard focuses on transaction monitoring, fraud alert analysis and risk indicators.

### Key Analytical Areas

- Overall transaction activity.
- Payment method analysis:
  - Card Payment
  - Bank Transfer
  - Cash Withdrawal
  - Internal Transfer
- Transaction initiation channel analysis:
  - Card
  - Mobile
  - Web
- Fraud alert priority analysis:
  - Critical
  - High
  - Medium
  - Low
- Fraud alert type analysis.
- Customer and account risk analysis.
- Device trust and risk analysis.
- Monthly transaction and fraud alert trends.
- Geographic analysis of transaction activity.

### Interactive Features

The dashboard includes interactive slicers and filters to analyse transaction activity and fraud alerts across different dimensions.

Users can explore specific payment methods, initiation channels, alert priorities and alert types to understand patterns within the reporting dataset.

## 7. Dashboard 2 – Fraud Investigation & Case Intelligence

This dashboard focuses on investigation outcomes, case management and operational analysis.

### Key Performance Indicators

- Total Investigation Cases
- Confirmed Fraud Cases
- False Positive Cases
- Escalated Cases
- Confirmation Rate
- Escalation Rate

### Key Analytical Areas

- Investigation status analysis.
- Final investigation decision analysis.
- Investigation type analysis.
- Risk category analysis.
- Monthly investigation trends.
- Investigator workload and case outcomes.
- Escalated investigation analysis.
- Confirmed fraud investigation analysis.

### Interactive Features

The dashboard enables users to explore investigation cases based on status, final decision, investigation type, risk category and investigator-related dimensions.

This supports a better understanding of investigation outcomes and operational workload distribution.

## 8. Key Analytical Insights

The project demonstrates how transaction-level data, fraud alerts and investigation records can be analysed together to identify suspicious patterns, understand fraud risks and evaluate investigation outcomes.

The following insights emerged from the dashboard analysis:

### 1. Fraud Alert and Transaction Monitoring

- The dashboard tracks transaction activity and fraud alerts across different payment methods, including card payments, bank transfers, cash withdrawals and internal transfers.
- Payment-channel analysis helps compare activity across card, mobile and web initiation channels.
- Alert priority analysis enables investigators to distinguish critical and high-priority alerts from lower-priority cases.

### 2. Investigation Outcomes

- A total of **600 investigation cases** were recorded in the reporting dataset.
- **144 cases** were classified as Confirmed Fraud, while **247** were classified as False Positive.
- **58 cases** were escalated for further investigation.
- The overall confirmation rate displayed by the dashboard was **28.24%**, highlighting the importance of effective alert prioritisation and investigation quality.

### 3. Risk-Based Investigation

- The high-risk investigation segment contained **270 cases**, including **144 confirmed fraud cases**.
- This demonstrates how risk categorisation can help investigators focus attention on cases with stronger indicators of suspicious activity.
- Risk categories should support investigation decisions rather than independently determine whether fraud has occurred.

### 4. Alert-Type Analysis

- Separate analysis of critical-priority alerts, device-change alerts and high-value transfer alerts helps illustrate how different suspicious activity indicators can be examined.
- Analysing alert types alongside transaction and customer context can support more informed investigation decisions.

### 5. Investigator Workload and Case Outcomes

- Investigator-level analysis provides visibility into case allocation, investigation volumes and outcomes.
- This can help identify workload distribution patterns and support operational planning.

### Business Significance

These insights demonstrate how data analytics can support financial crime operations through transaction monitoring, alert prioritisation, risk-based investigation, false-positive analysis and investigation workload visibility.

## 9. Business Recommendations

Based on the analytical patterns identified in the dashboards, the following operational recommendations could help strengthen fraud monitoring and investigation processes:

1. **Strengthen Risk-Based Alert Prioritisation**

   Prioritise critical and high-risk alerts for timely review while ensuring that lower-priority alerts are assessed through appropriate risk-based procedures.

2. **Improve False-Positive Management**

   Analyse recurring false-positive patterns to identify opportunities to refine alert rules and improve investigation efficiency without compromising fraud detection.

3. **Enhance Transaction Monitoring**

   Review suspicious activity across payment methods and initiation channels to identify patterns that may require additional monitoring or investigation.

4. **Strengthen Investigation Processes**

   Use investigation outcomes and risk categories to support consistent case assessment, escalation and decision-making.

5. **Monitor Investigator Workload**

   Review case allocation and investigation volumes to identify workload imbalances and support more effective operational planning.

*These recommendations are analytical suggestions derived from the project dataset and are not representations of production financial crime policies or procedures.*

## 10. Key Analytical Metrics

The dashboards include several important metrics to support transaction monitoring and investigation analysis.

| Metric | Purpose |
|---|---|
| Total Transactions | Measures overall transaction activity |
| Total Fraud Alerts | Measures the number of generated fraud alerts |
| Confirmed Fraud Cases | Tracks cases classified as confirmed fraud |
| False Positive Cases | Tracks cases classified as false positives |
| Escalated Cases | Measures cases escalated for further investigation |
| Confirmation Rate | Measures the proportion of investigated cases classified as confirmed fraud, according to the dashboard calculation |
| Escalation Rate | Measures the proportion of cases escalated, according to the dashboard calculation |

## 11. Financial Crime Terminology & Analytical Context

The project incorporates important concepts commonly used in fraud investigation, transaction monitoring and financial crime operations.

| Term | Explanation | Project Relevance |
|---|---|---|
| Transaction Monitoring | Reviewing transactions to identify unusual or potentially suspicious activity. | Transaction and payment-channel analysis |
| Transaction Velocity | The frequency or volume of transactions within a specific period. | Transaction activity analysis |
| High-Value Transaction | A transaction involving an unusually large amount relative to an expected pattern or applicable risk criteria. | High-value transfer alert analysis |
| Account Takeover (ATO) | A situation where an unauthorised person gains control of another person's account. | Account and device risk analysis |
| APP Fraud | Authorised Push Payment fraud, where a customer is manipulated into authorising a payment to a fraudster. | Potential APP investigation analysis |
| Mule Account | An account used to receive, transfer or move funds associated with illicit activity. | Investigation and transaction analysis |
| First-Party Fraud | Fraud involving an individual misrepresenting information or deliberately abusing a financial product or service. | Investigation type analysis |
| False Positive | An alert or case that is reviewed but not determined to involve the suspected fraudulent activity. | False-positive analysis |
| Risk-Based Investigation | Prioritising investigation efforts based on the level and nature of identified risk. | Risk category and alert priority analysis |
| Alert Prioritisation | Assigning priority levels to alerts based on risk indicators and potential severity. | Fraud alert priority analysis |

## 12. Data Preparation & Modelling

Data preparation and modelling were important stages of this project.

### Power Query – Data Cleaning & Transformation

Power Query was used to prepare the datasets for analysis.

Key activities included:

- Reviewing data types and column structures.
- Checking missing and invalid values.
- Identifying potential data-quality issues.
- Cleaning and trimming text fields.
- Applying appropriate data transformations.
- Creating calculated and conditional columns where required.
- Preparing tables for the data model.

### Power Pivot – Data Modelling

Power Pivot was used to establish relationships between the principal and supporting data tables.

This enabled analysis across customers, accounts, transactions, fraud alerts and investigation cases.

### DAX – Measures & KPIs

DAX measures were developed to calculate important analytical metrics, including:

- Confirmed Fraud Cases
- False Positive Cases
- Escalated Cases
- Confirmation Rate
- Escalation Rate

### PivotTables & PivotCharts

PivotTables and PivotCharts were used to summarise data, analyse patterns and create the visual components of both dashboards.

Slicers and timelines were incorporated to support interactive analysis.

## 13. Project Demonstration & Repository Contents

The repository provides a visual overview of the project through dashboard screenshots and a demonstration video.

### Project Demo Video

🎥 **Watch the project demonstration:**

- [▶️ Watch the Financial Crime & Fraud Investigation Dashboard Demo on YouTube](https://youtu.be/HFd2PhyPl6s)
- [GitHub Video](Project_Demo_Video/Financial_Crime_Fraud_Investigation_Dashboard_Demo.mp4) — View/download the demo directly from the repository.

The demonstration video showcases the dashboards, interactive filters, analytical views and key functionalities developed as part of this project.

### Dashboard Screenshots

- [Dashboard 1 – Fraud & Transaction Intelligence](Dashboard_1_Fraud_Transaction_Intelligence/)
- [Dashboard 2 – Investigation & Case Intelligence](Dashboard_2_Investigation_Case_Intelligence/)
- [Technical Implementation](Technical_Implementation/)

The screenshots provide a visual overview of the dashboards, their interactive capabilities and the analytical approach used in the project.

The complete working Excel workbook and its supporting source files are not included in this public repository.

## 14. Key Learnings & Project Limitations

### Key Learnings

Through this project, I gained practical experience in:

- Preparing and transforming structured datasets using Power Query.
- Building relational data models using Power Pivot.
- Developing DAX measures for analytical KPIs.
- Analysing transaction activity and fraud alert patterns.
- Understanding financial crime investigation concepts.
- Creating interactive dashboards using PivotTables, PivotCharts, slicers and timelines.
- Translating analytical findings into operational recommendations.

### Project Limitations

- The dashboards are based on a prepared dataset and a defined reporting period.
- The project demonstrates analytical workflows rather than a live fraud detection or transaction monitoring system.
- It does not connect to live banking transactions, customer accounts or production financial crime systems.
- The analysis does not automate fraud determinations or replace professional investigation.

## 15. Access to Complete Project Files

I retain the complete Excel workbook, including both interactive dashboards, supporting worksheets, Power Query transformations, Power Pivot data model and DAX measures.

Recruiters, hiring managers or other interested reviewers who would like to explore the complete working project are welcome to contact me through LinkedIn for further discussion and to request access to the original project files.

**To request access, connect with me or send me a message on LinkedIn:**

[Saumya Ranjan Nayak](https://www.linkedin.com/in/nsaumya01/)

Requests will be considered individually.

## 16. Author / Creator

**Created by: Saumya Ranjan Nayak**

Aspiring Financial Crime & Data Analytics Professional

This project was independently conceptualised and developed as part of my portfolio to demonstrate practical skills in fraud analysis, transaction monitoring, financial crime investigation and data visualisation using Microsoft Excel.

## 17. Disclaimer

This is an independent educational and portfolio project developed for learning and demonstration purposes. It is not an official product, service or representation of any financial institution or organisation.

The project does not use real customer investigations, live financial transactions or production banking data. Its dashboards and findings are intended to demonstrate analytical techniques and financial crime investigation concepts for educational purposes only.
