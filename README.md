# TradingView-indicators
Trade indicators that I am using, used or just working on 


===================== # Daily Fibonacci Retracement ====================

This repository contains a TradingView Pine Script indicator that automatically draws daily Fibonacci retracement levels based on the **previous trading day's High and Low**.  
The tool is designed for traders who use Fibonacci levels as support/resistance references during intraday or swing trading.

## Features
- Detects the start of a new trading day and updates levels automatically.
- Uses the previous day's **High** and **Low** to calculate retracement ranges.
- Customizable Fibonacci ratios (0.0, 0.1, 0.2, 0.236, 0.382, 0.5, 0.618, 0.786, 1.0).
- Lines extend to the right across the current session for clarity.
- Toggle option to switch retracement direction:
  - **Low → High (uptrend)**
  - **High → Low (downtrend)**
- Cleans up old lines/labels to avoid chart clutter.

---
## Installation
1. Open [TradingView](https://www.tradingview.com/).
2. Go to the **Pine Editor** tab.
3. Copy the code from the `.pine` file of your choice.
4. Click **Add to Chart**.
5. Save the script in your TradingView account for future use.
---
## Version History
- **v1.0**
  - Initial release.
  - Draws Fibonacci retracements from previous day’s Low → High.
  - Clears and redraws lines/labels at the start of each day.

- **v1.1**
  - Added toggle to choose retracement direction (Low → High or High → Low).
  - Cleaner code structure for easier upgrades.

---

## Planned Improvements
- Option to display only selected fib levels (user toggle checkboxes).
- Customizable line/label colors per level.
- Option to display previous day’s Close as a reference line.
- Multi-timeframe support (weekly/monthly fib retracements).
