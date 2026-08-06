# 💳 Power BI Executive Analytics Suite
* **Focus:** Interactive drill-downs, cross-filtering, and dynamic risk tier modeling.
<img width="1188" height="508" alt="Executive_Credit_Risk_Performance_Dashboard" src="https://github.com/user-attachments/assets/3750ed8a-ae22-44fa-9849-893d29e152e0" />

# 📊 Excel Exploratory Risk Dashboard
* **Focus:** Data auditing, initial pivot analysis, and baseline default distribution modeling.
* <img width="1321" height="560" alt="Credit_Risk_Analysis_Dashboard" src="https://github.com/user-attachments/assets/9a99f3ad-d798-46e9-8c18-3004e98455bc" />

## 📌 Project Overview
Financial institutions and credit risk managers require granular visibility into portfolio risk profiles to minimize loan defaults and maintain capital adequacy. 

This project delivers an interactive credit risk analytics engine evaluating **500 applicant profiles**, analyzing credit score tiers, Debt-to-Income (DTI) ratios, income distributions, and employment demographics to identify key risk indicators and optimize underwriting thresholds.

---

## 🎯 Key Business Objectives
* **Default Risk Assessment:** Identify high-risk borrower segments based on credit tier ratings, loan-to-value metrics, and default probability.
* **Underwriting Threshold Analysis:** Evaluate Debt-to-Income (DTI) ratio distributions to pinpoint high-risk lending zones.
* **Demographic & Employment Audit:** Analyze how income stability, employment tenure, and loan purpose correlate with repayment behaviors.
* **Portfolio Risk Stratification:** Categorize loan applicants into distinct risk tiers (Prime, Subprime, High Risk) for tailored interest rate strategies.

---

## 🧹 Data Pipeline & ETL Transformation
* **Data Ingestion & Cleaning:** Standardized applicant demographic logs, imputed missing income values, and audited employment status fields.
* **Risk Categorization:** Engineered custom risk bands combining credit score brackets and DTI threshold flags.
* **Validation & Integrity:** Verified total balance calculations, interest rates, and loan status metrics across all 500 applicant profiles.

---

## 🛠️ Data Architecture & Modeling
1. **Data Modeling:** Constructed a star schema linking borrower profiles, loan attributes, and default outcomes.
2. **DAX Measures & Risk Metrics:**
   * Developed custom formulas for **Default Rate (%)**, **Average DTI Ratio**, **Total Risk Exposure ($)**, **Prime vs. Non-Prime Loan Ratio**, and **Expected Loss Calculations**.
3. **Interactive Visual Reporting:**
   * Designed a dynamic dashboard featuring multi-parameter slicers (Credit Tier, Income Bracket, Loan Purpose) and distribution charts.

---

## 💡 Key Risk Insights
* **DTI Warning Thresholds:** Applicants with DTI ratios exceeding 45% demonstrate a significantly higher rate of default, indicating a critical threshold for loan approval boundaries.
* **Credit Tier Performance:** Subprime credit tiers account for a disproportionate volume of overall portfolio default losses despite lower initial loan amounts.
* **Employment Tenure Correlation:** Borrowers with less than 2 years of current employment tenure display higher default vulnerability during macroeconomic shifts.

---

## 🛠️ Tools & Technologies Used
* **Power BI Desktop:** DAX Calculations, Interactive Reporting, & Risk Tier Slicing
* **Microsoft Excel:** Advanced Pivot Tables, Baseline Modeling, & Data Auditing
* **Power Query:** ETL Operations, Data Cleaning, & Column Standardization
* **GitHub:** Portfolio Documentation & Version Control

---

## 📊 Excel Risk Dashboard Preview
<img width="1315" height="313" alt="Credit_Risk_Analysis_Dashboard_2" src="https://github.com/user-attachments/assets/5a2e3ab7-c6e8-45c8-9fc4-236bc5dd5652" />
