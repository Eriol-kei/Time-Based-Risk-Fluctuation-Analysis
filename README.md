# ⏰ Time-Based Risk Fluctuation Analysis (BRFSS 2019–2023)

This project analyzes how **diabetes risk patterns change over time** using Behavioral Risk Factor Surveillance System (BRFSS) datasets from **2019 to 2023**. It uses machine learning models (XGBoost classifiers), applies class balancing (SMOTE), and evaluates performance through F1-score optimized threshold tuning — all executed in **Google Colab**.

---

## 📌 Project Goals

- ⏳ **Track fluctuations in risk prediction** across multiple years
- 🧠 Use XGBoost classifiers for yearly classification
- ⚖️ Apply SMOTE to handle class imbalance
- 🧪 Tune probability threshold per year for best F1 score
- 📊 Visualize confusion matrices and feature importances

---

## 📁 Datasets

This project uses the publicly available BRFSS survey data from [CDC's official website](https://www.cdc.gov/brfss/annual_data/annual_data.htm). These files are in `.XPT` (SAS transport) format.

- **Files required**:
  - `LLCP2019.XPT`
  - `LLCP2020.XPT`
  - `LLCP2021.XPT`
  - `LLCP2022.XPT`
  - `LLCP2023.XPT`
