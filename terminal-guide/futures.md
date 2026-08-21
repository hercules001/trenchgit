---
icon: money-bill-trend-up
---

# Futures



{% tabs %}
{% tab title="Future Basics" %}
## Futures Trading Basics

Futures contracts allow traders to gain exposure to an asset's price movement without owning the underlying asset.

Powered by Hyperliquid, Trench provides access to global futures markets including cryptocurrencies, commodities, indices, stocks, and foreign exchange (FX) — all from a single terminal.

***

### Long & Short Positions

#### Long

A long position profits when the asset price increases.

**Example:**

* Enter BTC at $100,000
* BTC rises to $105,000
* Position generates profit

#### Short

A short position profits when the asset price decreases.

**Example:**

* Enter a short on BTC at $100,000
* BTC falls to $95,000
* Position generates profit

***

### Leverage

Leverage allows traders to control a larger position using a smaller amount of collateral.

**Example:**

* $100 collateral
* 10x leverage
* $1,000 position value

While leverage can amplify profits, it can also amplify losses.

***

### Margin Modes

#### Cross Margin

Cross margin shares available collateral across all open positions.

**Benefits:**

* Reduced liquidation risk
* Better capital efficiency

#### Isolated Margin

Isolated margin allocates collateral to a specific position.

**Benefits:**

* Risk limited to a single position
* Easier position-level risk management

***

### Order Types

#### Market Order

Executes immediately at the best available market price.

Best used when execution speed is more important than a specific entry price.

#### Limit Order

Executes only at a specified price or better.

Best used when targeting a precise entry or exit.

#### Stop Market Order

Triggers a market order once a specified stop price is reached.

Commonly used for stop losses or breakout entries where execution is prioritized over price precision.

#### Stop Limit Order

Triggers a limit order once a specified stop price is reached.

Provides more control over execution price but may not fill if the market moves quickly.

#### TWAP (Time-Weighted Average Price)

Splits a large order into smaller orders executed over a period of time.

Helps reduce market impact and achieve a more consistent average execution price.

Best suited for larger position sizes.

#### Scale Order

Allows multiple orders to be placed across a price range automatically.

Instead of entering a position at a single price, traders can gradually scale into or out of a position.

**Useful for:**

* Building positions over time
* Managing volatility
* Averaging entries and exits

***

### Collateral

Collateral is the capital used to open and maintain a leveraged position.

Futures trading on Trench uses **USDC collateral**.

The amount of collateral and leverage selected determines your total position size.

***

### Liquidation Price

The liquidation price is the level at which a position is automatically closed to prevent further losses.

Higher leverage generally moves the liquidation price closer to the current market price.

Monitoring liquidation risk is an important part of futures trading.

***

### Funding Rate

Funding is a periodic payment exchanged between long and short traders.

Funding helps futures prices remain aligned with the underlying market.

Depending on market conditions:

* Longs may pay shorts
* Shorts may pay longs

***

### Open Interest

Open Interest (OI) represents the total value of active futures positions.

Increasing OI often indicates growing market participation and positioning.

***

### Why Trade Futures?

Futures markets provide:

* 24/7 market access
* Long and short exposure
* Capital-efficient leverage
* Access to global markets
* Advanced risk management tools
* The ability to hedge existing positions
{% endtab %}

{% tab title="How to Trade" %}
Taking your first trade on Trench is simple. Choose a market, configure your position, review your order, and execute.

#### 1. Choose a Market

Open the **Futures** section and select the asset you want to trade.

You can switch markets using the asset selector at the top-left of the trading interface. Review the chart and key market data before entering a position.

<figure><img src="../.gitbook/assets/Screenshot 2026-08-21 at 08.29.26@2x.png" alt=""><figcaption></figcaption></figure>

#### 2. Choose Your Direction

Decide whether you want to **Long** or **Short**.

* **Long** — You profit if the asset price increases.
* **Short** — You profit if the asset price decreases.

Select the corresponding button on the trading panel.

<figure><img src="../.gitbook/assets/Screenshot 2026-08-21 at 08.31.57@2x.png" alt=""><figcaption></figcaption></figure>

#### 3. Set Your Leverage

Choose your leverage using the leverage selector.

Higher leverage gives you greater market exposure with less collateral, but also increases your risk. The maximum available leverage depends on the market.

<figure><img src="../.gitbook/assets/Screenshot 2026-08-21 at 08.32.46@2x.png" alt=""><figcaption></figcaption></figure>

#### 4. Choose Your Order Type

Select how you want your order to execute:

* **Market** — Execute immediately at the best available price.
* **Limit** — Execute only at your selected price.
*   **Advanced** — Access additional order types such as Stop Market, Stop Limit, TWAP, and Scale.\
    <br>

    <figure><img src="../.gitbook/assets/Screenshot 2026-08-21 at 08.33.26@2x.png" alt=""><figcaption></figcaption></figure>

#### 5. Enter Your Position Size

Enter the amount you want to use for the trade in **USDC**.

Your order panel will show your **collateral amount** and resulting **position size** based on your selected leverage.

You can also use the percentage selector to quickly allocate a portion of your available margin.

<figure><img src="../.gitbook/assets/Screenshot 2026-08-21 at 08.34.46@2x.png" alt=""><figcaption></figcaption></figure>

#### 6. Choose Margin Mode

Select between:

* **Cross** — Shares available margin across your positions.
* **Isolated** — Keeps margin allocated to this position separately.

Choose the mode that best fits your risk management approach.

<figure><img src="../.gitbook/assets/Screenshot 2026-08-21 at 08.35.36.gif" alt=""><figcaption></figcaption></figure>

#### 7. Add TP / SL

You can optionally enable **Take Profit / Stop Loss (TP/SL)** before placing your order.

These allow you to automatically manage your position when your target price or maximum acceptable loss is reached.

<figure><img src="../.gitbook/assets/Screenshot 2026-08-21 at 08.38.12@2x.png" alt=""><figcaption></figcaption></figure>

#### 8. Review & Place Your Order

Before confirming, review your:

* Direction
* Leverage
* Order type
* Position size
* Margin mode
* Estimated liquidation price
* TP/SL settings

Once everything looks right, click **Place Order**.

<figure><img src="../.gitbook/assets/Screenshot 2026-08-21 at 08.39.16.gif" alt=""><figcaption></figcaption></figure>

Your position will then appear in the **Positions** tab below the chart, where you can monitor its size, entry price, liquidation price, unrealized PnL, and TP/SL.

#### 9. Closing a Position

To close a position, click **Close** and choose **Market Close** to exit immediately, or enter a **Limit Price** if you want more control over your execution price.<br>
{% endtab %}
{% endtabs %}
