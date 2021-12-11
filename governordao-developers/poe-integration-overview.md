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

| Network | Proof-of-Existence Token Contract                                                                                           |
| ------- | --------------------------------------------------------------------------------------------------------------------------- |
| Mainnet | [0x5945bAF9272e0808165aDea61b932eC1604FB161](https://etherscan.io/token/0x5945baf9272e0808165adea61b932ec1604fb161)         |
| Polygon | [0x15a84e83e039a63a230ba786231dfb99544f7acb](https://polygonscan.com/token/0x15a84e83e039a63a230ba786231dfb99544f7acb)      |
| Rinkeby | [0x36c81cef9d311dcf46391e9cf8a776e9991946a3](https://rinkeby.etherscan.io/token/0x36c81cef9d311dcf46391e9cf8a776e9991946a3) |
