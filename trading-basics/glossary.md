---
icon: language
---

# Glossary

| Term                   | Description                                                                                                                      |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Perpetual Futures**  | Futures contracts with no expiration date, allowing positions to remain open as long as sufficient margin is maintained.         |
| **Long**               | A position that profits when the asset price increases.                                                                          |
| **Short**              | A position that profits when the asset price decreases.                                                                          |
| **Leverage**           | Allows you to control a larger position with less collateral.                                                                    |
| **Collateral**         | Funds deposited to open and maintain a leveraged position. Trench uses USDC as futures collateral.                               |
| **Position Size**      | The total value of your futures position, including leveraged exposure.                                                          |
| **Margin**             | The amount of collateral allocated to a position.                                                                                |
| **Cross Margin**       | Uses available account margin across positions to help maintain open trades.                                                     |
| **Isolated Margin**    | Allocates specific margin to an individual position, limiting its risk to that margin.                                           |
| **Entry Price**        | The average price at which a position was opened.                                                                                |
| **Mark Price**         | The reference price used to calculate unrealized PnL and liquidation.                                                            |
| **Liquidation Price**  | The price at which a position may be automatically closed when its margin is no longer sufficient.                               |
| **Unrealized PnL**     | The current profit or loss on an open position that has not yet been closed.                                                     |
| **Realized PnL**       | The profit or loss recorded after a position is closed.                                                                          |
| **ROE**                | Return on Equity; measures the profit or loss of a position relative to the margin used.                                         |
| **Funding Rate**       | A periodic payment exchanged between long and short traders to help keep the perpetual price aligned with the underlying market. |
| **Open Interest (OI)** | The total value of outstanding open futures positions in a market.                                                               |
| **Market Order**       | An order that executes immediately at the best available market price.                                                           |
| **Limit Order**        | An order that executes only at a specified price or better.                                                                      |
| **Stop Market**        | Triggers a market order once a specified trigger price is reached.                                                               |
| **Stop Limit**         | Triggers a limit order once a specified trigger price is reached.                                                                |
| **TWAP**               | Splits an order into smaller orders executed over a selected period to achieve a time-weighted average execution price.          |
| **Scale Order**        | Places multiple orders across a defined price range to gradually enter or exit a position.                                       |
| **Take Profit (TP)**   | An order that automatically closes a position when a target profit price is reached.                                             |
| **Stop Loss (SL)**     | An order that automatically closes a position when a specified loss threshold is reached.                                        |
| **Taker**              | A trader who executes against existing orders in the order book and takes liquidity.                                             |
| **Maker**              | A trader who places an order that adds liquidity to the order book.                                                              |
| **Slippage**           | The difference between the expected execution price and the actual fill price.                                                   |
| **Liquidation**        | The automatic closure of a position when its margin falls below the required level.                                              |
| **Order Value**        | The total market exposure of a position before accounting for leverage.                                                          |
| **Funding Countdown**  | Shows the time remaining until the next funding payment.                                                                         |
