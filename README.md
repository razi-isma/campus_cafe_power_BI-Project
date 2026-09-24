![Dashboard Overview](Screenshot%202026-09-24%20102408.png)

# 📊 Campus Cafe Sales & Profitability Analysis (Power BI)

## 📌 Executive Summary
This project analyzes sales performance, product profitability, and transaction patterns for a campus cafe network. The primary objective was to investigate a sudden dip in top-line revenue and identify actionable, data-driven strategies to improve profitability and average order value (AOV).

---

## 💡 Key Business Insights
* **Revenue vs. Profitability:** Although April experienced a slight revenue drop ($13K down to $12K), net profit grew to $5.67K and margins expanded to 46.24% due to strict cost control.
* **Category Efficiency:** High-margin **Drinks** and **Snacks** consistently outperformed **Meals** in profit margin yield.
* **Peak Time Opportunities:** Sales volume heavily concentrated in afternoon and evening time slots, leaving morning hours as a key growth opportunity.

---

## 🎯 Business Recommendations
1. **Morning Combo Strategy:** Launch morning "Kick-Start" bundles (specialty coffee + high-margin snack) to drive off-peak traffic.
2. **Margin Optimization:** Cross-sell high-margin drinks alongside meals to lift basket profitability.
3. **Campus Performance Balancing:** Replicate successful marketing from top-performing locations (North Campus) across other branches.

---

## 🛠️ Technical Implementation & Power BI Skills
* **Data Modeling:** Modeled a Star Schema featuring a custom Date table (`Datetable`) connected via a 1-to-Many (`1:*`) relationship.
* **DAX Time Intelligence:** Created dynamic measures for MoM Growth %, Net Profit, Profit Margin, and previous month metrics (`DIVIDE`, `PREVIOUSMONTH`).
* **Dashboard Design:** Implemented dynamic date slicers, interactive KPI cards, and cross-filtering across campuses, categories, and payment types.

---

## 📂 Repository Structure
* `campus_cafe_project power Bi.pbix`: The complete interactive Power BI report.
* `README.md`: Project documentation and executive summary.
