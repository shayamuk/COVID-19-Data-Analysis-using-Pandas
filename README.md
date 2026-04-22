# 📊 COVID-19 Data Analysis using Pandas & Matplotlib

## 📌 Overview

This project contains a small dataset of Covid 19 and it performs exploratory data analysis (EDA) using Pandas.

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

## Key Insights

Italy and Spain recorded the highest deaths during the observed period
Some regions show very low minimum deaths, indicating early-stage outbreak data

## ⭐ If you find this useful
Feel free to ⭐ the repository or fork it!

---
