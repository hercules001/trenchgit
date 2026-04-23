---
description: Slippage is one of the most important concepts in on-chain trading.
icon: person-falling-burst
---

# Slippage

{% hint style="info" %}
Slippage is the difference between the **expected price** and the **actual execution price**.

This happens because prices can change while your transaction is being processed.
{% endhint %}

***

### Why Slippage Happens

* Fast price movement
* Low liquidity
* Large order size
* High competition (many users buying at once)

### Example

You try to buy a token at $1.00.

* You set slippage to 5%
* Your trade may execute between $1.00 and $1.05

If the price moves beyond that range, the transaction fails.

***

### Low vs High Slippage

**Lower slippage (1–2%)** gives you **better price control**, but increases the chance that your transaction may fail if the price moves too quickly. This is typically suited for **stable markets or established tokens** where price movement is slower and more predictable.

**Higher slippage (5–30%+)** increases the **likelihood of execution**, especially in fast-moving or competitive environments, but comes with the risk of getting a **worse entry price**. This is commonly used for **new token launches or low-liquidity tokens** where prices can change rapidly.

***

### How Slippage Works on Trench

Before trading, you choose your slippage tolerance.

Trench uses this to:

* Protect you from large price changes
* Decide whether to execute or cancel your trade

***

### Summary

Slippage controls the balance between:

* Price accuracy
* Execution success
