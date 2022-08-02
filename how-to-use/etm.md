---
description: Enecuum Token Machine
---

# 🎰 ETM

Via ETM you can easily issue custom tokens to be deployed on the Enecuum blockchain. 

![ETM interface](<../.gitbook/assets/image (39).png>)

The next thing you will see is options for your future token on the ENQ.&#x20;

![issue token block](<../.gitbook/assets/image (44).png>)

The common parameters for all types of tokens are as follows:

* **Ticker** - short name of the token, comprising three or (a few more) letters. It will be displayed in most places on ENEX.SPACE.
* **Name** - full name of the token
* **Token Type** - we need to elaborate on that, but that's how it goes along the API documentation: 
* * _reissuable_ - a token with a flexible supply, that is, after the initial release the supply can be increased (_minted_) or decreased (_burned_). There is no maximum token supply restriction.
* * _non-reissuable_ - a token with a fixed supply, that is, after the initial release the amount of tokens cannot be changed
* * _mineable_ - a token that, once released with an initial supply, can be mined by users until the maximum token supply cap is reached or the mining period has ended. 
* **Emission** - total token emission volume
* **Decimals** - decimal points, allowing 
* **Fee type** - transaction fee type & tokens in which the transaction fee is charged:
* * _Flat_ - a fixed fee paid out to the token's issuer in _reward tokens_.
* * _Percentage_ - a fee calculated as a percentage of the transaction's sum paid out to the token's issuer in _reward tokens_. In addition, you can set the _minimum fee_, e.g., the fee shall be 0.5% of the transaction's sum, but no less that 1 token. 
* * _Native_ - a fixed fee paid out to the token's issuer in the network's _native tokens_. 
* **Fee** - Fee amount, nominated in the tokens defined by the fee type setting (see above).b

Mineable tokens have a number of additional parameters:

* **Premine** - the initial supply of tokens, once your token is created. 
* **Max(imum) Supply** - the maximum token emission; once reached, no new tokens can be mined.
* **Block Reward** - the reward for each mined macroblock, including the referral reward. 
* **Mining Period** - period (in days) since the issuing of the token when the mining can take place. 
* **Min(imum) Stake** - a minimum balance a user must possess in order to start mining stake to start mining. Note that it must be less of equal to the Referrer Stake (see below)
* **Referrer Stake** - a minimum balance a user must possess in order to become a _referral agent_. Having become a referral agent, the user can share the code with other prospective miners (_referrals_) and then receive rewards for blocks mined by those other miners. This system creates passive income. 
* **Ref(erral) Share** - the share of the total block reward that is equally distributed between the referral agent and its referral. 

## Issuing Non-Mineable (Reissuable or Non-Reissuable) Tokens

To issue a token, fill out the token's parameters as shown below and click **Issue Token**:

![issue token block](<../.gitbook/assets/image (44).png>)

You will be taken to the confirmation page, listing the properties of the token: 

-- 



