---
description: Here you can manage your assets in pools
---

# 🌊 Pool

## Getting Started with Pools 

A **Pool** is a mechanism to reward users that provide liquidity to the DEX. A Pool can be created by any user in the world. 

After the Pool is created, you can add assets to it. As long as the pool contains assets, the pool's stakeholders receive rewards from each trade in proportion to their liquidity share in the pool 

it can be filled up with assets. As long as pool has asset all stakeholders are rewarded with fees from each trade proportionally to their total liquidity share.\
Each stakeholder can do any actions with his liquidity (increase, decrease or take away) or take reward any time.&#x20;

**QUESTION: WHICH SCENARIO IS MORE IMPORTANT: ADDING LIQUIDITY TO AN EXISTING POOL OR CREATING A COMPLETELY NEW POOL FROM ZERO?**

So, below are **screenshots** of the **Pool** location:&#x20;

![home page](<../.gitbook/assets/image (6).png>)

## Add Liquidity

You provide tokens to the liquidity pool in a current pool's ratio. 
As an example, given the 1:100.000.000 BIT-SOS ratio in the pool, you should add simultaneously **10 $BIT** and **1.000.000.000 $ENQ** liquidity ($$\frac{10}{100000000} = \frac{1}{10}$$ ). ****&#x20;

![pool location](<../.gitbook/assets/image (1).png>)

When you add your token to a liquidity pool, you will receive **LP tokens** (liquidity provider tokens).\
For instance, if you deposit **$BIT** and **$SOS** into a liquidity pool, you will receive _BIT-SOS LP_ tokens.

![your liquidity](<../.gitbook/assets/image (32).png>)

The number of LP tokens you own shows your share of the BIT-SOS liquidity pool. You can always take your funds back by sending your LP tokens in exchange for **$BIT** and **$SOS**. But the proportion of $BIT and $SOS may vary based on the price change in the BIT-SOS pool. It is the risk the Liquidity Provider takes in exchange for the pool fees.

![adding liquidity](<../.gitbook/assets/image (19).png>)

![this's what you'll receive](<../.gitbook/assets/image (7).png>)

Next, you will see the baby-window again, waiting for you to confirm the operation in your wallet.

![waiting for confirmation](<../.gitbook/assets/image (34).png>)

After all the confirmations, you will be notified that the transaction was successful. Moreover, you will be asked to view information about the operation.&#x20;

![transaction was submitted](<../.gitbook/assets/image (14).png>)

## Creating a New Pool and Adding Liquidity To It

If you want to create a new pool to add liquidity to, you can do it yourself in a way similar to that of adding liquidity to an existing pool (see above). 

When creating a pool, you can set the initial exchange rate for the two tokens you add to the pool. This ration will quickly adjust as more liquidity providers add liquidity to the pool you have created, as well as through arbitrage.

When you're creating a new Pool, you will see the following once you've opened **Pool**: 

![pool 1st start](/img/pool-1st-start.png)

Click **Add Liquidity**. The following window appears:

![pool 1st liquidity input](/img/pool-1st-liquidity-input.png)

The window has two input blocks:

* Token 1 input

Here you can input the first token (Token 1) in the Pool. By default, this is the default token in your wallet; you can select another token using the dropdown to the right of the **Input** field. **Balance** shows your wallet's current balance as to the selected token. 

* Token 2 input

Here you can select the amount of the second token (Token 2) in the Pool. You should select the token from the dropdown to the right of the **Input** field. 

Once you've selected Token 2 and input the value, the windows looks like this: 

![pool both tokens](/img/pool-1st-liquidity-both-tokens.png)

**Price And Pool Share** section shows the following values: 
* Price of Token 1 nominated in Token 2
* Price of Token 2 nominated in Token 1
* Share of the amount of tokens you want to input in the pool

**LP tokens in your wallet** under **Add Liquidity** button shows the following:

* Amount of liquidity pool tokens you have at the moment
* Amount of Token 1 to be added
* Amount of Token 2 to be added

To proceed with adding tokens, click **Add liquidity**. The confirmation window opens:

![pool 1st confirmation](/img/pool-1st-liquidity-confirmation.png)

