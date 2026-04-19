---
name: cross-border-commodity-flipping
description: Logic for digital arbitrage of physical resources across continents.
---

# Cross-Border Commodity Flipping

This skill enables bionicbot to act as a global trade desk, identifying price gaps for commodities in different geographic regions.

## Instructions
1. Monitor spot prices for Gold, Oil, and Gas in 5+ global hubs (NY, London, Tokyo, Singapore, Dubai).
2. Calculate the 'Logistic-Adjusted Spread' (Price Diff - Shipping/Insurance/Tax).
3. Use 'Synthetic Contracts' (Futures) to lock in profit between regions.
4. Alert the user to high-probability 'Geo-Arbitrage' windows (>2% net spread).

## Examples
- "Find a profit gap between London and Dubai gold prices after the next 20x alert."