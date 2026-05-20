# Maven Market Business Intelligence Dashboard 📊

An advanced, end-to-end Power BI dashboard built using the **Maven Market** dataset to analyze global retail sales, profit margins, product performances, and store operations across multiple regions (USA, Mexico, and Canada).

---

## 🚀 Project Overview
This project transforms raw transactional, product, and store data into an interactive, insights-driven executive report. It leverages advanced Data Modeling, complex DAX calculations, and fully dynamic **SVG KPI Cards** to provide a seamless dark-themed corporate reporting experience.

### Key Dashboards Included:
1. **Executive Summary:** High-level overview of Revenue ($1.20M), Profits ($715.69K), and Transactions (182.88K) compared against Last Year (LY) and Last Month (LM) targets.
2. **Product Performance:** Analysis of Products Sold, Average Return Rates (with dynamic threshold alerts), Average Retail Prices, and Top Brand performance.
3. **Regional Operations:** Breakdown of total stores (24 stores across 3 countries), average store revenue, and regional sales distribution.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **BI Tool:** Power BI Desktop
* **Data Modeling:** Star Schema (Fact and Dimension table relationships)
* **Data Formatting & Cleaning:** Power Query (ETL)
* **Languages:** DAX (Data Analysis Expressions) & HTML/SVG (for custom UI/UX elements)
* **Design Philosophy:** Modern Dark Mode Theme with dynamic KPI badges

---

## 🧠 Advanced DAX & SVG Engineering
A key highlight of this project is the migration from standard Power BI cards to custom-coded **SVG KPI Cards** to eliminate visual clutter and handle complex alignments.

### Feature 1: Dynamic Revenue KPI (Custom SVG Code)
Constructed a single-measure card displaying Current Value, Target, LY, LM, and an automatic green/red growth indicator:
```dax
-- Example of the Revenue KPI logic built inside the project
Revenue KPI SVG = 
VAR Growth = DIVIDE([Total Revenue] - [Revenue LY], [Revenue LY])
VAR ArrowColor = IF(Growth >= 0, "#22C55E", "#F87171")
RETURN
"data:image/svg+xml;utf8,<svg ...> ... </svg>"
