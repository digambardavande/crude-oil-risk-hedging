**End-to-end crude oil price risk analysis and futures hedging simulation using Python, Excel, and historical WTI data.**
**Author:** Digambar Davande
---
## 🔎 Project Overview
This repository contains an end-to-end analysis that mirrors the work of a Risk Analyst on an oil trading desk. The project:
- Cleans and prepares historical **WTI futures** price data.
- Performs EDA (price trends, daily returns, rolling volatility).
- Simulates an **unhedged** physical exposure (default: **10,000 barrels**).
- Implements a **futures hedge** (1 WTI contract = 1,000 barrels) and computes hedged P&L.
- Quantifies risk using **Value-at-Risk (VaR)**, **Expected Shortfall (ES)**, and annualized volatility.
- Stress-tests the book on the worst historical days and compares hedged vs unhedged losses.
- Produces board-ready deliverables: Excel workbook, charts, and a short executive summary.

**One-line summary:** Built a crude oil risk analysis & hedging simulation that cut downside risk by ~90%, delivering board-ready insights.
---
## 📁 Repository structure
Crude_Oil_Risk_Analysis/
├─ data/
│ └─ Crude Oil WTI Futures Historical Data.csv # original raw CSV (NOT included)
├─ notebooks/
│ └─ Crude_Oil_Risk_Analysis.ipynb # main notebook (step-by-step)
├─ outputs/
│ ├─ wti_clean.csv
│ ├─ wti_project_pack.xlsx
│ ├─ chart_price_trend.png
│ ├─ chart_unhedged_vs_hedged.png
│ └─ chart_worst5.png
├─ requirements.txt
└─ README.md

🧾 Executive summary 
This project analyzed WTI crude oil futures data and simulated a 10,000-barrel exposure. Using daily price changes we computed P&L, Value-at-Risk (VaR), Expected Shortfall (ES), and annualized volatility for both unhedged and hedged (10 futures contracts) portfolios. The hedge reduced downside risk in VaR/ES and volatility by ~85–90% and significantly softened losses on the five worst historical days. The results demonstrate that a properly sized futures hedge is highly effective in stabilizing cash flows and protecting a trading book from severe downside events.

python, risk-analysis, finance, oil-gas, time-series, hedging, data-analysis

📬 Contact
For questions or help adapting the notebook for another dataset or reporting format, contact: Digambar Davande +918806120103 
