# 💻 Core math

### Swaps & Liquidity pools

#### Basic concepts

DEX is designed for digital asset exchange. Assets are exchanged within independent liquidity pools. Only one pool can exist for each pair. The fee for exchange operations in the pool is set automatically at the time of creation. Any user can create pools, add liquidity to existing pools, remove previously added liquidity, and exchange assets. Each operation is performed by calling the corresponding smart contract.

As the ratio may change during add liquidity transaction execution you fix one asset's amount and determine limits on the another. So in this example you may actually transfer **20 $ENX and 201.72 $ENQ.**

### Space Drops

#### Basic concepts

Pools is a mechanism to reward users who stake $ENX with arbitrary asset. Pool can be created by any user. After pool created it can be filled up with asset, and $ENX stakes can be put in. As long as pool has asset and there are staked $ENX, all stakeholders are rewarded with asset proportionally to their stakes. Distributed reward per time is set up by pool creator. Each stakeholder can do any actions with his stake (increase, decrease or take away) or take reward any time.

You can think of a pool as an actual pool which is filled with water pouring from reservoir, where water represents asset, pool represents staked $ENX, reservoir represents amount of asset to distribute and sink diameter represents reward per block. Water will pour as long is reservoir is not empty. The more pool area is, the slower water level rises.

At the beginning there are no stakes (pool area is zero), so no water pours from reservoir (asset is not spent). As first stake appears, pool area become equal to its size. E.g. stake is 10 $ENX.

Water begins to pour (rewards are added to stake), water level rises and water volume in reservoir decreases (asset is spending). If reward per block is 1 token per block, then _water_\__level_ is 10 units after 100 blocks.

Reward size is represented by water volume and can be calculated as _stake_ \* _water_\__level_. In our example **A** reward is 10 \* 10 = 100 tokens.

At block 100 two stakes (**B** and **C**) 10 $ENX each are added to pool. From this moment new reward has to be shared among all three stakes. But new stakes should not have affect on **A** reward. So we increase area of our pool, but make steps at current water level.

So, after 300 more blocks 300 tokens will be distributed over new stake, and water will be increased by 300 / 30 = 10 units and will be 20.

So, **A** reward will be 10 \* 20 = 200, while **B** and **C** reward will be 10 \* 10 each.

If stake **A** is removed, reward **A** (represented by water column over area **A**) moves to stakeholder balance. Taking reward while leaving stake is equivalent to removing stake and adding it again and can be made in one operation transparently for stakeholder.

###

###
