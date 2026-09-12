# 📊 Loan Default Analysis & Risk Dashboard

An end-to-end data analytics project that evaluates loan default behavior, portfolio risk, and key financial drivers. This project covers the full data lifecycle—from raw data cleaning and preprocessing using Python to building a polished, full-canvas Business Intelligence dashboard in Power BI.

---

## 🛠️ Tech Stack & Tools
* **Python (VS Code):** Data cleaning, handling missing values, filtering out blank entries, and exploratory data analysis (EDA).
* **Power BI:** Data modeling, measure calculations (averages, default rates), and interactive visualization design.

---

## 🧹 Data Cleaning & Preprocessing (Python)
Before visualization, the dataset underwent rigorous preparation in Python:
* Filtered out and removed invalid values across critical categorical fields.
* Standardized metrics and converted sum-based aggregates to proper averages (e.g., average interest rates and property values) to prevent skewed portfolio metrics.
* Structured loan-level metrics for relational mapping.

---

## 📈 Power BI Dashboard Features
The final dashboard is designed as an executive-level, full-canvas layout with zero wasted space:
1. **KPI Header Cards:** Total Loan Applications, Overall Status 1 Default Rate, Average Loan Amount, Average Property Value, and Average Interest Rate.
2. **Application & Regional Breakdowns:** Clustered column and bar charts analyzing default rates by application submission type, geographic region, and loan purpose.
3. **Risk Matrix (Heatmap):** A multi-variable matrix intersecting Loan-to-Value (LTV) groups with default rates and interest rates, enhanced with a conditional color gradient.
4. **Portfolio Composition:** Treemaps for occupancy types and donut charts breaking down loan volumes by loan type.
5. **Granular Scatter Plot:** Mapped individual loan amounts against property values using unique loan IDs as details, color-coded by default status.
6. **Interactive Slicers:** Dynamic filtering capabilities by Region and Security Type.

---

## 🚀 Key Insights
* **LTV Risk Thresholds:** Default rates spike significantly in higher risk brackets (such as LTV groups exceeding 100%).
* **Regional & Purpose Variations:** Noticeable variance in default trends across specific loan purposes and regional branches.
