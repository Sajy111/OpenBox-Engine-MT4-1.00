## Strategy Overview

This strategy is built around generating consistent trading volume to benefit from **broker rebates (cashback)**.  
It executes an average of **6 trades per day** on the **GBP/USD** pair, using a stable and lightly profitable algorithm.  

- **Expected daily volume**: ~2 lots (20 Instaforex lots) for a $10,000 account.  
- **Core design**: minimize slippage with **limit orders** and **smart profit-taking** techniques on higher volumes.  
- **Income model**:  
  - Primary income comes from **rebates (cashback)**.  
  - The trading algorithm itself aims to stay **slightly profitable or breakeven**.  

### Trading Logic

- **Indicators used**:
  - **Bollinger Bands (200, 2)**
  - **Linear Weighted Moving Average (LWMA 55)**  

- **Entry conditions**:
  - Only **buy trades** are executed.  
  - Entry occurs when the price **touches the upper Bollinger Band** and then **pulls back to the WMA (55)**.  

- **Trade management**:
  - Each trade is **optimized at entry** according to the **current volatility model** of the market.  
  - If price moves in the expected direction → take profit at **+8 pips**.  
  - If price retraces slightly → apply **light averaging** and close on the **breakout of the upper Bollinger Band**.  
  - If price retraces strongly → apply **aggressive averaging** with a built-in **nested cascading averaging system** for recovery.
  - Volatility 

### Special Account Setup

The system is optimized for zero spread accounts with a commission structure the more comission the better.
This allows generating **powerful cashback** while maintaining a balanced risk-to-reward profile.
