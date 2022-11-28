---
description: >-
  Trade, earn, issue and raise at ENEX.SPACE with uncompromising security and
  extremely low fees!
---

# 🚀 Welcome to ENEX.SPACE

## Overview

**ENEX** is the first DeFi platform powered by [**Enecuum Network.**](https://enecuum.com/)

ENEX.SPACE is a DeFi platform built on the Enecuum blockchain. ENEX.SPACE functions based on the ENX token. ENX benefits from overall liquidity in ENEX.SPACE and can be used to gain profit from trading operations. From the user’s point of view ENEX.SPACE consists of:

{% content-ref url="how-to-use/Swap.md" %}
[Swap.md](how-to-use/Swap.md)
{% endcontent-ref %}

{% content-ref url="how-to-use/pool.md" %}
[pool.md](how-to-use/pool.md)
{% endcontent-ref %}

{% content-ref url="how-to-use/top-pairs.md" %}
[top-pairs.md](how-to-use/top-pairs.md)
{% endcontent-ref %}

{% content-ref url="how-to-use/etm/" %}
[etm](how-to-use/etm/)
{% endcontent-ref %}

{% content-ref url="how-to-use/harvest-farms/" %}
[harvest-farms](how-to-use/harvest-farms/)
{% endcontent-ref %}

{% content-ref url="how-to-use/space-drops/" %}
[space-drops](how-to-use/space-drops/)
{% endcontent-ref %}

{% content-ref url="how-to-use/station.md" %}
[station.md](how-to-use/station.md)
{% endcontent-ref %}

## Commander ENEX

Commander is entity which has full access to treasury. **Treasury** is filled up with fees from pool trades in form of LP tokens(see [**Pools** ](how-to-use/pool.md)section). Some of these tokens are traded to ENX via liquidity pools. Commander ENEX occasionally sells these LP tokens for ENX. Tokens which cannot be traded to ENX are sent to burn address. All exchanged ENX are sent to [**Station**](how-to-use/station.md) for distribution.

On picture above, there are three liquidity pools. Trading fees are gathered in treasury in form of LPs:

![](<.gitbook/assets/image (18) (2).png>)

* Whiskey/Cola with LPwc liquidity token,
* Gin/Tonic with LPgt liquidity token,
* LPwc/ENX with LPwc\* liquidity token.

In time, treasury is filled up with LPwc, LPgt and LPwc\*.

As long as there is traiding pair LPwc/ENX, LPwc tokens are traded to ENX, while LPgt and LPwc\* are burned.

## Key points

When you use traditional **Uniswap-like AMM DEXes**, you always make so called "approve" operation. If you confirm it by default, you allow all possible amount of approved token to be managed by the DEX smart contract. This is a serious security problem as it **breaks one of the main principles of a cryptocurrency** --- the owner and only the owner of assets should have full control over the assets. Architecture of Enecuum Network without approval functionality opposite to Ethereum based blockchains **make your pools secure and leave you full control over the funds**.
