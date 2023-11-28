# Golden Horse EA

## Description
The Golden Horse EA is a forex trading robot developed by the Forex Robot Easy Team. It is a unique software designed to automate trading in the forex market. This code is a sample implementation of the Golden Horse EA, showcasing its functionality.

## Product Information
- Product: Golden Horse EA
- Developer: Forex Robot Easy Team
- Developer's Site: [forexroboteasy.com](https://forexroboteasy.com)

## Input Parameters
- LotSize: Trading lot size (default: 0.01)
- GridSize: Grid size (default: 20)
- RangePeriod: Ranging period (default: 20)
- StopLoss: Stop loss in pips (default: 50)
- TakeProfit: Take profit in pips (default: 100)
- TrailStop: Trailing stop in pips (default: 30)

## Global Variables
- ticket: Order ticket number
- lastRangeHigh: Last range high
- lastRangeLow: Last range low

## Initialization Function
The `OnInit` function is the expert initialization function. It adds an indicator to the chart for range detection and sets the indicator parameters.

## Deinitialization Function
The `OnDeinit` function is the expert deinitialization function. It removes the indicator from the chart.

## Start Function
The `OnTick` function is the expert start function. It checks if there is an open order and if the order is closed. If there is no open order and the current price is within the range, a new order is opened. The function also sets a trailing stop for the order.

## Custom Indicator Function
The `OnCalculate` function is a custom indicator function for range detection. It calculates the range high and low using the `iHigh` and `iLow` functions.

## Disclaimer
ForexRobotEasy is not the official developer of the Golden Horse EA. This code is a sample implementation provided for educational purposes. To find the official developer of the Golden Horse EA, please refer to MQL5.

For detailed reviews and trading results of the Golden Horse EA, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/golden-horse-ea-review-unique-forex-software-at-discounted-price/).
