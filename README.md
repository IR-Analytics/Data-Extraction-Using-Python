📊 Analyzing Real-Time Crypto Trends Using CoinMarketCap API

Welcome to this crypto data analysis project! In this project, I used the CoinMarketCap API to fetch live cryptocurrency data, processed it with Python, and explored price trends over time using beautiful visualizations.

🧠 What’s the Project About?
This is not just another crypto tracker. The goal here is to understand how the top 10 cryptocurrencies are performing over short and long time periods (1h, 24h, 7d, 30d, etc.). With Python, I pulled real-time data repeatedly, saved and processed it, and used Seaborn and Matplotlib to bring the trends to life.

🛠️ Tools & Libraries Used

Python 🐍

requests – for calling the CoinMarketCap API

pandas – for handling the data

json – for parsing the API response

time – to schedule multiple API calls over time

matplotlib and seaborn – for charts and visualizations

📦 What the Script Does

Connects to CoinMarketCap API to fetch live data for the top 10 coins in USD.

Appends the new data with timestamps to a master dataframe.

Repeats this process up to 250 times, with 1-minute intervals, to simulate time-based tracking.

Calculates average % changes over various timeframes (1h, 24h, 7d, 30d, etc.).

Visualizes these changes using various plots (bar charts, stacked bars, point plots).

📈 Key Visuals

Line & Bar Plots showing price change trends across multiple timeframes

Stacked Bar Charts comparing coins by their volatility

Countplots to view distribution of % changes by time period

✅ What I Learned

How to use APIs to get clean, real-time data

How to shape nested JSON data into something readable with pandas

How to visualize grouped/stacked time-based data for insights

The importance of consistent timestamping and indexing in time series

📂 Files

Crypto_API_Analysis.ipynb – The full working script

README.md – This documentation

💭 Final Thoughts

This was a fun and insightful project that really brought together real-world data, automation, and visualization. It’s a great starting point for anyone wanting to dive into API-based data analysis or explore financial trends.

