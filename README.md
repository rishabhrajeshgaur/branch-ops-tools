# branch-ops-tools
#  Excel Credit Assessment & NPA Tracking Tool  
*A complete Excel-based system for Credit Appraisal, EWI Monitoring, NPA Tracking, Provisioning & Audit Readiness.*

##  Overview  
This project is a comprehensive Excel-based Credit Risk & NPA Monitoring tool designed to streamline branch-level credit workflows.  
It consolidates loan-level MIS, borrower financials, Early Warning Indicators (EWI), provisioning rules, ageing buckets, and an audit checklist — all supported by dashboards and automated formulas.

## 📂 Contents of the Project  
**1. Loan Monitoring Module**  
- Loan master sheet (30 sample records)  
- Fields include: Loan_ID, Branch, Customer, Loan Amount, CIBIL, DSCR, LTV, Collateral Cover, Overdue Days, Status  
- Conditional formatting for NPA, Overdue, SMA, Restructured  
- Auto-updating EWI Score & Risk Band  

**2. Borrower Financial Analysis**  
- Borrower master with Business & KYC details  
- Added balance sheet fields:  
  - Current Assets / Liabilities  
  - Inventory  
  - EBIT  
  - Interest Expense  
- Automated ratios (with Excel formulas):  
  - Current Ratio  
  - Quick Ratio  
  - Interest Coverage Ratio  

**3. Credit Scorecard**  
- Weighted scoring model using:  
  - CIBIL Score  
  - DSCR  
  - LTV  
  - Payment Behaviour  
  - Collateral Coverage  
- Normalisation + 0–100 weighted score  
- Heatmap to highlight weak credits  

**4. Early Warning Indicators (EWI)**  
- Numeric EWI scoring based on key stress signals  
- Categorised into Low, Medium, High Risk  
- Dashboard EWI pie chart included  

**5. NPA & Provisioning Automation**  
- Ageing buckets:  
  - 0, 1–30, 31–60, 61–90, 91–180, 180+  
- Pivot-style Ageing Summary sheet  
- Formula-driven provisioning:  
  - Standard → 0%  
  - Substandard → 15%  
  - Doubtful → 25%  
  - SMA → 10%  
  - Closed → 0%  

**6. Dashboard & Visuals**  
- Branch-wise exposure chart  
- EWI risk distribution pie  
- Ageing insights  
- Clean visual formatting & filter-enabled tables  

**7. Audit Checklist**  
- Pre-Audit & Post-Audit compliance items  
- Owner column + status tracking  
- Internal audit readiness made structured  

##  File Structure  
|-- Credit_NPA_Audit_Tool_Enhanced.xlsx  
|-- README.md  
|-- walkthrough_script.txt  
|-- cv_blurb.txt  
|-- .gitignore  

##  How to Use  
1. Download the Excel file.  
2. Replace sample data in Loans and Borrowers sheet with your real data.  
3. Do not change column headers — dashboard updates automatically.  
4. Review EWI scoring & provisioning formulas (editable if required).  
5. Use the Dashboard for portfolio monitoring.  
6. Use the Audit Checklist before internal / concurrent audits.  

## Skills Demonstrated  
- Credit Risk Analysis  
- Early-Warning Indicators  
- Excel Modelling  
- MIS & Portfolio Monitoring  
- NPA classification & provisioning  
- Dashboarding & visual analytics  
- Internal audit & control readiness  

## CV Bullet  
Developed an Excel-based Credit Assessment & NPA Tracking tool that centralised loan monitoring, automated EWI scoring, standardised provisioning, and enabled audit-ready branch MIS.

## License  
Open for personal/portfolio use.

## Contributions  
Fork the repo or suggest improvements.
