# COVID-19 Drug Discovery & Bioactivity Prediction

## 📌 Project Overview
This project focuses on Exploratory Data Analysis (EDA) and Machine Learning classification of COVID-19 related drug compounds, using biomedical data from Kaggle.

## 🛠️ Tech Stack
- **Python** (Pandas, Seaborn, Matplotlib, Scikit-Learn)
- **Environment**: Google Colab
- **Data Source**: Kaggle API (`divyansh22/drug-discovery-data`)

## 📊 Methodology & Key Findings
1. **EDA**: Analyzed chemical properties such as `MolecularWeight`, `XLogP`, and `RotatableBondCount`.
2. **Machine Learning**: Built a `RandomForestClassifier` to predict drug bioactivity (`pIC50`).
3. **Feature Importance**: Identified `MolecularWeight` as the primary feature driving model predictions.
