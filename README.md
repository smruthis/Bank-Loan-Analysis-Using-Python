# 🏦 Bank Loan Analysis Project

## 📌 Overview
This project analyzes a bank’s loan portfolio to understand borrower behavior, repayment performance, risk distribution, and overall financial impact. The goal is to help improve underwriting strategies, reduce defaults, and optimize lending decisions.

---

## 🎯 Objective
- Analyze loan applications and funding trends  
- Identify Good Loans vs Bad Loans  
- Evaluate borrower risk patterns  
- Track key financial KPIs  
- Provide actionable business recommendations  

---

## 🛠️ Tools & Technologies
- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📊 Dataset Description
- Total Records: 38,576 loan applications  

### Key Features:
- Loan Details: loan_amount, funded_amount, interest_rate, term, loan_status  
- Borrower Info: emp_length, home_ownership, annual_income, DTI  
- Loan Purpose: purpose, state  
- Performance Metrics: total_received_amount, profit/loss, default_flag  

---

## 🧹 Data Cleaning & Preprocessing
- Removed missing and duplicate values  
- Converted financial columns to numeric format  
- Created time-based features (Month, Year)  
- Classified loans:
  - Good Loans → Fully Paid  
  - Bad Loans → Charged Off  
- Built aggregated datasets for analysis  

---

## 📈 Key KPIs

| KPI | Value |
|-----|------|
| Total Applications | 38,576 |
| Total Funded Amount | $435.76M |
| Total Amount Received | $473.07M |
| Avg Interest Rate | 12.05% |
| Avg DTI | 13.33% |

---

## 📊 Good vs Bad Loan Analysis

### Good Loans
- Applications: 33,243 (86.18%)  
- Funded Amount: $370.22M  
- Amount Received: $435.79M  
- Profit: $65.56M  

### Bad Loans
- Applications: 5,333 (13.82%)  
- Funded Amount: $65.53M  
- Amount Received: $37.28M  
- Loss: $28.25M  

---

## 📉 Exploratory Data Analysis (EDA)

### Key Insights:

### Monthly Trends
- Stable loan activity throughout the year  
- Peak in December (high demand & funding)

### State-wise Analysis
- Heavy concentration in California  
- High revenue but increased regional risk  

### Loan Term Analysis
- 36-month loans:
  - Higher repayment  
  - Lower default risk  
  - Better profitability  

### Borrower Profile
- Low-risk:
  - 10+ years employment  
  - Mortgage holders  
- High-risk:
  - Renters  
  - <1 year employment  

### Loan Purpose
- Dominated by Debt Consolidation  
- High profitability but high dependency risk  

---

## 🔍 Key Insights Summary
- Strong demand with consistent loan applications  
- High profitability driven by Good Loans (86%)  
- Significant losses from Bad Loans (13.82%)  
- Risk concentration in:
  - California  
  - Debt Consolidation loans  
- Short-term loans outperform long-term loans  

---

## 💡 Business Recommendations

### 1. Strengthen Underwriting
- Increase credit score thresholds  
- Improve income verification  
- Use ML-based risk scoring  

### 2. Diversify Loan Portfolio
- Expand to other states  
- Promote different loan types  
- Reduce dependency on one category  

### 3. Improve Recovery Strategy
- Use data-driven collections  
- Partner with recovery agencies  
- Automate reminders  

### 4. Risk-Based Pricing
- Adjust interest rates based on borrower risk  
- Use dynamic pricing models  

### 5. Early Default Prevention
- Detect missed payments early  
- Offer restructuring options  

---

## 📌 Conclusion
The bank’s loan portfolio is highly profitable, with strong performance driven by good loans. However, risks arise from:
- Bad loan losses  
- Geographic concentration  
- Borrower risk segments  

By improving underwriting, diversifying the portfolio, and using advanced analytics, the bank can significantly enhance stability and long-term growth.

---

## 🚀 Future Improvements
- Build Machine Learning model for default prediction  
- Create interactive dashboard (Power BI / Tableau)  
- Real-time loan monitoring system  
- Advanced customer segmentation  

---

## 📷 Project Workflow
1. Data Cleaning  
2. Data Transformation  
3. KPI Calculation  
4. EDA & Visualization  
5. Insights & Recommendations  

---


## 🙌 Author
Smruthi S Kumar 
Data Analyst  
