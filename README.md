# Strategies
This repository holds trading strategies that may be used as a fully automated trading system templates within the [Superalgos Desktop App](https://superalgos.org/tools-superalgos-desktop-app.shtml). They may be useful to learn or to obtain trading ideas that you may use to trade manually. You may also use the app for testing ideas, for backtesting strategies and paper-trading (signals!), and still live-trade manually if you wish.

# Disclaimer
THIS IS NOT FINANCIAL ADVICE. WE SHARE STRATEGIES FOR EDUCATIONAL PURPOSES ONLY. TRADE AT YOUR OWN RISK.

# Bull Run Rider - SDA v.0.0.1 - USDT - 1hr.json

## Specifications

### Market

USDT-BTC, with **USDT as the base asset**.

### Strategy Goal

Catching big market moves, with a conservative approach to minimize risk.

### Approach

We split the goal in two:

1. We focus on potentially big market moves, therefore, the strategy will be optimized for bull runs.

2. We will take the clearest and most promising opportunities only. We will pass on everything else.

### Trading idea

Identify breakouts of the Bollinger Bands (price going above the upper deviation band). Use %Bandwidth indicator to assess momentum and Bollinger Bands moving average to filter out late entries.

### Current Performance in Backtests (Poloniex)

| Details | 2019 | 2018 | 2017 |
| :--- | :---: | :---: | :---: |
| Trades: | 7 | 3 | 6 |
| Hits: | 7 | 1 | 4 |
| Fails: | 0 | 2 | 2 |
| ROI: | 189% | 16.5% | 44.5% |

As you can see, the strategy is conservative during 2017 and 2018, as it is optimized for current market conditions... that is why it performs better in 2019 than in 2017.


# Bull Run Rider - SDA v.0.0.1 - BTC - 1hr.json

## Specifications

### Market

USDT-BTC, with **BTC as the base asset**.

### Strategy Goal

Accumulate BTC during consolidation periods in the context of a bull run.

### Approach

Reversals are tricky to catch at the 1 hr timeperiod, so we will focus on continuation moves, being conservative and taking only the clearest opportunities.

### Trading idea

Identify breakouts of the Bollinger Bands (price going below the lower deviation band). Use %Bandwidth indicator to assess momentum and Bollinger Bands moving average to filter out late entries.

### Current Performance in Backtests (Poloniex)

| Details | 2019 | 2018 | 2017 |
| :--- | :---: | :---: | :---: |
| Trades: | 9 | x | x |
| Hits: | 9 | x | x |
| Fails: | 0 | x | x |
| ROI: | 103% | x% | x% |

As you can see, the strategy is conservative during 2017 and 2018, as it is optimized for current market conditions... that is why it performs better in 2019 than in 2017.

### 2019 Main Trades and Results

![2019 main trades](https://user-images.githubusercontent.com/13994516/65026396-c485a680-d938-11e9-905c-28df4f644cc3.png)
