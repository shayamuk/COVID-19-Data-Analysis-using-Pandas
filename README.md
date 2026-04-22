# 📊 COVID-19 Data Analysis using Pandas & Matplotlib

## 📌 Overview
This project performs exploratory data analysis (EDA) on COVID-19 dataset using Pandas.

The goal is to extract meaningful insights such as:
- Regions with highest/lowest deaths
- Trends in confirmed, recovered, and death cases
- Data cleaning and handling missing values

---

## 🛠️ Tech Stack
- Python
- Pandas
- Matplotlib

---

## 🧹 Data Cleaning
- Filled missing values in `State` column using:
  ```python
  data.loc[:, 'State'] = data['State'].fillna('Unknown')

  ## 📊 Key Analysis Performed
