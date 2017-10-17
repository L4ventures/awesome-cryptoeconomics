# Awesome Cryptoeconomics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

*A curated collection of links for cryptoeconomists. Part of the ["Awesome X" series](https://github.com/sindresorhus/awesome).*

The list is periodically updated with new links. Click "Watch" in the right top corner to follow.

Your contributions are welcomed. Add links to "Links Sent by Readers" [by yourself](contributing.md).

## Table of Contents

* [Fundamentals](#fundamentals)
* [Research](#research)
* [Applications](#applications)
* [Discussions](#discussions)
* [Other](#other)
* [License](#license)

## Fundamentals
* [Public-private key cryptography](https://security.stackexchange.com/questions/25741/how-can-i-explain-the-concept-of-public-and-private-keys-without-technical-jargo) - Simple explanation on StackExchange
* [Hash functions](https://medium.com/@ConsenSys/blockchain-underpinnings-hashing-7f4746cbd66b) - Basics of Hashing from Consensys
* [Ethereum](https://github.com/ethereum/wiki/wiki/White-Paper) - The Ethereum whitepaper
* [Design Rationale](https://github.com/ethereum/wiki/wiki/Design-Rationale) - The Ethereum design rationale
* [Merkling in Ethereum](https://blog.ethereum.org/2015/11/15/merkling-in-ethereum/) - Vitalik Buterin on Merkle trees
* [Homomorphic encryption](https://blog.cryptographyengineering.com/2012/01/02/very-casual-introduction-to-fully/) - Blog post by Matthew Green
* [Griefing Factors](http://vitalik.ca/files/extortion_griefing_bounds.pdf) - "A Note on Limits on Incentive Compatibility and Griefing Factors" by Vitalik Buterin
* [ZK-Snarks](https://medium.com/@VitalikButerin/zk-snarks-under-the-hood-b33151a013f6)] - ZK-Snarks under the hood by Vitalik Buterin
* [Atomic swap](https://en.bitcoin.it/wiki/Atomic_cross-chain_trading) - Wiki on atomic cross-chain trading
* [Patricia Tree](https://github.com/ethereum/wiki/wiki/Patricia-Tree) - Wiki on Merkle Patricia tree/trie used in Ethereum
* [Introduction to Cryptoeconomics](https://www.youtube.com/watch?v=pKqdjaH1dRo) - Vitalik Buterin's introduction to the field
* [What is Cryptoeconomics?](https://www.youtube.com/watch?v=9lw3s7iGUXQ) - Vlad Zamfir at Cryptoeconomicon
* [The current state of Cryptoeconomics](https://www.youtube.com/watch?v=u6VSPD5TrP4) - Another talk by Vlad Zamfir

## Discussions

* [Privacy on the Blockchain](https://blog.ethereum.org/2016/01/15/privacy-on-the-blockchain/) - Vitalik Buterin on privacy
* [Stateful Turing-Complete Policies](https://blog.ethereum.org/2015/11/09/stateful-turing-complete-policies/) - Vitalik Buterin on stateful turing-complete policies
* [On Anti-Pre-Revelation Games](https://blog.ethereum.org/2015/08/28/on-anti-pre-revelation-games/) - Vitalik Buterin on anti-pre-revelation games
* [On Public and Private Blockchains](https://blog.ethereum.org/2015/08/07/on-public-and-private-blockchains/)] - Vitalik Buterin on public and private blockchains
* [The Triangle of Harm](http://vitalik.ca/general/2017/07/16/triangle_of_harm.html) - Post on Casper’s incentivization philosophy
* [A Note on Metcalfe's Law, Externalities and Ecosystem Splits
](http://vitalik.ca/general/2017/07/27/metcalfe.html)] - Vitalik Buterin on blockchain splitting
* [Hard Forks, Soft Forks, Defaults and Coercion](http://vitalik.ca/general/2017/03/14/forks_and_markets.html) - Vitalik Buterin on when to hard fork or soft fork (and more)
* [On Path Independence](http://vitalik.ca/general/2017/06/22/marketmakers.html) - Vitalik Buterin on path independence

## Applications

### Smart Contracts
* [Making Sense of Blockchain Smart Contracts](https://www.coindesk.com/making-sense-smart-contracts/) - CoinDesk article on smart contracts
* [Thinking About Smart Contract Security](https://blog.ethereum.org/2016/06/19/thinking-smart-contract-security/) - Vitalik Buterin on smart contract security

### State Channels
* [State Channels](http://www.jeffcoleman.ca/state-channels/) - Jeff Coleman on state channels
* [Calculating Costs in Ethereum Contracts](https://hackernoon.com/ether-purchase-power-df40a38c5a2f) - Analysis on the purchasing power of ETH
* [Counterfactual Terminology](https://github.com/ledgerlabs/state-channels/wiki/Counterfactual-Terminology) - Jeff Coleman's use of the term counterfactual

### Token Design
* [How Does REP Work](http://blog.augur.net/faq/how-does-reputation-rep-work/) - Augur report on incentive structure of their prediction market token, REP
* [Introducing the Gnosis Tokens (GNO and WIZ)](https://blog.gnosis.pm/introducing-the-gnosis-tokens-gno-and-wiz-5295a65c3822) - Background and reasoning for design decisions for Gnosis and the GNO token
* [Applications of Security Deposits and Prediction Markets You Might Not Have Thought About](https://blog.ethereum.org/2015/11/24/applications-of-security-deposits-and-prediction-markets-you-might-not-have-thought-about/) - Vitalik Buterin on a few topics
* [SchellingCoin](https://blog.ethereum.org/2014/03/28/schellingcoin-a-minimal-trust-universal-data-feed/) - Vitalik Buterin on SchellingCoins

### Token Sales
* [Introducing the Gnosis Token Launch](https://blog.gnosis.pm/introducing-the-gnosis-token-launch-3cc4cffb5098) - Gnosis on using a dutch auction
* [Analyzing Token Sale Models](http://vitalik.ca/general/2017/06/09/sales.html) - Vitalik Buterin reviewing token sale models, including Gnosis' dutch auction
* [Vickrey auction](https://en.wikipedia.org/wiki/Vickrey_auction#Proof_of_dominance_of_truthful_bidding) - Method used to keep bids secret and have the winner pay the 2nd highest amount
* [Long-Term Cryptocurrency Distribution Models](https://blog.ethereum.org/2014/05/24/on-long-term-cryptocurrency-distribution-models/) - Early Vitalik Buterin post on token distribution

## Attacks
* [51 percent attack](https://bitcoin.stackexchange.com/questions/658/what-can-an-attacker-with-51-of-hash-power-do) - StackExchange answer to "What can an attacker with 51% of hash power do?"
* [Cost of a 51 percent attack](https://gobitcoin.io/tools/cost-51-attack/) - Present day cost for someone to do a 51% attack the Bitcoin network
* [The P+ epsilon Attack](https://blog.ethereum.org/2015/01/28/p-epsilon-attack/) - Vitalik Buterin on the P+ epsilon attack
* [Long-Range Attacks](https://blog.ethereum.org/2014/05/15/long-range-attacks-the-serious-problem-with-adaptive-proof-of-work/) - Post by Vitalik Buterin "The Serious Problem With Adaptive Proof of Work"

## Research

### Consensus Protocols
* [Proof of Work](https://www.youtube.com/watch?v=sADoZx7Ar4A) - A talk at Cryptoeconomicon
* [Proof of Stake](https://www.youtube.com/watch?v=1tdxPzQt4ZI) - A talk at Cryptoeconomicon
* [On Slow and Fast Block Times](https://blog.ethereum.org/2015/09/14/on-slow-and-fast-block-times/) - Vitalik Buterin on enabling faster block times
* [Is Ethereum ASIC resistant?](https://ethereum.stackexchange.com/questions/16811/is-ethereum-asic-resistant) - StackExchange question on ASIC resistance of Ethereum
* [The History of Casper](https://medium.com/@Vlad_Zamfir/the-history-of-casper-part-1-59233819c9a9) - Vlad Zamfir on Casper, a Proof of Stake Consensus Protcol
* [Proof of Stake with Casper](https://www.youtube.com/watch?v=9nQPcNY32JQ) - Vlad Zamfir podcast about Casper
* [A Proof of Stake Design Philosophy](https://medium.com/@VitalikButerin/a-proof-of-stake-design-philosophy-506585978d51) - Vitalik Buterin post about the design of a PoS system
* [Proof of Stake FAQ](https://github.com/ethereum/wiki/wiki/Proof-of-Stake-FAQ) - FAQ from the Ethereum wiki
* [On Inflation, Transaction Fees and Cryptocurrency Monetary Policy](https://blog.ethereum.org/2016/07/27/inflation-transaction-fees-cryptocurrency-monetary-policy/) - Vitalik Buterin
* [On Settlement Finality](https://blog.ethereum.org/2016/05/09/on-settlement-finality/) - Vitalik Buterin on settlement finality
* [Light Clients and Proof of Stake](https://blog.ethereum.org/2015/01/10/light-clients-proof-stake/) - Vitalik Buterin post on light clients using PoS
* [Weak Subjectivity](https://blog.ethereum.org/2014/11/25/proof-stake-learned-love-weak-subjectivity/) - Vitalik Buterin on PoS
- [Cryptocurrencies without Proof of Work](https://arxiv.org/abs/1406.5694)
- [Slasher Ghost, and Other Developments in Proof of Stake](https://blog.ethereum.org/2014/10/03/slasher-ghost-developments-proof-stake/)
- [Least Authority Performs Incentive Analysis For Ethereum](https://leastauthority.com/blog/least_authority_performs_incentive_analysis_for_ethereum/)
- [Demystifying incentives in the consensus computer](https://eprint.iacr.org/2015/702)
- [On Stake](https://blog.ethereum.org/2014/07/05/stake/)
- [Safety Under Dynamic Validator Sets](https://medium.com/@VitalikButerin/safety-under-dynamic-validator-sets-ef0c3bbdf9f6)
* [Using trusted hardware](https://medium.com/@loiluu/casper-sgx-8475e56244b)
- [Formal methods on some PoS stuff](https://medium.com/@pirapira/formal-methods-on-some-pos-stuff-e309775c2ab8)
- [A mechanized safety proof with dynamic validators](https://medium.com/@pirapira/a-mechanized-safety-proof-for-pos-with-dynamic-validators-17e9b45faff4)
- [Formal methods on another Casper](https://medium.com/@pirapira/formal-methods-on-another-casper-8a75f6e02073)
- [Sharding FAQ](https://github.com/ethereum/wiki/wiki/Sharding-FAQ) - Frequently asked questions on Sharding from Ethereum
- [Nothing at Stake Problem](https://ethereum.stackexchange.com/questions/2402/what-exactly-is-the-nothing-at-stake-problem) - StackExchange "What exactly is the Nothing-At-Stake problem?"

### Fault Attribution
* [The problem of censorship](https://blog.ethereum.org/2015/06/06/the-problem-of-censorship/) - Vitalik Buterin on attributability of censorship
* [Minimal Slashing Conditions](https://medium.com/@VitalikButerin/minimal-slashing-conditions-20f0b500fc6c) - Vitalik Buterin on slashing conditions
* [Shapley values](https://en.wikipedia.org/wiki/Shapley_value) - Technique for translating fault attributions into penalties

### Mechanism Design
* [Chain Interoperability](https://static1.squarespace.com/static/55f73743e4b051cfcc0b02cf/t/5886800ecd0f68de303349b1/1485209617040/Chain+Interoperability.pdf) - Cross-chain interoperability paper by Vitalik Buterin

### Decentralization
* [The Meaning of Decentralization](https://medium.com/@VitalikButerin/the-meaning-of-decentralization-a0c92b76a274) - Vitalik Buterin defining "Decentralization"
* [Mining](https://blog.ethereum.org/2014/06/19/mining/) - Early Vitalik Buterin post on mining

### Data Availability & Erasure Coding
* [A note on data availability and erasure coding](https://github.com/ethereum/research/wiki/A-note-on-data-availability-and-erasure-coding) - Comprehensive review of the data availability problem from the Ethereum Foundation
* [Secret Sharing and Erasure Coding](https://blog.ethereum.org/2014/08/16/secret-sharing-erasure-coding-guide-aspiring-dropbox-decentralizer/) - Vitalik Buterin guide for the Aspiring Dropbox Decentralizer

### Scalability
* [Scalability](https://www.youtube.com/watch?v=dboKNgdzA7M) - A talk at Cryptoeconomicon

### Identity & Reputation
* [Identity & Reputation](https://www.youtube.com/watch?v=yfM8gJnXa9A) - A talk at Cryptoeconomicon

### Stablecoins
* [Stablecoins](https://www.youtube.com/watch?v=Z8LV56xNwus) - A talk at Cryptoeconomicon
* [The Search for a Stable Cryptocurrency](https://blog.ethereum.org/2014/11/11/search-stable-cryptocurrency/) - Vitalik Buterin on stablecoins

### Other
* [Ethereum Research Problems](https://github.com/ethereum/research/wiki/Problems) - list of open research problems the Ethereum Foundation is tackling
* [More Ethereum Research Problems](https://github.com/ethereum/wiki/wiki/Problems) - The old page which is still full of good content
* [Awesome Cryptography](https://github.com/sobolevn/awesome-cryptography) - A curated list of cryptography resources and links.
* [Awesome Economics](https://github.com/antontarasenko/awesome-economics) - A curated collection of links for economists
* [Making Sense of Cryptoeconomics](https://www.coindesk.com/making-sense-cryptoeconomics/) - An article on CoinDesk by [Josh Stark](http://0xstark.com/about/).
* [Futarchy](https://blog.ethereum.org/2014/08/21/introduction-futarchy/) - An intro to futarchy by Vitalik Buterin

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
