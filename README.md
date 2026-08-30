# 📈 Stock Market Analytics & Executive Portfolio Dashboard

[![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/excel)
[![Financial Analytics](https://img.shields.io/badge/Analytics-Portfolio_Management-blue?style=for-the-badge)](https://github.com)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](https://github.com)

---

## 📌 Executive Summary & Objective

The **Stock Market Analytics & Portfolio Dashboard** is an end-to-end investment tracking and performance evaluation system built in Microsoft Excel. It automates portfolio tracking, calculates critical financial KPIs (P&L, CAGR, Return %, Holding Weights), and provides an interactive visual dashboard for executive-level market insights.

---

## 🖼️ Dashboard Preview

![Executive Dashboard](images/dashboard_overview.png)
*Figure 1: Executive Portfolio Analytics Dashboard featuring dynamic charts, KPIs, and allocation visuals.*

---

## 🚀 Key Performance Indicators (KPIs)

Based on the portfolio evaluation of **106 equity holdings**, here is the high-level financial summary:

| Metric | Value | Description |
| :--- | :--- | :--- |
| **Total Invested Capital** | **₹2,08,51,304.06** | Total initial capital deployed across all transactions |
| **Current Portfolio Value** | **₹6,78,43,907.65** | Present market valuation of active holdings |
| **Total Profit & Loss (P&L)** | **+₹4,69,92,603.59** | Absolute net profit generated |
| **Overall Portfolio Return** | **+225%** | Aggregate return on invested capital |
| **Total Holdings** | **106** | Total individual stocks tracked |
| **Profitable Positions** | **99 (93.4%)** | Holdings currently in positive returns |
| **Loss-Making Positions** | **7 (6.6%)** | Holdings currently in negative returns |
| **Best Performing Stock** | **ADANIGREEN (+4970%)** | Top multibagger stock in portfolio |
| **Worst Performing Stock** | **PAYTM (-59%)** | Highest drawdown stock |
| **Largest Portfolio Allocation** | **ABBOTINDIA (₹84.55 Lakhs)** | Single largest active holding by market value |

---

## 🔄 End-to-End Data Workflow Pipeline

The project follows a structured 6-tier data pipeline from raw market ingestion to executive reporting:

![Workflow and Navigation Hub](images/navigation_hub.png)
*Figure 2: Data Workflow Architecture and Central Navigation Hub.*

$$\text{Raw Market Data} \longrightarrow \text{Data Cleaning} \longrightarrow \text{Transaction Log} \longrightarrow \text{Portfolio Tracking} \longrightarrow \text{KPI Engine} \longrightarrow \text{Executive Dashboard}$$

---

## 📑 Workbook Architecture & Sheet Breakdown

| # | Sheet Name | Scope & Functionality |
| :---: | :--- | :--- |
| **1** | **`Dashboard`** | Executive interactive interface containing KPI cards, Sector/Stock P&L charts, investment vs current value comparisons, and return distribution. |
| **2** | **`KPIs`** | Central financial metrics summary engine computing Total Return, CAGR, Win/Loss ratios, holding distributions, and extreme performance values. |
| **3** | **`Portfolio_Analysis`** | Deep-dive performance analytics, benchmark comparisons, risk evaluation, and historical equity trends. |
| **4** | **`Portfolio`** | Master inventory of active assets, tracking quantities, weighted average buy prices, real-time market prices, current values, and portfolio weightages. |
| **5** | **`Transaction`** | Granular ledger of all historical Buy/Sell orders, transaction dates, executed prices, order quantities, and cash flow impacts. |
| **6** | **`Clean_Data`** | Standardized, normalized, and error-free dataset used for cross-sheet formulas, lookup logic, and data modeling. |
| **7** | **`Raw_Data`** | Multi-year historical daily stock market price data spanning 2015 to 2023 across various equity symbols. |

---

## 📊 Visual Analytics & Core Insights

### 1. Profit & Loss (P&L) Distribution
![P&L Distribution](images/pnl_distribution.png)
* **94% Profitable Positions** vs **6% Loss-Making Positions**, demonstrating a robust stock selection strategy and risk management profile.

### 2. Capital Invested vs Current Market Value
* Visual comparison tracking invested capital against current market value across all 106 individual assets, highlighting massive alpha generation in top performers (`TATAELXSI`, `ADANIGREEN`, `TITAN`, `KPITTECH`).

### 3. KPI Metrics Summary
![KPI Metrics](images/kpi_metrics.png)
* Structured tabular breakdown of core portfolio health parameters used for executive decision-making.

---

## 🛠️ Technical Skills & Excel Features Used

* **Advanced Formulas & Functions:** `XLOOKUP`, `INDEX-MATCH`, `SUMIFS`, `COUNTIFS`, `LET`, `FILTER`, `UNIQUE`, `SORT`
* **Financial Calculations:** CAGR, Holding Period Return (HPR), Portfolio Weightage, Weighted Average Cost of Capital (WACC)
* **Data Visualization:** Clustered Bar Charts, Line/Area Trend Overlays, Donut Breakdown Charts, Dynamic Formatting
* **Data Modeling & Architecture:** Multi-sheet relational data flows, clean navigation menus with hyperlink routing
* **Performance Optimization:** Saved as **Excel Binary Workbook (`.xlsb`)** for ultra-fast load times and reduced file footprint.

---

## 📂 Folder Structure Suggestion

```text
├── images/
│   ├── dashboard_overview.png   # Screenshot of main Dashboard sheet
│   ├── navigation_hub.png       # Screenshot of Navigation & Pipeline
│   ├── pnl_distribution.png     # Screenshot of Donut Chart
│   └── kpi_metrics.png          # Screenshot of KPI Summary Table
├── final excel project.xlsb     # Main Excel Project File
└── README.md                    # Project Documentation
