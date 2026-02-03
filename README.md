# 📞 Telecom Customer Churn Analysis

**Excel-based churn analysis dashboard identifying $137K+ in monthly revenue loss**

A comprehensive customer churn analysis for a telecommunications company, featuring dual dashboards (Executive & Operational) built with Excel pivot tables, DAX measures, and interactive visualizations. The analysis uncovers key churn drivers across 7,043 customers and provides actionable insights for retention strategies.

---

## 📊 Project Overview

**Business Problem:**  
A telecom company is experiencing significant customer churn (26.54%), resulting in substantial monthly recurring revenue loss. The company needs to identify which customer segments are churning and why.

**Solution:**  
Built two comprehensive Excel dashboards analyzing customer behavior patterns, contract types, service usage, and demographics to pinpoint high-risk segments and quantify financial impact.

---

## 🎯 Key Findings

### Financial Impact
- **$137,087** in monthly recurring revenue lost due to churn
- **$118,803** of losses attributed to Month-to-Month contracts alone
- **$107,326** in losses from Fiber Optic service customers
- **1,869 customers** churned (26.54% overall churn rate)

### High-Risk Segments Identified
1. **Contract Type:** Month-to-Month contracts lose **$119K/month** (89% of total churn revenue)
2. **Internet Service:** Fiber Optic customers churn at **40.72%** vs 18.58% for DSL
3. **Tenure:** **47% churn rate** for customers with less than 1 year
4. **Dependents:** Customers without dependents churn at **33%** vs only **7%** with dependents
5. **Payment Method:** Mailed Check users show **37% churn** vs 14% for Credit Card users

### Churn Drivers (by category)
- **Competition:** 45% of churned customers (highest driver)
- **Dissatisfaction:** 17.2% of churned customers
- **Attitude:** 16.8% of churned customers
- **Price:** 11.3% of churned customers

---

## 🛠️ Tools & Techniques

**Excel Features Used:**
- Pivot Tables (31 pivot tables for multi-dimensional analysis)
- Pivot Charts (combo charts, bar charts, column charts)
- Slicers (interactive filtering by Age Group, Dependents, Payment Method)
- Conditional Formatting (heat maps for quick pattern recognition)
- DAX Measures (calculated fields for churn rate, revenue loss)
- Data Modeling (relationships between customer, service, and billing tables)

**Analytical Techniques:**
- Customer Segmentation (by demographics, contract, service type)
- Churn Rate Analysis (by multiple dimensions)
- Revenue Impact Quantification
- Cohort Analysis (tenure-based grouping)
- Root Cause Analysis (churn category breakdown)

---

## 📸 Dashboard Preview

### Executive Dashboard
High-level KPIs and strategic insights for leadership decision-making.

![Executive Dashboard](assets/Exective_telecom.gif)

**Key Sections:**
- Overall churn metrics (Total Customers, Churn Rate, Revenue Lost)
- Contract Type analysis by revenue impact
- Internet Service churn rates
- Geographic distribution (Top Cities)
- Offer performance analysis
- Tenure-based churn patterns

---

### Operational Dashboard
Detailed breakdowns for operational teams to implement targeted retention strategies.

![Operational Dashboard](assets/Operation_telecom_.gif)

**Key Sections:**
- Service-level revenue loss (Fiber Optic, Month-to-Month)
- Contract × Tenure cross-tabulation
- Internet Type × Contract Type matrix
- Payment Method churn analysis
- Dependents impact on retention
- Churn category breakdown (Competition, Dissatisfaction, etc.)
- Online Security & Device Protection churn correlation

---

## 💡 Business Recommendations

Based on the analysis, here are data-driven recommendations:

1. **Contract Strategy:**
   - Incentivize Month-to-Month customers to convert to annual contracts
   - Offer discounts or loyalty rewards for 1-year/2-year commitments
   - **Potential Impact:** Reducing Month-to-Month churn by 20% = ~$24K/month saved

2. **Service Quality:**
   - Investigate Fiber Optic service quality issues (40.72% churn is critically high)
   - Consider competitive benchmarking on Fiber Optic pricing/performance
   - Focus retention efforts on customers in their first year of service

3. **Payment Experience:**
   - Encourage migration from Mailed Check (37% churn) to Credit Card (14% churn)
   - Offer autopay incentives or billing discounts for electronic payments
   - Improve billing communication for check-based customers

4. **Family Plans:**
   - Target single customers (33% churn) with family plan promotions
   - Customers with dependents show 5x better retention
   - Create bundled family packages to increase household stickiness

5. **Competitive Response:**
   - 45% of churn is competition-driven; requires market positioning review
   - Develop win-back campaigns targeting recently churned customers
   - Monitor competitor offers in high-churn cities (San Diego, Los Angeles)

---

## 📁 Repository Contents

```
Telecom-Churn-Analysis/
├── README.md                          # Project documentation
├── Telecom_Churn_Project_FINAL.xlsx   # Excel workbook with dashboards
└── assets/
    ├── Exective_telecom.gif           # Executive dashboard demo
    └── Operation_telecom_.gif         # Operational dashboard demo
```

---

## 🎓 Skills Demonstrated

- **Excel Advanced Features:** Pivot Tables, Pivot Charts, Slicers, DAX
- **Data Analysis:** Customer segmentation, churn analysis, cohort analysis
- **Business Intelligence:** Multi-dimensional analysis, KPI design
- **Data Visualization:** Dashboard design, chart selection, color coding
- **Financial Analysis:** Revenue impact quantification, loss attribution
- **Stakeholder Communication:** Executive vs operational reporting levels

---

## 📈 Dataset Information

**Data Source:** Telecom customer database (simulated dataset)  
**Time Period:** Analysis reflects current customer base snapshot  
**Sample Size:** 7,043 total customers analyzed  
**Key Variables:**
- Customer Demographics (Age, Dependents, City)
- Contract Details (Type, Tenure, Payment Method)
- Service Usage (Internet Type, Online Security, Device Protection)
- Billing Information (Monthly Charges, Total Revenue)
- Churn Status & Category

---

## 🔗 Connect With Me

If you found this analysis interesting or have questions about the methodology:

- **LinkedIn:** [linkedin.com/in/saleh-hossam](https://linkedin.com/in/saleh-hossam)
- **Portfolio:** [saleh-hossam.github.io](https://saleh-hossam.github.io)
- **Email:** salehhossam611@gmail.com

---

## 📌 Project Context

This project demonstrates my ability to build executive-ready dashboards that combine technical Excel proficiency with business acumen. The dual-dashboard approach shows understanding of different stakeholder needs: executives need high-level strategic insights, while operational teams need granular, actionable data.

The analysis goes beyond simple reporting by quantifying financial impact, identifying root causes, and providing specific recommendations based on the data patterns discovered.

---

*Built with Excel • Analyzed with Pivot Tables • Designed for Impact*
