
# 🌍 WHO COVID-19 Global Analysis

## 📌 Project Description
This project analyzes global COVID-19 trends using data provided by the **World Health Organization (WHO)**. It combines daily reported cases and deaths with global vaccination data to explore the pandemic's progression and the effectiveness of vaccination campaigns.

## 📊 Dataset Overview

- **COVID-19 Cases/Deaths**  
  Source: WHO  
  Includes daily reported cases and deaths by country and WHO region.

- **Vaccination Data**  
  Source: WHO  
  Includes total vaccinations, people vaccinated (1+ dose), booster doses, and per-capita vaccination rates.

## 🧪 Analysis Objectives
- Track and visualize global COVID-19 case and death trends.
- Compare regional and country-level pandemic impacts.
- Assess the impact of vaccination on cases and mortality rates.
- Forecast future cases and deaths using ARIMA time-series modeling.

## 🔍 Key Findings

### 📈 Global Peaks
- **Cases** peaked on **Dec 25, 2022** with over **44 million new cases** in a single day.
- **Deaths** peaked on **Jan 24, 2021** with over **103,000 reported deaths**.

### 💉 Vaccination Impact
- Deaths significantly declined following **mass vaccine rollouts**.
- **Booster doses** helped sustain protection, especially in vulnerable populations.

### 📉 Forecasting with ARIMA
- Predictive modeling shows a **gradual decline in deaths**.
- **New case trends** remain volatile due to variants and social/policy factors.

## 📦 Technologies Used
- Python: `pandas`, `matplotlib`, `scikit-learn`, `statsmodels`
- Jupyter Notebook
- WHO Public Datasets

## 📁 Files Included
- `WHO-COVID-19-global-data.csv` — Raw COVID-19 case/death data
- `vaccination-data.csv` — Global vaccination metrics
- `WHO_Covid19_Analysis.ipynb` — Full analysis notebook with visualizations, modeling, and insights

