# Blockchain Basics

## What is a Blockchain?

[`Blockchain`](https://www.investopedia.com/terms/b/blockchain.asp) is a decentralized digital ledger that securely stores records across a network of computers in a way that is transparent, immutable, and resistant to tampering. Each "block" contains data, and blocks are linked in a chronological "chain."

### Bitcoin and Blockchain

You might be familiar with `Bitcoin`, which is one of the first protocols to utilize the revolutionary blockchain technology. The Bitcoin Whitepaper, authored by the pseudonymous `Satoshi Nakamoto`, described how Bitcoin could facilitate peer-to-peer transactions within a decentralized network using cryptography. This gave rise to censorship-resistant finance and presented `Bitcoin` as a superior digital store of value, often referred to as _digital gold_. There is a fixed amount of Bitcoin, similar to the scarcity of gold. You can learn more about this in the [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf).

### Ethereum and Smart Contracts

A few years after Bitcoin's creation, Vitalik Buterin and others founded `Ethereum`, which builds upon the blockchain infrastructure, but with additional capabilities. With Ethereum, you can create decentralized transactions, organizations, and agreements without a centralized intermediary. This was achieved through the addition of `smart contracts`.

Though the concept of smart contracts was originally conceived in 1994 by **[Nick Szabo](https://en.wikipedia.org/wiki/Nick_Szabo)**, Ethereum made it a reality.

> [`Smart contracts`](https://chain.link/education/smart-contracts) are a set of instructions executed in a decentralized way without the need for a centralized or third party intermediary.

Smart Contract functionality is the primary difference between blockchains like `Ethereum` and `Bitcoin`. Technically `Bitcoin` does have smart contracts but they're intentionally `turing incomplete`.

### The Oracle Problem

However, smart contracts face a significant limitation – they cannot interact with or access data from the real world. This is known as the [`Oracle Problem`](https://betterprogramming.pub/what-is-a-blockchain-oracle-f5ccab8dbd72?source=friends_link&sk=d921a38466df8a9176ed8dd767d8c77d).

Blockchains are deterministic systems, so everything happens within their ecosystem. To make smart contracts more useful and capable of handling real-world data, they need external data and computation.

Oracles serve this purpose. They are devices or services that provide data to blockchains or run external computation. To maintain decentralization, it's necessary to use a decentralized Oracle network rather than relying on a single source. This combination of on-chain logic with off-chain data leads to [`hybrid smart contracts`](https://chain.link/education-hub/hybrid-smart-contracts).

> **Note:** Most of this course will assume we're working with an Ethereum or EVM environment. The skills you learn here will be compatible with the vast majority of blockchain architectures!

### Chainlink

**[Chainlink](https://chain.link/)** is a popular decentralized Oracle network that enables smart contracts to access external data and computation. Chainlink is also blockchain agnostic - so it's going to work with any chain out there.

### Layer 2 Scaling Solutions

As blockchains grow, they face scaling issues. Layer 2, or L2, solutions have been developed to address this. L2 solutions involve other blockchains hooking into the main blockchain, essentially allowing it to scale. There are two primary types of L2 solutions:

-   **Optimistic Rollups:** eg. Optimism, Arbitrum
-   **Zero-Knowledge Rollups:** eg. ZKsync, Polygon ZK EVM

Don't worry too much about this now. Once we understand how blockchains work 'under the hood', we'll go further into Layer 2's then.

### Terminology

You're going to hear some terms used in blockchain (and the community as a whole) a little interchangeably. Maybe you haven't heard these terms before. I hope this offers a bit of clarification. [`terminology`](https://connect.comptia.org/content/articles/blockchain-terminology)

Common Terms:

1. **Blockchain**: In web3, a blockchain is a digital ledger that records transactions across many computers in a secure and decentralized manner. Each block contains a number of transactions, and every new block is linked to the previous one, forming a chain. This makes the data tamper-resistant. _Example_: Bitcoin's blockchain records all BTC transactions.

2. **Oracle**: Oracles in web3 are intermediaries that provide smart contracts with external data. They act as bridges between blockchains and the outside world, allowing smart contracts to execute based on real-world events and data. _Example_: A weather oracle provides data for a smart contract that triggers crop insurance payments based on rainfall data.

3. **Layer 2**: Layer 2 solutions in web3 are technologies built on top of a blockchain (Layer 1) to improve its scalability and efficiency. These solutions handle transactions off the main chain, reducing congestion and fees, and then settle the final state on the main chain. _Example_: The Lightning Network for Bitcoin.

4. **Dapp (Decentralized Application)**: A Dapp is an application that runs on a decentralized network, typically a blockchain. It is powered by smart contracts and operates without a central authority. Dapps can serve various purposes, from finance to gaming. _Example_: Uniswap, a decentralized finance application.

5. **Smart Contract**: In web3, a smart contract is a self-executing contract with the terms of the agreement directly written into code. They run on blockchains and automatically execute when predetermined conditions are met, without the need for intermediaries. _Example_: A smart contract for an escrow service.

6. **Hybrid Smart Contract**: Hybrid smart contracts combine on-chain code (running on a blockchain) with off-chain data and computations provided by oracles. This allows the contracts to interact with data and systems outside their native blockchain. _Example_: A smart contract for insurance that uses real-world data (like weather or flight delays) provided by oracles.

7. **Ethereum/EVM (Ethereum Virtual Machine)**: Ethereum is a blockchain platform known for its smart contract functionality. The Ethereum Virtual Machine (EVM) is its computation engine that executes smart contracts. Ethereum allows developers to build decentralized applications and is the basis for many web3 projects. _Example_: ERC-20 tokens, a standard for creating fungible tokens on Ethereum.

### Web3

[`Web3`](https://en.wikipedia.org/wiki/Web3) is a term used to describe the new paradigm of the internet powered by blockchain and smart contracts. Unlike the previous versions of the web, web3 is permissionless and relies on decentralized networks rather than centralized servers. This ushers in an era of censorship-resistant and transparent agreements and transactions, often called an ownership economy.

**Web1:** The permissionless open sources web with static content

**Web2:** The permissioned web, with dynamic content where companies run your agreements on their servers.

**Web3:** The permissionless web with dynamic content.

-   Decentralized censorship resistant networks run your agreements and code.
-   User owned ecosystems where one owns a portion of the protocol they interact with - instead of solely being the product

## The Purpose of Smart Contracts

### The Essence of Blockchain and Smart Contracts

Almost every interaction or transaction in our lives involves some form of agreement or contract. For instance, purchasing a chair involves a contract to buy lumber, assemble it, and sell the finished product. Your electricity supply is also based on an agreement between you and the electric company. When you get an oil change for your car, you're promised a service in exchange for money.

Almost everything we do in modern life relates to an agreement or contract in some way.

To make it more relatable, think of contracts and agreements as promises. Traditional contracts, however, require trust between parties, and this doesn’t always work in favor of honesty and fairness.

### The Problem with Traditional Agreements

Lets consider some real world examples of where trust leveraged agreements can go wrong and why blockchain technology and smart contracts mitigate these risks.

### Consumer Trust

In the 80s and 90s, McDonald’s Monopoly game promised customers a chance to win money through game cards obtained with purchases. However, it turned out that the game was rigged by insiders who manipulated the system for their gain. Essentially, McDonald’s failed to keep its promise.

This example demonstrates that relying on trust within agreements can lead to fraudulent activities and broken promises.

With smart contracts, we can eliminate the need for trust. A smart contract is an agreement or a set of instructions that are deployed on a decentralized blockchain. Once deployed, it cannot be altered, it automatically executes, and everyone can see its terms.

Imagine if McDonald’s Monopoly game was operated on a blockchain through a smart contract. The fraudulent activities would have been impossible due to the immutable, decentralized, and transparent nature of smart contracts.

### Banking and Trust

Traditional banks have sometimes failed to keep the promise of safeguarding people's money, as seen during the Great Depression. Blockchain and smart contracts can ensure transparency and execute automated solvency checks, preventing the bank from becoming insolvent.

The core of blockchain and smart contracts lies in creating a trustless system where agreements are transparent, unchangeable, and executed without human intervention. This technology holds the potential to revolutionize industries and everyday agreements by ensuring honesty and fairness.

### Financial Markets Access

Centralized bodies, like traditional exchanges, have the power to restrict access to financial markets. This was evident when Robinhood restricted trading on certain assets in 2021. With decentralized exchanges like Uniswap, there is no central authority that can alter or limit market access. This introduces fairness and openness to the financial markets.

### To Summarize

-   Traditional Agreements: Require trust in a centralized entity.
-   Smart Contracts: Transparent, decentralized, and tamper-proof.

In a scenario where you have to choose, smart contracts are an obvious choice as they cannot be manipulated or altered in anyone's favor.

Smart contracts are _the_ solution to minimizing the reliance on trust based systems that have historically failed us time and time again.

### Under the Hood

Smart contracts are relatively new, but have already started transforming various markets. They do this by representing 'promises' as code on the blockchain. This code is executed by a decentralized collective, such that no single entity can alter the agreemeent in any way! The agreement and its terms are public knowledge and will automatically execute without human intervention.

More industries are adopting smart contracts and blockchain due to the numerous advantages they offer. This results in trust-minimized agreements or what can be simply termed as unbreakable promises.

### Beyond Trust Minimization

It is important to note that blockchain, smart contracts, and cryptocurrencies are not just about trust-minimized agreements. They offer security benefits, uptime advantages, execution speed, and **much more**.

### Caution: Not All Are Equal

However, beware of platforms that claim to be decentralized but are not in practice. An example from 2022 is the `SBF's FTX platform`. It presented itself as a Web3 platform, but was essentially a traditional Web2 company using cryptocurrency without the benefits of smart contracts.

As an emerging developer or user in this space, it's important to discern between legitimate projects and those that aren't contributing to the ethos of Web3. I want you to be successful, but I want you to be successful because you're creating value. Platforms like `FTX` were pretending to bring value to the space and leeching value from it.

## Features of Smart Contracts

Smart contracts come with various features that distinguish them from traditional agreements.

### Decentralization

The first feature is decentralization; smart contracts do not rely on any centralized intermediary. Instead, they run on a blockchain which is maintained by thousands of individuals known as node operators. It's the collective effort of these node operators running the smart contracts that make the network decentralized. This aspect will be discussed more in-depth later.

### Transparency and Flexibility

Transparency is inherent to blockchain networks. Since all node operators can see everything happening on-chain, there is no room for unfair or hidden deals. This transparency ensures that everyone has access to the same information and plays by the same rules.

It is important to note that this transparency does not necessarily compromise privacy. Blockchain is pseudo-anonymous, meaning that your transactions are not directly tied to your real-world identity.

### Speed and Efficiency

Smart contracts and blockchain transactions are incredibly fast and efficient compared to traditional banking systems. For example, bank transfers, especially international ones, can take up to several weeks, whereas blockchain transactions happen almost instantly. This speed is not only convenient but also allows for more efficient interactions between parties.

### Security and Immutability

Once a smart contract is deployed, it cannot be altered or tampered with. This immutability ensures that the terms of the contract are set in stone. This is a stark contrast to centralized systems where a server or database can be hacked, and data can be altered. The decentralized nature of blockchain makes hacking nearly impossible since an attacker would have to take control of more than half the nodes, which is significantly more challenging than compromising a single centralized server.

Additionally, the data on a blockchain is resilient. In a traditional system, if your computer and backups fail, you lose all your data. In contrast, in a blockchain, your data is replicated across thousands of nodes. Even if several nodes were to go down, your data would remain secure as long as there is at least one copy of the blockchain.

### Elimination of Counterparty Risk

Smart contracts eliminate the need for trust in transactions. Once a smart contract is deployed, its terms cannot be changed. This means that parties cannot alter the agreement based on greed or any other factors. This ensures that the agreement is enforced as originally intended.

In traditional systems, there is always a risk that the other party might not fulfill their end of the bargain. With smart contracts, this risk is eliminated, and agreements are enforced programmatically.

## Applications of Smart Contracts

Smart contracts have given rise to new industries and revolutionized existing ones.

### Decentralized Finance (DeFi)

DeFi, or Decentralized Finance, allows users to engage with financial markets without relying on centralized intermediaries. With smart contracts, users have transparent access to financial markets and can engage with sophisticated financial products efficiently and securely. We will provide practical examples of how to build and interact with DeFi protocols in upcoming lessons.

### Decentralized Autonomous Organizations (DAOs)

DAOs are governed entirely by smart contracts and operate in a decentralized manner. This structure offers benefits such as transparent governance, efficient engagement, and clear rules. DAOs are an evolution in politics and governance, and we will cover how to build and work with DAOs in future lessons.

### Non-Fungible Tokens (NFTs)

NFTs, or Non-Fungible Tokens, can be thought of as digital art or unique assets. NFTs have created new avenues for artists and creators to monetize their work. We will also cover how to create and interact with NFTs in this course.
