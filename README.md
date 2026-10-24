# TrendScore — Top 10 Crypto Scanner & Risk Levels for TradingView (Pine Script v6)

[![Live Web Terminal](https://img.shields.io/badge/Full_500+_Coin_Scanner-TrendScore.io-blue?style=for-the-badge)](https://trendscore.io)
[![TradingView](https://img.shields.io/badge/TradingView-Pine_Script_v6-brightgreen?style=for-the-badge)](https://www.tradingview.com)

A free, real-time cryptocurrency momentum scanner that embeds directly into your TradingView charts. Designed to eliminate low-liquidity noise and display actionable directional setups across top volume leaders.

---

## ⚡ Features

•⁠  ⁠*Multi-Factor Trend Scoring (0–100):* Combines EMA alignment (20/50/200), RSI momentum, and volume surge vs. 20-period average.
•⁠  ⁠*Top 10 Liquid Asset Monitoring:* Scans BTC, ETH, SOL, BNB, XRP, DOGE, ADA, AVAX, LINK, and SUI simultaneously.
•⁠  ⁠*Dynamic TP/SL Targets:* Calculates 1.5x ATR dynamic take-profit targets and 1.0x ATR invalidation stops in real time.
•⁠  ⁠*100% Free & Local:* Runs on any TradingView account (including free Basic tiers) without API keys or backend dependencies.

---

## 🚀 How to Install on TradingView (Free Account)

1.⁠ ⁠Open any chart on [TradingView](https://www.tradingview.com) (e.g., ⁠ BTCUSDT ⁠).
2.⁠ ⁠Open the *Pine Editor* at the bottom of the screen (or click the ⁠ { } ⁠ icon on the right sidebar).
3.⁠ ⁠Delete the default template code.
4.⁠ ⁠Copy the entire contents of [⁠ TrendScore_Top10_Scanner.pine ⁠](./TrendScore_Top10_Scanner.pine) and paste it into the editor.
5.⁠ ⁠Click *Save* and then click *Add to Chart*.
6.⁠ ⁠The interactive dashboard table will appear in the top-right corner of your chart.

---

## 📊 How the TrendScore (0–100) Works

| Factor | Weight | Metric |
| :--- | :--- | :--- |
| *Trend Alignment* | 40% | Location relative to EMA 20, 50, and 200 |
| *Momentum* | 35
