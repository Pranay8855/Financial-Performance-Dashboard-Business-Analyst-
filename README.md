# 💰 Financial Performance Dashboard (Tableau)

This project presents an interactive **Financial Performance Dashboard** built using **Tableau Desktop**, aimed at visualizing and analyzing key financial metrics such as **sales**, **profit**, **COGS**, and **discounts** across **countries**, **products**, and **time**.
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/810f6b3d-c428-4ea2-a18c-3284a47b1458" />

---

## 🎯 Project Objective

The objective of this project is to enable business stakeholders and analysts to:
- Monitor revenue and cost performance
- Analyze trends over time
- Identify high-performing regions and products
- Evaluate the impact of discounts on sales and profit
- Make data-driven financial decisions using dynamic filters and visual summaries

---

## 📁 Files Included

```
financial-performance-dashboard/
├── dashboard/
│   └── finance dashboard final.twbx
├── documentation/
│   └── Financial Performance Dashboard (Business Analyst).pdf
├── assets/
│   └── banner.png
├── README.md
```

---

## 📊 Dataset Features

| Column            | Description                          |
|------------------|--------------------------------------|
| Segment           | Business segment (Consumer, Corporate, etc.) |
| Country           | Geographic region of the sale       |
| Product           | Product category                    |
| Discount Band     | Discount tier applied               |
| Units Sold        | Number of units sold                |
| Manufacturing Price | Base production cost per unit     |
| Sale Price        | Final sale price per unit           |
| Gross Sales       | Units Sold × Sale Price             |
| Discounts         | Discount amount applied             |
| Sales             | Net sales after discounts           |
| COGS              | Cost of Goods Sold                  |
| Profit            | Sales - COGS                        |
| Date              | Transaction date                    |
| Month Name/Number | Date breakdown                     |
| Year              | Year of sale                        |

---

## 📈 Dashboard Features (Tableau)

### 📌 Key Visualizations:
- **Bar Chart**: Sales & Profit by Country
- **Line Chart**: Yearly and Monthly Profit Trends
- **Scatter Plot**: Gross Sales vs Discounts
- **Heat Map**: Sales by Product and Discount Band
- **KPI Cards**: Total Units Sold, Gross Sales, and Profit
- **Area Chart**: Monthly Profit Flow
- **Slicers/Filters**: Segment, Country, Product, Discount Band, Date Range

### 🎛️ Interactivity:
- Dynamic filtering by year, segment, and country
- Reset filter button to clear selections
- Hover-based tooltips for deep dive insights

---

## 🧠 Sample Calculated Fields (in Tableau)

- **Profit Margin**: `SUM([Profit]) / SUM([Sales])`
- **Total Revenue**: `SUM([Gross Sales])`
- **COGS to Sales Ratio**: `SUM([COGS]) / SUM([Sales])`
- **Discount Impact**: `SUM([Discounts]) / SUM([Gross Sales])`

---

## 📦 Tools Used

| Tool         | Purpose                         |
|--------------|----------------------------------|
| Tableau      | Data visualization and dashboard design |
| Excel/CSV    | Raw data storage and import      |
| Calculated Fields | KPI derivation and metrics |

---

## ✅ Key Insights

- Countries with the highest profits and sales can be identified in seconds.
- Seasonal trends and monthly sales drops are easily visible using the line and area charts.
- Discount strategy effectiveness is visualized through scatter plots and heat maps.

---

## 🧩 Future Improvements

- Add YoY growth metrics and profit forecasting
- Use parameters to switch between different KPIs dynamically
- Combine with live data from Google Sheets or a database source
- Publish to Tableau Public with embedded interactions

--
