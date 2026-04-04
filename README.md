# 🏥 Healthcare Claims Data Analysis | Advanced Excel Dashboard — 2024

> **Milestone 1 | Skillryt Data Analytics Program | KGiSL MicroCollege**

---

## 📌 Project Overview

An end-to-end Healthcare Revenue Cycle Claims Analysis built using Microsoft Excel. This project covers data cleaning, KPI calculations, PivotTable analysis, scenario modeling, macro automation, and interactive dashboard creation across 10,000 healthcare claims records.

---

## 🎯 Business Objective

- Analyze claim volumes, denial rates, and payment trends
- Identify revenue leakage through adjustment analysis
- Compare performance across insurance providers and types
- Simulate denial rate scenarios for financial planning

---

## 📊 Dashboard Preview

![Dashboard](Dashboard/dashboard.png)

---

## 🔢 Key Metrics

| Metric | Value |
|--------|-------|
| Total Claims | 10,000 |
| Total Paid Amount | $14,78,824.17 |
| Denial Rate | 30.01% |
| Top Insurance Provider | Cigna (2,932 claims) |
| Highest Paid Type | PPO ($0.9M) |

---

## 🧹 Data Cleaning — Power Query

| Step | Action |
|------|--------|
| Remove Duplicates | Duplicate claim records removed |
| Missing Values | Critical nulls reviewed; adj codes → "Not Specified" |
| Date Standardization | DOS converted to consistent date format |
| Financial Validation | Paid ≤ Allowed ≤ Charge verified |
| Column Renaming | All columns renamed for clarity |
| Data Types | Monetary, date, and code fields standardized |

---

## 📐 Excel Features Used

| Feature | Purpose |
|---------|---------|
| Power Query | Data import, cleaning, transformation |
| Power Pivot | Data model — Cleaned_data + Insurance_Master |
| PivotTables | 5 pivot sheets — Insurance, Volume, Trend, Financials, Denial |
| PivotCharts | Bar, Line, Column, Combo charts |
| Dashboard | Interactive — KPI cards, slicers, timeline |
| What-If Analysis | Denial rate impact simulation |
| Goal Seek | Target paid amount calculation |
| Scenario Manager | Low / Moderate / High denial scenarios |
| Macros (VBA) | `Reset_All_Filters_Final` — auto refresh + slicer reset |
| Formulas | SUM, COUNT, COUNTIF, IF, IFERROR, VLOOKUP |

---

## 💡 Key Insights

1. **PPO dominates** — highest paid amount at $0.9M among insurance types
2. **30.01% denial rate** is critically high — major revenue leakage
3. **Cigna leads** claim volume at 2,932 claims — highest among providers
4. **February dip** — lowest monthly claim volume at 495
5. **Adjustments** form a major portion of revenue gap between charged and paid

---

## ✅ Recommendations

| Priority | Action |
|----------|--------|
| 🔴 HIGH | Reduce denial rate from 30% → below 15% through claims audit |
| 🔴 HIGH | Focus on Cigna — highest volume, optimize processing |
| 🟡 MED | Investigate February volume drop — staffing or seasonal issue |
| 🟡 MED | Renegotiate HMO contracts — lowest paid amount |
| 🟢 LOW | Automate monthly reporting using existing Macro framework |

---

## 📂 Repository Structure
```
Healthcare-Claims-Data-Analysis/
│
├── 📊 Dashboard/
│   └── dashboard.png
│
├── 📁 Workbook/
│   └── DA_Healthcare_Revenue_Cycle_Claims_Dashboard.xlsm
│
├── 📄 Documentation/
│   └── DA_Healthcare_Claims_Analysis_Documentation.pdf
│
└── README.md
```

---

## 🛠️ Tools Used

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![VBA](https://img.shields.io/badge/VBA%20Macros-867DB1?style=for-the-badge&logo=microsoft&logoColor=white)

---

## 👤 Author

**Anthony Raj**
Data Analytics Intern | Skillryt × KGiSL MicroCollege

[![GitHub](https://img.shields.io/badge/GitHub-anthony--raj--analytics-181717?style=flat&logo=github)](https://github.com/anthony-raj-analytics)
