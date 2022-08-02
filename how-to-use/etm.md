---
description: Enecuum Token Machine
---

# 🎰 ETM

Via ETM, you can easily issue custom tokens to be deployed on the Enecuum blockchain. 

![ETM interface](<../.gitbook/assets/image (39).png>)

## Token Types and Parameters

You can create tokens of the following three types on Enecuum: 

* **Reissuable** - a token with a flexible supply, that is, after the initial release the supply can be increased (_minted_) or decreased (_burned_). There is no maximum token supply restriction.
* **Non-reissuable** - a token with a fixed supply, that is, after the initial release the amount of tokens cannot be changed.
* **Mineable** - a token that, once released with an initial supply, can be mined by users until the maximum token supply cap is reached or the mining period has ended. 

The common parameters for all types of tokens are as follows:

* **Ticker** - short name of the token, comprising three or (a few more) letters. It will be displayed in most places on ENEX.SPACE.
* **Name** - full name of the token
* **Token Type** - one of the three token types described above, _reissuable_, _non-reissuable_, or _mineable_. 
* **Emission** - total token emission volume
* **Decimals** - decimal points, allowing 
* **Fee type** - transaction fee type & tokens in which the transaction fee is charged:
    *    _Flat_ - a fixed fee paid out to the token's issuer in _reward tokens_.
    *    _Percentage_ - a fee calculated as a percentage of the transaction's sum paid out to the token's issuer in _reward tokens_. In addition, you can set the _minimum fee_, e.g., the fee shall be 0.5% of the transaction's sum, but no less that 1 token.
    *    _Native_ - a fixed fee paid out to the token's issuer in the network's _native tokens_. 

* **Fee** - Fee amount, nominated in the tokens defined by the fee type setting (see above).

Mineable tokens have a number of additional parameters:

* **Premine** - the initial supply of tokens, once your token is created. 
* **Max(imum) Supply** - the maximum token emission; once reached, no new tokens can be mined.
* **Block Reward** - the reward for each mined macroblock, including the referral reward. 
* **Mining Period** - period (in days) since the issuing of the token when the mining can take place. 
* **Min(imum) Stake** - a minimum balance a user must possess in order to start mining stake to start mining. Note that it must be less of equal to the Referrer Stake (see below)
* **Referrer Stake** - a minimum balance a user must possess in order to become a _referral agent_. Having become a referral agent, the user can share the code with other prospective miners (_referrals_) and then receive rewards for blocks mined by those other miners. This system creates passive income. 
* **Ref(erral) Share** - the share of the total block reward that is equally distributed between the referral agent and its referral. 

## Issuing Non-Mineable (Reissuable or Non-Reissuable) Tokens

To issue a non-mineable token, click the **ETM** in the ENEX.SPACE side bar. The following page opens:

![issue token block](<../.gitbook/assets/image (44).png>)

Fill in the token's parameters and click **Issue Token**. You will be taken to the confirmation page, listing the properties of the token: 

![issue token block](<../.gitbook/assets/etm-token-issue-confirmation.png>)

Click **Confirm Supply** to proceed. The Enecuum wallet app window opens to confirm the payment of the fee for the token's creation. Click **Confirm** to proceed. 

Once the token is created, the initial ETM view is restored. You can view the newly created token's properties by going to Blockchain Explorer's Wallet view and clicking on the token's name under **Token Balance**.  

## Issuing Mineable Tokens

To issue a mineable token, click **ETM** in the ENEX.SPACE side bar and select _Mineable_ token type. The following page appears:

![issue token block](<../.gitbook/assets/etm-token-issue-mineable.png>)

Fill in the token's parameters and click **Issue Token**. You will be taken to the confirmation page, listing the properties of the token: 

![issue token block](<../.gitbook/assets/etm-token-issue-mineable-confirmation.png>)

Click **Confirm Supply** to proceed. The Enecuum wallet app window opens to confirm the payment of the fee for the token's creation. Click **Confirm** to proceed. 

Once the token is created, the initial ETM view is restored. You can view the newly created token's properties by going to Blockchain Explorer's Wallet view and clicking on the token's name under **Token Balance**.
