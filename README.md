# Dynamic Risk Profiling and Performance Analysis in Consumer Lending Using Excel

### 📌 Project Overview
This project analyzes a large-scale consumer lending dataset to evaluate loan portfolio risk, profitability, and performance trends. Using Excel, I developed a dynamic, interactive dashboard that provides insights into loan defaults, recovery rates, borrower behavior, and risk-adjusted returns.

The analysis supports data-driven lending decisions by helping stakeholders identify high-risk segments, grade-wise profitability, and performance trends over time.

### 📂 Dataset Information
- **Source:** Provided dataset loan_final313_.csv
- **Size:** 390,000+ loan records
- **Key Features:**
  - **Loan Details:** Loan amount, term, interest rate, loan grade, purpose, region
  - **Borrower Information:** Annual income, employment length, home ownership
  - **Performance Metrics:** Loan condition (Good/Bad), total payments, recoveries, DTI ratio

### ⚙️ Methodology
1️⃣ Data Preparation
- Cleaned and standardized loan data
- Handled missing values and categorical encodings
- Created helper columns:
  - Default Flag (Good vs Bad Loan)
  - Profitability (Total Payment – Loan Amount)
  - Loan Profitability Index (LPI)

2️⃣ Risk & Performance Analysis
- Default Rate Analysis by grade, term, and region
- Risk-Adjusted Return Calculation for each grade
- Recovery Rate Analysis for defaulted loans
- Loan Purpose & Region Trends
- Correlation Analysis: Loan Amount vs Income, Interest Rate vs Default Rate

3️⃣ Dashboard Development
- Excel Tools Used:
  - Pivot Tables & Pivot Charts
  - Slicers for Year, Region, Grade, Loan Term
  - Conditional Formatting for high-risk loans
  - Advanced Excel Formulas (IF, VLOOKUP, SUMPRODUCT, COUNTIFS, MODE)
  - Scatter plots, bar charts, donut charts, line trends

📊 Dashboard Features
- KPI Summary: Total Loans, Avg Loan Amount, Avg Interest Rate, Default Rate
- Risk Profile Visualization: Default rates by grade & employment length
- Trend Analysis: Loan amounts, interest rates, and defaults over time
- Top 5 Lists: Regions and loan purposes with highest lending volume
- Interactive Controls: Slicers for filtering data by grade, region, and loan term

✅ Key Insights & Outcomes
- Identified Grades F & G as highest risk with negative risk-adjusted returns
- Grades A & B provided highest profitability after adjusting for defaults
- Certain loan purposes (e.g., debt consolidation) had higher default concentrations
- Recommended portfolio optimization by reallocating capital toward safer segments

**Dashboard link** - https://docs.google.com/spreadsheets/d/15sDan-LI8jnZ5LC6xYzN82_5CeZGYvu9/edit?usp=sharing&ouid=112633500626026739476&rtpof=true&sd=true
