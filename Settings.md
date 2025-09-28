## Bot Settings Explained

⚠️ **Important:** Use only **1-minute timeframe (M1)** and the **GBP/USD pair**!  

- **Magic Number** – Unique ID for robot transactions.  
- **Max Value** – Limit for the maximum deal value.  
- **Starting Lot** – Recommended **0.01 per $1000** of account balance.  
  - The higher the starting lot, the more aggressive the trading.  
- **Spread Filter** – Avoids trading during **high-impact events**.  
- **Highest Balance & Highest Equity** – Enter your **current balance** when starting or restarting the robot.  
- **Profit in Pips** – Default **80** (optimized for GBP/USD).  
  - This is the maximum **Take Profit** for trend deals (for 5-digit brokers).  
- **Max Deals** – Maximum number of averaging trades (prevents being stuck in the market too long).  
- **Recovery Index** – Default is **1**.  
  - Values **2+** make the robot very aggressive (**not recommended**).  
- **Turbo Recovery** – Increases lot size for each new chunk of deals.  
  - Helps recover losses faster but **increases risk**.  
- **OSD** – Shows debug info directly in the terminal.  
- **Rehigh TP** – Take Profit in **USD**.  
  - The higher this number, the harder it is to exceed the highest balance (make profit).  
  - Recommended: **10**.  
- **Instant Order Now** – Opens the **first order immediately**, without waiting for a signal.  
- **Any Nearest Signal** – Opens an order on the **first available signal**.  
- **Eurica** – Set to **true** for **0-spread accounts**.  
- **Aggressive Mode Pips** – Volatility check.  
  - Optimized for GBP/USD: **150–200**.  
- **First Mult** – Multiplier for the **first chunk of deals**.  
