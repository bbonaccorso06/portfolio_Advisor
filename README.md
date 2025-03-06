📈 AI-Powered Portfolio Tracker

🚀 Overview

The AI-Powered Portfolio Tracker is an advanced stock monitoring tool that uses real-time data, market news, AI-driven sentiment analysis, and macroeconomic indicators to intelligently recommend buy, sell, or rebalance actions for your investment portfolio. It continuously evaluates your stock positions, tracks sector performance, and delivers actionable insights via email alerts.

🎯 Features

✅ Stock Price & Trend Monitoring

Fetches real-time stock prices using Yahoo Finance, Alpha Vantage, and Finnhub.

Tracks daily, weekly, monthly, and 3-month price changes.

Identifies short-term vs. long-term trends to avoid emotional trading.

📊 Market Sentiment & News Analysis

Fetches news from multiple sources (Finnhub, NewsAPI, etc.).

Uses AI-driven sentiment analysis to classify market trends as Bullish, Neutral, or Bearish.

Filters news relevant to your portfolio holdings.

🌍 Macroeconomic Data Tracking

Monitors inflation (CPI), interest rates, and GDP growth.

Uses economic conditions to adjust portfolio strategies.

🔄 Sector Rotation & Performance Analysis

Tracks Tech, Healthcare, Financials, Energy, and Consumer Discretionary.

Detects capital flows across industries to suggest potential sector shifts.

📧 Automated Email Alerts

Sends portfolio health reports to your email.

Provides clear rebalancing suggestions based on price movements and market conditions.

🛠️ Installation & Setup

1️⃣ Clone the Repository

$ git clone https://github.com/your-repo/portfolio-tracker.git
$ cd portfolio-tracker

2️⃣ Install Dependencies

$ pip install -r requirements.txt

3️⃣ Set Up API Keys

Create an .env file and add the following keys:

SENDGRID_API_KEY=your-sendgrid-key
ALPHA_VANTAGE_API_KEY=your-alpha-vantage-key
FINNHUB_API_KEY=your-finnhub-key
NEWSAPI_KEY=your-newsapi-key

4️⃣ Run the Tracker

$ python tracker.py

📊 How the AI Works

1️⃣ Portfolio Monitoring

Watches daily, weekly, monthly, and 3-month price trends.

Threshold-based triggers:

Weekly change > 5% → Monitor 🚨

Monthly change > 10% → Consider rebalancing 🔄

3-month change > 15% → Strong action required 🔥

2️⃣ Market & Economic Research

Fetches real-time financial news & social sentiment.

Uses TextBlob AI to detect bullish vs. bearish sentiment.

Tracks macroeconomic factors (inflation, interest rates, GDP).

3️⃣ Intelligent Buy/Sell Recommendations

🔵 BUY: If a stock is undervalued, has strong fundamentals, and improving sentiment.
🟡 HOLD: If market conditions support stability.
🔴 SELL: If a stock is overbought, declining in strength, or sector rotation is required.

📩 Example Email Report

📊 Portfolio Health Report:
Total Portfolio Value: $10,520.45
Total Invested: $10,000.00
Overall Portfolio Return: +5.2%

🚨 Stock Alerts:
- AAPL has increased 12% in the past month.
- TSLA dropped 8%—consider monitoring closely.

🔄 Suggested Actions:
- Consider rebalancing TSLA due to recent losses.
- Hold AAPL as it is performing well.

📊 Market Sentiment: Bullish - Positive trends observed.
📊 Economic Indicators: Inflation 3.2%, GDP Growth 2.5%
📊 Sector Performance: Tech +8.4%, Energy -2.1%

🤖 Future Enhancements

Integration with Trading APIs (Alpaca, Robinhood, TD Ameritrade).

More AI-driven technical analysis (RSI, Moving Averages, Bollinger Bands).

Customizable alerts based on user-defined rules.

🏆 Contributions & Support

Want to contribute? Feel free to submit a pull request or open an issue.

📧 Contact: your-email@example.com

🚀 Happy Investing!
