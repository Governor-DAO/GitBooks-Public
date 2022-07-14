---
description: >-
  A number of questions have surfaced since the vault has launched. Questions
  answered below..
---

# FAQ Governance Vault

### FAQ Governance Vault v1.1

1\. **Can I deposit directly from Gate.io? (Gate.io is for non-US residents only)**

No, you must deposit using a Web3 compatible wallet ie Metamask.

2\. **Can I just transfer my GDAO into the Governance Vault instead of using the deposit function?**

No, if you do this you will lose your GDAO, and you will not be compensated!

3\. **Do I need to have a PoE Token to deposit to the vault?**

No PoE token is required, Vault is open to any GDAO holders but there will be a 3% fee of GDAO which was decided by the community.

4\. **Will I be warned or prompted about deposit fees when using a wallet without a PoE token or withdrawal fees when withdrawing early?**

Yes, for any fee on deposit or withdrawal a warning will display. The frontend website will detect the status of your PoE token and whether you are withdrawing early (under 10 days).&#x20;

![](<../.gitbook/assets/image (6).png>)

![](<../.gitbook/assets/image (5).png>)

5\. **How do I deposit my GDAO into the vault**

Navigate to the following URL [Governance Vault - Governor DAO](https://vault.governordao.org/), first transaction will be an ‘_**Approve**_’ and 2nd will be a ‘_**Deposit**_’ transaction which are both standard transactions that require gas \[eth]

**6. I enrolled for Proof-of-Existence, but I don’t see my wallet as holding a PoE token, Please explain?**

Once your [PoE enrollment](https://onlyoneme.governordao.org) is complete, you can mint your POE token from the [PoE Passport Portal](https://passport.governordao.org), which will cost a small gas fee to complete the transaction. An automated process runs every 4 hours which collects new enrollments and authorizes the new wallet to mint a PoE token. Once minted, the PoE token will not automatically be visible in your wallet, add the following contract address on Mainnet 0x5945bAF9272e0808165aDea61b932eC1604FB161

7\. **Why did APR go up/down?**

APR is dependent on a few different variables. It goes down when more users deposit (up when they withdraw). It goes down when GDAO goes up relative to ETH, and it goes up when GDAO goes down relative to ETH. These metrics don’t include the Non-PoE fees and early decay fees which can’t be incorporated.

8\. **My xGDAO is worth less than when I deposited it. I was informed xGDAO will only increase!**

The GDAO value of xGDAO only goes up, indefinitely. The dollar price can fluctuate in both directions as the price of GDAO does.

9\. **Why is my xGDAO not increasing in the ‘Wallet/Vault Balances’ panel**

When depositing GDAO, xGDAO is received as a receipt token. GDAO is staked in the vault not xGDAO therefore the value of xGDAO will increase not your holdings. Your GDAO balance will increase, not xGDAO.

10\. **I have staked my GDAO and not seeing any increase, please explain?**

There are 3 core components which would trigger an increase to your holdings.

&#x20;  a) GDAO deposits from a holder without a PoE token which would result in a 3% fee (GDAO) deposited into the vault, pushing up the value of xGDAO.

&#x20;  b) GDAO withdraws within 10 days, early withdrawals result in a decay fee starting at 10% on first day, decreasing 1 % per day. Decay fee of GDAO again distributed into vault increasing value of xGDAO and your GDAO balance.

&#x20;  c) BuyBack agent, when buybacks are active anyone can initiate a buyback every 72 hours (3 days), a buyback will pull ETH into the contract and kick off several transactions including buying GDAO from open market and LP. The transaction will increase the value of xGDAO and your GDAO balance. **Very important to note**, there must be ETH deposited to the buyback agent to allow a buyback. The community approved a vote [\[Link\]](https://forum.gdao.info/t/governance-vault-subsidization-strategy/2819) to subsidize ETH from the treasury to fund the vault until revenue starts to flow from NFT launches and potential LGE \[Liquid Generation Events] which the project will provide.

**11. How do I know how much ETH is available in the BuyBack agent and the duration it will last?**

There are two stats on the vault which will provide info on the above.

a) Buyback Agent Reservoir: xx days - In the stats panel there following value will display the number of days the buyback can run with the current ETH which is available.

b) In the 'Buyback Agent' panel the ETH balance displayed is the ETH that is remaining in the Buyback. Any proceeds from NFT launches etc will push the value up.

**12. What will happen if no one executes the buyback button, or if I execute it?**

If the Buyback button is not executed the only increase in rewards will be from non-PoE deposits and early withdrawal fees. The button must be manually executed to trigger off the buybacks detailed in Q9 c.&#x20;

If you execute the buyback there will be a gas cost for the transaction which will be reimbursed by the amount detailed in the buyback panel Reward: 0.xxxx ETH

13\. **Will the amount of xGDAO I receive change on deposit over time?**

The ratio or conversion on GDAO = XGDAO will change depending on how much GDAO is in the vault. If no one was to remove their GDAO over time depositors would receive less xGDAO for their GDAO. For example, early deposits would have received close to 1 GDAO = 0.9999 xGDAO, conversion on writing this is 1 GDAO = 0.9961 xGDAO therefore a slight decrease

14\. **Can I deposit from Ledger?**

Hardware wallets utilizing Web3 functionality (ie Ledger Live + MetaMask) can interact with the Governance Vault through the webpage.

15\. **After depositing GDAO and receiving xGDAO in my wallet, can I move xGDAO to a different wallet?**

xGDAO is an ERC-20 token therefore can be moved to any ERC-20 compliant wallet. If xGDAO is moved to another wallet, that wallet will need to be connected to the vault to withdraw the GDAO. Please note the 2nd wallet will not host a PoE token therefore if there is an intention to deposit back from the 2nd wallet there will be a non-PoE fee on deposit.

16\. **How can I see my xGDAO after I have staked my GDAO?**

Once GDAO has been staked in the vault and receive xGDAO, to view xGDAO in your wallet adding the xGDAO contract ID to your wallet will display your holdings **0x306978da6ebee060375f35418744f85c1cb6b353** or in the vault in the ‘Wallet/Vault Balances’ panel, there is an option to add the contract addresses to your wallet, click on the foxes.

![Click fox to add GDAO / xGDAO](<../.gitbook/assets/image (3).png>)

17\. **How can I see my xGDAO after I have staked my GDAO?**

Once GDAO has been staked in the vault and you receive xGDAO, you can view xGDAO in your wallet by adding the xGDAO contract ID to your wallet and it will then display your holdings.

18\. **How do I find out more regarding the vault?**

You can learn more about the Vault in this [user guide](https://docs.governordao.org/how-to-section/governance-vault-user-guide).



![Vault Buyback Overview](<../.gitbook/assets/Vault-Only-Diagram-V1-Large (1) (1).jpg>)
