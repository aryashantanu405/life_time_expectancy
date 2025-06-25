# WHO Life Expectancy Machine Learning Analysis

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-1.2.2-orange)
![Pandas](https://img.shields.io/badge/pandas-1.5.3-red)
![License](https://img.shields.io/badge/license-MIT-green)

A predictive modeling project analyzing life expectancy using WHO global health data.

## 🔗 Notebook Access
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15hxxpbUrf02BXQtBmw_-7QZw4KjLdrp-?usp=drive_link)

## 📌 Project Overview
This project examines the relationship between socioeconomic/health factors and life expectancy across 193 countries using:
- **Exploratory Data Analysis** (Correlation heatmaps, Feature distributions)
- **Machine Learning Models**:
  - Linear Regression (Baseline)
  - Decision Tree Regressor
  - Random Forest (Optional extension)
- **Interactive Prediction**:
  - Country-specific predictions
  - Custom scenario testing

## 🗂️ Dataset
**Source**: [WHO Global Health Observatory](https://www.who.int/data/gho)
- **Features** (22 indicators):
  - Health: `Adult Mortality`, `HIV/AIDS`, `Vaccination Coverage`
  - Economic: `Income Composition`, `Schooling Years`
  - Lifestyle: `Alcohol Consumption`, `BMI`
- **Target**: `Life expectancy at birth`
- **Time Span**: 2000-2015

