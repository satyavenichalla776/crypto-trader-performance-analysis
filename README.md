# crypto-trader-performance-analysis
Machine Learning project analyzing cryptocurrency trader performance using Bitcoin market sentiment.
# 📊 Crypto Trader Performance Analysis using Machine Learning

## 📌 Project Overview

This project analyzes cryptocurrency trader performance by combining Bitcoin market sentiment with historical trading data. The objective is to explore how market sentiment influences trader profitability and to build machine learning models that predict whether a trade will be profitable.

The project follows a complete data science workflow, including data cleaning, exploratory data analysis (EDA), statistical analysis, feature engineering, machine learning model development, and business recommendations.

---

## 🎯 Project Objectives

* Analyze the relationship between Bitcoin market sentiment (Fear/Greed) and trader profitability.
* Clean and preprocess trading data.
* Perform Exploratory Data Analysis (EDA).
* Validate insights using statistical tests.
* Build and compare multiple machine learning models.
* Generate business recommendations based on the findings.

---

## 📂 Dataset Information

This project is based on two datasets:

### 1. Bitcoin Market Sentiment Dataset

* Date
* Classification (Fear / Greed)

### 2. Historical Trader Dataset

* Account
* Symbol
* Execution Price
* Trade Size
* Side
* Direction
* Closed PnL
* Leverage
* Timestamp
* Other trading-related information

> **Note:** The original datasets are large and exceed GitHub's recommended file size limits. Therefore, this repository contains a **sample/cleaned dataset** for demonstration purposes. The notebooks and code are designed to work with the complete dataset as well.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy
* Scikit-learn
* Google Colab
* GitHub

---

## 📊 Project Workflow

```
Data Collection
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis (EDA)
        ↓
Statistical Analysis
        ↓
Machine Learning
        ↓
Model Evaluation
        ↓
Business Recommendations
```

---

## 📈 Exploratory Data Analysis (EDA)

The project includes analysis of:

* Profit Distribution
* Market Sentiment Distribution
* Profit vs Market Sentiment
* Closed PnL Distribution
* Top Traded Coins
* Buy vs Sell Analysis
* Trading Activity by Hour
* Trading Activity by Day
* Correlation Analysis

---

## 📉 Statistical Analysis

The following statistical techniques were used:

* Descriptive Statistics
* Correlation Analysis
* Independent T-Test
* Chi-Square Test
* ANOVA Test

---

## 🤖 Machine Learning Models

Three classification models were developed and compared:

* Logistic Regression
* Decision Tree
* Random Forest

---

## 📊 Model Performance

| Model               | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
| ------------------- | -------: | --------: | -----: | -------: | ------: |
| Logistic Regression |   92.48% |    85.10% | 98.99% |   91.52% |  95.65% |
| Decision Tree       |   99.00% |    98.79% | 98.78% |   98.78% |  98.97% |
| Random Forest       |   98.97% |    98.27% | 99.24% |   98.75% |  99.92% |

**Final Selected Model:** Random Forest

---

## ⭐ Key Findings

* Market sentiment has a measurable impact on trader behavior and profitability.
* Trade size, execution price, and trading direction are among the most influential features.
* Random Forest achieved the best overall performance based on predictive accuracy and ROC-AUC.
* Machine learning can effectively support cryptocurrency trading decisions.

---

## 💼 Business Recommendations

* Incorporate market sentiment into trading strategies.
* Consider trade size and execution price before entering positions.
* Monitor high-performing cryptocurrencies based on historical performance.
* Retrain machine learning models periodically using updated market data.

---

## 📁 Project Structure

```
Crypto-Trader-Performance-Analysis/
│
├── data/
│   └── sample_cleaned_trader_sentiment.csv
│
├── notebooks/
│   ├── 01_Data_Loading_and_Cleaning.ipynb
│   ├── 02_Exploratory_Data_Analysis.ipynb
│   ├── 03_Statistical_Analysis.ipynb
│   └── 04_Machine_Learning.ipynb
│
├── images/
│
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

* Perform hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
* Deploy the trained model using Streamlit.
* Integrate real-time cryptocurrency market data.
* Evaluate additional machine learning algorithms such as XGBoost and LightGBM.

---

## 👩‍💻 Author

**Satyaveni Challa**

Aspiring Data Scientist | Machine Learning Enthusiast

GitHub: https://github.com/satyavenichalla776

---

## ⭐ Acknowledgement

This project was developed as part of a machine learning portfolio to demonstrate end-to-end data science skills, including data preprocessing, visualization, statistical analysis, predictive modeling, and business insight generation.
