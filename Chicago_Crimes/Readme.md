# 🔮 Prophettime Part 1: 📊 Chicago Crime Time Series Forecasting

This notebook analyzes and forecasts **Chicago crime trends** using time series data and the powerful `Prophet` library by Meta. The data spans multiple years and includes various types of crimes.

---

## 📦 Key Features

- 🔍 Merges and cleans crime datasets (2005–2017)
- 🧹 Drops unnecessary and null columns
- 🕰️ Parses and standardizes datetime formats
- 📈 Resamples and visualizes crime data (monthly, quarterly, yearly)
- 🔮 Uses `Prophet` to forecast future crime counts
- 📊 Generates trend and seasonality plots

---

## 🧰 Libraries Used

- `pandas` for data handling
- `matplotlib` and `seaborn` for visualization
- `Prophet` for forecasting

---

## 📁 Data Source

Multiple CSV files representing crime data over time:
- `Chicago_Crimes_2005_to_2007.csv`
- `Chicago_Crimes_2008_to_2011.csv`
- `Chicago_Crimes_2012_to_2017.csv`

---

## 📈 Workflow Summary

1. 📂 Load and merge multiple CSVs
2. ❌ Remove irrelevant or corrupt rows
3. 🧠 Feature engineering on datetime and crime types
4. 🔍 Visualize top crime categories
5. 🕵️‍♂️ Forecast future crime trends using Prophet
6. 📉 Visualize forecasts and components

---

## ▶️ How to Run

```bash
pip install prophet pandas matplotlib seaborn
