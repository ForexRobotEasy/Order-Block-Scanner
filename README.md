# Order Block Scanner

This code is a custom indicator that scans all symbols and time frames to perform market analysis and print the analysis results. It is designed to be used in the MetaTrader platform.

## How it Works

1. Global Variables: The code initializes global variables, including the number of symbols, start and end times, and a flag for scanning.

2. Custom Indicator Initialization: The `OnInit()` function initializes the start and end times based on the current chart's time frame.

3. Custom Indicator Calculation: The `OnCalculate()` function is called for each tick to perform the market analysis. If scanning is enabled, it iterates through each symbol and time frame and performs the analysis. The analysis results are printed using the `Print()` function.

4. Start Scanning: The `StartScanning()` function sets the scanning flag to true, prints a scanning started message, and calls the `OnCalculate()` function to perform the market analysis.

5. Script Program Start: The `OnStart()` function is the entry point of the script. It starts the scanning process, waits for the scanning to complete, and prints a program completed message.

## Product Description

The Order Block Scanner is a powerful tool for traders looking to analyze multiple symbols and time frames simultaneously. With just one click, this scanner scans all symbols and time frames to provide detailed analysis results.

Key Features:
- Scans all symbols and time frames.
- Performs market analysis for each symbol and time frame.
- Prints detailed analysis results.
- Easy to use with a single click.

Please note that ForexRobotEasy is not the official developer of this product. We are providing this sample code to demonstrate how the product works. To find the official developer and access detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/order-block-scanner-review-one-click-all-symbol-time-frame-scan/). For any further assistance or support, we recommend using the MQL5 platform.
