# About
This repository holds an open-source trading strategy. The strategy conforms to the Superalgos Protocol, therefore, it may function as a fully automated trading system within the [Superalgos Desktop App](https://superalgos.org/tools-superalgos-desktop-app.shtml). 

People not interested in trading automation may still obtain the strategy's situations, conditions, and formulas by using the app's Designer interface, and use the set of rules as they see fit. The app may also be used for testing ideas, for backtesting and paper-trading (signals!).

## Disclaimer

> **THIS IS NOT FINANCIAL ADVICE. ALTHOUGH THE STRATEGIES IN THIS REPOSITORY MAY BE FULLY FUNCTIONAL, WE DO NOT MAKE ANY EXPRESS OR IMPLIED RECOMMENDATION AS OF HOW YOU SHOULD USE THEM. WE SHARE STRATEGIES FOR EDUCATIONAL PURPOSES ONLY. TRADE AT YOUR OWN RISK.**

# Bull Run Rider - SDA v.0.0.1 - USDT - 1hr.json

## Specifications

JSON file compatible with the Superalgsos Desktop App v.0.0.1

### Market

USDT-BTC, with **USDT as the base asset**.

### Strategy Goal

Catching big rallies, with a conservative approach to minimize risk.

### Approach

We split the goal in two:

1. We focus on potentially big market moves, therefore, the strategy will be optimized for bull runs.

2. We will take the clearest and most promising opportunities only. We will pass on everything else.

### Trading idea

Identify breakouts of the Bollinger Bands (price going above the upper deviation band). Use %Bandwidth indicator to assess momentum and Bollinger Bands moving average to optimize the *take position event*, and filter out late entries.

### Current Performance in Backtests (Poloniex)

| Details | 2019 | 2018 | 2017 |
| :--- | :---: | :---: | :---: |
| Trades: | 7 | 3 | 6 |
| Hits: | 7 | 1 | 4 |
| Fails: | 0 | 2 | 2 |
| ROI: | 189% | 16.5% | 44.5% |

As you can see, the strategy is conservative during 2017 and 2018, as it is optimized for current market conditions. That is why it performs better in 2019 than in 2017's bull run.
