# stock-strategy-analysis
Comparison of trading strategies vs long-term investing using Python
📊 Comparative Analysis of Trading Strategies vs Long-Term Investing
📌 Objective

This project aims to evaluate whether simple trading strategies can generate consistent profits using historical stock data, and to compare their performance with long-term investing.

📂 Dataset
Source: Yahoo Finance
Stock: Infosys (INFY.NS)
Time Period: 2000 – Present

Minimal missing values (~0.2%) were removed to ensure clean analysis.

⚙️ Strategies Implemented
1️⃣ Daily Trading

Buy at open and sell at close every day.

2️⃣ RSI Strategy

Buy when RSI < 30 and sell when RSI > 70 or after 3 days.

3️⃣ SMA Crossover Strategy

Buy when 20-day SMA crosses above 50-day SMA and sell on opposite crossover.

4️⃣ Bollinger Bands Strategy

Buy when price crosses below lower band and sell when it crosses above upper band.

5️⃣ Long-Term Investing

Buy once at the beginning and hold till the end.

📊 Key Results
Strategy	Type	Final Capital
Daily Trading	Random	~98
RSI	Mean Reversion	~33
SMA Crossover	Trend	~332
Bollinger Bands	Mean Reversion	~191
Investing	Passive	~1245
🔥 Key Insights
High win rate does not guarantee profitability (RSI failed despite high win rate).
Trend-following strategies performed better than mean reversion strategies.
Bollinger Bands outperformed RSI due to dynamic volatility adjustment.
Market behavior plays a critical role in strategy success.
Long-term investing significantly outperformed all trading strategies.
📈 Visualization

The project includes:

Capital growth curves for each strategy
Combined comparison plot
Final capital comparison bar chart

These visualizations clearly demonstrate the superiority of long-term investing in a trending market.

🏁 Conclusion

This project systematically evaluated multiple trading strategies and compared them with long-term investing.

While certain strategies like SMA crossover generated profits, none were able to outperform simple buy-and-hold investing.

This demonstrates the power of compounding and highlights that active trading does not always add value.

In strongly trending markets, long-term investing can be more effective than frequent trading.

🧠 Final Takeaway

Understanding market structure is more important than blindly applying trading strategies.

🛠️ Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
yFinance
