# AICTE-February-2026-Internship-Power-BI--Ujjwal-Kumar-Arun-Chouhan
# 🍫 Chocolate Sales Data Analysis — Power BI Dashboard

### AICTE February 2026 Internship – Power BI
**Internship Program:** Microsoft Elevate | AICTE February 2026 — Power BI  
**Presented By:** Ujjwal Kumar Arun Chouhan

---

## 📌 Project Overview

This project is an end-to-end Business Intelligence solution built as part of the **AICTE February 2026 Power BI Internship**. It involves analyzing chocolate sales data across multiple products, countries, and sales teams using **Microsoft Power BI**. The goal is to clean, model, and visualize the data to generate actionable business insights through an interactive dashboard.

---

## 📂 Dataset

- **Source:** Chandoo.org — Chocolate Sales Sample Dataset
- **Inspiration:** Chandoo YouTube Channel
- **File Format:** Microsoft Excel (.xlsx)
- **Sheets:** Shipments, Dimension Data, Calendar
- **Records:** 7,905 shipment transactions
- **Time Period:** January 2023 – October 2024
- **Products:** 22 chocolate products across 3 categories (Bars, Bites, Other)
- **Countries:** India, USA, UK, Canada, Australia, New Zealand
- **Sales Teams:** Delish, Yummies, Jucies, Tempo

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Primary data source |
| Power Query Editor | Data cleaning & transformation |
| Power BI Desktop | Data modeling, DAX measures & dashboard |
| DAX | Calculated KPI measures |
| Power BI Service | Report publishing & sharing |

---

## 🧹 Data Cleaning (Power Query)

- Removed null and blank values from Amount and Boxes columns
- Eliminated duplicate ShipmentID rows
- Dropped irrelevant and empty columns from Dimension Data sheet
- Corrected data types — Amount (Currency), Boxes (Whole Number), ShipDate (Date)

---

## 🗃️ Data Model

A **Star Schema** was built with the following structure:

- **Fact Table:** Shipments (transaction-level data)
- **Dimension Tables:** Products, Geographies, Salespersons, Calendar
- Relationships established via foreign keys — PID, GID, SPID

---

## 📊 DAX Measures

```
Total Revenue = SUM(Shipments[Amount])
Total Boxes = SUM(Shipments[Boxes])
Delivery Rate = Delivered Orders / Total Orders
Cancellation Rate = Cancelled Orders / Total Orders
```

---

## 📈 Key Insights

- **Total Revenue:** $44.69M
- **Total Boxes Shipped:** 3.78M
- **Total Shipments:** 7,905
- **Delivery Rate:** 80.4%
- **Cancellation Rate:** 4.7%
- **Top Product:** Peanut Butter Cubes ($3.74M)
- **Top Market:** UK ($10.54M) followed by India ($10.39M)
- **Lowest Market:** Canada ($2.65M) — growth opportunity
- **Best Sales Team:** Delish ($13.53M)
- **Weakest Sales Team:** Tempo ($6.42M)

---

## 🖥️ Dashboard Features

- Multi-page interactive Power BI dashboard
- Dynamic slicers for Country, Product, Team, and Date
- KPI cards for Revenue, Boxes, Delivery Rate, and Cancellation Rate
- Product-wise and region-wise revenue breakdown
- Sales team performance comparison
- Monthly trend analysis using Calendar dimension

---

## 🚀 Future Scope

- ML-based sales forecasting using Python/R visuals in Power BI
- Real-time data integration with live databases
- Profit margin analysis using cost-per-box data
- Individual salesperson scorecards with target vs. actual tracking
- Geo-map visuals for regional revenue density
- Power BI Mobile app optimization

---

## 📁 Project Structure

```
├── sample-chocolate-sales-data-all.xlsx   # Raw dataset
├── Chocolate_Sales_PowerBI.pbix           # Power BI project file
├── README.md                              # Project documentation
```

---

## 📜 References

- Chandoo.org — https://chandoo.org/wp/
- Chandoo YouTube Channel — https://www.youtube.com/@chandoo_
- Microsoft Power BI Docs — https://docs.microsoft.com/en-us/power-bi/
- DAX Reference Guide — https://dax.guide/

---

## 🎓 Internship Details

- **Program:** Microsoft Elevate — AICTE February 2026 Internship
- **Track:** Power BI
- **Student:** Ujjwal Kumar Arun Chouhan
