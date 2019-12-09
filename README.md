# About
This repository holds an open-source trading strategy maintained by the [Superalgos Community](https://t.me/superalgoscommunity). The strategy conforms to the Superalgos Protocol, therefore, it may function as a fully automated trading system within the [Superalgos Platform](https://superalgos.org/tools-superalgos-platform.shtml). 

People not interested in trading automation may still obtain the strategy's rules (situations, conditions, and formulas) from the app's Designer interface, and use the set of rules as they see fit. The app may also be used for testing ideas, for backtesting and paper-trading (to obtain live signals!).

# Weak-hands Buster - BTC

## Performance in Backtests (Poloniex)

| Details | Jan - Aug 2019 | 2018 |
| :--- | :---: | :---: |
| Trades: | 8 | 19 |
| Hits: | 7 | 12 |
| Fails: | 1 | 7 |
| ROI*: | 87.5% | 549% |

[ * ] The strategy starts with an *initial capital* and reinvests accumulated profits in every trade. ROI is calculated over the *initial capital*.

## Live Trading Performance

| Details | Sep - Dec 2019 |
| :--- | :---: |
| Trades: | 2 |
| Hits: | 2 |
| Fails: | 0 |
| ROI*: | 46.7% |

## Live Trades

### 2019 Sep - Dec

![image](https://user-images.githubusercontent.com/13994516/70468550-9a6efb00-1ac7-11ea-891f-0f3f04807cff.png)

## Specifications

JSON file compatible with the Superalgos Desktop App v.0.0.3

### Market

USDT-BTC, with **BTC as the base asset**.

### Description

The strategy is dissected [in this article](https://hackernoon.com/how-to-increase-your-bitcoin-holdings-in-a-bear-market-part-1-kjwp2gwu).

### Strategy Goal

Accumulate bitcoin during bear markets and / or consolidation periods, with a conservative approach to minimize risk.

### Approach

We split the goal in two:

1. We focus on potentially big market moves, therefore, the strategy is optimized for major trend reversals resulting in long bear markets. Significant consolidations during bull markets are targetted as well.

2. We take the clearest and most promising opportunities only. We pass on everything else.

### Trading idea

The main trading idea is to identify short-term reversals as well as continuations and deepening of trends marked by a break down of the Bollinger Bands (BB) in the 1-hour chart, using the Percentage Bandwidth (%B) indicator, the Bollinger Bands Moving Average (BB MA) and the Bollinger Band deviation to assess momentum and volatility, optimize the take position event, and filter out late entries.

## Main Backtesting Trades

### 2018 Jan-Mar
![Weak-hands-buster 2018 jan-mar](https://user-images.githubusercontent.com/13994516/65391693-70c9f180-dd6c-11e9-92d4-fe496462ead0.png)

### 2018 Apr-Jun
![Weak-hands-buster 2018 apr-jun](https://user-images.githubusercontent.com/13994516/65391728-f8176500-dd6c-11e9-95f4-5410ad4fd2be.png)

### 2018 Jul-Aug
![Weak-hands-buster 2018 jul-sep](https://user-images.githubusercontent.com/13994516/65391760-27c66d00-dd6d-11e9-9c1b-4ce11d1ef1f8.png)

### 2018 Oct-Dec
![Weak-hands-buster 2018 oct-dec](https://user-images.githubusercontent.com/13994516/65391772-517f9400-dd6d-11e9-8b16-e26f9694a5bf.png)

### 2019 Jan-Aug
![Weak-hands-buster 2019](https://user-images.githubusercontent.com/13994516/65391566-f2208480-dd6a-11e9-82d4-4dc05e9a7e0a.png)

# Disclaimer

> THIS IS NOT FINANCIAL ADVICE. ALTHOUGH THE STRATEGIES IN THIS REPOSITORY MAY BE FULLY FUNCTIONAL, WE DO NOT MAKE ANY EXPRESS OR IMPLIED RECOMMENDATION AS OF HOW YOU SHOULD USE THEM. WE SHARE STRATEGIES FOR EDUCATIONAL PURPOSES ONLY. TRADE AT YOUR OWN RISK.
