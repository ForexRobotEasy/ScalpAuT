# ScalpAuT Forex Robot

## Overview

ScalpAuT is an expert advisor (EA) developed by the Forex Robot Easy Team. It is designed to automate trading on the XAU/USD (Gold) currency pair. The EA utilizes the VIST (Forex Timing Bot) system to execute the ScalpAuT algorithm at specific timings.

For detailed reviews and trading results of this product, visit [forexroboteasy.com/forex-robot-review/scalpaut-review-unveiling-the-forex-timing-bots-real-results/](https://forexroboteasy.com/forex-robot-review/scalpaut-review-unveiling-the-forex-timing-bots-real-results/).

Please note that Forex Robot Easy is not the official developer of this product. This ReadMe file provides a sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.

## Installation

To install and use the ScalpAuT Forex Robot, follow these steps:

1. Download the ScalpAuT.mq5 file.
2. Open your MetaTrader 5 trading platform.
3. Go to 'File' > 'Open Data Folder' to open the data folder.
4. Navigate to the 'MQL5' folder.
5. Copy the ScalpAuT.mq5 file into the 'Experts' folder.
6. Restart the MetaTrader 5 platform.
7. The ScalpAuT Forex Robot will now be available in the 'Expert Advisors' section of the Navigator window.

## Usage

Once the ScalpAuT Forex Robot is installed, follow these steps to use it:

1. Load historical quotes for the XAU/USD currency pair by running the `LoadQuotes` function. You may need to modify this function to load quotes from your preferred source.
2. Set the VIST system timings by running the `SetVISTTimings` function. Adjust the timings according to your trading strategy.
3. Set the chart timeframe to 1-minute by running the `SetChartPeriod` function.
4. The EA will now be ready to execute the ScalpAuT algorithm.
5. The `OnTick` function checks if it's time to execute the algorithm based on the VIST timings. If it's the right timing, the `ExecuteScalpAuT` function is called.
6. Implement your own logic in the `ExecuteScalpAuT` function to execute the ScalpAuT algorithm.
7. The EA will continue to execute the algorithm based on the specified timings.

## Disclaimer

Please note that Forex Robot Easy is not the official developer of the ScalpAuT Forex Robot. This ReadMe file provides a sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com/forex-robot-review/scalpaut-review-unveiling-the-forex-timing-bots-real-results/](https://forexroboteasy.com/forex-robot-review/scalpaut-review-unveiling-the-forex-timing-bots-real-results/).
