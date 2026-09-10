# ☕ Coffee Shop Sales & Revenue Performance Dashboard

An end-to-end retail sales analytics project analyzing 149,000+ transactional records across three retail branches. This project uncovers peak operational hours, customer purchasing behavior, and revenue drivers to assist store managers in inventory planning and staff optimization.

---

## 📊 Executive Dashboard Preview

![Coffee Shop Sales Dashboard](Project_Screenshot.png)

---

## 🎯 Business Objectives
The primary goal of this project is to analyze retail sales records to deliver actionable operational insights:
- **Peak Hour & Staffing Analysis:** Identify footfall surges by hour of day and day of week to streamline barista scheduling.
- **Location Benchmarking:** Compare transaction volumes and revenue contributions across retail branches (Astoria, Hell's Kitchen, and Lower Manhattan).
- **Basket & Category Analysis:** Evaluate customer ticket size (Average Order Value) and determine high-margin product drivers (Coffee, Tea, Bakery).

---

## 📈 Key Performance Indicators (KPIs)

| Metric | Value |
| :--- | :--- |
| **Total Revenue** | **$698,812.33** |
| **Total Transactions (Footfall)** | **149,116** |
| **Total Items Sold** | **214,470 units** |
| **Average Bill per Person (AOV)** | **$4.69** |
| **Average Units per Order** | **1.44** |
| **Date Range Covered** | **Jan 1, 2023 – Jun 30, 2023** |

---

## 💡 Key Business Insights

- **Morning Demand Spike (8:00 AM – 10:00 AM):** Over **51%** of daily order volume occurs before 11:00 AM, with peak order quantities recorded between **8:00 AM and 10:00 AM (25,000+ units/hr)**. Operations should schedule maximum barista staffing during this 3-hour window.
- **Even Branch Distribution:** Revenue is distributed evenly across all three store branches, with **Hell's Kitchen leading at $236,511.17 (50,735 orders)**, closely followed by **Astoria at $232,243.91 (50,599 orders)** and **Lower Manhattan at $230,057.25 (47,782 orders)**.
- **Product Category Dominance:**
  - **Coffee (38.6%)** and **Tea (28.1%)** account for **~67%** of total revenue.
  - **Bakery items** contribute **11.8%** of sales, presenting a significant opportunity for morning combo bundles (e.g., Coffee + Pastry pairings) to increase Average Order Value above $4.69.
- **Top Revenue Generators:**
  1. *Barista Espresso* – $91,406.20
  2. *Brewed Chai Tea* – $77,081.95
  3. *Hot Chocolate* – $72,416.00
  4. *Gourmet Brewed Coffee* – $70,034.60
  5. *Brewed Black Tea* – $47,932.00

---

## 🛠️ Tools & Techniques Used

- **Microsoft Excel / Data Modeling:** Cleaned and structured 149K+ rows of raw POS transactions.
- **Calculated Columns:** Extracted time components (`Hour`, `Day Name`, `Month Name`, `Day of Week`) to model operational time-series trends.
- **Pivot Tables & Summary Views:** Aggregated multi-variable metrics across categories, branches, and hourly bins.
- **Interactive Dashboard:** Designed dynamic KPI metric cards, comparative bar charts, category donut/pie distributions, and interactive slicers for instant slicing by **Month** and **Day of Week**.

---

## 📂 Repository Structure

```text
├── coffee shop sales.xlsx              # Complete Excel workbook with Raw Data, Pivot Tables & Dashboard
├── Coffee Shop Sales Analysis.pdf      # Project requirements and analytical scope
├── Project_Screenshot.png              # High-resolution dashboard view
└── README.md                           # Detailed documentation and findings
