---
description: Summary of NFT sale options and considerations when planning sale
---

# Permissioned NFT Sale Scope



**PoE Permissioned NFT Sale Scope**\
****

**Summary**

Proof-of-Existence \[PoE] enables NFT sales to leverage the notion that users are only interacting with one account \[wallet]. This allows a more nuanced, advanced gamified approach to NFT sales that is not otherwise possible (most “games” reflect additional restrictions that can be bypassed when using multiple wallets).\
****

**There are two different avenues for approaching PoE integration:**\
****

**1] Tiered sales**

Tiered sales work on the assumption that both PoE and non-PoE users can participate, and emphasizes different sets of privileges for PoE holders only\
****

**2] Permissioned sales.**&#x20;

Permissioned sales are for PoE users ONLY who are verified as unique through biometrics, which are tailored to apply additional restrictions for fairer and more exciting NFT launches.\
****

The following will outline two different mechanisms for specifying sales. The first section is different ways to tier the sales. The second is how to gamify for the permissioned tier. Gamification elements can be applied to the PoE tier ONLY. You can gamify PoE and restrict non-POE. You cannot gamify non-PoE (as folks will just bypass the gamification you put into place).

### **PoE vs Non-PoE Tiering**

There are two main ways to make a distinction between PoE and non-PoE holders. \
****

**1] Pre Launch mint window**

POE holders can have a start time before non-POE holders, perhaps 24 hours before non-POE holders. Also can be seen as a presale. POE holders have the opportunity to mint at their leisure prior to a public release \[Non-PoE] when the masses would potentially challenge the network hence engaging in a ‘gas war’ resulting in potentially large out-of-pocket gas fees.\
****

**2] Incentivisation conditions for PoE holders**

The second way to do it is to provide a different set of minting terms. POE holders can have a cheaper rate to mint (for any amount of mints). They can have a decaying discount that ultimately normalizes with the non-PoE sale price. A consideration would be a free first mint.

### **PoE Sale Gamification**

Because we can limit PoE holders to participation on just one account, we can put various restrictions on the sale to level the playing field.\


The most obvious example demonstrated with the inaugural [YCSM](https://opensea.io/collection/ycsm-1) mint, is a straight one-mint-per-person limitation. You can ensure that no individual mints more than one of an NFT.\


You can also make a ramp-up cost, where each additional NFT mint is more expensive than the last. For example, the first mint is free, and each additional mint is +0.01 ETH.\
\
You can have a minting cooldown, where users can mint one NFT every hour until all are sold.\


You can do a dutch auction, where the price decreases over time until all are sold.\


You could do a cliff, where the first n mints are x price and additional mints are 10x price.\
****

### **Modifiers Table**

| **Sale type**        | **Description of conditions**                                                            |
| -------------------- | ---------------------------------------------------------------------------------------- |
| **Pre-Sale**         | **POE holders get \<time> to mint before global sale starts**                            |
| **Pricing Tiers**    | **POE holders get to acquire \<amount> of NFTs at a cheaper price than non-POE holders** |
| **Freebie**          | **POE holders get one free NFT mint each**                                               |
| **Limit per-person** | **POE holders can claim up-to \<max> NFTs in a mint**                                    |
| **Ramp Up Sale**     | **Each additional mint per person is more expensive than the last**                      |
| **Cooldown**         | **One mint at-a-time with a timelock between additional mints**                          |
| **Dutch Auction**    | **Price decreases over time until all nfts are minted**                                  |
| **English Auction**  | **Price increases over time until all nfts are minted**                                  |
| **Cliff Pricing**    | **One price up-to \<number> of mints. Higher price after.**                              |
