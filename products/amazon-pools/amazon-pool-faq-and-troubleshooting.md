# Amazon Pool FAQ & Troubleshooting





## Troubleshooting

### **I can't find the Amazon Pool I was staking in!**

You should be able to find the Amazon Pool under the “Finished” tab on the Amazon Pools page.

By selecting “Staked Only”, it will make it easier to find your assets.

### **Why can’t I unstake my tokens from a Amazon Pool?**

If you are unable to unstake from the Stake DEX, Earn DEX pools, please check to make sure that you haven’t sold the Amazon tokens in your wallet. This token acts as a \`proof of ownership\` over your DEX in the Manual DEX pool.

### **Why did my earned tokens go to zero after staking/unstaking?**

Don’t worry! They’re in your wallet already.

Whenever you stake or unstake from a Syrup Pool or farm, your earned tokens get harvested and sent to your wallet at the same time.

## **General Questions**

### How is APR for Amazon Pools calculated?

> Amazon Pool APR = Annualized rewards (USD) / User funds staked in Amazon Pool (USD) \* 100

As a basic example, let's take a 60-day pool with 300,000 USD worth of rewards, and 3,000,000 USD worth of DEX staked in it.

The APR fluctuates as more DEX is staked by users, and as the price of DEX, and the reward token, vary.

|                                                       | **Calculation**                  | Amount            |
| ----------------------------------------------------- | -------------------------------- | ----------------- |
| Total rewards to distribute (USD value)               |                                  | 300,000 USD       |
| Distribution period                                   |                                  | 60 days           |
| Daily distribution                                    | 300,000 / 60 =                   | 5,000 USD daily   |
| **Annualised rewards (USD value)**                    | 5,000 \* 365 =                   | **1,825,000 USD** |
| **Value of ADEX staked by users in pool (USD value)** |                                  | **3,000,000 USD** |
| **APR**                                               | (1,825,000 / 3,000,000) \* 100 = | **60.833% APR**   |

### **What does the “End” number on my Amazon Pool refer to?**

This shows the amount of blocks left until the rewards for that pool stop being distributed. Once the pool has reached that block, you should unstake your tokens, because you won’t be receiving any rewards after that.

### **Where do the rewards from Amazon Pools come from?**

There are three main types of Amazon Pools.

1. Stake Amazon earn DEX
2. Stake DEX, earn other tokens.
3. Stake other tokens, earn DEX

The rewards for the "Stake DEX, earn "DEX" Amazon Pools come from the DEX emissions. Each block, a number of ADEX tokens are allocated as rewards for these pools.

The rewards for the "Stake DEX, earn other tokens" type are provided by the project teams who sponsor an Amazon Pool.

For the "Stake other tokens, earn DEX" type, the Dex Asian treasury buys back DEX from the market to distribute as rewards. These pools are funded by Alpine Dex, not by the projects themselves.

### What’s Amazon Token?

Dex Asian’s Amazon Token is deposited in your wallet when you interact with the **Manual** “Stake DEX, Earn DEX” Amazon Pool. It's not staked for

It’s basically an IOU that shows how much DEX you’ve staked in the pool.

It’ll be returned automatically when you unstake your DEX from that pool.

{% hint style="warning" %}
Don’t sell your Amazon tokens! You need to return your Amazon to unstake your DEX from the Manual DEX pool. The amount of Amazon you return must be the same as the amount of DEX you unstake.
{% endhint %}
