# Phase 1 Project: Aviation Risk Analysis

## Project Overview

This project is part of the Phase 1 deliverables for my Data Science training.  
The goal is to help a company expanding into the aviation industry identify **low-risk aircraft** types by analyzing historical aviation accident data from 1962–2023.

By using python, pandas, data cleaning, and exploratory data analysis (EDA), I deliver actionable insights and visualizations. I also built an interactive Tableau dashboard to support decision-making.


##  Business Problem

The company is looking to purchase and operate aircraft for commercial and private purposes, but lacks knowledge of the risks associated with different aircraft types.  
I was tasked with analyzing accident data and making **three business recommendations** to guide low-risk aircraft selection.


## 📁 Contents

| File | Description |
|------|-------------|
| `aviation_data.csv` | Original raw dataset from the National Transportation Safety Board |
| `aviation_cleaned_data.csv` | Cleaned version of the dataset, ready for analysis |
| `Phase1_Project.ipynb` | Main Jupyter notebook with code, analysis, visualizations, and markdown |
| `Phase1_Project.pdf` | Exported PDF version of the notebook |
| `Tableau_Dashboard.twbx` | Tableau packaged workbook (dashboard file) |
| `README.md` | Project overview and documentation |


## 🔧 Tools & Technologies

- **Python** (pandas, matplotlib, seaborn)
- **jupyter Notebook**
- **Tableau**
- **Markdown**
- **Git & GitHub**


## 🔍 Key Steps

### ✅ Step 1: Business Understanding
Defined the main business objective — identify lowest-risk aircraft using accident data.

### ✅ Step 2: Data Understanding
- Inspected 90,000+ records
- Assessed missing values
- Identified relevant columns (e.g., aircraft make, engine type, damage level, injury severity)

### ✅ Step 3: Data Preparation
- Dropped irrelevant fields (e.g., location coordinates, report dates)
- Handled missing values using `Unknown` or `mode` imputation
- Cleaned categorical variables (standardized text, grouped rare categories)

### ✅ Step 4: Exploratory Data Analysis (EDA)
Created key visualizations to understand relationships:
- **Aircraft Make vs. Injury Severity**
- **Flight Purpose vs. Injury Severity**
- **Engine Type vs. Injury Severity**
- **Trend of Accidents Over Time**
- **Aircraft Damage Distribution**

### ✅ Step 5: Targeted Analysis
Drilled down into top 10 makes, engine types, and flight purposes to assess risk severity based on fatal and serious injury rates.


## 📈 Tableau Dashboard

The dashboard includes:
- Interactive filters by **Aircraft Make**, **Year**, and **Injury Severity**
- Visuals for:
  - Aircraft Make vs. Injury Severity
  - Flight Purpose vs. Injury Severity
  - Engine Type vs. Injury Severity
  - Aircraft Damage Types

> Tableau link: **https://public.tableau.com/app/profile/fatuma.tari/viz/phase1projecttablaeu/Dashboard1**


## 💡 Business Recommendations

1. ✅ **Favor Makes with Low Fatality Rates**: Aircraft such as Grumman ACFT COR-SCHWEIZER, Airbus, STINSON, and Raven show lower fatal/serious outcomes.
2. ✅ **Avoid High-Risk Engine Types**: Certain engine types like turbo fan, reciprocating, and turbo jet are linked to higher severity outcomes.
3. ✅ **Focus on Commercial/Business Flights**: Flight purposes like instructional, aerial application and public aircraft(local) had significantly higher severe injury rates.


## 🏁 Conclusion

This project demonstrates how data cleaning, exploratory analysis, and business intelligence can guide strategic investment decisions in aviation.  
The insights and dashboard support **data-driven decision-making** for safe aircraft selection.


## Author

**Fatuma Tari**  
Data Science Trainee | www.linkedin.com/in/fatuma-abdi-tari-337b5a34b | Fatumatari@gmail.com

