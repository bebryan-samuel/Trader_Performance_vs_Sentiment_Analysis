# Trader Performance vs Market Sentiment Analysis

## 📊 Project Overview
This project analyzes the relationship between **Bitcoin market sentiment** (Fear & Greed Index) and **trader performance** using historical trading data from Hyperliquid.

The goal is to explore hidden patterns, visualize trends, and deliver actionable insights to help traders make smarter decisions.

---

## ✅ Dataset Description

### 1. Fear & Greed Index Dataset
- **Columns**: 
    - `timestamp`, `value`, `classification` (Fear/Greed), `date`

### 2. Historical Trader Data
- **Columns**:
    - `Account`, `Coin`, `Execution Price`, `Size Tokens`, `Size USD`, `Side`, `Timestamp IST`, `Start Position`, `Direction`, `Closed PnL`, `Fee`, `Timestamp`, etc.

---

## 🚀 Key Features
- Data preprocessing and merging based on dates
- Visualizations using **Matplotlib** and **Seaborn**:
    - Time series of Fear & Greed index
    - Distribution of trader Closed PnL
    - Boxplot of sentiment classification vs Closed PnL
    - Correlation heatmap between sentiment and performance
- Correlation analysis between market sentiment and trader profitability
- Clear insights summary and strategic recommendations

---

## 📁 Files
- `Trader_Performance_vs_Sentiment_Analysis.ipynb`: Jupyter Notebook with full analysis and visualizations
- `fear_greed_index.csv`: Market sentiment dataset
- `historical_data.csv`: Trader historical data
- `merged_trader_sentiment_data.csv`: (Optional) Processed dataset combining both sources

---

## 🛠️ How to Run
1. Clone the repository:
    ```bash
    git clone <repository_url>
    ```
2. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Trader_Performance_vs_Sentiment_Analysis.ipynb
    ```
3. Run the notebook cells sequentially.

---

## 📊 Insights Summary
- Weak/moderate correlation between Fear/Greed Index and Closed PnL.
- Extreme sentiment periods show higher variability in performance.
- Recommendation: Avoid high-leverage trading during extreme market sentiment to reduce risk.

---

## ⚡ Author
[Your Name]  
[Your Email or GitHub Profile Link]

---

## 📜 License
This project is open-source under the MIT License.
