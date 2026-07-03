# Trader Performance vs Market Sentiment Analysis

## Project Objective

This project analyzes historical cryptocurrency trading data together with the Bitcoin Fear & Greed Index to understand how market sentiment influences trader performance and trading behaviour


## Dataset

1. Historical Trader Data
2. Bitcoin Fear & Greed Index


## Methodology

- Loaded both datasets
- Cleaned and formatted dates
- Merged datasets using trading date
- Calculated:
  - Average PnL
  - Win Rate
  - Worst Trade (Drawdown Proxy)
  - Trade Frequency
  - Position Size
- Performed trader segmentation
- Generated visualizations
- Proposed strategy recommendations


## Key Insights

- Greed periods produced the highest average profits.
- Fear periods showed the highest trading activity.
- Larger position sizes were observed during Extreme Greed and Fear.
- Infrequent traders achieved higher average profitability than frequent traders.


## Strategy Recommendations

1. Increase risk controls during Greed periods due to higher volatility.
2. Encourage disciplined trading during Fear periods instead of increasing trade frequency.


## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook


## Files

- Trader_Performance_vs_Market_Sentiment.ipynb
- Trader_Performance_vs_Market_Sentiment.html