This window shows the following information:

* Amount of liquidity pool tokens you will receive, once the liquidity is added
* Amount of Token 1 to be deposited
* Amount of Token 2 to be deposited
* Price of Token 1 nominated in Token 2
* Price of Token 2 nominated in Token 1
* Transaction fee for the adding of liquidity
* Share of the amount of tokens you want to input in the pool

Review this information and, if you want to proceed, click **Confirm Supply**. The Enecuum Wallet confirmation window opens:

![pool 1st wallet confirmation](/img/pool-1st-liquidity-wallet-confirmation.png)

This window gives the details of the transaction fee you should pay as you add liquidity. Click **Confirm** to proceed. 

![pool tx submitted](/img/pool-1st-liquidity-tx-submitted.png)

You can click **View on ...enecuum.com** to view the transaction properties in Blockchain Explorer. The following page opens:

![pool tx info](/img/pool-1st-liquidity-tx-info.png)

**Parameters** section includes the following information:

* **Type**: transaction type (**Add Liquidity** in this case)
* **Asset 1**: Token 1 hash
* **Amount 1**: Token 1 amount
* **Asset 2**: Token 2 hash
* **Amount 2**: Token 2 amount

**Additional** section shows the amount of LP tokens you have received for adding liquidity to the pool. 

If you don't want to view the transaction properties, just click **Close** to close that window. 

### Adding Liquidity to an Existing Pool

To add liquidity to an existing pool, got to **Pool** as described in **Getting Started with Pool**. The following window opens:

![pool add more](/img/pool-add-more-start.png)

You can see the following information here:

* Token pair name (tickers of Token 1 and Token 2)
* Pooled Token 1: amount of Token 1 in the pool
* Pooled Token 2: amount of Token 2 in the pool
* Your Pool Tokens: the amount of LP tokens you have at the moment
* Pool Share: your share in the pool as of now

Click **Add** to proceed. The further steps are the same as described above in **Add Liquidity**.


## Removing Liquidity From a Pool

To remove liquidity from a pool, open the pool and click **Remove**. The following window opens:

![pool remove selector](/img/pool-remove-liquidity-selector.png)

Here you can select the liquidity share you wish to remove from the pool, either by using the slide or clicking on the preset values of 25%, 50%, 75%, or MAX for the maximum possible liquidity withdrawal. 

If you want to see the amount of LP tokens involved in the liquidity withdrawal, click **Detailed** above the slider. The window will expand so that it looks as follows: 

![pool remove selector detailed](/img/pool-remove-liquidity-selector-detailed.png)

The top token selector shows the amount of LP tokens that (?? gets returned) as you remove liquidity from a pool. The next two token selectors show the amount of Token 1 and Token 2, respectively, to be withdrawn. 

**Price** displays the price of Token 1 and Token 2 in the same way as elsewhere in the Pool interface.

Click **Remove Liquidity** to proceed. The confirmation window appears:

![pool remove liquidity confirmation](/img/pool-remove-liquidity-confirmation.png)

You can see how many Token 1 and Token 2 you will receive, once the liquidity removal is accomplished. Click **Remove liquidity** to proceed. **ENEX.SPACE** warning window opens: 

![pool remove warning](/img/pool-remove-liquidity-pool-warning.png)

At the same time, Enecuum Wallet transaction confirmation window opens:

![pool remove wallet confirmation](/img/pool-remove-enecuum-wallet-confirmation.png)

Once you have confirmed the transaction, the transaction confirmation window opens. **Click View on...** to view the transaction information in Blockchain Explorer:

![pool remove tx info](/img/pool-remove-liquidity-tx-info.png)

If you don't want to view that information, just close the window. 









### A2A

By the way, at [**ENEX**](https://devapp.enex.space/#!action=pool\&pair=BIT-ENX\&from=0000000000000000000000000000000000000000000000000000000000000001\&to=824e7b171c01e971337c1b25a055023dd53c003d4aa5aa8b58a503d7c622651e) **** you can create a liquidity pool with any token, issued over Enecuum Network and any tokens — any to any (A2A).&#x20;

Here you can read more about ETM:&#x20;

ETM LINK
