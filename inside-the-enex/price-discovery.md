---
description: Aggregated prices in Pools and a way to find the USD value
---

# 📈 Price Discovery

### Value in USD

General idea is described in the following Figma diagram. Details will be supplied later.

{% embed url="https://www.figma.com/file/k8qiaGIGVeeCFeY45Aihq9/Enecuum-%24%24%24-token-price-flow?node-id=0%3A1" %}

### Aggregated Pool Prices

To have on-chain price oracles we are implementing aggregated price for each Enex Pool. That price will be dependent on the hole history of swaps in the pool. Thus removing short-term price fluctuations to make price information robust to various kinds of manipulations.&#x20;
