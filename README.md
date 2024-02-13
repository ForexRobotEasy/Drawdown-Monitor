# Drawdown Monitor

This code is a drawdown monitoring tool developed by the Forex Robot Easy Team. It is designed to monitor the drawdown percentage of the trading account and take necessary actions when a maximum drawdown threshold is reached.

## Features

- Monitors the drawdown percentage of the trading account on a daily basis.
- Closes all open positions and deletes pending orders when the maximum drawdown threshold is reached.
- Sends an email notification when the maximum drawdown threshold is reached.

## Installation

To use this code, you need to have a MetaTrader 5 trading platform installed. Follow the steps below to install the code:

1. Copy the code and save it as a new file with the extension '.mq5'.
2. Open the MetaEditor in the MetaTrader 5 trading platform.
3. Click on 'File' > 'Open' and select the saved file.
4. Click on 'Compile' or press F7 to compile the code.
5. Close the MetaEditor.

## Usage

Once the code is compiled and installed in the MetaTrader 5 trading platform, it will start monitoring the drawdown percentage of the trading account automatically. The maximum drawdown threshold is set to 5% by default, but you can modify it by changing the value of the variable `MaxDailyDrawdown`.

When the drawdown percentage reaches or exceeds the maximum drawdown threshold, the code will take the following actions:

1. Close all open positions.
2. Delete all pending orders.
3. Send an email notification with the subject 'Maximum drawdown reached' and the message 'Closing all positions and deleting pending orders.'

The code will also keep track of the maximum equity of the trading account. If the equity reaches a new maximum, the code will reset the maximum drawdown reached flag to allow for further monitoring.

## Disclaimer

Forex Robot Easy is not the official developer of this product. This code is provided as a sample that can work as described in the product. To find the official developer of this product, please refer to the MQL5 platform.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/drawdown-monitor-review-streamlined-forex-risk-management/).
