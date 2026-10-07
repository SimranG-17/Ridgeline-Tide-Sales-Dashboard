
# Ridgeline & Tide Outfitters: Sales Performance Dashboard (Excel)

An interactive Excel dashboard that answers core sales questions for a fictional outdoor-gear retailer selling in 10 countries across North America, Oceania, South America and the UK & Ireland.

> **Note:** All data is **synthetic**. "Ridgeline & Tide Outfitters" is a made-up brand. No real company, customer or transaction is represented.

<img width="695" height="376" alt="image" src="https://github.com/user-attachments/assets/d1c058e2-d959-4e94-b661-a7074679d838" />


---

## Project at a glance

| | |
|---|---|
| **Goal** | Give a sales manager one page to track revenue, profit, markets, channels and products |
| **Data** | 6,200 order lines, Jan 2024 - Dec 2025, 20 columns |
| **Tool** | Microsoft Excel (PivotTables, PivotCharts, slicers, KPI cards linked to cells, Data Model) |
| **Interactivity** | Slicers for **Country**, **Product** and **Quarter** filter every KPI and chart |

## Headline results

| Metric | Value |
|---|---|
| Total revenue | **$1.42M** |
| Gross profit | **$722K** |
| Gross margin | **51%** |
| COGS | $696K |
| Orders | 6,200 |
| Units sold | 14,244 |

---

## Business questions answered

The dashboard answers these directly:

1. How is the business performing overall? (revenue, COGS, profit, margin, orders, units)
2. Which countries generate the most revenue?
3. Which regions matter most?
4. Which sales channels drive revenue?
5. Which products sell best?
6. When does revenue peak, and does profit follow?
7. How does performance change by quarter, country or product? (slicers)

**Key answers:**
- Five countries produce about **79%** of revenue, led by the United States ($393K, 27.7%).
- North America is **45%** of revenue; the Web Store is the top channel at **36%**.
- The top 10 products make up about **74%** of revenue.
- November and June are the strongest months; February and March are the weakest.

Further analysis of the dataset found that revenue grew **15%** from 2024 to 2025, that margin falls from **54.5% to 38.3%** as discounts rise to 25%, and that Team & Club Sales is **25% of revenue from 6.5% of orders**.

---

## How the workbook is built

| Sheet | Purpose |
|---|---|
| **DASHBOARD** | KPI cards, five pivot charts and three slicers |
| **PIVOT TABLE** | Six PivotTables that feed the dashboard (KPIs, monthly trend, countries, regions, channels, products) |
| **SALES DATA** | The 6,200-row source table |

Key calculations: `Revenue = Units x Unit Price x (1 - Discount %)`, `COGS = Units x Unit Cost`, `Gross Profit = Revenue - COGS`, `Gross Margin % = Gross Profit / Revenue`.

## Skills demonstrated
Excel PivotTables and PivotCharts, slicers connected across multiple pivots, KPI cards linked to live cells, calculated fields, dashboard layout and design, business-question framing, synthetic data design, and turning numbers into recommendations.

## Repository structure
```
ridgeline-tide-sales-dashboard/
├── README.md
├── dashboard/
│   └── Ridgeline_Tide_Sales_Dashboard.xlsx
├── docs/
│   └── BUSINESS_QUESTIONS_AND_ANSWERS.md
├── data/
│   ├── ridgeline_tide_sales_data.csv
│   └── DATA_DICTIONARY.md
└── images/
    └── dashboard.png
```

## How to open it
1. Download `dashboard/Ridgeline_Tide_Sales_Dashboard.xlsx`.
2. Open it in **desktop Excel** (2016 or later). Slicers and pivot charts do not work in GitHub's preview or in most web viewers.
3. Click the slicers on the DASHBOARD sheet to filter.

## Limitations
- Data is synthetic, so the patterns reflect how it was designed rather than a real market.
- All amounts are USD-equivalent with no currency conversion or tax.
- The dashboard covers revenue and profit only, with no forecasting, returns or customer-level analysis.

## Author
**Simran Grover** | www.linkedin.com/in/simrangrover98 | grover.simran1998@gmail.com
