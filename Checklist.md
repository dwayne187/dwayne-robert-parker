Below is a set of frequently asked questions you need to answer, if you want to implement a cryptocurrency algorithmic trading bot yourself or if you want us to make one for you. Try being as specific as you possibly can.

# Strategy

  - What type of trading strategy you want implemented (say, if it is an arbitrage strategy, what kind of arbitrage you want: basic, statistical, rebalancing, etc...)?
  - What's considered to be a trading opportunity for the bot?
  - What are desired conditions to enter a trade (TA params, indicators, signaling, etc)?
  - What are the exit conditions?
  - What are your risk management requirements?
  - Do you want to trade with one account or multiple accounts within each exchange?
  - Do you want advanced asset management within the bot or trading software itself (withdraws, ?
  - Does your strategy involve OTC trading or darkpools?

# Access

  - Which exchanges you want?
  - Which pairs/instruments you want?
  - Do you need chat integrations (like, slack, telegram, discord, irc)?
  - Do you want to control it from a phone application?
  - Do you want network access to your bot? 
  - Do you need the bot to notify you on significant market events by email, text messaging, push notifications or other means?
  - Do you want web access to your bot (to open it within a browser tab)?
  - Do you want to integrate with the actual blockchain or a transaction graph of an existing cryptocurrency like Bitcoin, Ethereum, altcoins?    
  - Which external sources of data and online services you want integrated for market insights, signals (other purposes, maybe)?

# Technology

  - What programming language do you prefer?
  - What are you hardware requirements?
  - What's your target OS / runtime environment?
  - Do you want REST over HTTP?
  - Do you need Websockets to receive market data feeds directly from the exchanges (this is usually faster than REST)?
  - Do you need support for FIX / IFEX?
  - Do you need to proxify your requests? (to work around exchange request rate limits)
  - What parameters do you want for control?
  - Do you want it to have a rich end-user GUI?
  - Do you need sophisticate interactive charts?

# Testing

  - Do you want to have backtesting functionality (trade simulation with recent data from the past)?
  - Do you want paper trading capabilities (trade simulation in real time)?
  - Do you want to conduct a test of your strategy before running it in real action?
  - How much historical data you need?
  - How much of statistical calculations you want to perform, do you want concurrency, parallelism?

# Scalability

  - Do you want to run it from your computer for personal use (intra-day orders, up to several trades per minute)?
  - Do you want a large-scale High-Frequency Trading business operation across multiple countries (do you need lowest possible latencies for HFT) ?
  - Do you want to have it online in a distributed network of leased vds/vps close to the exchange?
  - What are your requirements for redundancy and maximum downtime, can you afford to stop the trade?
  - Do you need server / bot instance hot-swap?
  - Do you want to use it yourself / in-house, or you want to sell it as part of your service or product to your clients?
  - Do you want to integrate coin exchange functionality with your running business?