# Atomic79 MT5 EA ReadMe

### Overview

Atomic79 MT5 EA is an Expert Advisor (EA) developed by the Forex Robot Easy Team. It is a trading robot designed to trade in the gold market (symbol: XAUUSD) using the iTrend indicator. The EA provides multiple entry strategies based on the iTrend indicator and also includes functions for market analysis, investment protection, and TURBO mode operation.

### Installation

To use the Atomic79 MT5 EA, follow these steps:

1. Import the necessary libraries: Trade.mqh and iTrend.mqh.
2. Define the constants: SYMBOL (set to 'XAUUSD' for gold market symbol), MAGIC_NUMBER (unique identifier for trade identification), and LOT_SIZE (fixed lot size for trading).
3. Create objects for the Trade class and the iTrend indicator.
4. Implement custom entry strategies using the iTrend indicator.
5. Define custom functions for market analysis, strategy adjustment, investment protection, and TURBO mode operation.
6. Initialize the EA in the OnInit() function by setting the expert magic number and creating the iTrend indicator.
7. In the OnTick() function, analyze the market and execute the entry strategies, adjust strategies based on daily market analysis, implement investment protection, and handle TURBO mode operation.
8. Clean up code and perform necessary actions before deinitialization in the OnDeinit() function.

### Entry Strategies

The Atomic79 MT5 EA provides the following custom entry strategies based on the iTrend indicator:

1. Strategy 1: Buy when iTrend crosses above 0.
2. Strategy 2: Sell when iTrend crosses below 0.
3. Strategy 3: Buy when iTrend is above a certain threshold.
4. Strategy 4: Sell when iTrend is below a certain threshold.
5. Strategy 5: Buy when iTrend changes direction from negative to positive.

### Custom Functions

The EA includes the following custom functions:

1. calculateMarketIndicators(): Calculates and analyzes market indicators, including the iTrend indicator.
2. analyzeMarketAndExecuteStrategies(): Analyzes the market using the iTrend indicator and executes the entry strategies.
3. adjustStrategiesBasedOnDailyAnalysis(): Adjusts the strategies based on daily market analysis (to be implemented).
4. implementInvestmentProtection(): Implements investment protection using averaging techniques (to be implemented).
5. handleTurboMode(): Handles TURBO mode operation (to be implemented).

### ForexRobotEasy Disclaimer

Please note that ForexRobotEasy is not the official developer of the Atomic79 MT5 EA. We are providing this sample code for informational purposes only. To find the official developer of this product and access detailed reviews and trading results, visit [this link](https://forexroboteasy.com/forex-robot-review/atomic79-mt5-ea-review-your-key-to-gold-market-success/). To obtain the official version of the EA, please use MQL5.
