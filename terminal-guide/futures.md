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

{% tab title="How to Fund?" %}
#### Option 1: Transfer from HyperCore

If you already have funds on Hyperliquid, you can transfer them directly into your futures account through the Deposit panel.

This is the fastest method for existing Hyperliquid users and allows you to start trading immediately without bridging assets.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-17 at 15.19.27@2x.png" alt=""><figcaption></figcaption></figure>

***

#### Option 2: Bridge from Your Existing Trench Wallet

You can also fund your futures account using assets from your existing Trench wallet.

Navigate to the **Bridge** section and transfer supported assets to your futures wallet. Funds will be converted and deposited as USDC collateral for futures trading.

Bridging is powered by our infrastructure partner - [Relay](https://relay.link) and typically completes within a few minutes.

<figure><img src="../.gitbook/assets/Screenshot 2026-06-17 at 15.20.42@2x.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}
