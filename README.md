# Credit Portfolio Health & Early Warning Dashboard

This repository demonstrates the analytical logic behind a **credit portfolio health and early warning dashboard**, designed to support proactive credit risk monitoring and portfolio oversight.

The project focuses on **delinquency behavior, roll-rate migration, risk tier movement, and early warning indicators**, using synthetic and anonymized data to reflect real-world credit risk workflows.

---

## 📊 Key Analytics Covered

### 1. Delinquency & Roll-Rate Trends
- Distribution of accounts and balances across delinquency buckets (Current, 30, 60, 90+ DPD)
- Month-over-month roll-rate matrices showing flow between delinquency states
- Identification of structural deterioration versus short-term volatility

### 2. Risk Tier Migration
- Tracking customer movement across Low / Medium / High risk tiers
- Migration matrices highlighting upward and downward risk shifts
- Concentration analysis by risk segment

### 3. Early Warning Indicators (EWIs)
Forward-looking signals designed to surface risk **before delinquency materializes**, including:
- Sudden utilization spikes
- Rapid balance growth
- Repeated minor payment delays while still “current”
- Dispute and exception frequency spikes

Accounts are flagged and scored to support prioritization and early intervention.

### 4. Portfolio-Level Risk Visibility
- Executive-ready summary metrics by risk tier
- Account-based and balance-based delinquency rates
- Inputs designed for dashboards, risk reviews, and committee reporting

---

## 🛠️ Tech Stack & Design Approach

- **SQL (primary):** Portfolio aggregation, roll-rate logic, migration analysis, and EWI flagging  
- **Python (optional layer):** Orchestration, automation, and downstream reporting  
- **Visualization:** BI dashboards (Power BI / Tableau / Looker compatible)  
- **Data:** Fully synthetic and anonymized  

The design prioritizes **interpretability, auditability, and governance readiness**, rather than black-box modeling.

---

## 📁 Repository Structure

