# 🏦 Bank Loan Monitoring Analytics Dashboard

## 📌 Project Overview

The **Bank Loan Portfolio Performance Analytics Dashboard** is an end-to-end Power BI solution designed to analyze loan applications, funding performance, repayment behavior, credit quality, borrower profiles, and portfolio risk.

The dashboard provides banking professionals, credit analysts, and business stakeholders with a comprehensive view of loan portfolio health by tracking loan issuance, funded amounts, collections, interest rates, debt-to-income ratios, and loan performance classifications.

The solution consists of three interactive reporting layers:

- Executive Summary Dashboard
- Portfolio Overview Dashboard
- Loan-Level Details Dashboard

---

## 🎯 Business Problem

Financial institutions process thousands of loan applications and manage large lending portfolios. Monitoring portfolio performance and identifying risk exposure can be challenging without centralized reporting.

Key business questions include:

- How many loans have been issued?
- What is the total funded amount?
- How much revenue has been collected?
- What percentage of loans are performing?
- What percentage of loans are at risk?
- Which borrower segments receive the most funding?
- Which loan purposes generate the highest lending volume?
- How do interest rates and DTI ratios impact portfolio performance?

The objective of this dashboard is to provide a centralized analytics platform that helps lenders monitor portfolio health, repayment performance, and lending risk.

---

# 📊 Executive KPIs

| KPI | Value |
|------|--------|
| Total Loan Applications | 38.6K |
| Total Funded Amount | $435.8M |
| Total Amount Received | $473.1M |
| Average Interest Rate | 12.05% |
| Average DTI Ratio | 13.33% |

---

## Month-over-Month Performance

| Metric | MTD |
|----------|----------|
| Loan Applications | 4.3K |
| Funded Amount | $54.0M |
| Amount Received | $58.1M |
| Avg Interest Rate | 12.4% |
| Avg DTI | 13.7% |

---

# 🔷 1. Executive Summary Analysis

The Summary Dashboard provides a high-level overview of lending performance and portfolio quality.

---

## Business Questions Answered

- What is the total lending volume?
- How much funding has been disbursed?
- How much money has been collected?
- What percentage of loans are performing?
- What percentage of loans are considered risky?

---

## Loan Quality Analysis

The portfolio is segmented into:

### Good Loans

| Metric | Value |
|----------|----------|
| Loan Applications | 33.2K |
| Funded Amount | $370.2M |
| Amount Received | $435.8M |
| Portfolio Share | 86.2% |

---

### Bad Loans

| Metric | Value |
|----------|----------|
| Loan Applications | 5.3K |
| Funded Amount | $65.5M |
| Amount Received | $37.3M |
| Portfolio Share | 13.8% |

---

## Loan Status Analysis

Loan performance categories include:

- Current
- Fully Paid
- Charged Off

### Key Insights

- Over **86% of loans** belong to the performing portfolio.
- Fully paid loans contribute the largest share of collections.
- Charged-off loans represent a manageable risk segment.

---

## Business Value

- Portfolio quality monitoring
- Risk assessment
- Collection performance tracking
- Lending strategy optimization

---

# 🔷 2. Loan Portfolio Overview Analysis

The Overview Dashboard provides detailed portfolio insights across borrower demographics, loan characteristics, and funding trends.

---

## Business Questions Answered

- How has lending volume changed over time?
- Which states receive the most funding?
- Which loan terms dominate the portfolio?
- What loan purposes receive the most approvals?
- Which borrower segments receive the highest funding?

---

## Monthly Lending Trend Analysis

Tracks total funded amount across the year.

### Insights Generated

- Funding growth patterns
- Seasonal lending activity
- Portfolio expansion trends

### Key Insight

Funded loan volume increased consistently throughout the year, reaching approximately **$54M** during the latest reporting month.

---

## Geographic Lending Analysis

The state-level funding map identifies:

- High-performing lending markets
- Regional funding concentration
- Geographic portfolio distribution

### Business Value

- Regional lending strategy
- Market expansion planning
- Geographic risk diversification

---

## Loan Term Analysis

Loan portfolio segmented by term:

- 36 Months
- 60 Months

### Key Insight

Long-term loans account for the majority of funded volume, contributing approximately **63% of total funding**.

---

## Employment Length Analysis

Funding distribution by borrower employment tenure.

### Top Segments

- 10+ Years
- 2 Years
- Less than 1 Year
- 3 Years

### Business Value

- Borrower stability analysis
- Credit profile evaluation
- Risk segmentation

---

## Loan Purpose Analysis

Funding allocation across loan purposes:

- Debt Consolidation
- Credit Card
- Home Improvement
- Small Business
- Major Purchase
- Car Loan
- Wedding Loan

### Key Insight

**Debt Consolidation** represents the largest share of funded loans.

---

## Home Ownership Analysis

Funding segmented by:

- Mortgage
- Rent
- Own

### Insights Generated

- Borrower financial profile analysis
- Housing-based risk segmentation
- Lending concentration monitoring

---

# 🔷 3. Risk & Credit Performance Analysis

The dashboard evaluates credit risk indicators and lending quality.

---

## Metrics Analyzed

### Interest Rate

