# Trend AMA MT5 ReadMe

The Trend AMA MT5 indicator is a custom indicator developed by the Forex Robot Easy Team. It is designed to enhance forex trades by using an adaptive moving average calculation.

## Indicator Settings
- AMA_Period: Period for adaptive moving average calculation (default: 14)
- Noise_Period: Period for market noise filter calculation (default: 10)

## Indicator Buffers
- Trend: Buffer for trend direction values
- Power: Buffer for trend power values

## Initialization Function
The custom indicator initialization function (OnInit) sets the indicator buffers and labels.

## Deinitialization Function
The custom indicator deinitialization function (OnDeinit) clears the indicator buffers.

## Iteration Function
The custom indicator iteration function (OnCalculate) calculates the adaptive moving average, market noise, applies the market noise filter, determines the trend direction, and calculates the trend power.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Trend AMA MT5 Review](https://forexroboteasy.com/forex-robot-review/trend-ama-mt5-review-enhancing-forex-trades-with-adaptive-moving-average/).

**Note:** Forex Robot Easy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
