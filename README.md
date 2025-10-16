# Silver Price Forecast: LSTM + XGBoost

![Silver Price Forecast (LSTM + XGBoost)](/mnt/data/Silver-Price-Prediction.png)

## 🔍 Project Overview

This project forecasts silver prices over **1-, 2-, and 5-year horizons**, using historical data to capture crisis behavior and recent trends. The hybrid model combines **LSTM** for temporal patterns and **XGBoost** to correct residuals using external indicators (e.g. gold, USD index).

## 📈 Chart & Key Findings

- **Current Price (2025)**: ~ 99 USD/oz  
- **Forecast for 2030**: ~ 158 USD/oz — implies ~1.6× growth over 5 years  
- **Trend**: Strong upward slope in the 5-year forecast, reflecting extrapolation of historical cycles and momentum

### Key Insights

1. **Significant Upside Expected**  
   Based on learned patterns, silver may rise by ~ 60% in USD terms by 2030.

2. **Drivers of Model Predictions**  
   The model primarily learns from past silver price dynamics, gold–USD relationships, and volatility regimes, including crisis periods (e.g. 2008) captured in the training range.

3. **Factors Not Included That Could Shift the Path**  
   - Industrial & technological demand surges  
   - Supply constraints or mining disruptions  
   - Major monetary/fiscal policy shifts  
   - Geopolitical or systemic shocks  
   - Currency & exchange rate changes  
   - Speculative and sentiment-driven flows

## 🧩 How to Use This Forecast

- Treat it as a **scenario-based projection**, not a guarantee  
- Use alongside fundamental research, demand/supply analysis, and currency forecasts  
- For local analysis (e.g. in INR), always layer USD/INR projection risk on top  

## 📈 Next Steps & Enhancements

- Incorporate **demand data, mining supply data, inflation & interest rates**  
- Add **confidence intervals** or **Monte Carlo simulations** to capture uncertainty  
- Backtest predictions on crisis windows (e.g. 2008, 2020) to validate robustness  

## 🛠 Tech Stack & Files

- **Models**: LSTM (TensorFlow/Keras) + XGBoost  
- **Data**: Yahoo Finance (silver, gold, USD index)  
- **Scripts / Notebooks**: `silver_forecast.ipynb`, `data_preprocess.py`, etc.  
- **Chart**: `Silver-Price-Prediction.png` embedded in this README  

---

*Disclaimer: All forecasts are for informational purposes. Real assets are influenced by real-world contingencies not captured by any model.*  
