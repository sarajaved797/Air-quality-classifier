# 🌍 What is in the Air?
### Classifying Global Air Quality with Pollution & Weather Signals”

---

## 📌 Project Overview

This project uses real-world global air quality and weather data to classify air pollution risk levels across major cities. Instead of just predicting raw pollutant values, we translate scientific measurements into human-impactful AQI categories — the labels that influence how people feel, behave, and protect themselves.

🔮 The goal:  
**Predict the Air Quality Index (AQI) Category** — such as "Good", "Moderate", or "Unhealthy" — using current pollution + weather data.

---

## 🎯 Key Objectives

- Clean and enrich global air quality data with AQI scoring logic, seasonal info, and geographic mapping
- Engineer predictive features (rolling averages, pollutant ratios, weather interactions)
- Train a classification model to predict AQI Category
- Evaluate and interpret model performance
- Frame findings in emotionally intelligent, human-centered terms

---

## 🧠 Why This Matters

Most people don't respond to PM2.5 = 162.  
They respond to:  
> 🔴 “Unhealthy — Avoid outdoor activity”

This project bridges the gap between **data and decision-making**, showing how analytics can inform public behavior and health policy.

---

## 🧪 Tools & Skills Used

- Python (Pandas, NumPy, Scikit-learn)
- Feature Engineering
- Classification Models (Decision Tree, Random Forest, etc.)
- Data Cleaning & EDA
- Matplotlib / Seaborn for minimal visuals
- Git & GitHub for version control

---

## 🧱 Project Structure

```bash
├── data/
│   └── raw_air_data.csv
│   └── enriched_air_data.csv
├── notebooks/
│   └── 01_data_cleaning_enrichment.ipynb
│   └── 02_model_training_evaluation.ipynb
├── README.md
└── requirements.txt
