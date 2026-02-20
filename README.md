# trader-sentiment-analysis
Comprehensive analysis of trader behavior and performance across market sentiment regimes (Fear vs Greed) using statistical analysis, visualization, and modeling.


# Trader Performance vs Market Sentiment Analysis

## 📌 Problem Statement
This project analyzes how crypto trader performance changes across different Bitcoin market sentiment regimes (Fear vs Greed).

The goal is to understand whether market psychology influences:
- Profitability
- Risk exposure
- Trading frequency
- Drawdowns

---

## 🎯 Objectives
- Compare trader PnL across sentiment regimes
- Evaluate risk-adjusted performance
- Analyze behavioral changes during Fear vs Greed
- Identify volatility and drawdown patterns
- Perform trader segmentation

---

## 📊 Methodology
1. Data cleaning & preprocessing
2. Time alignment between trade data and sentiment index
3. Feature engineering (daily PnL, volatility, risk metrics)
4. Statistical comparison across regimes
5. Visualization and behavioral analysis

---

## 🔍 Key Insights
- Trading activity increases during Greed regimes.
- Drawdowns expand significantly during Fear periods.
- Risk-adjusted returns vary across sentiment classifications.
- Consistent traders maintain stable volatility profiles.

---

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Repository Structure

```
trader-sentiment-analysis
│
├── data/
├── notebooks/
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Dataset
The raw trading dataset (~45MB) is not included due to GitHub file size limits.

To reproduce:
Place:
- historical_data.csv
- fear_greed_index.csv

inside the `data/` folder.

---

##  How to Run
1. Clone the repository  
2. Install dependencies:
   pip install -r requirements.txt  
3. Open the notebook in Jupyter
