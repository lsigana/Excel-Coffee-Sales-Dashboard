# ☕️ Interactive Coffee Sales Dashboard in Excel

## 📌 Project Overview

This project features an interactive, dynamic **Coffee Sales Dashboard** built entirely in Microsoft Excel. It allows users to explore multi-year sales trends by product type, region, and customer segment using slicers and filters, all without requiring any coding or external BI tools.

> 📈 Ideal for business managers, sales teams, and analysts looking to **gain quick insights** and **make strategic decisions** from sales data.

---

## Why This Dashboard Matters

> **Why should someone spend time looking at this dashboard?**

Because it enables **real-time, low-cost decision-making** by revealing:
- Which roast and pack sizes drive revenue
- What seasonal trends or sales spikes exist
- Where your most loyal, high-value customers are concentrated
- How regional performance compares over time

No Power BI, Tableau, or SQL needed — just Excel.

---

## 🧭 Dashboard Features

![Coffee Sales Dashboard Screenshot](screenshots/dashboard-preview.png)

- 📅 **Interactive Timeline** – Filter sales by specific months or years (2019–2022)
- 🏷️ **Slicers** – Roast Type, Coffee Size, Loyalty Card status
- 📈 **Line Chart** – Sales trend over time, segmented by coffee type
- 🌍 **Bar Chart** – Sales by country (US, Ireland, UK)
- 👥 **Top Customers** – Names and sales totals of highest-spending customers

---

## 📊 Key Business Metrics Tracked

| Metric              | Description |
|---------------------|-------------|
| Total Sales Over Time | Shows fluctuations and seasonality from 2019–2022 |
| Sales by Roast Type   | Reveals popular products: Arabica, Robusta, Liberica, Excelsa |
| Sales by Country      | Regional performance with standout markets |
| Top Customers         | Ranked by total sales value |
| Loyalty Card Usage    | Allows segmentation of repeat vs. one-time buyers |

---

## 🔍 Sample Insights

> These insights are immediately visible from the dashboard:

- 📈 **End-of-year sales spikes** are consistent — likely due to holidays or promotions.
- 🌍 **United States** overwhelmingly dominates in sales (~80%), with Ireland and UK trailing far behind — indicating a strong regional concentration.
- ☕ **Arabica and Excelsa** perform consistently well, while Robusta shows higher volatility.
- 👥 Customers like **Allis Wilmore** and **Terri Farra** contribute disproportionately to sales — suggesting high LTV (lifetime value).

---

## 💡 Recommendations

1. **Double down on the U.S. market** with exclusive product lines and faster fulfillment.
2. **Create bundle offers** around Arabica and Excelsa, especially during peak seasons.
3. **Build a loyalty program** targeting customers like Allis and Terri to retain top spenders.
4. **Investigate Robusta volatility** — is it supply chain, taste preference, or price-related?

---

## 🧠 Tools & Formulas Used

| Tool / Technique       | Purpose |
|------------------------|---------|
| `XLOOKUP`              | Merge Customer and Product details into Orders table |
| `INDEX MATCH`          | Pull dynamic product attributes (e.g. size, roast) |
| `IF` Statements        | Handle blanks and rename values (e.g., “Med” → “Medium”) |
| Data Formatting        | US Dollars, Kilo labels, Month abbreviations |
| PivotTables & Charts   | Build visuals (Line, Bar) and interactivity |
| Timeline + Slicers     | Dynamic user filtering of dashboard |

---

## 📁 Project Structure

 Excel-Coffee-Sales-Dashboard
├── Coffee_Sales_Dashboard.xlsx # Final interactive Excel dashboard
├── README.md # Project documentation
├── screenshots/
│ └── dashboard-preview.png # This dashboard screenshot
├── data/ # Raw source files
│ ├── CoffeeOrdersData.xlsx



---

## 🚀 How to Use This Dashboard

1. Open `Coffee_Sales_Dashboard.xlsx` in Excel
2. Use the Timeline to filter specific periods (e.g., Q4 2021)
3. Select roast types, sizes, or loyalty card filters
4. Observe how visuals change dynamically
5. Use insights to guide product, pricing, or marketing decisions

---

## 🧠 For Business Decision Makers

This dashboard answers critical sales questions like:

- Who are our top customers and where are they located?
- Which products generate the most revenue, and when?
- Are our loyalty customers spending more?
- What product should we focus on stocking, bundling, or upselling?

---

---

## 📚 Data Source

The dataset used in this dashboard was sourced from [Kaggle]
It includes sales records, customer data, and product details related to coffee sales over a multi-year period.

*Data has been cleaned and transformed for the purpose of this project.*



## 🙋‍♀️ Feedback & Contact
Feel free to fork, download, or ask questions via:
- [Email](leahsigana47@gmail.com)

