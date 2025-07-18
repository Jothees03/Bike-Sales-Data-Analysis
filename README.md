# 🚲 Bike Sales Data Analysis - Tableau

A data visualization and analysis project focused on identifying sales trends and actionable insights from simulated bike sales data across the United States, conducted using **Tableau**.

---

## 📊 Project Overview

This project explores a synthetic dataset of 1,000 bike sales records in the U.S., spanning from 2022 to 2023. The analysis focuses on uncovering seasonal trends, category performance, and region-wise sales behaviors using interactive Tableau dashboards.

> 📅 **Completed on:** 12 JULY 2025  
> 👨‍💻 **By:** Jotheeswaran S

---

## 🧾 Dataset Description

- **Source:** Generated using [Mockaroo](https://mockaroo.com/)
- **Records:** 1,000 entries
- **Period Covered:** 2022–2023
- **Coverage:** Multiple showrooms and regions across the United States
- **Fields Include:**
  - Bike ID, Bike Name, Category  
  - Price, Discount, Final Price  
  - Showroom Name, Region, Sales Date  
  - Sales Representative, Payment Method, EMI Status, Bank Name

---

## 🧹 Data Preparation Steps

1. **Data Collection:**  
   - Generated via Mockaroo with 12 custom fields.

2. **Data Cleaning:**  
   - Removed blanks, fixed date formats, spelling, capitalization.

3. **Validation:**  
   - Ensured consistent data types and formats.

4. **Exporting:**  
   - Cleaned dataset exported to Excel.

5. **Visualization:**  
   - Imported into Tableau for analysis.

---

## 🔢 Key Calculations

| Formula | Description |
|--------|-------------|
| `AVG([Price])` | Calculates the average price of all bikes |
| `-[Price]` | Returns the negative price (for visuals/comparisons) |
| `COUNT([Unique Bike Id])` | Counts the number of unique bikes sold |
| `([DISCOUNT VALUE]/[Price])*100` | Calculates discount percentage |
| `[Discount]*10` | Multiplies discount value (for scaling/tests) |
| `[Price] - [DISCOUNT VALUE]` | Final price after discount |

---

## 📈 Dashboards & Visuals

Created interactive Tableau dashboards to explore:
- Sales by region and showroom  
- Monthly/seasonal performance  
- Revenue and pricing trends  
- Category-wise performance breakdown

---

## 🔍 Key Insights

- **Seasonal Demand:** Sales peak in **June–July**; high from **May–August**  
- **Best-Selling Category:** **Hybrid Bikes** lead in sales and revenue  
- **Low Off-Season:** Sales drop significantly in **November–February**  
- **Stable Revenue Patterns:** Pricing remains steady; revenue mirrors sales  
- **Underperforming Category:** **Electric Bikes** show low sales in all seasons

---

## 📌 Recommendations

- **Peak Season Focus:** Boost inventory & marketing from April–August  
- **Winter Promotions:** Use discounts, service offers, or bundles  
- **Promote Low Performers:** Create targeted campaigns for Electric Bikes  
- **Spring Launches:** Introduce new models in March–April  
- **Data-Driven Stocking:** Align inventory with historical demand trends

---

## ✅ Conclusion

- **Seasonality Drives Sales** – Summer is the key revenue season  
- **Hybrid Bikes Dominate** – Focus category for marketing and stock  
- **Revenue Mirrors Volume** – Pricing strategies are consistent  
- **Off-Season Potential** – Use creative strategies to boost winter sales  
- **Data-Driven Planning** – Leverage insights for inventory and promotions

---

## 🛠️ Tools & Technologies

- **Tableau** – Dashboard & visualization  
- **Excel** – Data cleaning and exporting  
- **Mockaroo** – Dataset generation  
- **PowerPoint** – Presentation design

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `Bike_Sales_Dataset.xlsx` | Cleaned dataset used for Tableau |
| `BIKE SALES DATASET ANALYSIS-TABLEAU.pptx` | Final project presentation |
| `Bike_Sales_Dashboard.twb` *(optional)* | Tableau Workbook file |

---

## 📬 Contact

**Jotheeswaran S**  
📧 jotheeswaransakthi2gmail.com 
🔗 [LinkedIn] https://www.linkedin.com/in/jotheessakthi3/

---

