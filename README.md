
# Seasonal Agriculture Performance Analysis 🌾

## VOIS AICTE Internship 2026–2027

### 📌 Project Overview

This project focuses on analyzing agricultural data across different seasons to identify meaningful patterns, trends, relationships, and variations in agricultural performance.

The project also uses machine learning techniques to predict agricultural yield based on relevant farm, environmental, soil, irrigation, and agricultural features.

---

## 🎯 Objectives

- Analyze agricultural performance across different seasons.
- Explore crop-wise and irrigation-wise patterns.
- Understand relationships between agricultural factors and crop yield.
- Perform exploratory data analysis (EDA).
- Build machine learning models for yield prediction.
- Compare model performance using standard evaluation metrics.
- Select the better-performing model for yield prediction.

---

## 📊 Dataset

The dataset contains agricultural farm-level records with information related to:

- State and District
- Crop
- Season
- Farm Area
- Rainfall
- Temperature
- Humidity
- Sunlight
- Soil characteristics
- Nutrient levels
- Irrigation method
- Fertilizer and pesticide usage
- Seed quality
- Crop yield
- Production
- Market price
- Cost and revenue
- Water usage
- Disease and pest risk

The dataset contains **4,000 records and 28 columns**.

> Note: The original dataset is not included in this repository if its distribution is restricted by the internship/provider.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Google Colab

---

## 🔍 Exploratory Data Analysis

The following analyses were performed:

- Season-wise distribution
- Crop-wise distribution
- Irrigation-method distribution
- Numerical feature distributions
- Crop-wise yield analysis
- Season-wise yield analysis
- Irrigation-method vs yield analysis
- Correlation analysis
- Outlier detection

---

## 🤖 Machine Learning

### Target Variable

`Yield_Tonnes_Ha`

### Models Used

1. Linear Regression
2. Random Forest Regression

Categorical features were encoded using One-Hot Encoding, followed by an 80:20 train-test split.

---

## 📈 Model Performance

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 1.9910 | 3.8395 | 0.9235 |
| Random Forest | 0.5011 | 1.7820 | 0.9835 |

### 🏆 Best Model

**Random Forest Regression**

It achieved the better performance with:

- **MAE:** 0.5011
- **RMSE:** 1.7820
- **R² Score:** 0.9835

---

## 📌 Key Outcome

The project demonstrates how agricultural and environmental data can be analyzed to understand factors associated with crop yield and how machine learning can be used for agricultural yield prediction.

---

## 📁 Project Structure

```text
Seasonal_agriculture_analysis/
│
├── Vaishnavi_Seasonal_agricultural_data_analysis.ipynb
├── README.md
└── data/
    └── seasonal_agriculture_performance_dataset.csv
