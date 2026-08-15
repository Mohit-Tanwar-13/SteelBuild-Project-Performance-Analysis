# 🏗️ SteelBuild — Project Performance & Cost Analysis

### Excel-based construction project cost analysis, budget monitoring and management dashboard

---

## 📌 Project Overview

**SteelBuild** is an end-to-end Excel analytics project designed around a construction project management scenario.

The project transforms project, procurement, expense, equipment, payment, progress and safety data into a structured analytical model and an interactive management dashboard.

The primary objective is to help management identify projects with high cost exposure, monitor budget utilization, understand cost drivers and prioritize projects requiring attention.

---

## 🎯 Business Problem

Managing multiple construction projects requires continuous monitoring of project costs and budgets.

Management needs to answer questions such as:

- Which projects have the highest actual cost?
- Which projects are approaching or exceeding their approved budgets?
- What is driving project expenditure?
- Which projects require immediate investigation?
- How does project health relate to budget utilization?
- Does a high absolute project cost necessarily mean high financial risk?

This project was developed to answer these questions using **Excel-based data analysis, PivotTables, PivotCharts, slicers and dashboard reporting**.

---

## 🎯 Project Objectives

- Analyze project-level Budget vs Actual Cost
- Calculate Budget Variance and Budget Utilization %
- Classify projects based on budget utilization
- Identify major project cost drivers
- Identify the Top 5 projects by Actual Cost
- Analyze Actual Cost by Project Health
- Compare average Budget Utilization across project health categories
- Build an interactive management dashboard
- Convert analysis into actionable management insights

---

## 📊 Dataset

The project contains multiple interconnected datasets representing a construction business environment.

| Data Area | Records |
|---|---:|
| Projects | 150 |
| Clients | 80 |
| Vendors | 180 |
| Employees | 450 |
| Material Purchases | 7,477 |
| Labour Attendance | 8,000 |
| Equipment Usage | 2,500 |
| Daily Expenses | 3,000 |
| Project Progress | 1,200 |
| Client Payments | 700 |
| Safety Incidents | 120 |

The project uses the relevant datasets to create a project-level financial and operational analysis model.

---

## 🧹 Data Preparation & Analysis

The workflow included:

- Data quality checks
- Duplicate and missing-value checks
- Data validation
- Structured Excel Tables
- Calculated columns
- Project-level cost aggregation
- Budget variance analysis
- Budget utilization analysis
- Project health classification
- Cost-driver analysis
- PivotTable analysis
- PivotCharts
- Interactive slicers
- Management dashboard

---

## 🧮 Key Calculations

### Total Actual Cost

`Material Cost + Daily Expenses + Equipment Cost`

### Budget Variance

`Budget - Total Actual Cost`

### Budget Utilization

`Total Actual Cost / Budget × 100`

### Project Health

| Budget Utilization | Project Health |
|---:|---|
| < 80% | Healthy |
| 80% – 100% | Attention |
| > 100% | Critical |

---

## 📈 PivotTable Analysis

Five major analytical views were developed:

### 1. Project Financial Overview

Compares project-level:

**Budget vs Actual Cost**

### 2. Cost Driver Analysis

Analyzes project expenditure across:

- Material Cost
- Daily Expenses
- Equipment Cost

### 3. Top 5 Projects by Actual Cost

Identifies projects with the highest actual expenditure and compares their budget position.

### 4. Actual Cost by Project Health

Analyzes how total actual cost is distributed across:

- Healthy
- Attention
- Critical

### 5. Average Budget Utilization by Health

Compares average budget utilization across project health categories.

---

## 📊 Dashboard

The final interactive dashboard provides an executive-level view of project performance.

### KPIs

| KPI | Value |
|---|---:|
| Total Projects | **150** |
| Total Budget | **₹3,324.00 Cr** |
| Total Actual Cost | **₹791.34 Cr** |
| Overall Budget Utilization | **23.8%** |
| Critical Projects | **2** |
| Attention Projects | **4** |

### Visualizations

- Top 5 Budget vs Actual
- Actual Cost by Project Health
- Budget Utilization by Project Health

### Interactive Filter

A **Project Health slicer** allows users to interactively filter relevant project-level analysis.

---

## 🔍 Key Business Insights

### 🔴 P132 — Immediate Investigation

P132 has approximately **113.1% budget utilization**, meaning actual cost has exceeded its approved budget.

Approximately **97% of its actual cost is Material Cost**, making material expenditure the first area for investigation.

**Recommended action:** Review material pricing, quantities, wastage and the adequacy of the original project estimate.

---

### 🔴 P135 — Budget Overrun

P135 has approximately **102.3% budget utilization** and approximately **97% Material Cost contribution**.

**Recommended action:** Review procurement costs, quantities and project estimation.

---

### 🟠 P099 — Monitor Closely

P099 has approximately **88.1% budget utilization** and is approaching its approved budget.

**Recommended action:** Closely monitor remaining expenditure, particularly material costs.

---

### 📊 Project Health & Budget Pressure

Average budget utilization increases significantly across project health categories:

**Healthy → ~29%**

**Attention → ~88%**

**Critical → ~108%**

This indicates increasing budget pressure as project health deteriorates.

---

### 💡 High Actual Cost ≠ High Financial Risk

Some projects appear among the Top 5 projects by Actual Cost but have relatively low budget utilization because their approved budgets are much larger.

Therefore:

> **Absolute Actual Cost should not be evaluated independently from Budget Utilization and Budget Variance.**

This helps management distinguish between **large projects** and **financially risky projects**.

---

## 💼 Business Recommendations

### 1. Strengthen Material Cost Monitoring

Critical projects should receive detailed reviews of:

- Procurement prices
- Purchase quantities
- Material wastage
- Supplier pricing
- Original project estimates

### 2. Proactively Monitor Attention Projects

Projects approaching 100% budget utilization should be reviewed before they become Critical.

### 3. Evaluate Cost Relative to Project Scale

Large projects naturally have higher absolute expenditure.

Management should evaluate:

**Actual Cost + Budget Variance + Budget Utilization**

rather than Actual Cost alone.

### 4. Prioritize Critical Projects

Projects exceeding their approved budgets should receive immediate management review and corrective action.

---

## 🛠️ Tools & Skills Demonstrated

### Microsoft Excel

- Excel Tables
- Structured References
- Data Cleaning & Validation
- Calculated Columns
- Business Formulas
- PivotTables
- Show Values As
- Top-N / Value Filters
- Slicers
- PivotCharts
- Dashboard Design
- Conditional Analysis
- Management Reporting

### Analytical Skills

- Data Quality Analysis
- Cost Analysis
- Budget Analysis
- Variance Analysis
- Risk Prioritization
- Cost Driver Analysis
- Business Insight Generation
- Management Decision Support

---

## 📁 Project Structure

The repository will contain:

- **Excel/** — Final SteelBuild Excel workbook
- **Dashboard/** — Final dashboard screenshot
- **Documentation/** — Supporting project documentation
- **README.md** — Project documentation

---

## 🏆 Project Outcome

The project converts detailed construction data into a structured management reporting solution that helps decision-makers understand:

**Where money is being spent → Which projects require attention → What is driving the cost → Where management should investigate.**

The final solution demonstrates an end-to-end workflow from **raw business data to analysis, visualization and actionable management insights**.

---

## 👤 Author

**Mohit Tanwar**

**MIS Executive | Aspiring Data Analyst**

**Skills:** Excel | SQL | Power BI | Data Analysis | Dashboarding
