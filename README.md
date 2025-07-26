# 🌍 CO₂ Emission Forecasting and Predictions (Agro-Food Sector)

This project forecasts CO₂ emissions from the agro-food sector for major world regions using historical data from the past 30 years. The project uses [Facebook Prophet](https://facebook.github.io/prophet/) to make predictions and visualize trends.

---

## 📌 Project Goals

- 📊 Forecast CO₂ emissions for the next 5 years (2021–2025)
- 🌎 Group countries by continent and analyze region-wise trends
- ⚙️ Evaluate model accuracy using MAPE
- 📈 Provide raw and normalized trend plots for better interpretability

---

## 🗃️ Dataset

- **Source:** FAO agro-food CO₂ emissions data  
- **Period Covered:** 1990–2020  
- **Features:** Country, Item, Year, Emission Estimates  
- **Unit:** Unknown (possibly metric tons per year, based on scale)

---

## 🧠 Methodology

1. **Data Cleaning & Aggregation**
   - Grouped country-level data by continent
   - Aggregated total yearly emissions per continent

2. **Time Series Forecasting**
   - Used 25 years of data for training (1990–2014)
   - Used 5 years for testing (2015–2020)
   - Forecasted next 5 years (2021–2025) using Prophet

3. **Evaluation**
   - Calculated **MAPE (Mean Absolute Percentage Error)** for each continent

4. **Visualization**
   - Line chart of raw predicted emissions
   - Line chart of normalized emissions to compare trends



