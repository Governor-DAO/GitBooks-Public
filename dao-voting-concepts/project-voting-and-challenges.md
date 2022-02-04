---
description: >-
  A few examples on how GDAO can change the landscape for project voting
  including challenges
---

# Project Voting & Challenges

**PoE Use Case - Snapshot & Voting**

**Executive Summary**

In today’s rapidly evolving crypto-space governance and community voting systems play an integral part in project direction and development. An organized and structured project will have an on-chain or off-chain voting apparatus to capture temperament from token holders on individual improvement proposals in order to reach quorum before continuing to build out the proposal. Multiple voting systems are available such as Snapshot, Scattershot and Commonwealth which all share a similar form, function and common goal - a conduit for pursuing improvement or project direction in the form of proposals and a central platform to administer a vote on raised proposals. Governance and DAO architecture is built around these voting mechanisms, and provide an integral role to the fairness, stability and growth of the project backed by an engaged community with an opportunity to debate each decision and proposal.

**Challenges**

While the importance for voting is key, the process has a number of challenges on a permissionless network. For example, anyone can create numerous wallet addresses and falsely “represent” the impression of many token holders representing unique voters.

A common default strategy utilized for voting is weight-based voting mechanics: ie, the more tokens you hold, the bigger your vote/weight/voice. In some situations the logic can be beneficial __ (like in Proof-of-Work consensus, where maximum hashrate is ideal). For community driven governance, the optics for voting requires a flat schema to ensure all voting members are allowed only one vote from one authorized wallet allowing for a fair and equal vote towards a proposal.

Unless the source of a vote can be isolated and verified to one individual with one wallet, democratic or egalitarian governance procedures are always vulnerable to sybil attacks - users taking on numerous wallets/personas to gain an unfair, potentially malicious advantage over other holders.

Without a fair voting mechanism, large token holders can create proposals which are not in the best direction of the project’s future. Due to their weighted voting power they could direct the project financially in any direction abusing their power and dominating all proposals they feel is not in their personal best interest.

**Our Solution for Fluid Voting**

Governor DAO, in collaboration with Finnovant, has implemented a biometric Proof of Existence (PoE) token early in 2021. This token solves the often discussed challenge in question - Sybil Resistance. To mitigate the problem, GDAO deployed a biometric solution through a Governor front end which provides biometric enrollment. This biometric enrollment is compiled into an irreversible hash - the individual voice and face associated to one wallet - which allows a logical proof that any given address is owned by a specific (yet still anonymous) person, erasing the ability for someone to have two or more wallets and act as a single entity.

PoE (Proof of Existence) is a universal defense against Sybil Attacks - a situation where a single entity uses more than one wallet to pass as multiple entities. In addition to its current utilization for provably fair minting during an NFT launch, PoE also enables truly democratic voting standards - giving one vote per holder (wallet), or one quasi-weighted vote per holder similar to the United States electoral system. The discussed voting logic allows for ALL holders in a given protocol to engage with the voting system in a fair and honest manner without clouding judgment via token holders throwing their token weight around. There are numerous ways to implement the Governor DAO Proof-of-Existence token (ERC20) into current as well as new governance portals and voting systems in a way that establishes fair voting and encourages voter equality. A summary of examples as highlighted below include common use-case scenarios based on challenges experienced in the governance blockspace currently - as well as the Governor DAO solution demonstrating utility and addressing these problems. _All solutions simply require_ _including a single line of code or less to implement._

1. “Pure” Democratic Voting Using Global PoE
   * **Use Case:** A vote for new proposed emissions on a pool is being run. Generally, the largest holders (whales) would make up 75%+ of the vote tally which could benefit these same large holders.
   * **Challenge**: Current governance votes weigh token holdings and incentivize large holders via vote weight, sometimes leaving smaller holders - albeit many individuals, unable to quantifiably make a difference. This leads to poor voter adherence and lack of participation. Multiple wallets owned by the same holder or an entity can sway the vote in their favor or collapse the vote for malicious reasons.
   * **Solution**: The PoE token can be added to a voting portal for any project by adding it’s logic as a primary, secondary, or combined logic. This means that the PoE token can be used by itself - giving users a single vote across the board, or in addition to the protocol token - allowing a mixed vote of unique individuals as well as their holdings, or in a mixed scenario where multiple votes are run in tandem and weighted.
   * **Outcome Differential:** Adding the global PoE token contract to current snapshot logic allows for smaller players to provide input and the ability to weight votes by more than just total holdings - all the while ensuring input is received from verifiably unique individuals. This can be done with a single line added to the logic pointing to the global PoE token contract using the Balance\_of variable. A dual-approach can also be accommodated where both the primary token and PoE are weighted. (Total Tokens Held x Multiplier \[ONLY for PoE Holders])

In addition, PoE allows smaller voters or even non-holders to participate, bringing up voting participation and allowing for true individual input from all who have a say regardless of benefit. This includes global PoE members who are NOT token holders but have input on the project as a sideliner or potential future holder. Proven individuals who are smaller holders can have an increased voting weight via the dual-token weighted approach leading to more voter adhesion and increased vote accuracy.

1. Creating a “Gated” Community Voting Atmosphere
   * **Use Case:** A yield farm is running a vote for an improvement of the ecosystem. Swing traders and short-term holders that have not completed the PoE process are exempt from voting regardless of holdings.
   * **Challenge**: On-Chain voting is a great alternative to snapshot - or gasless voting - because it makes the vote immutable and further decentralizes the process. Because on-chain voting is a public contract call, individuals who may have just jumped in to the project, or who are swing trading the token can vote on initiatives that they are not well informed on, or that do not inevitably affect them.
   * **Solution**: Logic can be added to on-chain voting to call upon PoE as a verifier before the vote contract can be interacted with via web3 or directly - leading to a “gated” community voting portal for unique individuals only. Creating access control to the actual on-chain vote via a single line of code allows for project votes on-chain to be verified as originating from unique, token holders that have been around for a pre-set time and completed the PoE sign-up process which greatly increases their likelihood of passion for the project and caring about the outcome of the vote. Currently, any cryptocurrency user could buy tokens prior to the vote (whether announced prior or by luck) and skew the vote without having the proper knowledge of implications. The vote itself could still use token balance OR the “One Voice, One Vote” system of single vote weight per holder - at the project’s discretion.
   * **Outcome Differential:** The vote itself can still be weighted by token holdings, or a Democratic voting process can be implemented using the PoE token as the voting token - giving one vote per verified individual.
2. Other various use-cases which are more project-specific, but just as portable and easy to integrate:
3. PoE could be queried AFTER a vote has concluded to show the percentage of votes that are verified authentic.
4. PoE subtypes could be used to demarcate developer or team-member/influencer votes so that they are considered differently.
5. Completely separate voting portals can be utilized. One for traditional voting for more generic proposals, and a second, PoE-enabled portal for more important proposals.

**Conclusion:**

After implementing these governance strategies enhanced by the PoE token, a project can expect proposals to have much more user input via votes placed as well as a much more dynamic ratio of input on both sides of the vote. Studies have shown that psychological manifestation of equality is important in allowing individuals to provide their true feelings via voting when an even basis is placed on vote weight coupled with anonymization. Since GDAO’s Proof of Existence technology continues to hold the user anonymous, yet marked as an individual - the outcome is a perfect solution for DAOs and projects looking to maximize voting to build out the future of their platform with the will of all those involved in mind.

_If you are a project looking to integrate PoE into your voting strategy, contact us._
