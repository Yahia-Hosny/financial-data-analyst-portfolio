# Yahia Hosny Yahia — Executive Portfolio Case Studies (100% Real Verified Outcomes)
**Role:** Financial Data Analyst & Python Data Automation Specialist | **Email:** Yahiahosny23@gmail.com | **Phone:** +20 115 676 1938 | **LinkedIn:** https://www.linkedin.com/in/yahia-hosny | **GitHub:** https://github.com/yahia-hosny | **Live Portfolio:** https://yahia-hosny.github.io/financial-data-analyst-portfolio/

---
## CS-01: Real-Time 1.5h Aggregator Stock Sync (OneDrive -> MS Graph API -> SFTP)
- **Tech Stack & Grain Proof:** `Python, MS Graph API (MSAL), Power Automate, openpyxl, SFTP (paramiko), smtplib` | `(po_number, sku)` CTE grain pre-aggregation | Control Tie-Out `0.00 Drift`
- **Problem:** Once-daily manual branch stock uploads to InstaShop caused stale catalog availability, manual file handling overhead, and delayed store synchronization.
- **Solution:** Engineered a Power Automate + MS Graph API (MSAL) -> Python (openpyxl) branch-code mapping validator -> paramiko SFTP delivery service with automated OneDrive cleanup, packaged vs. bulk produce validation, and smtplib run/error email digests.
- **Impact:** Cut aggregator stock sync SLA from 24 hours to 1.5 hours (16x faster refresh cycle) while eliminating manual file transfers completely (0.00 manual touches).

## CS-02: D365 F&O Multi-Entity Financial Close, P&L & Delivery P&L Suite
- **Tech Stack & Grain Proof:** `D365 F&O (OData, BYOD, Dataflows), Python, Polars, DuckDB, MS SQL, MySQL` | `(po_number, sku)` CTE grain pre-aggregation | Control Tie-Out `0.00 Drift`
- **Problem:** Consolidating Daily and Monthly P&L, Delivery P&L, General Ledger (GL), Accounts Receivable (AR), and Tax Reports across Microsoft Dynamics 365 F&O, MS SQL, and MySQL required slow, error-prone manual reconciliation.
- **Solution:** Architected repeatable Python (Polars LazyFrame + DuckDB + openpyxl) transformation pipelines extracting directly from Dynamics 365 F&O (OData, BYOD, Dataflows) with automated 0.01-tolerance Control Tie-Out assertions and Dashboard_YYYY-MM-DD / Delivery_Dashboard workbooks.
- **Impact:** Standardized 12+ daily & monthly financial close, cost control, Household Sales, and Promotion/Magazine cycle workflows with 0.00 control drift.

## CS-03: Automated 3-Way Match Reconciliation (PO vs. GRN vs. Invoice) & Waste Audits
- **Tech Stack & Grain Proof:** `DuckDB, Polars, SQL, 3-Way Match Reconciliation, Cost Control, Audit Tie-Out` | `(po_number, sku)` CTE grain pre-aggregation | Control Tie-Out `0.00 Drift`
- **Problem:** Direct many-to-many joins between Purchase Orders, Goods Receipt Notes (GRN), and Vendor Invoices caused Cartesian fan-out, masking unreceipted billing, quantity/price variances, and consignment settlement gaps.
- **Solution:** Implemented strict DuckDB & Polars CTE grain pre-aggregation at (po_number, sku) before joining Receipts vs. Invoices alongside automated Daily Waste Report, Lost Sales Digest, Daily Stock Control, and Consignment Vendor Settlement audit checks.
- **Impact:** Eliminated relational fan-out errors during procurement reconciliation and enforced zero-leakage tie-out audit readiness prior to AP payment release.

## CS-04: Power BI Star-Schema Restructuring & DAX / SQL Performance Optimization
- **Tech Stack & Grain Proof:** `Power BI, DAX, Star-Schema Data Modeling, MS SQL, MySQL, Power Query` | `(po_number, sku)` CTE grain pre-aggregation | Control Tie-Out `0.00 Drift`
- **Problem:** Legacy company-wide Power BI dashboards and complex SQL views suffered from slow refresh/rendering times across Finance, Marketing, and Operations KPI tracking.
- **Solution:** Redesigned relational star-schema data models, refactored bi-directional relationships, tuned MS SQL / MySQL queries, and rewrote heavy DAX measures using Microsoft Press / LinkedIn Learning best practices.
- **Impact:** Improved Power BI and SQL report execution & loading speeds by 60% across executive Finance, Marketing, and Operations KPI dashboards.

## CS-05: Sales Revenue Time-Series Forecasting & End-to-End Retail Python POS Systems
- **Tech Stack & Grain Proof:** `Python, Pandas, Scikit-learn, NumPy, POS Systems, Inventory Automation` | `(po_number, sku)` CTE grain pre-aggregation | Control Tie-Out `0.00 Drift`
- **Problem:** Retail inventory budgeting needed reliable forward-looking demand signals, while small/medium retail shops needed lightweight end-to-end POS and stock control software.
- **Solution:** Built a Python (Pandas, Scikit-learn, NumPy) time-series revenue forecasting model (2025) and previously engineered standalone Python POS systems (2023–2025) automating sales ledger capture, inventory tracking, and receipt printing.
- **Impact:** Delivered 95% time-series revenue forecasting accuracy for inventory & budget allocation and deployed production-ready POS tools for retail operations.
