# 📞 Telecom Customer Churn Analysis

**Strategic Excel dashboard analyzing 7,043 customers across 21 service features**  
**Business Impact:** Identified $137K monthly revenue loss | 26.54% churn rate

[![Excel](https://img.shields.io/badge/Excel-Power_Pivot_&_DAX-217346?logo=microsoft-excel)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Dataset](https://img.shields.io/badge/Dataset-IBM_Telco-0052CC)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## 🎯 Project Context

**Business Scenario:** A telecommunications provider is hemorrhaging $137K in monthly recurring revenue through customer churn. As the analyst tasked with finding root causes, I needed to deliver actionable insights quickly to executives who don't have access to BI tools.

**Tool Selection Rationale:**  
Built in **Excel** (not SQL/Python) to enable:
- Immediate distribution to non-technical stakeholders
- Editable, drill-down capabilities without BI license dependencies  
- Rapid iteration with business teams during discovery phase

*For production-scale analysis with larger datasets, see my [Supply Chain SQL project](https://github.com/Saleh-Hossam/Supply-Chain-Root-Cause).*

---

## 📊 Dashboard Preview

### Executive Dashboard (High-Level Metrics)
![Executive Dashboard](assets/Exective_telecom.gif)
*Focus: Financial impact, segment performance, strategic KPIs*

### Operational Dashboard (Diagnostic Deep-Dive)
![Operational Dashboard](assets/Operation_telecom_.gif)
*Focus: Granular filters, cohort analysis, churn drivers by dimension*

---

## 🔍 The Analysis Process

### 1. Problem Definition
**Initial Hypothesis:** Late-stage customers (tenure >5 years) are churning due to better competitor offers.

**Reality Check:** Data revealed the opposite—47% of churned customers had <1 year tenure, indicating an **on
