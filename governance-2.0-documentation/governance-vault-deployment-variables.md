---
description: >-
  Details on vault variables which can be changed in the future under a
  community vote
---

# Governance Vault Deployment Variables

The Governance Vault and associated Buyback Agent is deployed to mainnet, which is the first iteration of Governor's autonomous, on-chain revenue model. This is very important in the iterative road to "DAOification".Note that several tweaks have been made to deployment variables versus community testing on Rinkeby. Tweaks made are starred and explained below.**Governance Vault**

* Tax for non-POE holders: 3%
* Decaying withdrawal fee: 10%. -1% per 24 hours
* Timelock on deposit: 600 seconds\*

**Buyback Agent**

* Maximum Buyback: 0.75 ETH
* Minimum Buyback: 0.01 ETH\*
* Buyback cooldown: 259200 (72 hours)
* Revenue Split:\*
  * Governance Vault: 50%
  * Liquidity Add: 40%
  * Treasury: 7.5%
  * Buyback Executor: 2.5%
* Treasury address: 0xc597b10eB4DBabA8c6a887792b60AabcBF27e076

Timelock: Timelock has been changed from 0 to 600 as a future-proof defense against an attacker looking to leverage GDAO/xGDAO with flash loans. Mintable-through-contract tokens (like xGDAO) have been vehicles for flash loan attacks against lending platforms recently ([$130mm CREAM drain](https://www.coindesk.com/business/2021/10/27/cream-finance-exploited-in-flash-loan-attack-worth-over-100m/) for example). A short timelock on deposits defeats this attack vector.Minimum Buyback: Minimum buyback has been changed from 0 to 0.01 ETH in case of a nefarious "denial of service" style attack where users input 0 ETH (which is significantly cheaper gas-wise) to trigger the cooldown. This makes the DOS vector cost-prohibitive.Revenue Split: Revenue split has been shifted slightly to include a 7.5% draw back to the treasury. Contract deployments and POE signups cost the treasury significant amounts in gas, and this split will alleviate that draw.Treasury Address: Treasury has been set to [Gnosis GovBox](https://gnosis-safe.io/app/eth:0xc597b10eB4DBabA8c6a887792b60AabcBF27e076/balances) rather than [Aragon treasury](https://client.aragon.org/?#/gdao/0xaae388734ba304e77da770b04887e8e5801ddb5a/). This is due to the flexibility granted by Gnosis, which is important for quickly moving ETH for contract deployments as well as to more actively manage liquidity (treasury owned liquidity can be migrated to Uniswap V3 for better capital efficiency/lower slippage for users).Please see the [Vault User Guide](https://docs.governordao.org/how-to-section/governance-vault-user-guide) for more information about interacting with the Governance Vault.
