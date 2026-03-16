# 📈 Gold Price Historical Data Analysis (2000–2026)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualizations-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Heatmap-9cf)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📌 Project Overview
An exploratory data analysis (EDA) of gold futures prices spanning 
26 years (2000–2026), uncovering long-term trends, seasonal patterns, 
volatility, and market behavior during major global events like the 
2008 Financial Crisis, COVID-19, and recent geopolitical tensions.

---

## 📂 Dataset
- **Source:** [Kaggle — Gold Price Historical Data (2000–2026)](https://www.kaggle.com/datasets/hamzasamiullah/gold-price-historical-data-2000-2026)
- **File used:** `golddata.csv` (daily data)
- **Rows:** 6,383 daily observations
- **Period:** August 2000 – February 2026
- **Features:** 20 columns including OHLCV, Moving Averages, Volatility

---

## 🎯 Objectives
- Analyze 26 years of gold price trends
- Identify seasonal and day-of-week patterns
- Study market volatility during major global events
- Understand relationships between price features

---

## 🛠️ Tools & Libraries
| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data cleaning & manipulation |
| Matplotlib | Visualizations |
| Seaborn | Correlation heatmap |
| Jupyter Notebook | Development environment |

---

## 📊 Analysis Performed

### 1. 🧹 Data Cleaning
- Handled missing values in `Price_Change` and `Price_Change_Percent`
- Converted `DateTime` to UTC format
- Retained warm-up nulls in MA and Volatility columns naturally

### 2. 🔍 Exploratory Data Analysis
- Shape, dtypes, null check, summary statistics
- Year-over-year and quarterly breakdowns

### 3. 📈 Visualizations
- Gold price over time (2000–2026)
- Average monthly trading volume
- Daily price change % distribution
- Average price by month (seasonality)
- Average price by day of week
- Yearly average price (2000–2026)
- Price with moving averages (MA_7, MA_30, MA_365)
- 30-day rolling volatility

---

## 💡 Key Findings
- Gold has grown **~16x** from \$300 (2000) to \$5000+ (2026)
- Prices **spike during crises** — 2008 Financial Crisis, 
  COVID-19 (2020), and 2025–2026 geopolitical tensions
- **January** is historically the strongest month for gold prices
- **Friday** shows the highest average closing price of the week
- Volatility peaked at **~3.2%** during the 2008 financial crisis
- MA_365 reveals three clear phases:
  - 📈 Bull run (2000–2012)
  - ➡️ Consolidation (2012–2019)
  - 🚀 Explosive bull run (2020–2026)

---

## 📁 Project Structure
```
gold-price-analysis/
│
├── gold price analysis.ipynb   # Main Jupyter notebook
└── README.md                   # Project documentation
```

---

## 🚀 How to Run
1. Clone the repository
```bash
git clone https://github.com/diyakath8/gold-price-analysis.git
```
2. Install dependencies
```bash
pip install pandas matplotlib seaborn jupyter
```
3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/hamzasamiullah/gold-price-historical-data-2000-2026) and place it in the project folder

4. Open the notebook
```bash
jupyter notebook "gold price analysis.ipynb"
```

---

## 👩‍💻 Author
**Diya Kathuria**  
Aspiring Data Analyst  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/diyakathuria/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/diyakath8)
