---
description: Zap in - Zap Out. Adding and Removing Liquidity becomes much simpler.
---

# ⚡ ZAP

<figure><img src="../.gitbook/assets/zap.png" alt=""><figcaption></figcaption></figure>

**ZAP** is zkSwap Finance’s smart liquidity tool that lets users add or remove liquidity using **any ratio of two tokens**, eliminating manual balancing and multi-step transactions.

It simplifies liquidity provision for both **Classic Pools (V2)** and **Concentrated Liquidity Pools (V3)**, performing all required swaps and liquidity actions in a **single seamless transaction**.

### 🎯 ZAP for Concentrated Liquidity Pools (V3)

Adding liquidity to V3-style pools can be complex due to custom ranges and non-50/50 ratios.

**ZAP V3** solves this by letting you add liquidity using any proportion of the two pool tokens. The system automatically handles balancing and price range placement.

#### Zap In — Add Liquidity with Any Ratio

* Input any ratio of the two pool tokens (e.g., 80% USDC and 20% S).
* ZAP simulates optimal swap routes via the integrated aggregator.
* On-chain, it revalidates pool state and adjusts for slippage or price drift.
* Tokens are optimally converted and added into your selected price range.
* You receive a **Liquidity Position NFT**.

**Example:** You’re adding to the **S–USDC** pool. You can supply any ratio, such as mostly USDC or mostly S. ZAP automatically converts and balances your inputs to match the current pool ratio and your selected price range, then mints your Liquidity Position NFT.

#### Zap Out — Withdraw to One Token or Any Ratio

* Choose a single token or any ratio between both tokens to receive on withdrawal (e.g., only USDC).
* ZAP auto-converts all assets from your NFT position to your chosen token(s).

#### Built-In Safety

* Slippage Protection: Reverts if swap output is too low.
* Min Liquidity Check: Reverts if added liquidity doesn't meet expectations.

#### Benefits

* 🧠 Handles complex liquidity logic behind the scenes
* 🤖 Adaptive on-chain rebalancing at execution time
* 🔁 Eliminates leftover or idle tokens
* ⚡ Aggregator-powered for best swap efficiency

### 🌀 Zap for Classic Pools (V2 Pools)

Classic pools normally require liquidity in a strict **50/50 ratio**.\
With ZAP, you can supply **any ratio of the two tokens**, and the system automatically balances them to the required 50/50 composition.

#### **Zap In –** Add Liquidity with Any Ratio

* Supply any ratio of the two tokens (e.g., mostly USDC, less ETH).
* ZAP performs the necessary swap to reach a 50/50 balance.
* Adds both tokens into the pool and returns your LP tokens.

**Example:** You want to add to the USDC-ETH pool, but only have USDC. ZAP converts a portion of your USDC into ETH and adds the pair into the pool in the correct proportions. Then Zap returns the LP tokens to your wallet.

#### **Zap Out – Withdraw and Receive with Any Ratio**

* Remove liquidity and choose to receive a single token or both tokens.
* ZAP converts both sides of your LP tokens into your chosen token(s) (e.g. only USDC).
* Helps avoid unwanted assets and reduces post-withdrawal swap steps.

#### Benefits

* 💡 Simple UI, single transaction
* ⛽ Fewer gas fees
* 🧠 No need to calculate token ratios manually
* 🔁 Aggregator-powered for best swap efficiency



**ZAP** facilitates the uncomplicated adding or removal of liquidity, allowing users to specify the amount of desired tokens they wish to add or receive.

Enhancing user experience remains a central focus for all zkSwap Finance products, and ZAP represents a novel feature designed to make liquidity provision more accessible, particularly for those new to the DeFi landscape. This update aims to attract a broader user base to zkSwap Finance, allowing them to explore the intricacies of DeFi effortlessly.
