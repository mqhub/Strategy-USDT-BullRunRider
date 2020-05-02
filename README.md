# About
This repository holds an open-source trading strategy maintained by the [Superalgos Community](https://t.me/superalgoscommunity). The strategy conforms to the Superalgos Protocol, therefore, it may function as a fully automated trading system within the [Superalgos Desktop App](https://superalgos.org/tools-superalgos-desktop-app.shtml). 

People not interested in trading automation may still obtain the strategy's rules (situations, conditions, and formulas) from the app's Designer interface, and use the set of rules as they see fit. The app may also be used for testing ideas, for backtesting and paper-trading (to obtain live signals!).

# Bull Run Rider - USDT - 1hr

## Specifications

JSON file compatible with the Superalgos Desktop App v.0.0.1

### Performance in Backtests (Binance)

| Details | Jan 2018 - Aug 2019 | Jan 2019 - Aug 2019 | 2018 |
| :--- | :---: | :---: | :---: |
| Trades: | 10 | 7 | 3 | 
| Hits: | 7 | 6 | 1 | 
| Fails: | 3 | 1 | 2 | 
| Hit Ratio: | 70% | 85.7% | 33.3% | 
| ROI*: | 160.4% | 125.2% | 15.6% | 

### Live Performance (Binance)

| Details | Aug 2019 - Apr 2020 |
| :--- | :---: |
| Trades: | 5 |
| Hits: | 2 |
| Fails: | 3 |
| Hit Ratio: | 40% |
| ROI*: | -0.9% |


[ * ] The strategy starts with an *initial capital* and reinvests accumulated profits in every trade. ROI is calculated over the *initial capital*.

### Market

USDT-BTC, with **USDT as the base asset**.

### Strategy Goal

Catching big rallies, with a conservative approach to minimize risk.

### Approach

We split the goal in two:

1. We focus on potentially big market moves, therefore, the strategy is optimized for bull runs.

2. We take the clearest and most promising opportunities only. We pass on everything else.

### Trading idea

Identify breakouts of the Bollinger Bands (price going above the upper deviation band). Use %Bandwidth indicator to assess momentum and Bollinger Bands moving average to optimize the *take position event*, and filter out late entries.

# Disclaimer

> THIS IS NOT FINANCIAL ADVICE. ALTHOUGH THE STRATEGIES IN THIS REPOSITORY MAY BE FULLY FUNCTIONAL, WE DO NOT MAKE ANY EXPRESS OR IMPLIED RECOMMENDATION AS OF HOW YOU SHOULD USE THEM. WE SHARE STRATEGIES FOR EDUCATIONAL PURPOSES ONLY. TRADE AT YOUR OWN RISK.
