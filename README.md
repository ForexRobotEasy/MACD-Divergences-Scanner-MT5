# MACD Divergences Scanner MT5 ReadMe File

## About the Code

This code is an example of a MACD Divergences Scanner for MetaTrader 5 (MT5) platform. It is designed to identify divergences between asset price and the MACD indicator and send alerts or notifications to the user. The code is provided as a sample and is not the official code developed by ForexRobotEasy.

## Usage

To use this code, follow the steps below:

1. Install MetaTrader 5 platform on your computer.
2. Open MetaEditor in MetaTrader 5 and create a new Expert Advisor.
3. Copy and paste the entire code into the Expert Advisor file.
4. Save the file with a desired name and compile it.
5. Attach the Expert Advisor to a chart in MetaTrader 5.

## Functionality

The code consists of several functions:

### 1. `OnInit()`

This function is called during the initialization of the Expert Advisor. Custom initialization code can be added here.

### 2. `OnDeinit(const int reason)`

This function is called during the deinitialization of the Expert Advisor. Custom deinitialization code can be added here.

### 3. `OnTick()`

This function is called on each tick of the chart. Custom tick code can be added here. It also checks for divergences using the `CheckDivergence()` function and sends an alert or notification if a divergence is found.

### 4. `CheckDivergence()`

This function calculates the MACD indicator and compares it with the asset price to identify divergences. It returns `true` if a divergence is found and `false` otherwise.

### 5. `SendAlert()`

This function sends an alert or notification to the user. Custom code can be added here to define the type of alert or notification to be sent.

### 6. `CalculatePerformanceReports()`

This function calculates the accuracy and profitability of the scanner's signals based on historical data. Real-time results are displayed and updated as new data becomes available.

### 7. `CreateUserInterface()`

This function creates a user-friendly interface for the scanner. Traders can customize settings and parameters according to their preferences. Clear instructions on how to use the scanner effectively are provided.

### 8. `OnStart()`

This function is called when the Expert Advisor starts. It starts the expert and calls the functions `CreateUserInterface()` and `CalculatePerformanceReports()` to create the user interface and calculate performance reports.

## Product Description

The MACD Divergences Scanner MT5 is a powerful tool designed for professional forex traders. It helps traders identify divergences between asset price and the MACD indicator, providing valuable insights for making informed trading decisions.

With its intuitive and user-friendly interface, traders can easily customize the settings and parameters according to their preferences. The scanner continuously scans the market and sends alerts or notifications to the trader whenever a divergence is detected, ensuring that no trading opportunity is missed.

The scanner's performance reports provide accurate and real-time information on the accuracy and profitability of its signals. Traders can rely on these reports to evaluate the effectiveness of the scanner and make necessary adjustments to their trading strategies.

Please note that ForexRobotEasy is not the official developer of this product. We only provide the sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/macd-divergences-scanner-mt5-review-real-results-for-professional-forex-traders/).
