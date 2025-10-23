# 📊 Trader Behavior Insights Based on Market Sentiment

This project analyzes how crypto traders behave under different market sentiments such as Fear, Greed, Extreme Greed, and Extreme Fear. It combines historical trading data from Hyperliquid with the Bitcoin Fear & Greed Index to uncover patterns that can help design smarter trading strategies.

## 📁 Folder Structure

├── csv_files/
│ └── cleaned_trader_sentiment_data.csv
├── outputs/
│ └── *.png visualizations (charts and plots)
├── ds_report.pdf 
├── notebook_1.ipynb # Google Colab notebook with full analysis
└── README.md 


## 🧠 Project Objective

To explore how trader behavior (profitability, volume, trade direction, risk) aligns with overall crypto market sentiment. Key questions include:

- Do traders earn more in Greed than Fear?
- Is there more risk-taking in certain sentiments?
- Are there predictable behavior patterns?


## 📂 Datasets Used

1. **Hyperliquid Trader Data**
   - Fields: `Account`, `Coin`, `Execution Price`, `Size USD`, `Side`, `Closed PnL`, `Timestamp`, etc.

2. **Bitcoin Fear & Greed Index**
   - Fields: `Date`, `Classification` (Fear, Greed, Extreme Greed, etc.)


## 🔧 Key Steps

- Cleaned and formatted timestamp columns
- Merged both datasets by date
- Performed exploratory data analysis (EDA)
- Created visualizations to compare behavior across sentiments


## 📊 Visuals & Insights

- 📈 Boxplot of Closed PnL across sentiments
- 📊 Buy vs Sell trade volume
- ⚠️ % of High-Risk Trades in each sentiments
- 👤 Top Performing Traders chart
- ⏳ Weekly trend of average PnL

All visuals are saved in the `outputs/` folder.


## 📄 Final Report

See `ds_report.pdf` for a detailed summary of:
- Cleaning steps
- Charts
- Insights
- Final conclusions


## 🚀 Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Google Colab
- GitHub
- Google Docs (for PDF report)

---

## 🔗 Colab Notebook

 [Click here to view notebook](https://colab.research.google.com/drive/1Ae3OyHpbi2L8zD8iqWkiD30LGJEVMlim?usp=sharing)



