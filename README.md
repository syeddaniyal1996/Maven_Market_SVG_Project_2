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

## Page 1: Executive Summary
<img width="1455" height="820" alt="01" src="https://github.com/user-attachments/assets/85fa7a34-552f-4d5d-863e-2ee8b5e06ef0" />

## Page 2: Product Performance
<img width="1456" height="818" alt="02" src="https://github.com/user-attachments/assets/86ca6237-9e4c-48ed-93d2-d86b065357a0" />

## Page 3: Regional Analysis
<img width="1456" height="819" alt="03" src="https://github.com/user-attachments/assets/1b89258b-50a9-4669-adcc-8deadbcdc49a" />

## 📈 Business Insights Extracted
* # Target Achievement: Total Revenue successfully hit $1.20M, achieving a massive +112.18% growth vs LY, beating the internal target of $59.81K.

* # Return Rate Control: The overall Return Rate was kept low at 0.85% (well below the critical 1.5% company threshold).

* # Top Performer: USA emerged as the Top Region, contributing 61.9% of the total revenue share, with Portland and Tacoma stores leading in operational excellence.

## 📂 Dataset Structure
The dataset contains the following relational tables structured in a Star Schema:

Fact_Sales (Sales transaction logs)

Fact_Returns (Product return details)

Dim_Products (Product specifications and brand listings)

Dim_Stores (Store locations, country, and regional details)

Dim_Calendar (Time intelligence setup)

## 🎨 UI/UX Design System
Background: Dark Slate #1E293B (Tailwind-inspired CSS palette)

Typography: Clean, uniform Arial fonts with optimized vertical hierarchies

Accents: Distinct color coding for specific metrics (Orange for Revenue, Blue for Stores, Purple for Transactions, Coral for Returns)
