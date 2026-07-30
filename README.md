# Canadian Banking Excel Data Quality, Transformation & Statistical Analytics Project

## Project Overview

This is an end-to-end Excel portfolio project built for Canadian finance analyst, FP&A analyst, data analyst, reporting analyst, and BI analyst roles.

The project uses a synthetic Canadian banking dataset to demonstrate how raw financial data can be profiled, cleaned, prepared, validated, transformed, analyzed, and presented inside Microsoft Excel.

This public repository includes project documentation and screenshots only. The full Excel workbook is not publicly uploaded to protect the integrity of the project and prevent direct reuse.

---

## Business Scenario

A Canadian banking analytics team needs reliable customer, account, transaction, loan, credit card, campaign, and branch performance data before producing executive reports.

The goal of this project is to turn messy raw banking data into clean, analysis-ready tables and management-ready insights using Excel.

---

## Tools Used

- Microsoft Excel
- Power Query
- Excel Tables
- Structured references
- PivotTables
- PivotCharts
- Slicers
- Analysis ToolPak
- Excel formulas
- Data validation
- Conditional formatting
- Dashboard design

---

## Dataset

This project uses synthetic and fictional Canadian banking data created for portfolio demonstration purposes.

Main data areas include:

- Customers
- Accounts
- Transactions
- Loans
- Credit cards
- Campaign responses
- Branch monthly performance
- Product lookup tables
- Branch lookup tables
- Province lookup tables

No real customer, bank, or personal financial data is included.

---

## Project Workflow

| Stage | Description |
|---|---|
| Business Framing | Defined project scope, business scenario, target roles, and final deliverables |
| Source Inventory | Documented source tables, table grain, primary keys, and business use |
| Raw Data Profiling | Identified duplicate IDs, missing values, invalid dates, relationship issues, and financial exceptions |
| Power Query Cleaning | Cleaned and standardized raw data using repeatable Power Query transformations |
| Data Quality Validation | Created validation flags for IDs, dates, emails, postal codes, lookup relationships, and financial logic |
| Reconciliation Checks | Compared raw vs cleaned row counts, expected exclusions, financial totals, and controlled exceptions |
| Feature Engineering | Created business features for customers, accounts, transactions, loans, credit cards, campaigns, and branches |
| Pivot Analysis | Built summary analysis across customer, product, transaction, loan, campaign, and branch dimensions |
| Statistical Analysis | Applied selected Excel Analysis ToolPak methods for finance-related interpretation |
| Dashboarding | Designed an executive finance KPI dashboard |
| Executive Reporting | Created a final business summary with insights and recommendations |

---

## Workbook Structure

The Excel workbook was organized into a professional analytics workflow:

| Workbook Area | Purpose |
|---|---|
| README / Project Scope | Explains project objective, business case, and review path |
| Data Dictionary | Documents fields, definitions, and business meaning |
| Quality Rules | Defines validation and exception logic |
| Source Inventory | Lists raw and lookup tables with grain and key structure |
| Raw Profiling | Summarizes issues found before cleaning |
| Power Query Cleaning Log | Documents each cleaning and transformation step |
| Cleaned Tables | Stores cleaned and analysis-ready outputs |
| Reconciliation Checks | Validates row counts, financial totals, and controlled exceptions |
| Feature Engineering | Creates business-ready analytical variables |
| Pivot Analysis | Summarizes key business questions |
| ToolPak Statistical Analysis | Applies Excel statistical analysis methods |
| Finance KPI Dashboard | Presents management-level metrics and visuals |
| Executive Summary | Communicates final insights and recommendations |
| Skill Coverage Matrix | Maps workbook outputs to Excel and analyst skills |

---

## Key Analysis Areas

### 1. Data Cleaning and Preparation

The project profiles and cleans raw banking data by handling:

- Duplicate customer and transaction records
- Missing values
- Invalid emails
- Invalid postal codes
- Inconsistent province values
- Invalid or inconsistent dates
- Orphan account, customer, branch, and product relationships
- Negative or unusual financial values
- Controlled data quality exceptions

### 2. Power Query Transformation

Power Query was used to preserve raw data while creating repeatable and refreshable cleaning steps.

Examples of transformations include:

- Trimming and cleaning text fields
- Standardizing case formatting
- Converting data types
- Standardizing province values
- Validating lookup relationships
- Removing duplicate master records
- Creating cleaned reporting-ready tables
- Flagging records requiring review

