---
description: >-
  A quick guide to common transaction errors, helping you diagnose issues and
  retry with the right adjustments.
icon: rotate-exclamation
---

# Common Errors

| Error                                              | What it means                          | What to do                                         |
| -------------------------------------------------- | -------------------------------------- | -------------------------------------------------- |
| Slippage exceeded                                  | Price moved beyond your allowed range  | Increase slippage or retry quickly                 |
| Insufficient tokens                                | Not enough token balance               | Check balance and retry                            |
| Insufficient funds                                 | Not enough balance for trade or fees   | Add funds and keep extra for network fees          |
| Pool liquidity too low                             | Not enough liquidity in the pool       | Avoid the token                                    |
| Transaction timed out                              | Transaction not processed in time      | Retry or increase priority fee, bribe, or slippage |
| Pool not open yet                                  | Trading has not started for this token | Wait and retry                                     |
| Order size is smaller than the current requirement | Trade size too small                   | Increase trade amount                              |
| Price out of allowed range of the pool             | Price moved outside allowed range      | Retry with higher slippage                         |
| Cannot find your token account                     | Wallet state not updated               | Refresh and retry                                  |
| Arithmetic overflow, try increasing slippage       | Calculation failed due to limits       | Increase slippage or reduce size                   |
