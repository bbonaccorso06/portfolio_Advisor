*********How Your Stock Adviser Works to Monitor and Suggest Actions
Your automated portfolio adviser is designed to continuously monitor both your portfolio and the overall stock market and suggest strategic actions when necessary. Here’s how it works:

1️⃣ Daily, Weekly, and Monthly Price Monitoring
📌 How it Works:

It fetches stock prices from multiple sources (Yahoo Finance, Alpha Vantage, Finnhub).
It tracks daily, weekly, monthly, and 3-month price movements.
It calculates the percentage change in each stock to determine if an action is needed.
📌 How This Helps You: ✅ Avoid reacting to short-term price fluctuations
✅ Identify long-term uptrends and downtrends
✅ Prevent unnecessary buying/selling caused by daily market noise

2️⃣ Market Sentiment & News Analysis
📌 How it Works:

It pulls financial news from Finnhub & NewsAPI.
It filters news related to your stocks.
It uses AI-driven sentiment analysis to determine if the market is bullish, neutral, or bearish.
📌 How This Helps You: ✅ Helps you stay informed on market conditions
✅ Identifies external risks (e.g., inflation, regulations, earnings reports)
✅ Avoids bad trades based on hype or panic selling

3️⃣ Smart Rebalancing Recommendations
📌 How it Works:

It tracks your entire portfolio and checks if certain stocks are moving significantly.
It compares short-term vs. long-term trends to make smarter buy/sell decisions.
It uses the following thresholds:
Weekly change > 5% → Monitor closely 🚨
Monthly change > 10% → Consider adjusting 🔄
3-month change > 15% → Strong rebalance signal 🔥
📌 How This Helps You: ✅ Keeps your portfolio diversified and aligned with your goals
✅ Helps capture profits at the right time instead of holding too long
✅ Suggests adding to undervalued positions for long-term gains

4️⃣ When Will It Suggest Buying, Selling, or Sector Rotation?
Your AI-based stock adviser will only suggest actions when market conditions align.

🔵 ✅ It will suggest selling if:

A stock has grown significantly over months (e.g., +20% in 3 months)
Market sentiment shows potential risks ahead
Other stocks/sectors offer better long-term opportunities
🟡 🔄 It will suggest rebalancing if:

A stock is declining over multiple weeks/months
Your portfolio is too concentrated in one sector
Other sectors are showing strength
🟢 💰 It will suggest buying if:

A stock has dropped but fundamentals remain strong
Market sentiment indicates recovery or growth potential
A sector is emerging as a strong long-term opportunity
5️⃣ Fully Automated Decision-Making
📌 How it Works:

Runs every hour (time.sleep(3600)) and can be modified for daily or weekly checks.
Sends you an email report with clear recommendations on what to do next.
Avoids spamming you with unnecessary alerts unless something meaningful has changed.
📌 How This Helps You: ✅ You don’t need to check your portfolio daily
✅ You’ll always know when to act—without guessing
✅ It eliminates emotional trading & market noise distractions
