# 📉 The Startup Cash Runway & Burn Rate Predictor

[![Notion](https://img.shields.io/badge/Notion-Workspace-black?logo=notion)](https://wholesale-archer-889.notion.site/India-D2C-Femtech-d8ff4eb28dd082c2b757017ce999e1ba)
[![Excel](https://img.shields.io/badge/Excel-Financial_Model-107C41?logo=microsoft-excel&logoColor=white)](#)

A dynamic, scenario-based financial forecasting template designed for early-stage startup founders, operators, and finance teams. This model allows users to manipulate headcount plans, operational levers, and growth multipliers to instantly compute monthly gross burn, net burn, and exact cash runway limitations.

---

## 📊 Model Structure & Sheets

The model is built with modular formulas and clean separation between logic inputs and dynamic dashboard displays across three primary worksheets:

### 1. ⚙️ Driver Inputs
* **General Financial Drivers:** Centralizes assumptions like starting cash balances and cost baselines (e.g., base developer or engineer salaries).
* **Operational Multipliers:** Scalable nodes for dynamic marketing cost scaling and discretionary spend.
* **Active Scenario Selector:** Dropdown triggers allowing users to instantly switch between strategic scenarios (e.g., *Hire 2 Engineers* vs. conservative runway retention) to dynamically recast projections.

### 2. 📅 Financial Forecast
* **12-Month Timeline:** Maps cash progression month-over-month from baseline start through end-of-year projections.
* **Revenue Tracking:** Captures operational top-line incoming cash streams against dynamic outflows.
* **Granular Opex Breakdown:** Segregates resource allocations across core operational vertices:
  * *Salaries & Compensation*
  * *Growth & Marketing*
  * *Tech Stack, Cloud, & Infrastructure*
  * *Rent, Office, & General Administrative Overheads*
* **Burn Rate Core:** Automatically calculates dynamic **Gross Burn** and **Net Burn** variables across the timeline.

### 3. 🎯 Dashboard
A executive summary layout aggregating mission-critical tracking metrics at a single glance:
* **Current Runway (Months):** The definitive countdown clock indicating operational lifespan before default.
* **Current Cash Balance:** Live monitoring of capital reserves.
* **Average Monthly Net Burn:** Aggregated net deficit highlighting structural capital health.

---

## 🚀 How to Implement

1. **Set the Baseline:** Enter your actual cash position and fixed overhead baselines into the `Driver Inputs` canvas.
2. **Toggle Scenarios:** Use the active scenario selection node to stress-test your cash buffer against aggressive expansion or sudden revenue contractions.
3. **Audit the Burn:** Review the `Dashboard` to identify exactly when the startup transitions from green operational territory into safety fundraising windows.

---

## 📋 Features & Formula Architecture

- [x] Dynamic macro-free architecture utilizing cellular referencing chains
- [x] Clear decoupling of Variable Drivers, Core Ledgers, and Visual Dashboards
- [ ] Add rolling 24-month horizon expansions
- [ ] Incorporate automated multi-tiered fundraising trigger notifications

---
*For product roadmaps, D2C market context, and deeper investor relations templates, check out our core [Notion Workspace Directory](https://wholesale-archer-889.notion.site/India-D2C-Femtech-d8ff4eb28dd082c2b757017ce999e1ba).*