### 3. Data Quality and Reconciliation

The workbook includes reconciliation controls to prove that cleaned outputs remain reliable after transformation.

Controls include:

- Raw vs cleaned row counts
- Duplicate removal checks
- Expected transaction exclusions
- Controlled exception tracking
- Financial total checks
- Failed control count review

This demonstrates a finance-focused approach to data accuracy, auditability, and reporting control.

### 4. Feature Engineering

The project creates analytical features across multiple banking subject areas.

Feature examples include:

- Customer age and tenure
- Income bands
- Credit score bands
- Account activity indicators
- Monthly transaction summaries
- Loan risk indicators
- Credit card utilization bands
- Campaign uplift metrics
- Branch revenue variance and performance metrics

### 5. Pivot Analysis

PivotTables were used to answer practical finance and banking questions, including:

- Customer distribution by province and segment
- Account balances by product and province
- Transaction trends by month and channel
- Loan exposure by status and risk category
- Credit card utilization by customer group
- Campaign response and uplift performance
- Branch actual vs target revenue performance

### 6. Statistical Analysis

Excel Analysis ToolPak was used for selected business-relevant statistical analysis.

Completed methods include:

- Descriptive Statistics
- Histogram
- Correlation
- Regression
- t-Test
- ANOVA Single Factor
- Moving Average
- Exponential Smoothing
- Rank and Percentile

The purpose of this section is not only to run statistical tools, but to interpret the outputs in a finance and banking analytics context.

### 7. Dashboard and Executive Reporting

The final workbook includes a finance KPI dashboard and executive summary designed for management review.

Dashboard areas include:

- Total customers
- Total accounts
- Total current balance
- Total transaction amount
- Total loan balance
- Total credit card balance
- Campaign response rate
- Branch revenue variance
- Controlled data quality exceptions

---

## Screenshots

The full workbook is not publicly uploaded. Screenshots are provided to demonstrate the project output.

| Screenshot | Description |
|---|---|
| `screenshots/dashboard.png` | Executive finance KPI dashboard |
| `screenshots/executive_summary.png` | Final business insights and recommendations |
| `screenshots/reconciliation_checks.png` | Data reconciliation and control checks |
| `screenshots/toolpak_statistical_analysis.png` | Excel Analysis ToolPak statistical analysis |
| `screenshots/feature_engineering.png` | Feature engineering summary |
| `screenshots/pivot_analysis.png` | PivotTable business analysis |

---

## Skills Demonstrated

| Skill Area | Examples |
|---|---|
| Excel Data Cleaning | Text cleaning, duplicate handling, missing-value treatment, validation flags |
| Power Query | ETL-style transformation, type conversion, lookup validation, refreshable workflows |
| Data Quality | Exception flags, valid/invalid logic, controlled review categories |
| Reconciliation | Raw vs clean checks, control totals, expected adjustments, failed-control review |
| Feature Engineering | Customer, account, transaction, loan, credit card, campaign, and branch features |
| Financial Analysis | Balances, revenue, loan exposure, utilization, variance analysis |
| Statistical Analysis | Regression, correlation, t-test, ANOVA, forecasting, ranking |
| Reporting | PivotTables, PivotCharts, KPI cards, dashboard design, executive reporting |
| Documentation | README, source inventory, cleaning log, reconciliation notes, skill matrix |

---

## Recommended Review Path

1. Review the project overview and business scenario.
2. Review the screenshots of the dashboard and executive summary.
3. Review the reconciliation checks to understand data control quality.
4. Review the feature engineering and PivotTable analysis screenshots.
5. Review the ToolPak statistical analysis screenshot.
6. Review the skills demonstrated section to understand the Excel and analyst capabilities covered.

---

## Workbook Availability

The full Excel workbook is not publicly uploaded to protect the integrity of the project and prevent direct reuse.

Screenshots and documentation are provided in this repository. The workbook can be shared upon request during recruiter, hiring manager, or interview discussions.

---

## Repository Contents

| Item | Description |
|---|---|
| `README.md` | Project documentation |
| `screenshots/` | Screenshots of the Excel workbook outputs |

---

## Notes

This project is a portfolio demonstration using synthetic and fictional data. It is not affiliated with any real Canadian bank, financial institution, customer, or employer.
