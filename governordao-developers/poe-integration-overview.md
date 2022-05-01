# POE Integration Overview

The universal Proof-of-Existence whitelist can be integrated permissionlessly into any smart contract.

Developers can "authenticate" contract calls by requiring the addresses executing those calls to hold the ERC20 POE token.

The base integration of "only authenticated users can call this function" can be achieved by pasting the following requirement statement into the desired write function:

```
require(IERC20(0x5945bAF9272e0808165aDea61b932eC1604FB161).balanceOf(msg.sender) == 1, "Need to authenticate first!");
```

The 'require' syntax asserts that a logic statement resolves true in order for a contract call to execute. This line requires that the address calling the contract \<msg.sender> holds exactly 1 POE.

POE balance of an address is binary, they can only ever be 1 (authenticated) or 0 (non-authenticated).

#### NOTE: For cleaner code, initialize the POE token address as a global variable and reference that variable in the 'require' statement in place of the address itself.

### Building Authenticated Logic

With a POE balance requirement in place, developers can easily add gamification to their contracts and platform mechanics.&#x20;

Some of the (otherwise not possible) gamification/logic improvements could include...

#### Token Sale/NFT Mint

* Individual "cap" on mints or size of purchase
* Anti-Whale price curve: each additional purchase is more expensive than the last
* One-claim-per-person with a free or fixed rate
* Pre-sale phase where authenticated users get a grace period to interact without competing for gas

#### Token Contracts

* Max/Minimum allowed balance per user (ie: NFT that is limited to one-per-person)
* "Bot-Free" Trading

#### DeFi Games

* Capped or anti-whale yield farming/liquidity providing
* Modified weight-based pools (minimum and maximum weight)

#### Governance

* Democratic voting (one-vote-per-person)
* Logarithmic voting (unlike quadratic, token-based weight is not linear. Min/max voting weights based on token ownership + POE)

### Contract List

| Kava          | [0x968354437FDBc3E5b209e363988715c36E5fF10E](https://explorer.evm-alpha.kava.io/address/0x968354437FDBc3E5b209e363988715c36E5fF10E/write-contract) |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Mainnet       | [0x5945bAF9272e0808165aDea61b932eC1604FB161](https://etherscan.io/token/0x5945baf9272e0808165adea61b932ec1604fb161)                                |
| Polygon (new) | [0x523b6CD6191C45B0134B175fD36b82586EaeC41D](https://polygonscan.com/token/0x523b6cd6191c45b0134b175fd36b82586eaec41d)                             |
| Polygon (old) | [0x15a84e83e039a63a230ba786231dfb99544f7acb](https://polygonscan.com/token/0x15a84e83e039a63a230ba786231dfb99544f7acb)                             |
| Rinkeby       | [0x36c81cef9d311dcf46391e9cf8a776e9991946a3](https://rinkeby.etherscan.io/token/0x36c81cef9d311dcf46391e9cf8a776e9991946a3)                        |

| Network | Merkle Minter                                                                                                                       |
| ------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| Kava    | [0x4784855c2802132d1dc3212111Ae70613CA7A1D0](https://explorer.evm-alpha.kava.io/address/0x4784855c2802132d1dc3212111Ae70613CA7A1D0) |
| Mainnet | [0xc4f97fcf045c0bfb9faa19515446eb0c7ffde8bf](https://etherscan.io/address/0xc4f97fcf045c0bfb9faa19515446eb0c7ffde8bf)               |
| Polygon | [0xb17e1062F89Dff41197F1f6d82De4Bff2d0db29D](https://polygonscan.com/address/0xb17e1062f89dff41197f1f6d82de4bff2d0db29d)            |

