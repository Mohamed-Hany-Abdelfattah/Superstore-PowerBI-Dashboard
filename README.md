# Superstore Power BI Dashboard

An end-to-end Business Intelligence solution built in **Microsoft Power BI**, transforming the
**Sample Superstore dataset (2016–2019)** into an interactive, executive-ready reporting model.

---

## 📌 Overview

The goal of this project was to replace manual, spreadsheet-based reporting with an automated
and governed BI solution. Raw transactional data was ingested, cleaned, modeled, and analyzed to
surface business trends, evaluate performance, and highlight areas for improvement.

---

## 🛠️ Tech Stack

- **Microsoft Power BI Desktop** — reporting & data model
- **Power Query** — data ingestion and transformation (ETL)
- **DAX** — measures and calculated columns
- **Microsoft Excel** — source dataset

---

## ✨ Solution Highlights

### 1. Data Preparation — Power Query
- Imported and standardized the raw dataset
- Corrected data types, trimmed text fields, and removed invalid/null order lines

### 2. Data Modeling
- Fact table (`Orders`) + Date dimension table
- A dedicated **Date table (1,461 days)** with a custom **Year → Month → Day hierarchy**
- Relationships configured to support time intelligence

### 3. Analytics — DAX
- **16 measures**, including Total Sales, Total Profit, Profit Margin %, Running Total,
  Year-over-Year Growth, Loss-Making %, Average Order Value, and Average Shipping Delay
- **3 calculated columns**: Profitability Category, Profitability Order, and Shipping Delay

### 4. Reporting — 3 Interactive Pages
- **Executive Summary** — KPI overview with sales and profit trends
- **Product Analysis** — top products, margin analysis, and a product matrix
- **Product Details** — a drill-through page for deep-dive analysis

### 5. Interactivity
- **9 slicers**, cross-filtering, and drill-through analysis
- Cross-page navigation and a one-click **Reset Filters** action

### 6. Data Security — Row-Level Security
- **5 security roles** (Central / East / South / West Region + Manager)
- Supports region-based data access, while managers retain full visibility

---

## 📈 Key Insights

| Insight | Value |
|---|---|
| Total Sales (2016–2019) | **$2.30M** |
| Total Profit | **$286K** |
| 2019 Sales | **$733K** (+20.4% YoY) |
| 2019 Profit Growth | **+14.2% YoY** |
| Furniture Profit Margin | **~2%** |
| Technology / Office Supplies Margin | **~17%** |
| Loss-Making Order Lines | **1,871** |
| Average Shipping Delay | **~4 days** |

---

## 📂 Repository Contents

| File | Description |
|---|---|
| `SuperstoreDashboard.pbix` | The Power BI report and data model |
| `Sample - Superstore 2019.xlsx` | Source dataset |
| `README.md` | Project documentation |

---

## 🚀 Getting Started

1. Install **Power BI Desktop**.
2. Clone or download this repository.
3. Open `SuperstoreDashboard.pbix`.
4. Explore the three report pages and the interactive slicers.

> **Note:** The data model is embedded in the `.pbix`. If you refresh the report, point the
> source to `Sample - Superstore 2019.xlsx`.

---

## 👤 Author

**Mohamed Hany Abdelfattah**
GitHub: [@Mohamed-Hany-Abdelfattah](https://github.com/Mohamed-Hany-Abdelfattah)

---

*Built as part of the Digital Egypt Pioneers Initiative (DEPI) — Data Analytics track.*
