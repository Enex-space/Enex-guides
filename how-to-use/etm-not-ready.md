---
description: Enecuum Token Machine
---

# 🎰 ETM (not ready)

Via ETM you can easily issue custom token to be deployed on the Enecuum blockchain. 

(tokenomics to be added)

![ETM interface](<../.gitbook/assets/image (39).png>)

The next thing you will see is options for your future token on the ENQ.&#x20;

![issue token block](<../.gitbook/assets/image (44).png>)

The parameters are as follows:

* **Ticker** - short name of the token, comprising three or (a few more) letters. It will be displayed in most places on ENEX.SPACE.
* **Name** - full name of the token
* **Token Type** - we need to elaborate on that, but that's how it goes along the API documentation: 
* * _reissuable_ - a token with a flexible supply, that is, after the initial release the supply can be increased (_minted_) or decreased (_burned_). There is no maximum token supply restriction.
* * _non-reissuable_ - a token with a fixed supply, that is, after the initial release the amount of tokens cannot be changed
* * _mineable_ - a token that, once released with an initial supply, can be mined by users until the maximum token supply cap is reached.  
* **Emission** - token emission volume (equal to total supply in the API? what to we do with mineable tokens, then, how do we set max_supply for them?)
* **Decimals** - 
* **Fee type** - transaction fee type & tokens in which the transaction fee is charged:
* * _Flat_ - a fixed fee paid out to the token's issuer in _reward tokens_.
* * _Percentage_ - a fee calculated as a percentage of the transaction's sum paid out to the token's issuer in _reward tokens_. 
* * _Native_ - a fixed fee paid out to the token's issuer in the network's _native tokens_
* **Fee** - Fee amount (nominated in accordance with the fee type setting)
