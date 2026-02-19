# trader-sentiment-analysis
Trader Performance vs Market Sentiment Analysis 

>>Objective

Analyze how Bitcoin sentiment (Fear/Greed) relates to trader behavior and performance on Hyperliquid.

>>Methodology

1.Aggregated trade-level data to daily trader-level metrics.

2.Computed daily PnL, win rate, trade frequency, trade size, and long bias.

3.Compared performance across sentiment regimes.

4.Segmented traders by frequency and consistency.

5.Applied clustering to identify behavioral archetypes.

>>Key Insights

Fear regimes exhibit higher volatility and trading activity.

High-frequency traders outperform low-frequency traders across regimes.

Inconsistent traders experience severe losses during Greed regimes.

>>Strategy Recommendations

Tighten risk controls for inconsistent traders during Greed regimes.

Allow higher activity for high-frequency traders during Fear regimes.

>>How to Run

Install required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

Open the notebook and run all cells sequentially.
