# 🎓 Unemployment Rate Analysis - India (Exploratory Data Analysis)

## ✅ Project Overview

This project performs an in-depth exploratory data analysis (EDA) of unemployment trends in India using a CSV dataset containing regional unemployment statistics. We visualize and interpret key trends over time and across regions, and assess the potential impact of COVID-19 on employment levels.

---

## ⚙️ Technologies Used

- **Python**
- **Pandas** for data handling  
- **Matplotlib** and **Seaborn** for visualization

---

## 📊 Dataset Insights

- The dataset includes columns such as `Region`, `Date`, `Unemployment Rate`, and other employment-related indicators.
- The data spans multiple months around the COVID-19 outbreak period, allowing comparison before and after March 2020.

---

## 🔄 Workflow Summary

### 1. Data Loading
- Loaded data using `pandas.read_csv()`.
- Previewed shape, column names, and summary statistics.

### 2. Data Cleaning
- Checked for missing values.
- Applied forward-fill (`ffill`) strategy to handle null values.
- Converted `Date` column to datetime format for temporal analysis.

### 3. Unemployment Over Time
- A line plot shows the trend of unemployment rate across all dates.
- Highlights visible spikes in unemployment during certain months of 2020.

### 4. Unemployment by Region
- A boxplot provides insights into the distribution of unemployment across various Indian regions.
- Some regions show higher variability or consistently higher unemployment.

### 5. COVID-19 Impact Analysis
- Separated the dataset into two time periods: **Before** and **After March 2020**.
- Calculated and printed the average unemployment rates for both periods.
- Identified a clear increase in unemployment after the onset of COVID-19.

### 6. Monthly/Seasonal Trends
- Extracted month from the `Date` column.
- Created a bar plot to show average unemployment rates per month.
- Allows us to understand seasonal hiring or layoffs, if any patterns exist.

---

## 🤔 Key Insights

- **Unemployment spiked** in mid-2020, aligning with lockdowns and the initial wave of COVID-19.
- **Regional disparities** exist: some states consistently report higher unemployment.
- **Seasonal effects** may play a role in employment levels.

---

## 🚀 Future Scope

- Correlate unemployment rates with **education levels**, **GDP**, or **sector-wise data**.
- Apply **machine learning** models to predict future unemployment rates.
- Include **interactive dashboards** (e.g., using Plotly or Tableau).

---

## 📚 Author

**Arooj Gull**  
Intern at CodeAlpha  
**Task:** Exploratory Data Analysis - Unemployment in India  
**Date:** July 2025
