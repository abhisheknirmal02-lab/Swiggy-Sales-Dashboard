
# 🛵 Swiggy Sales Analytics — Excel Dashboard

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Pivot Tables](https://img.shields.io/badge/Pivot%20Tables-Data%20Analysis-orange)
![Domain](https://img.shields.io/badge/Domain-Food%20Tech-red)

An end-to-end **food delivery sales analytics dashboard** built entirely in Microsoft Excel, modelled on Swiggy's order data across 28 Indian states. The dashboard tracks revenue, customer satisfaction, and ordering behaviour through multiple time lenses — monthly, daily, weekly, and quarterly — with interactive slicers for month, food category, and restaurant filtering.

---

## 📈 Business KPIs — Jan to Aug 2025

| Metric | Value |
|---|---|
| Total Sales | ₹53.01M |
| Total Orders | 197.43K |
| Average Order Value | ₹268.51 |
| Average Rating | 4.34 ⭐ |
| Rating Count | 5.59M |

---

## 📊 Dashboard Charts & Visuals

### 📅 Monthly Sales Trend
Line chart tracking revenue across Jan–Aug. January (₹6.83M) and August (₹6.79M) are peak months; February records the seasonal low at ₹6.27M.

### 📆 Daily Sales Trend
Bar chart across all 7 days of the week. Saturday leads with ₹7.78M, Sunday drives strong weekend momentum at ₹7.64M, while Tuesday is the weekday low at ₹7.36M.

### 🗓 Weekly Sales Trend
Week-by-week bar chart across 36 weeks, identifying consistency and peak bursts to support promotional timing and staffing decisions.

### 🥗 Sales by Food Type — Veg vs Non-Veg
Donut chart comparing cuisine preference. Veg orders dominate at 64% (₹33.84M) vs Non-Veg at 36% (₹19.17M) — a critical input for menu and inventory planning.

### 🗺 Sales by State — Map Visualisation
India choropleth map showing state-wise revenue distribution across all 28 states. Karnataka leads at ₹5.46M, followed by Maharashtra (₹3.02M), Telangana (₹3.02M), and Uttar Pradesh (₹3.12M).

### 🏙 Top 5 Cities by Sales

| City | Sales |
|---|---|
| Bengaluru | ₹5.46M |
| Lucknow | ₹3.12M |
| Mumbai | ₹3.02M |
| Hyderabad | ₹3.02M |
| New Delhi | ₹2.83M |

### 📋 Quarterly Performance Summary

| Quarter | Sales | Avg Rating | Orders |
|---|---|---|---|
| Q1 (Jan–Mar) | ₹19.67M | 4.34 | 73.1K |
| Q2 (Apr–Jun) | ₹19.90M | 4.34 | 74.2K |
| Q3 (Jul–Aug) | ₹13.44M | 4.34 | 50.2K |

---

## 🛠 Tools & Skills

- **Microsoft Excel** — full dashboard design, layout, and interactivity
- **Pivot Tables & Pivot Charts** — powering all KPIs and trend charts dynamically
- **Excel Slicers** — Month, Food Category, and Restaurant-level filtering across all visuals
- **Bing Maps (Excel)** — state-wise geographic revenue visualisation across India
- **Data Cleaning** — raw transaction data structured with State, City, Day, Quarter, Food Type, Restaurant, Category columns
- **KPI Card Design** — custom formatted metric tiles with icons for executive-level summary
- **Conditional Formatting** — highlighting top performers in the quarterly matrix table

---

## 💡 Key Insights

- **Bengaluru** is the top revenue city at ₹5.46M — nearly 2× the next highest city
- **Veg cuisine** accounts for 64% of all sales, reflecting India's dietary preferences
- **Saturday** is the busiest sales day; Tuesday is the quietest — useful for targeted promotions
- Q1 and Q2 are nearly equal in performance across sales, rating, and orders
- Customer satisfaction is remarkably consistent — average rating holds at 4.34 across all quarters
- Average Order Value of **₹268.51** reflects a mid-premium ordering profile across the platform

---

## 📂 Files


├── [Swiggy Dashboard](https://github.com/abhisheknirmal02-lab/Swiggy-Sales-Dashboard/blob/main/Swiggy%20Sales%20Dashboard.xlsx)   # Raw data + Analysis + Dashboard sheets
└── [Dashboard Preview](https://github.com/abhisheknirmal02-lab/Swiggy-Sales-Dashboard/blob/main/Swiggy%20Dashboard.png)             


---

## 🚀 How to Use

1. Download `Swiggy_Raw_Data_Excel.xlsx` and open in Microsoft Excel
2. Navigate to the **Dashboard** sheet for the interactive overview
3. Use the **Month**, **Category**, and **Restaurant** slicers to filter all charts simultaneously
4. Visit the **Analysis** sheet to explore the underlying pivot tables and calculated KPIs
5. Raw transactional data is in the **Data** sheet — filterable by State, City, Day, Quarter, Food Type, and more

---

## 📐 Dataset Fields

State · City · Date · Day · Quarter · Week No · Restaurant · Area · Food Category · Dish Name · Food Type (Veg/Non-Veg) · Price (INR) · Rating · Rating Count

---

*Built as a portfolio project to demonstrate end-to-end Excel data analytics — from raw food delivery transactions to a fully interactive business intelligence dashboard. ⭐ Star this repo if you find it useful!*
