# trading-performance-dashboard
Trade Frequency vs Performance Project 
# Trading Performance Analysis — Trade Frequency vs Results

## Overview
This project analyzes my trading backtest data to study the relationship between **trade frequency** and **performance**.

The main question:
**Does trading more frequently reduce overall performance and consistency?**

Using Python for data preparation and Tableau for visualization, I built a dashboard to compare:
- Original equity curve vs a 1 trade/day cap
- Average R by trades per day
- Total R by trades per day
- Performance by instrument
- Performance by day of week
- A focused breakdown of the worst-performing month

## Key Insight
Capping trades per day improves consistency and total performance.  
As trade frequency increases, both **average R** and **total R** decline, indicating that **overtrading negatively impacts results** in this dataset.

## Data & Workflow

**Data Source:**
- Raw trade logs recorded in Excel during live backtesting

**Data Cleaning & Preparation (Python / pandas):**
- Imported raw Excel/CSV data
- Cleaned and standardized date formats
- Removed invalid / missing records
- Calculated:
  - Trades per day
  - R-multiples
  - Equity curve
  - Aggregated performance metrics
- Exported a clean dataset for visualization

**Analysis & Visualization (Tableau):**
- Built a multi-view dashboard including:
  - Equity curve comparison (original vs 1 trade/day cap)
  - Average R vs trades per day
  - Total R vs trades per day
  - Instrument performance
  - Day-of-week performance
  - Worst-month deep dive

## Tools Used
- **Python** (pandas) — data cleaning, transformation, feature engineering
- **Excel** — raw data logging during backtesting
- **Tableau** — analysis and dashboard visualization

## Files
- `Trading_Performance_Dashboard.pdf` — Final dashboard export
- (Optional) `data/` — Raw and/or cleaned datasets

## Why This Project Matters
This project demonstrates:
- End-to-end data workflow (raw data → clean dataset → analysis → insights)
- Practical performance analysis and risk/behavior evaluation
- Ability to use Python for data preparation and Tableau for storytelling
- Data-driven decision making applied to trading performance

This is relevant for:
- Junior trading / trading assistant roles
- Data / business / performance analyst roles
