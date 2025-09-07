# Liquidity-Heatmap
A TradingView Pine Script™ indicator that highlights liquidity zones using PVSRA (Price, Volume, Support/Resistance Analysis) or VSA (Volume Spread Analysis). Each zone is assigned a probability score (20–85%) based on volume strength, distance from price, trend alignment, and volatility.

✨ Features

Dual Mode: Switch between PVSRA and VSA logic.

Probability Scoring: Zones ranked by hit likelihood with labels (green = strong, yellow = moderate, red = weak).

Dynamic Zone Sizing: Adjustable by ATR, % of candle, or ticks.

Aging & Fading: Zones gradually fade with time for clarity.

Statistics Panel: Tracks prediction accuracy, expected vs. actual hits, and assigns a quality rating.

Configurable Inputs: Control volume thresholds, wick size, ATR multipliers, zone limits, and more.

📊 How It Works

Detects high-volume candles with specific price action (climaxes, springs, upthrusts, wide spreads).

Creates support or resistance zones based on the candle structure.

Assigns each zone a probability score (heuristic formula).

Displays ongoing statistics to evaluate performance.

⚠️ Disclaimer

This script is for educational purposes only. It provides heuristic probabilities, not true statistical odds. Do not use as a standalone trading system—combine with market context, volume profile, and order flow.

📷 Screenshot

<img width="2219" height="1007" alt="image" src="https://github.com/user-attachments/assets/864d8bb5-3e49-4493-b792-7e2dce9a6489" />


📥 Installation

Copy the code into a new Pine Script editor in TradingView.

Save & add to chart.

Adjust inputs in the settings panel.
VSA vs PVSRA Zones
Mode	What it highlights	Best use for
PVSRA	High-volume support/resistance zones based on price + volume	Good for seeing structural zones where smart money might enter/exit. Works well with your order flow context.
VSA	Volume Spread Analysis: climaxes, upthrusts, springs	More focused on traps and potential reversals. Useful if you want zones where price may reject.

Rule of Thumb for You:

If you want zones likely to be touched → use PVSRA.

If you want zones likely to cause a reaction or trap → use VSA.

🔧 Requirements

TradingView account with Pine Script v6 support.

Would you like me to also make a short tagline version (like the one-line description you’d put at the very top of the README under the title)?
