# Sales Forecasting and Data Analysis using Excel

## Project Overview
This project focuses on analysing historical sales data using Quantitative Techniques and Microsoft Excel. The main objective is to identify relationships between marketing spend, product pricing, and sales demand using statistical tools such as correlation, regression, trend analysis, and forecasting.

The project demonstrates how Excel can be used for business analytics and decision-making through data cleaning, visualization, and predictive analysis.

---

# Objectives
- Perform data cleaning using Box & Whisker Plot
- Identify and remove outliers
- Analyse correlation between variables
- Develop regression equations using Excel
- Forecast future demand
- Create trendline visualizations
- Generate business insights and recommendations
- Build an interactive dashboard for analysis

---

# Dataset Information
The dataset contains historical sales information including:
- Year
- Month
- SKU/Product
- Marketing Spend
- Product Price
- Sales Units

Total observations: 351 records

---

# Tools & Techniques Used

## Software
- Microsoft Excel

## Quantitative Techniques
- Correlation Analysis
- Regression Analysis
- Forecasting
- Trend Analysis
- Box & Whisker Plot
- Pivot Tables
- Dashboard Visualization

---

# Data Cleaning Process
Outliers were identified using Box & Whisker Plot and Interquartile Range (IQR) analysis.

### IQR Formula
Q3 − Q1

### Outlier Limits
- Lower Bound = Q1 − 1.5(IQR)
- Upper Bound = Q3 + 1.5(IQR)

Extreme observations outside the whiskers were removed to improve forecasting accuracy.

---

# Correlation Analysis

| Variables | Correlation |
|---|---|
| Marketing Spend & Sales | 0.9804 |
| Price & Sales | -0.0899 |

### Interpretation
- Marketing Spend has a very strong positive relationship with sales.
- Price has a weak negative relationship with sales.

---

# Regression Model

## Regression Equation

Sales = 52.89 + 0.049(Marketing Spend) − 1.16(Price)

### Interpretation
- Increasing marketing spend increases sales.
- Increasing price slightly reduces sales.

---

# R Square Analysis

R² ≈ 0.97

This indicates that approximately 97% of the variation in sales is explained by marketing spend and price.

---

# Forecasting
Future sales demand was predicted using:
- Trendline Analysis
- Forecasting Functions in Excel
- Pivot Tables

Forecasts were generated for:
- Next Month
- Next Quarter
- Next Year

---

# Dashboard Features
The project also includes an interactive Excel dashboard containing:
- KPI cards
- Trendline charts
- Box & Whisker Plot
- Scatter plots
- Forecast visualizations
- Pivot table filters and slicers

---

# Key Insights
1. Marketing expenditure strongly affects sales growth.
2. Product pricing has relatively low influence on demand.
3. Sales show a positive growth trend over time.

---

# Recommendations
- Increase marketing investments during high-demand periods.
- Use forecasting models for inventory planning.
- Focus on high-performing products.
- Avoid unnecessary price increases.

---

# Project Structure

```bash
📂 Sales-Forecasting-Project
│
├── 📄 README.md
├── 📊 Raw_Data.xlsx
├── 📊 Cleaned_Data.xlsx
├── 📈 Dashboard.xlsx
├── 📑 Project_Report.pdf
├── 📽️ Presentation.pptx
└── 📷 Screenshots/