Measures lending profitability and borrower risk.

| KPI | Value |
|------|--------|
| Avg Interest Rate | 12.05% |

---

### Debt-to-Income Ratio (DTI)

Measures borrower repayment capacity.

| KPI | Value |
|------|--------|
| Avg DTI | 13.33% |

---

## Credit Quality Dimensions

- Loan Grade
- Sub Grade
- Loan Status
- Repayment Performance

### Business Value

- Credit risk monitoring
- Lending policy evaluation
- Portfolio optimization
- Default prevention

---

# 🔷 4. Loan-Level Details Analysis

The Details Dashboard provides transaction-level visibility into every loan application.

This section serves as the operational reporting layer of the solution and enables users to validate aggregated KPIs.

---

## Business Questions Answered

- Which loans were funded?
- What purpose was the loan issued for?
- What borrower grade was assigned?
- What interest rate was charged?
- How much funding was disbursed?
- How much has been collected?

---

## Available Loan Attributes

| Field |
|---------|
| Loan ID |
| Loan Purpose |
| Home Ownership |
| Grade |
| Sub Grade |
| Issue Date |
| Funded Amount |
| Interest Rate |
| Installment Amount |
| Amount Collected |

---

## Interactive Capabilities

Users can:

- Filter loans by grade
- Analyze loan quality
- Investigate borrower segments
- Validate funding calculations
- Review repayment performance
- Export filtered datasets

---

## Business Value

The Details Dashboard supports:

- Portfolio auditing
- Loan investigation
- Credit review
- Collection analysis
- Regulatory reporting

---

# 📈 Key Business Insights

## Portfolio Performance

- Total funded amount exceeded **$435M**.
- Total collections reached **$473M**.
- Strong repayment performance indicates healthy portfolio quality.

---

## Risk Insights

- Good loans account for **86.2%** of the portfolio.
- Bad loans account for **13.8%** of total applications.
- Average DTI remains within manageable lending thresholds.

---

## Lending Insights

- Debt consolidation is the most common loan purpose.
- Long-term loans dominate funded volume.
- Borrowers with longer employment histories receive higher funding amounts.

---

## Geographic Insights

- Lending activity is concentrated in key states.
- Geographic diversification opportunities exist for portfolio expansion.

---

# 🛠️ Technical Implementation

## Data Modeling

A Star Schema model was implemented for scalable and optimized reporting.

### Fact Tables

- Fact Loan Applications
- Fact Funding
- Fact Collections

### Dimension Tables

- Dim Borrower
- Dim Date
- Dim Geography
- Dim Loan Purpose
- Dim Loan Status
- Dim Credit Grade

---

## Power Query Transformations

Data preparation included:

- Data Cleaning
- Missing Value Handling
- Data Type Conversion
- Relationship Creation
- Derived Attributes
- Data Validation

---

## DAX Measures

```DAX
Total Loan Applications

Total Funded Amount

Total Amount Received

Good Loan %

Bad Loan %

Average Interest Rate

Average DTI

MTD Applications

MTD Funded Amount

MTD Amount Received

Funding Growth %

Collection Rate

Funded Amount by Purpose

Funded Amount by State
```

# 🧰 Tools & Technologies

| Tool | Purpose |
|--------|----------|
| Power BI Desktop | Dashboard Development |
| Power Query | Data Transformation |
| DAX | KPI & Measure Development |
| Excel / CSV | Source Data |
| Data Modeling | Star Schema Design |

---

# 📷 Dashboard Screenshots

## Executive Summary Dashboard

<img width="1322" height="740" alt="image" src="https://github.com/user-attachments/assets/8e75c6d2-b31d-4179-865d-0a914be0c1fb" />

---

## Portfolio Overview Dashboard

<img width="1327" height="742" alt="image" src="https://github.com/user-attachments/assets/8c970024-c5b2-4bb4-9fa9-0a61d7a2727d" />

---

## Loan Details Dashboard

<img width="1313" height="737" alt="image" src="https://github.com/user-attachments/assets/11543cb6-f017-4cc1-9f93-fbdc08736ed4" />

```
# 📂 Project Structure

```text
Bank-Loan-Portfolio-Performance-Analytics/
│
├── Dataset/
│   └── Bank_Loan_Data.xlsx
│
├── Dashboard/
│   └── Bank_Loan_Analytics.pbix
│
├── Images/
│   ├── bank-loan-summary.png
│   ├── bank-loan-overview.png
│   └── bank-loan-details.png
│
└── README.md
```

# 📌 Conclusion

The **Bank Loan Portfolio Performance Analytics Dashboard** provides a comprehensive lending analytics solution by combining loan performance monitoring, portfolio risk assessment, borrower segmentation, funding trends, repayment analysis, and transaction-level reporting into a single interactive Power BI experience.

The dashboard enables banking professionals and financial institutions to monitor portfolio health, optimize lending strategies, improve risk management, and make data-driven decisions through actionable financial insights.

### ⭐ Project Summary

> An interactive Power BI dashboard that analyzes loan portfolio performance, lending activity, repayment behavior, borrower risk profiles, and portfolio quality to support data-driven banking and credit management decisions.
