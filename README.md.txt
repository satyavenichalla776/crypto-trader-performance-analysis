# 📊 Crypto Trader Performance Analysis using Machine Learning

## 📌 Project Overview

This project analyzes cryptocurrency trader performance by combining Bitcoin market sentiment with historical trading data. The goal is to understand how market sentiment influences trading outcomes and to build machine learning models that predict whether a trade will be profitable.

---

## 🎯 Objectives

- Analyze the relationship between Bitcoin market sentiment (Fear/Greed) and trader profitability.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Apply statistical tests to validate insights.
- Build and evaluate machine learning models.
- Generate business recommendations for improving trading strategies.

---

## 📂 Dataset

The project uses two datasets:

1. **Bitcoin Market Sentiment Dataset**
   - Date
   - Classification (Fear / Greed)

2. **Historical Trader Dataset**
   - Account
   - Symbol
   - Execution Price
   - Trade Size
   - Side
   - Direction
   - Closed PnL
   - Leverage
   - Timestamp
   - Other trading information

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Scikit-learn
- Google Colab
- GitHub

---

## 📊 Project Workflow

```
Data Collection
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis
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

## 📈 Exploratory Data Analysis

The EDA includes:

- Profit Distribution
- Market Sentiment Distribution
- Profit vs Market Sentiment
- Closed PnL Distribution
- Top Traded Coins
- Buy vs Sell Analysis
- Trading Activity by Hour
- Trading Activity by Day
- Correlation Heatmap

---

## 📉 Statistical Analysis

The following statistical tests were performed:

- Descriptive Statistics
- Correlation Analysis
- Independent T-Test
- Chi-Square Test
- ANOVA Test

---

## 🤖 Machine Learning Models

The following classification models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

---

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------|---------:|----------:|--------:|----------:|---------:|
| Logistic Regression | 92.48% | 85.10% | 98.99% | 91.52% | 95.65% |
| Decision Tree | 99.00% | 98.79% | 98.78% | 98.78% | 98.97% |
| Random Forest | 98.97% | 98.27% | 99.24% | 98.75% | 99.92% |

---

## ⭐ Key Findings

- Market sentiment influences trader behavior and profitability.
- Trade size, execution price, and trading direction are important predictors of profitable trades.
- Random Forest achieved the best overall performance based on ROC-AUC and generalization capability.
- Machine learning can be used as a decision-support tool for cryptocurrency trading.

---

## 💼 Business Recommendations

- Monitor Bitcoin market sentiment before opening new positions.
- Consider trade size and execution price when evaluating trades.
- Use predictive models to support trading decisions.
- Continuously retrain models with new market data to adapt to changing market conditions.

---

## 📁 Project Structure

```
Crypto-Trader-Performance-Analysis/
│
├── data/
│   └── cleaned_trader_sentiment.csv
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

- Perform hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
- Deploy the trained model using Streamlit or Flask.
- Integrate real-time cryptocurrency market data.
- Compare additional machine learning algorithms such as XGBoost or LightGBM.

---

## 👩‍💻 Author

**Satyaveni Challa**

Aspiring Data Scientist | Machine Learning Enthusiast

GitHub: https://github.com/satyavenichalla776
