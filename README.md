# 📈 Smart Volume & Breakout Risk Indicator

A custom **Pine Script (v5)** indicator designed to detect high-probability breakout risks by analyzing volume surges, price momentum, and candlestick anatomy. 

## 🚀 How It Works (The Logic)

This algorithm combines three main factors to identify valid breakouts:
1. **Volume Analysis:** Compares the current volume against a Simple Moving Average (SMA) to filter out fake breakouts and identify true market participation.
2. **Momentum Detection (ATR):** Utilizes the Average True Range (ATR) with a custom multiplier to spot oversized, high-momentum price movements.
3. **Candle Anatomy:** Calculates the body-to-wick ratio (Body Control Threshold) to ensure the candle is dominant and not just a volatile wick.


## 🛠️ Tech Stack
- **Language:** Pine Script (v5)
- **Platform:** TradingView

## 💻 How to Use

1. Open [TradingView](https://www.tradingview.com/).
2. Navigate to the **Pine Editor** tab at the bottom of the chart.
3. Open the `indicator.pine` file from this repository, copy the code, and paste it into the editor.
4. Click **Add to Chart**.
5. Adjust the parameters in the indicator settings to fit your trading style.

---
*Developed by [Ahmed Issa](https://github.com/engahmedessa) - Integrating engineering logic with algorithmic trading.*
