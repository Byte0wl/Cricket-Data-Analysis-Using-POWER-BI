# 🏏 Cricket Data Analysis using Power BI

## 📌 Overview

This repository contains resources and analyses for exploring and visualizing cricket datasets (specifically T20 match data) using Power BI, supplemented by data preprocessing and transformation steps. 

The goal is to surface insights such as **team performance trends, player statistics, match comparisons, and advanced metrics** — all in an interactive dashboard format.

---

## 📂 Repository Structure

```
Cricket-Data-Analysis-Using-POWER-BI/
│
├── t20_csv_files/
│ └── Raw CSV files (match data, ball-by-ball data, etc.)
│
├── t20_json_files/
│ └── JSON versions of the raw data for flexible ingestion
│
├── t20_data_preprocessing.ipynb
│ └── Jupyter Notebook for cleaning, transforming, and feature engineering the raw data
│
├── DAX Measures and Calculated columns.xlsx
│ └── Reference sheet listing the DAX measures, calculated columns, and business logic used in Power BI
│
├── DIC.pbix
│ └── Power BI Report file (dashboard + data model)
│
└── Paramaeter Scoping.pdf
└── Documentation describing how parameters and scoping are handled in the Power BI solution
```

---

## 🎯 Features & Insights

In the Power BI dashboard, you’ll find:

- **Team & Player Performance Trends** 
Visualize how teams and players perform over time, across seasons, venues, run rates, etc.

- **Match Comparisons & Head-to-Head Analyses** 
Compare teams or players side-by-side; look at win/loss breakdowns, scoring patterns, and more.

- **Advanced Metrics & Derived Features** 
Metrics such as strike rates, dot ball percentages, and death overs performance, engineered during preprocessing.

- **Interactive Slicers, Drill-downs & Filters** 
Filter by season, venue, team, innings, match phases, and drill into granular insights.

- **DAX-Driven Measures & Calculated Columns** 
Business logic for ratios, rankings, and dynamic filters (refer to the Excel file for full definitions).

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Byte0wl/Cricket-Data-Analysis-Using-POWER-BI.git
cd Cricket-Data-Analysis-Using-POWER-BI
```

### 2. Data Preprocessing

- Open `t20_data_preprocessing.ipynb` in **Jupyter Notebook** or **VS Code**.
- Run the preprocessing pipeline to clean and transform raw CSV/JSON into analytical tables.
- This produces curated datasets consumed by the Power BI model.

### 3. Open the Power BI Report

- Open `DIC.pbix` in **Power BI Desktop**.
- Connect or point the model to the preprocessed tables.
- Refresh the data to see updated results.
- Explore interactive report pages and slicers.

### 4. Understand the DAX Logic

- Use `DAX Measures and Calculated columns.xlsx` as a guide.
- It documents every measure, calculated column, and KPI.

### 5. Parameter Scoping & Customization

- Refer to `Paramaeter Scoping.pdf` to understand how filters and parameters are applied across visuals and pages.
- Extend or modify scoping for new custom scenarios.

---

## ✅ Requirements & Dependencies

- **Power BI Desktop** (latest version recommended)
- **Python 3.x** with:
- `pandas`
- `numpy`
- (Optional) `matplotlib`, `seaborn` for EDA

---

## 🧩 Possible Extensions

You can extend this project by:

- Adding **ODI & Test match data** alongside T20.
- Including **bowling & fielding statistics** for richer insights.
- Deploying to **Power BI Service** for web sharing.
- Applying **forecasting, clustering, or ML insights** on top of dashboards.
- Building storytelling pages with commentary, tooltips, and drillthroughs.

---
## 🙌 Acknowledgements

- Tools used: **Python**, **Power BI Desktop**, **DAX**
- Inspired by the love for cricket & analytics 🏏
---

