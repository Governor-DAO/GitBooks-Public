---
description: Common terminology used throughout the Governor DAO ecosystem
---

# 📓 Glossary of Terms

### **Glossary**

#### **General Blockchain**

**ERC20:** Standard token format for fungible assets on the Ethereum blockchain. GDAO is an ERC20.\
****

**Gas:** The ETH fee required to send transactions on the Ethereum blockchain.\
****

**Smart Contracts:** Codified interactions that exist on the blockchain. Smart contracts assert a financial exchange between two or more parties.\
****

**On-Chain:** Interactions that happen on the blockchain. Ownership, revenue management, products, and more that exists on the blockchain: which ensures that those activities are decentralized, transparent, and infallible.\
****

**Decentralized Exchange (DEX):** A cryptocurrency exchange that is permissionless (ie: anyone can participate) and orders happen on-chain via smart contracts. There is no middleman in a DEX: buyers and sellers interact with each other directly in a secure manner that prevents any party from being taken advantage of.\
****

**Automated Market Maker (AMM):** A particular instance of a decentralized exchange where all liquidity (collective buy and sell orders) are pooled together. Traders can only place market buys/sales and the price moves up or down with every trade.\
****

**Liquidity/Liquidity Providing:** The act of contributing capital to an AMM where it is used as the order book for traders to sell into/buy out of.\
****

**Decentralized Autonomous Organization (DAO):** A tokenized entity (almost akin to a corporation) where ownership and management responsibilities are delegated to token holders.

#### **Governor DAO Terminology**

**xGDAO:** The revenue sharing, governance, and ownership token at the center of the Governor DAO ecosystem. xGDAO is a derivative of GDAO, initially pegged 1:1, with the GDAO value of xGDAO increasing with revenue realized. Users can always mint xGDAO using GDAO and redeem xGDAO back for the underlying GDAO with no penalty\*

**\*Subject to decay conditions detailed on an early withdrawal**\
****

**Governance Vault:** The smart contract that owns other Governor DAO smart contracts. Ownership represents the ability to upgrade, replace, and phase out these contracts. Ownership decisions from the Governance Vault are made via consensus among the xGDAO holders who participate in this vault.\
****

**Revenue Splitter:** A smart contract that handles on-chain sales of GDAO products (initially, Proof-of-Existence signups). It designates the different destinations of ETH from incoming sales (ie: splitting some % to referrers, some % to Buyback Agent, etc.).\
****

**Buyback Agent:** A smart contract responsible for Governor DAO revenue strategy. On-chain revenue is sent to the Buyback Agent, which then converts and sends to destinations as needed. Buyback Agent will buy GDAO from the open market to deliver to xGDAO participants as revenue share, as well as to replenish the treasury and add liquidity.\
****

**Proof-of-Existence (POE):** Governor DAO’s biometric blockchain product that tags Ethereum addresses as belonging to provably unique individuals. The POE itself is a non-transferrable ERC20 that is anchored to the wallets of users who sign up. Any developer can reference that POE token to create authenticated smart contracts.\
