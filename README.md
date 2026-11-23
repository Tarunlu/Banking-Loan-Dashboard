# Banking-Loan-Dashboard

# 🏦 Bank Loan Analysis Dashboard (Power BI & SQL)

An end-to-end **Bank Loan Portfolio & Risk Analysis** project built in **Power BI** (validated with **SQL**) to monitor lending performance, track repayments, and assess portfolio health across **38,576 loan applications** ($435.76M funded | $473.07M received).
---
## 🎯 Project Objectives
- Track core lending KPIs (**Total Applications, Funded Amount, Amount Received, Average Interest Rate, and Average DTI**) with **MTD** and **MoM** comparisons.
- Segment portfolio risk into **Good Loans** (*Fully Paid* & *Current* — 86.18%) vs. **Bad Loans** (*Charged Off* — 13.82%).
- Uncover borrowing trends across time, geography, loan term, employment length, loan purpose
---
## 📊 Dashboard Architecture (3 Pages)

### 1. Summary Dashboard
- **Primary KPI Cards:** Dynamic MTD & MoM metrics for applications, funding, collections, interest rate (12.05% avg), and DTI (13.33% avg).
- **Good vs Bad Loan Breakdown:** Application counts, funded amounts, received amounts, and percentage share.
- **Loan Status Grid:** Granular breakdown by *Fully Paid*, *Current*, and *Charged Off* statuses.
### 2. Overview Dashboard
- **Dynamic Measure Slicer:** Switch all visuals seamlessly between *Total Applications*, *Total Funded Amount*, and *Total Amount Received*.
- **Visual Breakdowns:** Monthly Trends (Area Chart), Regional Analysis by State (Filled Map), Loan Term (Donut Chart), Employee Length (Bar Chart), Loan Purpose (Bar Chart), and Home Ownership (Tree Map).

### 3. Details Dashboard
- **Interactive Data Grid:** Loan-level table displaying Loan ID, Purpose, Home Ownership, Grade/Sub-Grade, Issue Date, Funded Amount, Interest Rate, Installment, and Amount Received for granular auditing.
---
## 🛠️ Tech Stack & Key Skills
- **Power BI:** Power Query (ETL & data cleaning), Data Modeling (Date Table), **DAX** (Time Intelligence `TOTALMTD`, `PREVIOUSMONTH`, dynamic titles, and field parameters), Page Navigation, and Interactive Slicers (*State, Grade, Purpose*).
- **SQL:** Querying and validating all dashboard KPIs and aggregations against raw data.
- **Dataset:** `financial_loan.csv` (38,576 rows × 24 columns).

---

## 📁 Repository Structure
- `Bank_Loan_Analysis.pbix` — Interactive Power BI dashboard file
- `financial_loan.csv` — Raw lending dataset
- `Bank_Loan_Queries.sql` — SQL validation queries
- `Screenshots/` — Preview images of Summary, Overview, and Details views
