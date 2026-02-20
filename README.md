# trading-performance-dashboard
Trade Frequency vs Performance Project 
# Trading Performance Analysis — Trade Frequency vs Results

# Trading Performance Dashboard  
**Trade Frequency vs Performance**

## Overview

This project analyzes how **trade frequency impacts trading performance** using real backtesting data tracked in Excel, cleaned in Python (pandas), and visualized in Tableau.

The core question:
> Does trading more often improve results — or hurt them?

The analysis shows that **capping trades per day improves consistency and overall performance**, while higher trade frequency leads to worse total R and more volatile equity curves.

This project demonstrates:
- Data cleaning and feature engineering in **Python (pandas)**
- Working with **raw trading logs from Excel**
- Exporting clean data for **Tableau visualization**
- Building a **business-focused analytical dashboard**
- Communicating insights clearly for decision-making

---

## Key Findings

- 📉 **More trades per day = worse total performance**
- 📈 **1 trade per day cap produces smoother, more consistent equity growth**
- ⚠️ Higher trade frequency increases drawdowns and volatility
- 📊 Certain **days of the week and instruments** perform significantly better than others

---

## Files in This Repository

- `Dashboard 1.pdf`  
  → Final Tableau dashboard export (ready to view)

- `trades_clean.csv`  
  → Cleaned dataset used in Tableau

- `trades_clean_csv.ipynb`  
  → Python (pandas) notebook used to:
  - Load raw trade data
  - Clean and transform fields
  - Create features like trades per day
  - Export the clean CSV for Tableau

- `README.md`  
  → Project documentation (this file)

---

## Data Pipeline

1. **Raw data** tracked in Excel during live backtesting
2. **Python (pandas)** used to:
   - Clean trade records
   - Standardize dates and results
   - Create derived metrics (e.g. trades per day)
3. **Clean CSV exported** from Python
4. **Tableau** used to:
   - Build equity curves
   - Compare capped vs uncapped strategies
   - Analyze performance by trade frequency, instrument, and day of week
5. **Dashboard exported to PDF** for sharing and portfolio use

---

## Tools Used

- **Python** (pandas, numpy)
- **Jupyter / Google Colab**
- **Excel** (raw data tracking)
- **Tableau** (data visualization & dashboarding)
- **GitHub** (project version control & portfolio hosting)

---

## Dashboard Preview

Open `Dashboard 1.pdf` to view the full interactive layout and analysis.

The dashboard includes:
- Original vs 1-trade-per-day equity curves
- Trades per day vs total R
- Average R vs trade frequency
- Instrument performance comparison
- Performance by day of week
- November subset analysis

---

## Why This Project Matters

This project shows:
- Practical data cleaning skills in Python
- Real-world performance analysis (not toy data)
- Ability to connect **data → insight → decision**
- Clear communication of trading and performance metrics

It’s designed to reflect the kind of analysis used in:
- Trading performance reviews
- Strategy optimization
- Risk management and overtrading control
- Data-driven decision-making environments

---

## Author

Quin Watson  
Project: *Trading Performance Dashboard – Trade Frequency vs Performance*
