# Application Project – LEAP x ORA Cash

This repository contains the work developed by **Mouad Elansari** and **Mohamed-Rida Elhani** as part of the **LEAP project** in collaboration with **ORA Cash**. The objective of this project is to build a **predictive model** that can identify users who are at risk of **churn**, in order to help ORA Cash improve user retention strategies.

---

## 🔍 Project Overview

The project involves the following key phases:

- **Exploratory Data Analysis (EDA)**
- **Data Cleaning & Feature Engineering**
- **Model Training and Evaluation**

---

## 📁 Repository Contents

| File / Folder | Description |
|---------------|-------------|
| `Transactions_descriptions.csv` | Contains metadata and descriptions of each feature in the transactions dataset. |
| `Users_descriptions.csv` | Contains metadata and descriptions of user-level features. |
| `EDA_Phase.ipynb` | Full EDA process: data cleaning, exploratory analysis, feature engineering, and correlation analysis. This notebook is **read-only** — there's no need to rerun it. |
| `Ora_Data.csv` | Cleaned and preprocessed dataset resulting from the EDA phase. This is the **final dataset** used for modeling. |
| `Ora_Data_Descriptions.csv` / `.xlsx` | Contains the description and meaning of each feature in the final dataset. |
| `ML+phase.ipynb` | Initial model training, evaluation, and performance analysis using multiple algorithms. |

---

## 📊 Modeling Details

In the modeling phase, we applied several machine learning techniques, including:

- **Random Forest** (with cross-validation)
- **XGBoost**
- **CatBoost**

We achieved promising results, including a **recall score of up to 80%**, despite challenges related to class imbalance (churned users are underrepresented).

---

## ⚙️ Requirements

To run this project, ensure you have the following Python libraries installed:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `xgboost`
- `catboost`

You can install the dependencies via pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost catboost
