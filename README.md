# Agricultural-Material

# 🌾 Agricultural Raw Materials Price Analysis (1990–2020)

## 📌 Overview
This project explores agricultural raw material prices from 1990 to 2020 using a Kaggle dataset.

The goal is to understand price behavior, volatility, and relationships between different raw materials over time.

Dataset:  
https://www.kaggle.com/datasets/kianwee/agricultural-raw-material-prices-19902020

---

## 🎯 Objectives
- Analyze long-term price trends of agricultural raw materials  
- Identify low and high-priced commodities  
- Measure price volatility using percentage change  
- Explore correlations between materials using a heatmap  
- Classify materials based on price behavior  

---

## 📊 Key Insights

- 🌱 Cotton is the lowest-priced raw material over the years  
- 🌲 Soft sawn timber shows the highest price variation (>60%)  
- 📉 Plywood shows the lowest variation (<20%)  
- 🧺 Fine wool and hardwood logs show strong price fluctuations  
- 📊 Clear grouping exists between low and high-priced materials  

---

## 📈 Exploratory Data Analysis

The analysis includes:

- Time series analysis of raw material prices  
- Percentage change computation  
- Volatility estimation (standard deviation of returns)  
- Interquartile range (IQR) analysis  
- Correlation matrix (heatmap)  

---

## 📦 Price Classification

### 💰 Low-priced materials:
- Cotton  
- Leather  
- Soft logs  
- Hardwood logs  
- Soft sawn timber  
- Rubber  

### 💎 High-priced materials:
- Coarse wool  
- Copra  
- Fine wool  
- Hardwood sawn timber  
- Wood pulp  
- Plywood  

---

## 🔬 Statistical Concepts Used

- Mean, median, quartiles (Q1, Q3)  
- Interquartile range (IQR)  
- Outlier detection  
- Percentage change (returns)  
- Correlation analysis  

---

## 🔮 Future Work

- Predict raw material prices using time series models (ARIMA / LSTM)  
- Identify substitution relationships between materials  
- Build a forecasting model for procurement planning  
- Optimize raw material selection based on volatility and cost  
- Combine economic indicators with price trends  

---

## 🛠 Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/agricultural-raw-material-analysis
cd agricultural-raw-material-analysis
pip install -r requirements.txt
jupyter notebook
