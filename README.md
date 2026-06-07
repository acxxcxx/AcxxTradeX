# ACXX TradeX v1.0.0 

ACXX TradeX is a High-Frequency Trading (HFT) AI crypto scalping bot built for Binance Futures. It utilizes local Random Forest AI models to predict short-term price actions, coupled with strict risk management, dynamic leverage, and real-time execution.

## Key Features
* **AI Price Prediction:** Ultra-fast, RAM-only Random Forest models running locally to predict 3-minute timeframe momentum.
* **Smart Risk Management:** Automated Stop-Loss, Trailing Stop, and Breakeven features to protect capital.
* **Volume Validation & Pattern Recognition:** Filters out "scam wicks" by validating order book volume and candlestick patterns (e.g., Bullish Engulfing, Hammer, Flags).
* **Anti-Liquidation Shield:** Automatically blacklists extremely volatile or low-liquidity coins (flash crash protection).
* **Standalone Executable:** Compiled natively for Windows 10, requiring no Python environment installation.

## System Requirements
* **OS:** Windows 10 (64-bit)
* **API:** Active Binance Futures API Keys (with Futures Trading enabled)

## Setup Configuration

Before running the bot, configure the settings from the **Global Settings** panel:

* **Enable Dry Run Mode (Recommended)**
  - Keep **Dry Run Mode** enabled during initial testing.
  - The bot will generate signals and simulate trades without placing real orders on Binance.

* **Configure Trading Parameters**
  - Set your preferred **Global Leverage**.
  - Enter the **Cost USD** amount per trade.
  - Adjust the **Minimum Score** threshold for signal validation.
  - Configure **ADX Filter** according to your strategy.

* **Configure API Access**
  - Enter your **Binance API Key** and **Binance Secret**.
  - Ensure your API key has the required permissions for Futures trading.
  - Never share your API credentials with anyone.

* **Volume Filter**
  - Enable the **Volume Filter** to avoid trading on low-volume assets.
  - Set the minimum volume requirement in millions of USD.

* **Activate Your License**
  - Enter your **Pro License Key** and click **Apply**.
  - Verify that your current license status is displayed correctly.

* **Secure Your Account**
  - Change the default username and password immediately after installation.
  - Use a strong password containing uppercase letters, lowercase letters, numbers, and special characters.

* **Save Configuration**
  - Click **Save Config** to store all settings before starting the bot.

Pro License & Trial
Want to unlock all premium features and maximize your trading potential? You can request a Trial Pro License by contacting us via mail:

<img width="1293" height="911" alt="image" src="https://github.com/user-attachments/assets/7109ca87-9e1c-46ed-b36e-d945568669a6" />
<img width="702" height="885" alt="image" src="https://github.com/user-attachments/assets/a41e531c-be99-43c6-bb21-c48836eced00" />




## Disclaimer
**USE AT YOUR OWN RISK.** Cryptocurrency trading, especially using high leverage on the Futures market, carries a high level of risk and may not be suitable for all investors. The author of this software is not responsible for any financial losses incurred while using this bot. Always test with `dry_run` mode first.
