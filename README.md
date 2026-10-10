# 📊 Sales Dashboard Using Excel

## 📌 Project Overview

A business needs one place to monitor sales health: *How much are we earning and keeping as profit? Which countries and regions perform best? What channels drive revenue? How is performance trending month to month?*

This project builds a single-page **Executive Summary & Profitability** dashboard in Excel that answers all of this interactively, using Pivot Tables as the data engine and Slicers for filtering by Product Category, Region, and ID.

---

## 🗂️ Dataset

| Detail | Info |
|---|---|
| **Total Records** | 2,708 rows |
| **Tool** | Microsoft Excel |
| **Core Components** | Sales Data sheet, Pivot Tables, Pivot Charts, Slicers |

### Fields Used
`Order ID`, `Product Category`, `Country`, `Region`, `Revenue`, `Gross Profit`, `COGS`, `Units Sold`, `Order Date`, `Sales Channel`

---

## 🛠️ Tools & Excel Features Used

- **Pivot Tables** — the underlying data engine for every visual
- **Pivot Charts** — line chart, bar chart, pie chart, donut chart
- **Slicers** — Product Category, ID, Region (synced across visuals)
- **Map Chart** — Country-wise revenue heat map (Bing Maps)
- **KPI Cards** — built with formula-linked cells (SUM, AVERAGE)
- **Conditional Formatting** — color gradients on the map visual
- **Dashboard Design** — rounded card layout, consistent color theme, single-screen view

---

## 📐 Dashboard Layout

| Section | Visual Type | Purpose |
|---|---|---|
| KPI Cards | Metric cards | Total Revenue, Gross Profit, Profit Margin, Units Sold, Orders, COGS |
| Monthly Revenue & Profit | Line chart | Revenue vs. Gross Profit trend, Jan–Dec |
| Top 5 Country by Revenue | Bar chart | Country-level revenue ranking |
| Revenue Share by Channel | Pie chart | Corporate / Marketplace / Online Store / Retail Partners |
| Region-Wise Comparison | Donut chart | Central / Northern / Southern / Western Europe |
| Country-Wise Map | Choropleth map | Geographic revenue distribution |
| Filters | Slicers | Product Category, ID, Region |

---

## 📊 Results

### 🔑 Key Metrics (KPI Cards)

| Metric | Value |
|---|---:|
| 💰 Total Revenue | **$6,45,223.18** |
| 📈 Gross Profit | **$2,96,384.25** |
| 📊 Profit Margin | **45.94%** |
| 📦 Total Units Sold | **6,698** |
| 🧾 Total Orders | **2,707** |
| 💵 COGS | **$64,647.53** |

### 📅 Monthly Revenue & Profit

| Month | Total Revenue | Total Gross Profit |
|---|---:|---:|
| Jan | $7.69K | $3.73K |
| Feb | $4.72K | $2.33K |
| Mar | $9.79K | $4.76K |
| Apr | $11.63K | $5.66K |
| May | $11.46K | $5.48K |
| Jun | $15.53K | $7.21K |
| Jul | $13.71K | $6.34K |
| Aug | $12.21K | $5.95K |
| Sep | $9.72K | $4.64K |
| Oct | $9.52K | $4.45K |
| Nov | $11.03K | $5.20K |
| Dec | $6.71K | $3.34K |

### 🌍 Top 5 Countries by Revenue

| Rank | Country | Revenue |
|---|---|---:|
| 1 | United Kingdom | 13,651.03 |
| 2 | Germany | 13,076.89 |
| 3 | Spain | 11,983.05 |
| 4 | Netherlands | 11,284.06 |
| 5 | France | 8,911.08 |

### 🛒 Revenue Share by Channel

| Channel | Share |
|---|---:|
| Online Store | 41% |
| Corporate | 29% |
| Retail Partners | 17% |
| Marketplace | 13% |

### 🗺️ Region-Wise Comparison

| Region | Share |
|---|---:|
| Western Europe | 33% |
| Central Europe | 27% |
| Southern Europe | 21% |
| Northern Europe | 19% |

### 🌐 Country-Wise Map
Revenue heat map across Europe, ranging from **$3,264.97** (lowest) to **$13,651.03** (highest) by country.

### 🔎 Filters Available
- **Product Category:** Camping, Cycling, Fitness, Hiking, Travel
- **Region:** Central Europe, Northern Europe, Southern Europe, Western Europe
- **ID:** individual order-level filtering

---

## 💡 Key Insights

- **Online Store is the top channel**, driving **41%** of revenue — more than Corporate (29%) and Retail Partners (17%) combined with Marketplace.
- **Western Europe leads regional sales** at **33%**, with Northern Europe trailing as the weakest region at **19%**.
- **The UK and Germany are the top two markets**, each contributing over $13K in revenue, while **France rounds out the top 5** at roughly $8.9K — about 35% behind the UK.
- **June was the peak month** for both revenue ($15.53K) and profit ($7.21K), while **February was the weakest** ($4.72K revenue). This suggests a mid-year seasonal peak worth planning inventory around.
- **Profit margin holds steady at ~46%** across the year, meaning COGS scales roughly in line with revenue rather than eating into margin during high-revenue months.
- **Revenue and profit move together month to month**, with profit consistently sitting at roughly 48% of revenue — a healthy, stable margin structure.

---

## 🎯 Business Recommendations

1. **Double down on the Online Store channel** with more marketing spend, since it already drives 41% of revenue.
2. **Investigate the Northern Europe gap** — at 19%, it's the weakest region and may have untapped demand or distribution issues.
3. **Plan inventory and promotions around the June peak** and build campaigns to lift the February low.
4. **Strengthen the Marketplace channel** (only 13% share) — it may be underutilized compared to its potential reach.
5. **Expand presence in markets below France** in the ranking, where revenue drops off significantly after the top 5.

---

## 📁 Repository Structure

```
├── Sales_Dashboard.xlsx         # Excel file with Pivot Tables, Charts & Slicers
├── dashboard_screenshot.png     # Dashboard preview image
└── README.md                    # Project documentation
```

---

## 🚀 How to Use

1. Download `Sales_Dashboard.xlsx` and open it in Microsoft Excel (2016 or later, for Map Chart support).
2. Use the **Slicers** on the right (Product Category, ID, Region) to filter the entire dashboard interactively.
3. All KPI cards and charts update automatically via linked Pivot Tables.

---

## 📚 Skills Demonstrated

`Microsoft Excel` · `Pivot Tables` · `Pivot Charts` · `Slicers` · `Map Charts` · `Dashboard Design` · `Data Visualization` · `Business Intelligence`

---

## 👤 Author

**Kuldeep Kumare**
🔗  💻 [GitHub](https://github.com/Kuldeep225301/Excel_Sales_Dashboard/)

⭐ If you found this project useful, please give it a star!
