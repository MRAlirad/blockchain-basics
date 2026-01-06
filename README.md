# What Is A Blockchain

## What Is a Blockchain? From Centralized Problems to a Decentralized Solution

To truly grasp what a blockchain is, we must first understand the fundamental problems it was designed to solve. At its core, blockchain technology is a response to the vulnerabilities and limitations inherent in centralized systems, from the way we manage money to how we make collective agreements.

### The Problem: A World Built on Centralized Trust

Our modern world runs on intermediaries. We trust banks to manage our money, tech companies to hold our data, and election committees to count our votes. While often efficient, this reliance on a central authority creates significant issues related to control, permission, and trust.

#### The Flaws of Centralized Money

In the traditional financial system, sending money isn’t a direct exchange. It’s a request to a central intermediary, like a bank, to update their private records. You trust them to debit your account and, in coordination with other banks, credit the recipient's account. This system places immense power in the hands of a few.

-   **Absolute Control:** A central institution has the unilateral power to freeze your assets, block transactions, or deny you service entirely. You must have their permission to use your own money.
-   **Exclusion:** This system can easily exclude people. Consider a freelancer in a country without a robust banking infrastructure. They may not be able to open a bank account without a permanent address—a requirement set by the bank—making it impossible for them to get paid by international clients. They are locked out of the global economy by a centralized gatekeeper.
-   **Lack of Privacy and Censorship:** When Ethereum creator Vitalik Buterin wanted to donate to humanitarian efforts in Ukraine in 2022, using the traditional banking system would have created a public paper trail. This could have alerted hostile governments and put the recipients at risk. By using cryptocurrency on a blockchain, he was able to transfer funds instantly and without a central party that could block, monitor, or censor the transaction.

#### The Challenge of Centralized Agreements

Beyond finance, we rely on central authorities to act as the source of truth for collective agreements. This works only as long as everyone trusts that authority to be fair and honest.

Imagine a simple town election between the Apple, Pear, and Banana parties. A central committee collects and counts all the paper ballots in private. When they announce the Apple Party as the winner, chaos erupts. The losing parties claim the vote was rigged, but they have no way to independently verify the results. The committee holds the "truth," and if trust in them erodes, the entire system's legitimacy collapses.

This isn't just a theoretical problem. When questions of fraud arise in major elections, the underlying issue is the same: citizens cannot independently audit the process. They are forced to trust an intermediary, and when that trust is questioned, there is no mathematical or verifiable way to settle the dispute.

### The Solution: A Trust-Minimized System

Blockchain technology offers a new model for money and agreements—one that doesn't require trusting a person or institution. Instead, it creates a **trust-minimized system** where participants rely on transparent, verifiable mathematics and code. It achieves this through a few core concepts.

#### The Shared, Decentralized Ledger

Instead of each bank maintaining its own secret ledger, a blockchain is a **single, shared, and distributed digital ledger**. Think of it as a global record book that is copied and spread across thousands of computers worldwide. Each computer or participant that holds a copy of this ledger is called a **node**.

These nodes form a decentralized, peer-to-peer (P2P) network. There is no central server or single point of failure. When a new transaction occurs, it is announced to the network and propagates from node to node, almost like gossip, until every participant has an identical, up-to-date copy of the ledger.

#### Blocks: The Pages of the Ledger

Transactions are not added to this shared ledger one by one. Instead, they are collected and bundled together into groups called **blocks**. You can think of a block as a single page in our global record book. Once a page is filled with a list of verified transactions, it is ready to be added to the book.

#### The Chain: A Cryptographic Link of Trust

This is where the "chain" in blockchain comes from. Blocks are linked together chronologically and secured using cryptography, creating a permanent and unbroken history.

Here’s how it works:

1.  **The Hash:** When a block is created, all the transaction data inside it is passed through a cryptographic algorithm to produce a unique code called a **hash**. This hash acts like a digital fingerprint or a "seal of approval" for that specific block. If even a single character in the transaction data is changed, the hash will change completely.
2.  **Linking the Chain:** Each new block contains two key cryptographic elements: its own unique hash and the hash of the _previous_ block. This is the crucial link. By including the previous block’s fingerprint, it creates a mathematical chain connecting every block all the way back to the very first one.

This structure is what makes a blockchain **tamper-proof**, or **immutable**. If a malicious actor tried to alter a transaction on an old block—say, on Page 10 of the ledger—it would change the hash (the "fingerprint") of Page 10. This would instantly "break the seal." Because Page 11 contains the original, valid hash of Page 10, the link between them would sever. This break would cascade down the entire rest of the chain, making the tampering immediately obvious to all other nodes on the network. The network would automatically reject this fraudulent version of the ledger, preserving the integrity of the true record.

#### Digital Currency: The Fuel for the Network

To operate a decentralized financial system without banks, blockchains use their own **digital currencies** (cryptocurrencies). These are currencies that exist purely on the ledger itself, allowing users to transfer value directly and securely within this new trust-minimized framework, without needing permission from any central authority.

In summary, a blockchain is a decentralized, distributed, and shared digital ledger. It is composed of **blocks** of transactions linked together chronologically to form a **chain**. This chain is secured with **cryptography**, making it a permanent and tamper-proof history of all activity. By removing the need for a trusted central intermediary, it empowers users to transact and agree with one another in a more transparent, secure, and open way.

## History Of Blockchain

### The Genesis of Blockchain: From Digital Cash to Bitcoin

To understand the power and purpose of blockchain technology, we must first look to its origins in the long-standing quest for a true digital currency. This journey began not with blockchains themselves, but with the fundamental challenges of creating and transferring value in a digital world. The story starts with a critical problem that stumped computer scientists for decades and culminates in the creation of Bitcoin, the first technology to solve it.

### Bitcoin: The First Decentralized Digital Currency

In 2008, an anonymous person or group known as Satoshi Nakamoto published a paper that introduced Bitcoin. More than just a digital currency, Bitcoin is also the name of the decentralized network—the blockchain—on which it operates. It quickly earned the moniker "digital gold" for a key reason: like the precious metal, it has a provably **finite supply**. The code dictates that a maximum of 21 million Bitcoin will ever be created, making it a scarce digital asset.

Bitcoin's primary innovation was revolutionary: it was the first system that allowed two people, anywhere in the world, to send and store value digitally without relying on a trusted intermediary like a bank, credit card company, or government. While it wasn't the first attempt at digital cash, it was the first to successfully solve a critical flaw known as the double-spend problem.

### Solving the Double-Spend Problem

The double-spend problem is the inherent risk that a unit of digital currency can be spent more than once. With physical cash, this is impossible; once you hand someone a $20 bill, you no longer possess it to spend again. Digital information, however, is different.

Think of it like emailing a photograph. When you send a photo to a friend, you don't lose your copy; you simply create a duplicate. If digital money worked the same way, you could send someone $100, they would receive it, and you would still have the original $100 to spend again. This ability to duplicate money would render any digital currency worthless.

Early attempts at digital currencies, such as DigiCash in the 1980s, tried to solve this. DigiCash’s solution was to use a **central authority**—a single company—to keep a master ledger of all balances and validate every transaction. This worked, but it introduced a fatal flaw. The central entity had absolute control, giving it the power to freeze funds, reject transactions, and censor users. This defeated the core purpose of creating a monetary system free from centralized control and single points of failure.

### The Challenge of Decentralized Trust: The Byzantine Generals Problem

The challenge of building a system that can agree on a single source of truth without a central leader is a classic computer science dilemma known as the **Byzantine Generals Problem**.

The analogy goes like this: A group of Byzantine generals has surrounded an enemy city. They must all agree on a coordinated time to attack. They can only communicate via messengers, but some of the generals or messengers could be traitors who will deliver false information to sabotage the plan. How can the loyal generals reach a consensus and ensure a successful, unified attack?

This is directly analogous to a decentralized network of computers (nodes) trying to maintain a currency ledger. The network must collectively agree on which transactions are valid and in what order they occurred, even if some nodes on the network are malicious and trying to spread false information (like attempting to double-spend).

### Satoshi Nakamoto's Breakthrough: The Bitcoin Whitepaper

Satoshi Nakamoto's 2008 whitepaper proposed an elegant solution to both the double-spend problem and the Byzantine Generals Problem. The solution was Bitcoin, a system built on a new technology: the blockchain.

The core idea was to eliminate the need for a central authority by distributing the transaction ledger to everyone on the network. In this peer-to-peer system, every participant holds a copy of the entire history of transactions. When a new transaction occurs, the network collectively works to verify it, bundle it into a "block," and add it to the "chain" of previous blocks, creating a permanent and unchangeable record.

This design created a **credibly neutral** system.

-   **Neutrality:** The network is impartial. It doesn't know or care about a user's identity, location, wealth, or the purpose of their transaction. It simply processes valid transactions according to the rules written in its code.
-   **Credibility:** The system’s neutrality is not based on trust in a person or institution that could be biased. It is credible because its rules are built into its open-source code and enforced by the entire decentralized network.

The result is a global, permissionless, and censorship-resistant monetary system accessible to anyone with an internet connection. This has life-changing implications for individuals in countries with unstable currencies, restrictive financial systems, or for the billions of people excluded from traditional banking.

### Ethereum: The Evolution to a World Computer

A few years after Bitcoin's creation, a young developer named Vitalik Buterin saw an opportunity to expand on its core concepts. He believed the principle of a credibly neutral system could be applied to more than just money—it could be applied to **agreements**.

In 2015, Buterin and a team of co-founders launched **Ethereum**. Like Bitcoin, Ethereum has its own native digital currency, **Ether (ETH)**, which is used to power the network. But Ethereum's true superpower is its ability to run computer code on the blockchain. This capability allows it to execute "unbreakable agreements" known as smart contracts.

### Smart Contracts: Code as Unbreakable Law

The concept of a smart contract was first described by cryptographer Nick Szabo in 1994, but it was blockchain technology that finally made it practical. A smart contract is a digital agreement where the terms are written directly into lines of code. This code lives on the blockchain, and the network itself automatically enforces the rules and executes the outcomes of the contract.

Consider the difference between a traditional agreement and a smart contract:

-   **Traditional Agreement (Buying a House):** This process involves numerous trusted intermediaries like banks, lawyers, and title agents. It is slow, expensive, and requires you to trust that each party will act honestly and efficiently.
-   **Smart Contract Agreement (Flight Insurance):** Imagine an insurance policy written as a smart contract. The terms are simple: "IF flight is delayed by more than 24 hours, THEN automatically refund the passenger's ticket." The smart contract is connected to a reliable flight data source. If the condition is met, the code executes automatically, sending the refund to your digital wallet within minutes. There is no claim to file, no company to argue with, and no possibility for the insurer to change the terms or refuse to pay. The agreement is enforced by the immutable logic of the code.

### Bitcoin vs. Ethereum: Calculator vs. Computer

A simple analogy helps clarify the fundamental difference between these two pioneering blockchains:

-   **Bitcoin is like a calculator.** It is designed with intentional simplicity to do one thing exceptionally well: serve as a secure, decentralized store of value and medium of exchange. Its functionality is deliberately limited (it is **Turing incomplete**) to maximize security and reliability.
-   **Ethereum is like a world computer.** It can do everything Bitcoin can do, but its purpose is far broader. As a **Turing complete** system, it is designed to be a flexible platform on which developers can build and run a vast range of unstoppable applications and complex agreements using smart contracts.

## Benefits Of Blockchain

### The Permissionless Power of Blockchain

To understand why blockchain technology is so revolutionary, we first need to look at a fundamental concept: ownership. In the traditional financial world, your access to your own money is based on permission. Think about it—you need a bank's permission to open an account, to send money internationally, to withdraw large sums, or to make a major purchase. These intermediaries have ultimate control. They grant you permission to use your funds, and that permission can be revoked at any time. This raises a critical question: if someone else can deny you access to your money, is it even really yours?

Blockchains flip this model on its head by being **permissionless**. On a blockchain network, you have true ownership and control over your assets. There is no central authority or intermediary that can deny you access to the network or prevent you from sending a transaction. You don't need to ask for permission to use what is rightfully yours. This shift from a permissioned system to a permissionless one restores power and autonomy to the individual.

### Credible Neutrality: A System Without Favorites

Traditional financial systems are not always neutral. They can, and often do, discriminate. Access to services can be denied based on your nationality, your credit score, or even your political views. Many systems require a government-issued ID or a physical address, automatically excluding millions of people around the globe. Banks can block international payments to certain countries, effectively cutting off entire populations from the global economy.

Blockchains, by contrast, are **credibly neutral**. The underlying protocol—the code that runs the network—is designed to be impartial. It doesn't know your name, your location, your wealth, or your background. The system literally cannot play favorites because it is just code following rules. Transactions are validated based on mathematical principles, not human bias. This creates a level playing field where the rules apply equally to everyone, regardless of who they are or where they come from.

### Decentralization: The Unstoppable Network

The power behind these benefits comes from decentralization. Traditional systems are centralized, meaning they have a single point of control and, therefore, a single point of failure. A government can shut down a bank. A bank can freeze your account. A company can go bankrupt, taking customer funds with it. If a central server is seized or goes offline, the entire service can collapse.

A blockchain is **decentralized**. It isn't run by a single company or stored on a single server. Instead, it is maintained by a global network of thousands of computers (nodes), each storing an identical copy of the information. There is no central point of control to attack or shut down. To stop the network, you would effectively have to shut down the internet itself. Even if governments or banks try to block it, the network continues to run and process transactions because no single entity controls it. This makes it incredibly resilient, secure, and unstoppable.

### Immutability and Transparency: Building Trust with Code

Finally, traditional financial and legal systems are often opaque. Key decisions and actions happen behind closed doors. Furthermore, the rules can change without warning. A bank might change its fee structure, a company can update its terms of service long after you've agreed to them, and governments can alter regulations overnight. This creates uncertainty and a lack of trust.

Blockchains provide a foundation of trust through **immutability** and **transparency**.

-   **Transparency:** All transactions recorded on a public blockchain are visible to everyone. Anyone can audit the network to verify where funds are moving and confirm that the system is operating as expected. The rules of the protocol are also written in open-source code, available for anyone to inspect.
-   **Immutability:** Once a transaction is validated and added to the blockchain, it cannot be changed, altered, or deleted. This creates a permanent, unchangeable record of history.

Together, these features ensure that the system is both predictable and trustworthy. You don't have to trust a person or a company to act honorably; you only have to trust the code, which operates exactly as it is written for all to see.

## Use Cases Of Blockchains

### Practical, Real-World Use Cases of Blockchain Technology

Beyond the hype and speculation, what are the tangible problems that blockchain technology is solving today? This lesson explores the practical, real-world applications of blockchains, moving from foundational concepts like digital money to revolutionary ideas like decentralized governance and digital ownership.

### Key Blockchain Applications: From Digital Money to Smart Contracts

Blockchain's capabilities can be broken down into several key categories that are already creating significant impact across various industries.

#### Digital Money and Decentralized Finance (DeFi)

This is the most well-known application of blockchain. At its core, blockchain technology enables the creation of digital money, or cryptocurrency, that can be sent directly between individuals over the internet without intermediaries like banks. Bitcoin (BTC) on the Bitcoin blockchain and Ether (ETH) on Ethereum are prime examples.

This concept extends far beyond simple digital cash into the world of Decentralized Finance (DeFi). A critical innovation within DeFi is the **stablecoin**.

-   **Stablecoins:** These are digital currencies designed to maintain a stable value, often by being pegged to a real-world asset like the US dollar. For example, **USDC (USD Coin)** is a digital dollar where 1 USDC is designed to always equal $1. This provides a life-changing solution for people in countries experiencing hyperinflation, allowing them to protect their savings from the rapid devaluation of their local currency by holding a stable digital asset.

#### Decentralized Agreements with Smart Contracts

Blockchains enable the creation of deterministic, tamper-proof agreements known as smart contracts. Think of them as traditional legal contracts, but with their terms written in code and stored on the blockchain. These contracts automatically execute when their predefined conditions are met, making them transparent, immutable, and highly efficient.

-   **Example: Automated Insurance:** An insurance policy can be written as a smart contract. If a verifiable event, such as a major flood reported by a trusted data source, occurs, the smart contract can automatically execute the payout to the policyholder. This deterministic process eliminates administrative overhead, the need to file a claim, and the reliance on an insurance company's approval, ensuring a fast and fair settlement.

#### Solving Cross-Border Payments

The traditional system for sending money internationally is often described as broken—it's slow, expensive, and inaccessible to many. Services like PayPal or Venmo are not universally available, and wire transfers can take days to clear while incurring high fees.

Blockchain offers a powerful solution. It allows anyone to send value to anyone else, anywhere in the world, at any time. Transactions are typically settled in minutes, not days, and for a fraction of the cost. Applications like **Klever** leverage this technology to make sending money to a friend in another country as seamless as sending a text message.

#### Verifiable Digital Ownership

Blockchain provides a revolutionary way to prove ownership of both digital and physical assets. By representing ownership as a unique token (like an NFT) on an immutable ledger, it creates a universally verifiable and unfalsifiable certificate of authenticity.

This has profound implications for a wide range of assets:

-   **Digital Art & Music:** Creators can sell their work directly to fans, bypassing traditional gatekeepers like galleries or record labels that take a significant cut.
-   **In-Game Items:** Gamers can gain true ownership of the items they earn or purchase in video games, allowing them to trade or sell them on open marketplaces.
-   **Educational Certificates:** Academic and professional credentials can be issued on-chain, making them instantly verifiable and fraud-proof.
-   **Real-World Assets:** Physical assets, like real estate, can be "tokenized" and recorded on the blockchain, enabling new models like fractional ownership where multiple people can invest in a single property.

#### Democratizing Access to Financial Services

Billions of people globally are either "unbanked" or "underbanked," meaning they lack access to fundamental financial services like savings accounts, loans, or investment opportunities.

Blockchain and DeFi change this paradigm. With only a smartphone and an internet connection, anyone can access the same sophisticated financial tools that were once reserved for Wall Street. Users can trade assets, earn interest on savings, and invest to build wealth, regardless of their geographic location or socioeconomic status.

#### New Models of Governance with DAOs

Blockchain enables new forms of community-led decision-making through **Decentralized Autonomous Organizations (DAOs)**. A DAO functions like an internet-native organization or club where members use tokens to vote on proposals that dictate the group's rules and actions.

The entire process—from proposal to vote to execution—is transparently recorded on the blockchain. The outcomes are automatically implemented by smart contracts, ensuring that the community's decisions are carried out without the risk of censorship or manipulation by a central authority.

### Understanding Key Terminology

To navigate this space, it's essential to understand a few core concepts that define the technological shift underway.

-   **DApp (Decentralized Application):** A DApp is an application (like a website or mobile app) whose backend logic runs on a decentralized blockchain network instead of on centralized servers owned by a single company. If a service like Google ran its backend on a blockchain, it would be considered a DApp.
-   **The Evolution of the Web:**
    -   **Web1:** The initial phase of the internet, characterized by static, "read-only" websites.
    -   **Web2:** The "read-write" internet we use today. It's interactive and social, but our data and content are controlled by the large corporations that own the platforms.
    -   **Web3:** The next evolution of the internet, built on blockchain technology. It introduces smart contracts and digital ownership, creating an open internet where users have true control over their data and digital assets.

### Addressing Common Criticisms of Blockchain

As with any transformative technology, blockchain faces its share of skepticism. Here are answers to some of the most common concerns.

1.  **"Isn't it just for criminals?"**
    While any tool, including cash and the internet, can be used for illicit activities, blockchain transactions are fundamentally public and traceable. This permanent, immutable record makes it a challenging tool for anonymous crime. The technology itself is neutral, and its positive impact—such as providing financial access to billions of unbanked people—vastly outweighs its potential for misuse.

2.  **"Isn't it bad for the environment?"**
    This criticism is largely aimed at older blockchains like Bitcoin that use an energy-intensive consensus mechanism. However, the vast majority of modern blockchains are incredibly energy-efficient. After its major upgrade known as "The Merge," the Ethereum network now consumes significantly less energy than traditional banking systems and even large tech companies like Google or Netflix.

3.  **"Isn't it too complicated for the average person?"**
    The underlying technology is complex, but the user experience is improving at a rapid pace. Most people use the internet every day without understanding the intricate protocols like TCP/IP that make it work. Similarly, you won't need to be a blockchain expert to use DApps. The industry is focused on abstracting away the complexity to create simple, intuitive applications for everyone.

### The Future Powered by Blockchain

At its core, a blockchain is a shared, immutable ledger that allows communities to agree on what is true without needing to trust a central authority. It empowers individuals with direct ownership and control over their digital lives.

Looking ahead, this technology opens the door to a future where we can vote in elections with verifiable transparency, own fractional shares of real estate across the globe, manage a universal digital identity, and get paid instantly for our work.

To get a hands-on feel for the problems blockchain solves, visit the **Updraft Learning Hub** at `demos.updraft.cyfrin.io`. This interactive platform features challenges that simulate real-world scenarios like cross-border payments and hyperinflation, demonstrating exactly why this technology is so powerful.

## Many Many Chains

### Navigating the Multi-Chain World: From L1s and L2s to Testnets

When you first enter the world of web3, it's easy to assume that "the blockchain" is a single entity. However, the reality is a vast and expanding universe of different blockchains, a "multi-chain world" that can feel overwhelming. Beyond Bitcoin and Ethereum lie names like **zkSync, Solana, Arbitrum, Polygon, and Optimism**. This lesson will serve as your high-level map to this landscape, helping you understand why so many blockchains exist and how they are organized.

#### The Scalability Problem: Why So Many Chains?

The primary driver behind the explosion of new blockchains is the challenge of **scalability**. To understand this, let's look back at the NFT boom of 2021.

During this period, thousands of users rushed to the Ethereum network to mint, buy, and sell NFTs. But Ethereum was designed to process only about 15-30 transactions per second. When the demand for transactions far exceeds the available supply, the network becomes congested.

Imagine the Ethereum network as a single major highway leading into a bustling city. During rush hour, this highway gets jammed. Traffic slows to a crawl, and the cost of a cab ride skyrockets. Similarly, on a congested blockchain, transaction speeds plummet and **transaction fees**—the cost to have your transaction processed—become incredibly expensive. It wasn't uncommon for a user to face a $200 fee just to send $50 to a friend, making the network impractical for everyday use.

This fundamental problem of high demand leading to slow speeds and exorbitant fees is what prompted the crypto community to find a solution. The answer? Build more roads.

#### Building More Roads: Layer 1 and Layer 2 Blockchains

The "build more roads" solution has manifested in two primary ways: creating entirely new highways (Layer 1s) and adding express lanes to the existing highway (Layer 2s).

##### Layer 1 (L1) Blockchains

A **Layer 1 (L1)** is a foundational, independent blockchain built from the ground up. Think of **Solana** or **Avalanche**. These are entirely new highways, designed with different engineering principles to achieve higher speeds and lower costs than Ethereum. Each L1 has its own security model, developer community, and unique ecosystem.

Learning about different L1s is like learning different languages. This course focuses on the Ethereum ecosystem because it is the largest and most established, much like Spanish is a widely spoken language. Once you understand Ethereum, you'll find it much easier to learn and interact with other L1s, just as knowing Spanish makes it easier to pick up Italian or Portuguese.

##### Layer 2 (L2) Blockchains

A **Layer 2 (L2)** is a blockchain built _on top of_ an underlying Layer 1, most commonly Ethereum. L2s like **Arbitrum**, **Optimism**, and **zkSync** act as express lanes built above our congested Ethereum highway.

Their primary function is to handle transactions more efficiently. They process large batches of transactions "off-chain" at a very low cost, bundle them into a compressed summary, and then submit that summary back to the main Ethereum L1. By doing this, they inherit the security and decentralization of Ethereum while offering significantly faster transaction speeds and dramatically lower fees.

#### Real Money vs. Practice: Understanding Mainnet and Testnet

When you interact with any of these blockchains, you will be operating in one of two distinct environments: Mainnet or Testnet.

##### Mainnet

**Mainnet** is the live, public blockchain where transactions have real-world financial consequences. When you send tokens or interact with an application on Ethereum Mainnet, you are using digital assets with real monetary value. Every transaction costs real money in fees, and any mistakes are permanent. It's like sitting down at a poker table for the first time and playing with your own cash.

##### Testnet

A **Testnet** is a parallel testing environment. It is a replica of the Mainnet's protocol, but it uses tokens that have no real-world value. This risk-free environment allows developers to deploy and test their smart contracts, and it lets users experiment with applications without fear of losing real money.

To get these "fake" tokens for a testnet, you use a **faucet**. A faucet is typically a website where you can request free testnet tokens to be sent to your wallet address. At the time of this writing, Ethereum's primary testnet is called **Sepolia**.

#### A Unique Identifier: What is a Chain ID?

With so many different networks—L1s, L2s, mainnets, and testnets—how do our wallets and applications know which one they're connected to? The answer is the **Chain ID**.

A **Chain ID** is a unique number that serves as a specific identifier for a blockchain network. This simple number prevents you from accidentally trying to spend your valuable Ethereum Mainnet funds on the Sepolia Testnet, or vice-versa. For example:

-   **Ethereum Mainnet** has a Chain ID of **1**.
-   **Sepolia Testnet** has a Chain ID of **11155111**.

Your wallet uses the Chain ID to ensure it is communicating with the correct network for every transaction you sign. You can find the Chain ID and other connection details for hundreds of blockchains on websites like `chainlist.org`.

As we move forward, remember that repetition is the mother of skill. You don't need to memorize every name and number today. These core concepts—the multi-chain world, L1s, L2s, Mainnets, Testnets, and Chain IDs—will be revisited and reinforced throughout your journey.

## What Is the Blockchain Oracle Problem?

Before we explore one of the most fundamental challenges in Web3, let's quickly recap two core concepts. First, a blockchain is a decentralized, trustless source of truth. It's a shared ledger distributed across many nodes, ensuring that no single entity has control. This creates a transparent, permissionless, and censorship-resistant system.

Second, smart contracts are decentralized, unbreakable agreements that live on the blockchain. They are programs that execute deterministically based on their code, without needing an intermediary to enforce the rules. In essence, the code itself is the law.

These two technologies create a powerful, self-contained, and secure digital world. However, their greatest strength—their secure isolation—is also their greatest limitation.

### The Blockchain's Isolated World

By design, blockchains and the smart contracts that run on them are isolated systems. They can only read and interact with data that is already on the blockchain, or **on-chain**. This includes things like account balances, token transfers, or the state of other smart contracts.

They have no native capability to access any external, real-world data, often called **off-chain** data. This creates a significant problem because for smart contracts to be truly useful in real-world agreements, they often need information from outside their digital walls. Consider these examples:

-   A decentralized insurance contract needs weather information to pay out a claim for a flood.
-   A DeFi lending protocol needs real-time stock and cryptocurrency prices to manage collateral.
-   A prediction market needs to know the final score of a sports game or the results of an election to settle bets.
-   A supply chain application needs confirmation that a package has been delivered.

Without access to this off-chain data, smart contracts are limited to simple token-based operations. The challenge of securely getting external data onto the blockchain is known as the **Blockchain Oracle Problem**.

### Determinism: The Root of the Problem

You might ask, "Why can't a smart contract just make an API call to a weather website?" The reason lies in a core principle of blockchains: **determinism**. A deterministic system will always produce the same output given the same input. This predictability is what allows thousands of nodes around the world to process the same transactions and all arrive at the exact same state, maintaining consensus and security.

Real-world data, however, is **non-deterministic**. Data from an API can change from one moment to the next. If different nodes in the network were to fetch data at slightly different times, they would receive different values. One node might get a temperature of 25°C, while another gets 25.1°C a millisecond later. This discrepancy would cause the nodes to disagree on the resulting state of the blockchain, breaking the consensus mechanism and causing the entire system to fail.

### Oracles: The Bridge to the Real World

The solution to this problem is an **oracle**. An oracle is a service that acts as a bridge, fetching external, off-chain data and delivering it to the blockchain for smart contracts to use.

However, using a single, centralized oracle reintroduces the very problem that blockchains were designed to solve. If your decentralized, trustless smart contract relies on one centralized oracle, you create a single point of failure. What if that oracle gets hacked? What if it goes offline? What if its owner maliciously provides incorrect data? Your unbreakable agreement is now entirely dependent on a single, trusted entity, undermining the core value of decentralization.

### Decentralized Oracle Networks (DONs)

Just as blockchains require a decentralized network of nodes to be secure, oracles need a decentralized network to be trustworthy. This is where **Decentralized Oracle Networks (DONs)** come in.

A DON is a network of multiple, independent oracle nodes. Instead of relying on a single source, a smart contract can query a DON. Here’s how it works:

1.  Multiple independent nodes in the network fetch the same piece of data from the real world (e.g., the price of ETH from multiple premium data sources).
2.  The nodes cross-check the data with each other.
3.  They run a consensus protocol to agree on a single, correct value.
4.  This validated, agreed-upon value is then submitted on-chain to the smart contract.

This decentralized process ensures that the data delivered to the blockchain is accurate, reliable, and resistant to manipulation or single points of failure.

### The Rise of Hybrid Smart Contracts

The combination of secure on-chain code and reliable off-chain data provided by a DON creates what we call a **hybrid smart contract**. This architecture consists of two key parts:

-   **On-chain Component:** The core smart contract logic that lives on the blockchain, providing decentralization, security, and transparency.
-   **Off-chain Component:** The real-world data and computation provided by a Decentralized Oracle Network.

This hybrid model combines the best of both worlds: the tamper-proof security of the blockchain and the rich data and functionality of the real world. Today, most major Web3 protocols, from DeFi to blockchain gaming, use this hybrid architecture. In fact, the term "smart contract" is now often used interchangeably with "hybrid smart contract" because this model is essential for creating powerful, real-world applications.

### Chainlink: The Industry-Leading Oracle Network

**Chainlink** is the industry-standard, modular, and decentralized oracle network that provides the critical infrastructure to solve the oracle problem. One of its key strengths is that it is **blockchain-agnostic**, meaning its services can be integrated with many different blockchains, including Ethereum, Avalanche, Polygon, zkSync, and more. This makes learning Chainlink a highly transferable skill for any Web3 developer.

Chainlink provides a suite of essential services that enable hybrid smart contracts, including:

-   **Data Feeds:** Provide highly reliable, real-time financial market data, such as `Price Feeds`, which are the backbone of the DeFi ecosystem.
-   **Automation:** Allows for the automated execution of smart contract functions based on predefined triggers, such as time intervals, without relying on a centralized server.
-   **Verifiable Random Function (VRF):** Provides a source of provably fair and verifiable randomness, which is impossible for a blockchain to generate on its own. This is crucial for blockchain gaming, NFTs, and any application requiring unpredictable outcomes.
-   **Cross-Chain Communication:** Enables smart contracts on one blockchain to send messages and interact with smart contracts on another, connecting the fragmented Web3 ecosystem.

By solving the oracle problem, Decentralized Oracle Networks like Chainlink are the critical link that allows blockchains to securely interact with the real world, unlocking the full potential of smart contracts.

## The Purpose Of Smart Contracts

### Our World is Built on Promises

Take a moment to look around you. The chair you're sitting in, the electricity powering your screen, the food in your fridge—nearly every aspect of modern life exists because of an agreement. At its core, every contract, transaction, and service is a simple **promise**.

When you go for an oil change, the mechanic promises to perform the service correctly in exchange for your promise to pay. When you buy insurance, the company promises to cover your expenses if something goes wrong. Even the global supply chain that delivered your chair is an intricate web of promises between manufacturers, suppliers, and retailers.

In the traditional world, these agreements are essentially glorified "pinky swears." We ask the other party to promise they will act fairly and won't break the rules. The fundamental problem is that these pinky swears are broken all the time.

### The Problem: Why Promises Are So Easily Broken

The current system for managing agreements relies on trusting a central authority—a company, a bank, a government—to uphold its end of the bargain. This creates a massive point of failure known as **counterparty risk**: the risk that the other party will default on its obligation.

Why does this happen? Because these centralized entities are run by people with their own self-interests. When an opportunity arises to profit by bending or breaking the rules, the incentive to do so can be overwhelming. This isn't just a hypothetical problem; it's a recurring theme throughout history.

-   **The 2008 Financial Crisis**: This global meltdown was a direct result of broken promises. Centralized financial institutions engaged in non-transparent, back-room deals, creating complex financial products they knew were risky. Their implicit promise to manage the economy responsibly was shattered, leading to catastrophic consequences for millions.
-   **The McDonald's Monopoly Scam**: In the 1990s, McDonald's promised its customers a fair chance to win millions. However, an insider at the company responsible for the game pieces rigged the system, stealing up to $24 million in prize money. Because the game was centrally controlled and opaque, the public's promise of a fair shot was worthless.
-   **Robinhood Trading Halts**: During the GME and AMC stock frenzy, the trading platform Robinhood promised to provide fair market access to retail investors. Yet, at the height of the volatility, they broke that promise by halting trading for certain stocks. As a centralized company, they had a "switch" they could flip, denying users the ability to participate freely.
-   **Bank Runs**: The classic example is a bank run, as seen during the Great Depression. Banks promise to keep your money safe and available for withdrawal. But when too many people try to access their funds at once, the bank's broken promise—that it lent out the money and doesn't have it on hand—is exposed, causing the system to collapse.

In each case, the failure stemmed from having to trust a centralized party that ultimately acted in its own interest.

### The Solution: Creating Unbreakable Promises with Smart Contracts

What if we could create agreements that didn't rely on trusting another person or company? What if we could build promises that were guaranteed to execute exactly as written, without any possibility of tampering or censorship? This is the fundamental purpose of smart contracts and blockchain technology.

A **smart contract** is simply an agreement written in code and deployed on a decentralized blockchain. It's a set of instructions that automatically executes when specific conditions are met. Think of it as a digital vending machine: you insert your coin (data or value), and the machine is programmed to automatically dispense your product (an outcome). There's no intermediary needed to decide whether to honor the transaction.

By running this code on a decentralized network, we create a new kind of agreement—one that is "trust-minimized" and, for all practical purposes, unbreakable.

### The Three Pillars of Trustless Agreements

Smart contracts derive their power from three core properties inherited from blockchain technology:

1.  **Immutability**: Once a smart contract is deployed on the blockchain, its code **cannot be changed**. This is a revolutionary concept. In the McDonald's Monopoly example, if the lottery rules were in an immutable smart contract, it would have been cryptographically impossible for an insider to alter the outcome. The rules are locked in forever.
2.  **Decentralization**: The contract is not run on a single company's server; it's executed and verified by a global network of thousands of independent computers. This means there is no central "off switch." No single person or company, like Robinhood, can decide to halt its operation. The network as a whole ensures the contract continues to run as intended.
3.  **Transparency**: The code of a smart contract is typically public and viewable by anyone. This eliminates the "back-room deals" that led to the 2008 financial crisis. With transparency, anyone can audit the rules of the agreement and verify that they are fair before choosing to interact with it.

Together, these three pillars remove the need to trust a counterparty. You no longer have to trust their brand or their intentions; you only have to trust the verifiable logic of the code.

### Shifting from Brand-Based Trust to Math-Based Guarantees

This introduces a fundamental paradigm shift in how we establish trust.

The traditional world operates on **brand-based trust**, or "paper guarantees." You trust a bank because it has a well-known logo and a long history. You trust a company because of its reputation. But in this model, counterparty risk is high, transparency is often intentionally removed, and the promises are only as good as the people making them.

The Web3 world, powered by smart contracts, operates on **math-based trust**, or "cryptographic guarantees." You don't need to know or trust the people who wrote the code. You can trust the system because the cryptography and mathematics that underpin it are verifiable, deterministic, and enforced by a decentralized network. In this model, counterparty risk is low and transparent, and the system's rules are unavoidably built-in.

### How Smart Contracts Are Already Solving Real-World Problems

This isn't just theory; it's already in practice, most prominently in the world of Decentralized Finance (DeFi).

The problem exposed by Robinhood's trading halt has already been solved by **Decentralized Exchanges (DEXs)** like Uniswap. A DEX is a marketplace that runs entirely on smart contracts. There is no central company that can halt trading, freeze funds, or deny access. The rules are coded into immutable contracts, and the platform is available to everyone equally, 24/7. The rapid growth of assets managed by DeFi protocols—from under a billion to over $200 billion in just a few years—shows the immense demand for these trust-minimized financial systems.

Let's revisit the McDonald's Monopoly scam. If it were run on a blockchain, a smart contract could have used a **Decentralized Oracle Network**, like Chainlink's Verifiable Random Function (VRF), to generate a provably random and tamper-proof winning number. The entire process would be transparent and auditable, making it impossible to defraud.

### A Note on Centralized Failures vs. Decentralized Technology

It's crucial to address recent headlines about failures in the crypto space, such as the collapse of FTX. These events are often mistakenly cited as failures of blockchain or smart contracts. This is incorrect.

FTX was a **centralized, traditional company** operating with the same opaque, trust-based model as any Wall Street bank. It was a Web2 company masquerading as a Web3 innovator. Its collapse was a failure of centralized trust—the very problem that smart contracts are designed to solve. These events don't weaken the case for DeFi; they strengthen it by highlighting the urgent need for true decentralization and on-chain transparency.

## The Future is Verifiable

The purpose of smart contracts is to replace breakable, human-based promises with verifiable, math-based guarantees. It's about building systems where the rules are fair, transparent, and enforced automatically, without relying on the good intentions of a central party.

For developers and creators entering this space, the goal should be to act as a force for good. The technology offers a powerful toolkit to build applications that are inherently more fair and resilient than their traditional counterparts. By focusing on creating verifiable, trust-minimized systems, we can build a world based not on blind faith in institutions, but on a shared, unbreakable foundation of code.

## An Introduction to the Ethereum Virtual Machine (EVM)

If you’ve spent any time learning about Ethereum, you've likely encountered the term Ethereum Virtual Machine, or EVM. While it can sound complex, understanding the EVM at a high level is crucial for grasping how the network functions. This lesson will demystify the EVM, explaining what it is, why it’s essential, and how it relates to the broader Ethereum ecosystem. The goal is not to achieve deep technical mastery but to build a solid foundational understanding.

### What is the EVM?

At its core, the Ethereum Virtual Machine is the computation engine that drives the Ethereum network. It is a globally shared, sandboxed environment that exists on every full Ethereum node. The EVM provides a standard set of rules that governs how the state of the Ethereum blockchain changes from one block to the next. Its primary function is to execute smart contracts.

To make this concept more tangible, consider these two analogies:

1.  **An Operating System:** Think of the EVM as an operating system like Windows or macOS. Your computer's OS is designed to run various software applications. Similarly, the EVM is designed to run and manage a specific type of software: smart contracts.
2.  **A Robotic Chef:** Imagine a smart contract is a detailed "recipe" with precise, step-by-step instructions. The EVM is the "robotic chef" that follows this recipe. No matter how many times the chef is given the same recipe and ingredients (inputs), it will execute each step identically, producing the exact same dish (outcome) every single time.

This predictable, deterministic execution is the defining characteristic of the EVM.

### Why the EVM is Essential for Decentralization

Blockchains like Ethereum are decentralized, meaning they are run and maintained by thousands of independent computers (nodes) distributed across the globe. When a user interacts with a smart contract, that transaction is broadcast to the network, and every node must process it independently to validate it.

This presents a significant challenge: how do you ensure that every single one of these thousands of nodes arrives at the exact same result?

This is where the EVM comes in. The EVM acts as a universal standard for computation. Because every node on the network runs an implementation of the EVM, they all follow the exact same rules for executing smart contract code. This guarantees that a transaction will produce the same outcome on every machine, allowing the entire network to agree on a single, shared state. This deterministic execution is the bedrock of consensus in a decentralized system.

While the EVM is a specification—a set of rules—it is brought to life by client software. Nodes run client software like GETH (Go Ethereum), which contains an EVM implementation that follows the specification to the letter.

### EVM Equivalence vs. EVM Compatibility: A Key Distinction

The EVM's success has led many other blockchains, particularly Layer 2 rollups, to adopt its design. However, not all "EVM chains" are created equal. It's important to understand the difference between EVM Equivalence and EVM Compatibility.

#### EVM Equivalence

An EVM Equivalent chain is designed to behave **identically to the Ethereum mainnet in every way**. The underlying mechanics, opcodes, and state-transition logic are the same.

-   **Implication for Developers:** You can take a smart contract that works on Ethereum and deploy it directly to an EVM Equivalent chain without changing a single line of code or using different development tools. Its behavior will be exactly as expected.
-   **Examples:** Optimism (OP), Arbitrum.

#### EVM Compatibility

An EVM Compatible chain can execute smart contracts written in EVM-native languages like Solidity, but there are **some differences in how the chain works "under the hood."** These chains have made modifications or optimizations to the core architecture.

-   **Implication for Developers:** While most code will work seamlessly, these underlying differences may require developers to make small adjustments to their smart contracts or use specialized tooling to deploy and interact with them.
-   **Examples:** Polygon zkEVM, zkSync Era.

### A Crucial Tip for Developers

As you build within the Ethereum ecosystem—which includes the mainnet and its vast network of Layer 2s and rollups—it is vital to recognize these nuances. A critical piece of advice is to **always check the official developer documentation** for any EVM chain you plan to build on. Understanding the subtle differences between that chain and Ethereum is crucial for both functionality and security.

## Understanding the Core Benefits of Smart Contracts

Before we dive into the practical applications of web3—interacting with the blockchain, acquiring testnet funds, and sending transactions—it is crucial to solidify our understanding of why this technology is so revolutionary. Building on our foundational knowledge, this lesson explores the specific, transformative benefits of smart contracts. Most of these advantages are inherited directly from the underlying blockchain technology that powers them.

### Decentralization: No Single Point of Failure

At their core, smart contracts are decentralized. This means they are not controlled by any single entity or server. Blockchains are supported by thousands of independent computers, or nodes, around the world, all running the same software and validating the same set of transactions. Because a smart contract is simply code that lives on the blockchain, it inherits this robust, decentralized nature.

Consider a traditional, centralized system like a bank. The bank has complete control. It can decide to freeze your assets, and if its central servers go down, you are left without access to your funds. There is a single point of failure. In contrast, a smart contract on a blockchain will continue to execute as programmed even if hundreds of its supporting nodes go offline. As long as at least one node in the network remains operational, the system endures.

### Transparency and Verifiability: No Hidden Surprises

Every action and every line of code on a public blockchain is transparent and verifiable by anyone. Before you interact with a smart contract, you can inspect its code to see exactly what it is programmed to do. There are no hidden fees, no obscure fine print, and no risk of the terms changing without your knowledge.

This is like knowing the precise rules of a game before you agree to play, with the added assurance that those rules are enforced for everyone and cannot be changed mid-game.

A powerful example is insurance. Imagine you have traditional home insurance that covers wildfires. If a wildfire is forecasted near your home, the insurance company could legally amend its terms of service to exclude wildfire coverage, even after you have paid premiums for years. They can simply decide not to pay out.

With a smart contract, this is impossible. An insurance agreement could be coded to automatically trigger a payout based on verifiable, real-world data. Using a decentralized oracle network like Chainlink, the smart contract could receive data confirming a wildfire in your location. Once that condition is met, the funds are released automatically according to the immutable terms you agreed to.

### Pseudo-Anonymity: Transparency with Privacy

While the blockchain is transparent, it is also pseudo-anonymous. This means that on-chain actions are not directly tied to your real-world identity. Instead of your name, your identity is represented by a long, cryptographic address. While every transaction from that address is public, linking that address to a specific person requires external information. This model provides public verifiability while preserving a crucial degree of personal privacy.

For use cases requiring even greater privacy, advanced cryptographic technologies like Zero-Knowledge Proofs (ZKPs) are being developed, allowing users to prove something is true without revealing the underlying information.

### Speed and Efficiency: Automation Without Borders or Business Hours

Smart contracts offer a dramatic increase in speed and efficiency compared to traditional processes. An international bank transfer can take several business days or even weeks to clear, subject to holidays, time zones, and manual processing.

Smart contracts, however, execute automatically the moment their predefined conditions are met. They operate 24/7, 365 days a year, without the need for manual intervention or intermediaries. This instant, automated execution drastically reduces the time and cost associated with complex agreements.

### Immutability: Code That Cannot Be Changed

Once a smart contract is deployed to the blockchain, its code is immutable—it cannot be changed or deleted. The terms of the agreement are locked in permanently. This prevents the kind of "bait-and-switch" scenario described in the insurance example, where one party unilaterally alters the terms to their advantage. The code is on-chain, and it is there forever.

There is a small caveat to this: **upgradeable smart contracts**. This is an advanced design pattern where an initial contract is designed to delegate its logic to a second, newer contract. It acts like a permanent signpost that can be updated to point to a new address. However, this capability for upgrading must be programmed into the original contract from the very beginning, so users are fully aware of it. The process is still transparent, and users can verify who has the authority to implement such an upgrade.

This immutability also creates incredible security. To hack a traditional system, a malicious actor only needs to breach a single central server. To alter the history of a major blockchain like Ethereum, a hacker would need to control over half of the network's entire computing power—an event known as a **51% attack**. This is considered virtually impossible on established networks, making them exceptionally tamper-proof.

### Trust Minimized: From Promises to Mathematical Certainty

Perhaps the most profound benefit of smart contracts is that they create a "trust-minimized" environment. In traditional systems, we rely on trusting our counterparties. We trust the insurance company to pay out, the bank to safeguard our funds, and the employer to pay our salary. This trust is based on brand reputation, legal recourse, and promises.

Smart contracts replace this reliance on trust with the cryptographic certainty of code. You don't have to trust that the other party will honor their promise because the contract will execute deterministically as programmed. The system shifts from a "brand-based" world to a "math-based" one, where agreements are not just promises but unbreakable, verifiable, and self-enforcing digital protocols.

# Sending Transactions

## What Is a Blockchain Wallet?

To understand what a blockchain wallet is, let’s start with a simple, real-world scenario. Imagine Jess owes her friend Ciara $5. If they are in the same room, the process is simple: Jess opens her physical wallet, takes out a $5 bill, and hands it directly to Ciara. This is a direct, wallet-to-wallet transfer—it's immediate, simple, and involves no one else.

Now, imagine Jess and Ciara are on opposite sides of the world. Sending that same $5 becomes much more complicated. Jess would need to use a bank or another third-party service, which involves fees, delays, and a more complex process.

Blockchain technology was designed to solve this problem. It allows for digital transactions that are as direct and easy as handing cash to someone in person, regardless of physical distance. The tool that makes this possible is the blockchain wallet.

A blockchain wallet is a secure digital application that allows you to manage your digital assets and interact with blockchain networks. Think of it as your personal access point to the world of Web3. With a wallet, you can perform three essential functions:

1.  **Review your balances** (e.g., see that you have 0.1 ETH or 0.02 BTC).
2.  **View your transaction history** (e.g., review a record of sending or receiving tokens).
3.  **Send and receive digital tokens**.

While the underlying technology is complex, the wallet handles all the technical details for you, providing a user-friendly interface for managing your assets.

### Understanding Native Currency and Your Wallet Address

Before you can send or receive assets, there are two fundamental concepts to grasp: native currency and your wallet address.

**1. Native Currency**

Most blockchains have a primary, built-in token called a "native currency." This is similar to how different countries have their own national currencies, like the Great British Pound in the UK or the US Dollar in America.

For example:

-   The native currency of the **Bitcoin** blockchain is **Bitcoin (BTC)**.
-   The native currency of the **Ethereum** blockchain is **Ether (ETH)**.

For the purpose of this course, we will focus primarily on **Ether (ETH)** and the **Ethereum blockchain**.

**2. Your Wallet Address**

When you create a new blockchain wallet, it generates a **unique wallet address**. This address is a long string of letters and numbers, such as `0x5392BD00571157Fa11103b0eE6D492c9563a6799`.

The easiest way to think of your wallet address is as your **digital mailbox**. In the physical world, if someone wants to send you a package, they need your mailing address. In the digital world, if someone wants to send you digital tokens like Ether, they need your wallet address. It is the public identifier you share with others to receive funds.

### How a Wallet Works in Practice

Let’s return to our example. Jess and Ciara agree that the $5 debt will be paid in digital tokens. To complete the transaction, Jess needs only one piece of information from Ciara: her wallet address.

The process is straightforward:

1.  Jess asks Ciara for her wallet address.
2.  Ciara provides her address (e.g., `0x5328ef2...`).
3.  Jess opens her own blockchain wallet, initiates a new transaction, and enters Ciara's wallet address as the destination.
4.  She specifies the amount of tokens to send and confirms the transaction.

Her wallet securely approves and broadcasts this transaction to the blockchain network. Moments later, the tokens arrive in Ciara's wallet. The transfer is complete—direct, secure, and without the need for a traditional bank.

### Summary

A blockchain wallet is your gateway to interacting with a blockchain. It allows you to review your balances, view transaction history, and send or receive digital tokens. When you create a wallet, you get a unique **wallet address**—your public "digital mailbox" that you share with others to receive funds.

## Getting Started: Setting Up Your First Blockchain Wallet

Blockchains are peer-to-peer networks that allow for the secure transfer of digital assets. To interact with these networks, you need a specialized tool called a blockchain wallet. This lesson provides a practical, step-by-step guide to setting up your first wallet using MetaMask, one of the most popular and reliable options available.

MetaMask is a software application that functions as both a cryptocurrency wallet and a gateway to the decentralized web. It allows you to view your asset balances, review your transaction history, and send or receive digital tokens securely.

### How to Install the MetaMask Browser Extension

The first step is to install MetaMask as a browser extension. Follow these instructions carefully.

1.  Open your web browser and navigate to the official MetaMask website: `metamask.io`.
2.  **Security Warning:** Always double-check that the URL is correct. Scammers create phishing sites with similar-looking URLs to steal your information. The only official site is `metamask.io`.
3.  Click the "Download" or "Get MetaMask" button on the homepage. You will be redirected to your browser's official extension store (e.g., Chrome Web Store, Firefox Add-ons).
4.  Click the button that says "Add to Chrome" or the equivalent for your browser.
5.  A permission prompt will appear. Review it and click **"Add extension"** to proceed.
6.  Once the installation is complete, a MetaMask welcome page will open in a new tab. Click "Get Started" and agree to the Terms of Use to begin creating your wallet.

### Creating Your Wallet and Understanding Self-Custody

On the setup screen, select the option to **"Create a new wallet."** You will be presented with a few setup methods, including "Continue with Google," "Continue with Apple," or "Use Secret Recovery Phrase."

For maximum security, we strongly recommend using the **Secret Recovery Phrase (SRP)** method. While linking to a Google or Apple account may seem convenient, it creates a potential point of failure. If those accounts are compromised, a hacker could potentially gain access to your wallet.

Using an SRP ensures your wallet is completely independent and self-custodied. **Self-custody** is a core concept in web3, meaning you—and only you—have full control over your private keys and digital assets. This control comes with the full responsibility for securing your wallet.

**Important Disclaimer:** The wallet you create by following this tutorial should be used for educational and practice purposes only. **You should NEVER deposit real funds into a wallet whose Secret Recovery Phrase has been exposed or viewed on screen, as it is in this guide.** Once you are comfortable with the process, you should create a separate, completely private wallet for managing real assets.

### Setting a Strong Local Password

The first step in the SRP setup process is to create a local password.

This password does not control your funds directly. Its purpose is to encrypt your wallet's data on the specific computer and browser you are currently using. If you were to install MetaMask on a new device, this password would be useless; only your Secret Recovery Phrase can restore your wallet.

When creating your password, follow these best practices:

-   Use a strong, unique combination of uppercase and lowercase letters, numbers, and symbols.
-   Never reuse a password from another website or service.

You will need to check a box acknowledging that **MetaMask cannot recover this password for you.** If you forget it, you will need to restore your wallet using your Secret Recovery Phrase.

### Your Secret Recovery Phrase: The Master Key to Your Funds

This is the most critical step in securing your digital assets. After setting your password, MetaMask will reveal your Secret Recovery Phrase (SRP).

The SRP is a unique list of **12 words** that acts as the master key to your wallet. Anyone who possesses this 12-word phrase can access your wallet and control all of your funds from any device in the world.

If you lose your SRP, you will lose access to your funds **permanently and irreversibly**. There is no customer support to call and no "forgot my SRP" button. This is the fundamental trade-off for the complete control that self-custody provides.

To protect your SRP, you must follow these rules without exception:

-   **DO NOT** take a screenshot of your SRP.
-   **DO NOT** take a photo of it with your phone.
-   **DO NOT** save it in a text file, Word document, or notes app on your computer.
-   **DO NOT** store it in a password manager or any cloud-based service like Google Drive, iCloud, or Dropbox. Any device connected to the internet is a potential target for hackers.

-   **DO** write the 12 words down on a physical piece of paper.
-   **DO** double-check that you have written them down correctly and in the right order.
-   **DO** store this piece of paper in a secure, offline location that only you know about, such as a physical safe or a safety deposit box. For ultimate durability, some users engrave their phrase onto a metal plate to protect it from fire or water damage.

### Confirming Your Setup and Accessing Your Wallet

After you have securely written down your Secret Recovery Phrase, click "Next." To ensure you have saved it correctly, MetaMask will prompt you to confirm the phrase by asking you to fill in some of the missing words in the correct order.

Once you have correctly entered the words, click "Confirm." You will see a "Congratulations" screen indicating your wallet has been created successfully. After clicking through the final informational pop-ups, you will be taken to your main MetaMask wallet dashboard. Your account balance will be displayed, starting at $0.00.

### Key Takeaways and Next Steps

Congratulations, you have successfully set up a blockchain wallet. MetaMask is a type of **software wallet**, often called a "hot wallet" because it is connected to the internet. For storing significant value, many users opt for **hardware wallets** (or "cold wallets"), which are physical devices that keep your keys completely offline, offering an even higher level of security.

Remember, the wallet you just created is a practice wallet. Use it to get comfortable with the interface and security protocols in a risk-free environment. When you are ready to manage real funds, create a brand new wallet and ensure its Secret Recovery Phrase is never exposed to any digital device.

Always remain vigilant. The digital asset space is targeted by scammers. Never, under any circumstances, share your Secret Recovery Phrase with anyone. No legitimate company or support agent will ever ask for it. Your security is your responsibility.

## MetaMask Wallet: A Detailed Walkthrough

### Pinning the MetaMask Extension for Quick Access

To ensure your MetaMask wallet is always just a click away, you should pin the extension to your browser's toolbar.

1.  In your Chrome browser, locate and click the jigsaw puzzle icon (Extensions) in the top-right corner.
2.  A dropdown menu will appear, listing all your installed extensions.
3.  Find MetaMask in the list and click the **pin icon** next to it.

The MetaMask fox logo will now be permanently visible on your toolbar, allowing for instant access from any webpage.

### Navigating the MetaMask Interface

You can interact with your wallet in two primary views. The view you choose depends on the complexity of the task you are performing.

-   **Pop-up View:** Clicking the pinned MetaMask icon opens a compact, pop-up window. This is ideal for quick actions like signing transactions or checking your balance.
-   **Expanded View:** For a more detailed and less cramped experience, click the three-dots menu in the top-right corner of the pop-up and select **"Expand view"**. This opens your wallet in a new, dedicated browser tab, providing a full-screen interface that is easier to navigate for more complex tasks.

### Understanding Networks and Multi-Chain Capability

A common misconception is that MetaMask is only for Ethereum. In reality, it is a powerful multi-chain wallet compatible with any blockchain built on the Ethereum Virtual Machine (EVM). This means a single wallet, secured by one Secret Recovery Phrase, can manage assets and interact with decentralized applications across numerous networks, including:

-   Ethereum
-   Arbitrum
-   Optimism
-   Base

MetaMask is also expanding its support for non-EVM chains, with recent integrations like Solana.

### Managing and Switching Between Networks

Your wallet must be connected to the correct network to view your assets or interact with an application on that chain.

#### Viewing and Switching Networks

To switch between networks, click the network dropdown menu located at the top-left of the wallet interface. By default, this will show "Ethereum Mainnet." Clicking it opens a "Select network" menu where you can choose from a list of popular mainnets and any custom networks you have added.

#### Adding a Custom Network

If a network isn't listed by default, you can add it manually.

1.  Click the network dropdown menu.
2.  Navigate to the **"Custom"** tab.
3.  Click **"Add custom network"**.
4.  You will be prompted to enter the network's configuration details. The key fields are:
    -   **`Network name`**: The human-readable name of the chain (e.g., Polygon Mainnet).
    -   **`Default RPC URL`**: The endpoint your wallet uses to communicate with the blockchain.
    -   **`Chain ID`**: The unique numerical identifier for the network, which prevents transaction replay attacks across different chains.

#### Enabling and Using Testnets

For developers and users who want to experiment without risking real funds, testnets are essential. These are not visible by default and must be enabled.

1.  Click the three-dots menu in the top-right of your wallet.
2.  Select **"Networks"**.
3.  In the "Manage networks" pop-up, scroll to the bottom.
4.  Find the **"Show test networks"** option and click the toggle to enable it.

Once enabled, testnets like **Sepolia** (the most popular Ethereum testnet) will appear in your network selection list. When you switch to a testnet, your balance will update to reflect your assets on that specific network (e.g., "0 SepoliaETH").

### Your Wallet Address and Using a Block Explorer

Your wallet address is your public identifier on the blockchain. Think of it as a digital mailbox where anyone can send you cryptocurrencies and NFTs.

The address is a long string of characters starting with `0x...` and is displayed directly under your account name (e.g., "Account 1"). You can click on the address to instantly copy it to your clipboard.

To view the activity of any wallet address, you can use a **block explorer** - a public tool that lets you search and view blockchain data transparently. The most popular options are **Etherscan** (`etherscan.io`) and **Blockscout** (`eth.blockscout.com`), an open-source alternative. By pasting a wallet address into the search bar on either explorer, you can view its balance and complete transaction history. For a brand-new wallet, the explorer will correctly show a balance of `0 ETH` and no transactions.

### Creating and Managing Multiple Accounts

MetaMask allows you to generate multiple, separate accounts within the same wallet installation. This is useful for organizing assets or separating different activities.

1.  Click the account name dropdown at the top-left (e.g., "Account 1").
2.  In the menu that appears, click **"Add account or wallet"**.
3.  Select **"Create a new account"** and then **"Ethereum account"**.
4.  Name your new account (e.g., "Account 2") and click "Add account".

Each account you create will have its own unique wallet address. However, it is critical to understand that **all accounts are derived from and secured by the same 12-word Secret Recovery Phrase**. If you lose this phrase, you lose access to every account you have created within that wallet.

### Essential Security: Separating Your Development and Main Wallets

As a final and crucial security practice, you must maintain a strict separation between wallets used for different purposes.

-   **Development/Educational Wallet:** The wallet you create while learning and experimenting should be used **exclusively for testnets and educational activities**. Never store any real, valuable assets in this wallet, as you may be interacting with unaudited smart contracts or potentially malicious websites.
-   **Real Funds Wallet:** When you are ready to manage real assets, create a **brand new Chrome profile**. Inside this clean, separate profile, install MetaMask again. This will generate a completely new wallet with a new, unique Secret Recovery Phrase. This wallet should be used exclusively for your personal funds.

This separation is a fundamental principle of operational security (OpSec) in web3. It creates an essential firewall between your experimental environment and your valuable assets, significantly reducing your risk of loss.

## How to Send Your First Blockchain Transaction with a Tenderly Virtual Testnet

Welcome to your practical guide to interacting with a blockchain. In this lesson, you will learn how to set up your own private, simulated blockchain environment, connect it to your MetaMask wallet, and send your very first transaction. We will use a powerful tool called Tenderly to accomplish this, which allows us to experiment safely without spending any real money.

Before we begin the step-by-step process, let's clarify the environment we'll be working in: a testnet.

A testnet is a blockchain that functions as a sandboxed testing ground. It’s a critical tool for developers and learners, allowing you to simulate transactions, deploy smart contracts, and test blockchain features without any financial risk. There are two primary types of testnets:

1.  **Public Testnets (e.g., Sepolia):** These are decentralized blockchains that mimic a mainnet like Ethereum. They are kept running by a global network of volunteer node operators and are publicly accessible to anyone.
2.  **Virtual Testnets (e.g., Tenderly):** These are private, simulated blockchain environments provided as a service. Instead of relying on public volunteers, the service provider (Tenderly) manages the infrastructure. This gives you complete control and allows for incredibly fast setup, letting you create a personal copy, or "fork," of a blockchain in seconds.

For this lesson, we will focus on the speed and convenience of a Tenderly Virtual Testnet.

### Step 1: Create a Tenderly Account

First, you need to sign up for a free Tenderly account. We will start from the official course repository to ensure you are using the correct link.

1.  Navigate to the course's GitHub repository: [https://github.com/Cyfrin/blockchain-basics-cu](https://github.com/Cyfrin/blockchain-basics-cu)
2.  In the main `README.md` file, scroll down to the section titled **"Testnet Faucets"**.
3.  Locate the link next to **"Tenderly Virtual Signup"** and click it. Using this specific link, which contains tracking parameters (`...&mtm_kwd=cyfrin`), signals to Tenderly that you came from this course. This support helps us continue to provide free educational content.
4.  On the Tenderly website, click the **"Build for free"** button and follow the prompts to create your account.

### Step 2: Create Your Virtual TestNet

Once you are logged into your Tenderly dashboard, you can create your own personal blockchain.

1.  From the navigation menu on the left, select **"Virtual TestNets"**.
2.  Click the prominent **"Create Virtual TestNet"** button.
3.  A configuration screen will appear. Set the following options:
    -   **Parent network:** Select **Mainnet**. This instructs Tenderly to create a fork—a direct copy—of the current state of the Ethereum Mainnet.
    -   **Name:** Give your testnet a unique name. For example, `MyFirstChain`.
    -   **Chain ID:** This is a critical security step. Every blockchain network has a unique ID (Ethereum Mainnet is `1`). To prevent transaction conflicts and a security risk known as a "replay attack," you must set a custom ID. A good practice is to prefix the parent network's ID with `7357`. Since we are forking Mainnet (`1`), your custom Chain ID should be `73571`.
4.  Leave all other settings as their default values and click **"Create"**.

Congratulations! You have just created your own private, functioning blockchain.

### Step 3: Connect MetaMask to Your Virtual TestNet

Now, let's connect your new blockchain to a real crypto wallet so you can interact with it.

1.  On your new virtual testnet's dashboard page in Tenderly, look for a small wallet icon labeled **"Add RPC to Wallet"** in the top-right corner and click it.
2.  MetaMask will automatically open with two requests for your approval:
    -   First, it will ask for permission to let `tenderly.co` connect to your wallet. Click **"Connect"**.
    -   Second, it will ask for permission to add your new network (e.g., `MyFirstChain`) to your wallet's list of available networks. Click **"Approve"**.
3.  Your MetaMask wallet is now connected to your private virtual testnet. You can confirm this by looking at the network selector dropdown in the top-left of MetaMask, where your new network should be selected.

### Step 4: Fund Your Wallet with Test Ether

To send a transaction, you need some currency. On our virtual testnet, we can instantly mint test Ether (ETH) with no real-world value.

1.  Open MetaMask and ensure you are on your virtual testnet. Copy your wallet address (e.g., "Account 1") by clicking on it.
2.  Return to your testnet's dashboard in Tenderly and click the **"Fund"** button.
3.  In the pop-up window, fill in the details:
    -   **Wallet:** Paste your copied MetaMask address.
    -   **Token:** Select **Ether (ETH)** from the dropdown.
    -   **Amount:** Enter the amount of test ETH you'd like. For this exercise, enter `1000`.
4.  Click **"Top up account"**.

This funding action is technically your first transaction on this blockchain. Behind the scenes, Tenderly executed a function called `addBalance` to mint 1,000 test ETH and place it directly into your wallet. You can see this transaction appear in the list at the bottom of your Tenderly dashboard. To verify the funds in your wallet, open MetaMask and check your token balance; it should now read 1,000 ETH.

### Step 5: Send a Wallet-to-Wallet Transaction

You are now ready to perform the most fundamental action on a blockchain: sending currency from one wallet to another. We will simulate this by sending ETH from your primary account ("Account 1") to a secondary account in the same MetaMask wallet.

1.  **Get the Recipient Address:** In MetaMask, click the account icon in the top right (next to "Account 1") and select **"Account 2"**. Copy the address for Account 2 to your clipboard.
2.  **Switch Back to Sender:** Switch back to **Account 1**, which holds the 1,000 test ETH.
3.  **Initiate the Transfer:** Click the **"Send"** button in MetaMask.
4.  **Enter Transaction Details:**
    -   In the recipient field, paste the address for **Account 2**.
    -   In the **Amount** field, enter the amount you wish to send. Let's send `50` ETH.
5.  **Confirm the Transaction:** Click **"Continue"**. MetaMask will show you a final review screen detailing the amount and the network fee (gas). Click **"Confirm"** to broadcast the transaction to your virtual blockchain.

In a few moments, the transaction will be confirmed. You can verify the transfer was successful in two ways:

-   In **Account 1**, your ETH balance will now be 950, and the "Activity" tab will show a "Sent" transaction for -50 ETH.
-   Switch to **Account 2**. The token balance will now show **50 ETH**.

You have now successfully created a private blockchain, funded a wallet, and executed a genuine wallet-to-wallet transfer. This process covers the fundamental mechanics of using any blockchain, providing you with a safe and effective foundation for your Web3 journey.

## A Crucial Guide to Testnets: Public vs. Virtual

Deploying a smart contract or making a transaction on a testnet is often a final, satisfying step in the development process. It’s the moment your code comes to life on a blockchain, making your work feel tangible and real. However, the landscape of testnets has evolved, and choosing the right environment is critical for a smooth and productive learning experience. This lesson serves as an important advisory for navigating testnets within the Cyfrin Updraft curriculum.

### The Growing Challenge of Public Testnets

Public testnets, such as **Sepolia**, are designed to mimic the conditions of a mainnet blockchain. They are decentralized networks that require volunteers to run nodes, keeping the chain operational and secure. To perform any action on these networks, like deploying a contract, you need the network's native test currency, such as testnet ETH. This is traditionally acquired from a service called a **faucet**, which distributes small amounts of test currency for free.

Unfortunately, what was once a simple process has become a significant bottleneck for developers. Over the last couple of years, acquiring testnet ETH has become incredibly challenging for several reasons:

-   **Scarcity and High Barriers to Entry:** Faucets for major public testnets are no longer open to everyone. Many now require you to hold a minimum amount of real, mainnet ETH in your wallet to prove you are a legitimate developer. This creates a financial barrier that is impractical for those just starting their learning journey.
-   **Time-Consuming Process:** Even if you meet the requirements, the process of claiming from a faucet can be frustrating and time-consuming.
-   **Minimal Payouts:** After navigating these hurdles, the amount of testnet ETH you receive is often minuscule—sometimes as little as 0.05 ETH. This is often insufficient for the comprehensive testing and multiple deployments required when learning smart contract development.

For these reasons, relying on public testnets for your day-to-day development and coursework has become almost impossible.

### The Recommended Solution: Tenderly's Virtual Testnets

To ensure you can focus on learning without these frustrations, we strongly recommend using **Tenderly's virtual testnets** for all development and testing purposes throughout this course.

A virtual testnet is a private, simulated blockchain environment that gives you complete control. As you’ve seen in previous lessons, you can fund any account with any amount of test ETH instantly with the simple click of a "Fund" button.

Using a virtual testnet offers significant advantages:

-   **Ease of Use:** Eliminate the need to hunt for functional faucets or hold mainnet funds. Get the resources you need, when you need them.
-   **Efficiency:** Save valuable time and avoid the frustrating experience of being blocked by a lack of testnet funds.
-   **Educational Equivalence:** For the purpose of learning core development concepts, deploying contracts, and interacting with the blockchain, a virtual testnet is just as effective as a public one. The skills you build are directly transferable.

Therefore, whenever a lesson requires you to deploy to or interact with a testnet, your default choice should be the Tenderly virtual testnet.

### A Look Ahead: Demonstrating Public Tools

While you will be working in a virtual environment, understanding the tools used on public networks is still essential for your career as a web3 developer. In an upcoming lesson, we will demonstrate making a transaction on the **Sepolia** public testnet.

**Crucially, this demonstration is for observation only. You are not encouraged to follow along.** The goal is not for you to repeat the steps but to see how essential public-facing tools like block explorers work in a live environment. We will showcase popular block explorers like **Etherscan** and **Blockscout**, which are indispensable for debugging transactions and inspecting contracts on both testnets and mainnet.

By watching this demonstration, you will gain familiarity with the public blockchain ecosystem without having to face the real-world costs and complexities of acquiring funds. The core skills remain the same, whether you are inspecting a transaction on Tenderly, Sepolia, or the Ethereum mainnet.

## A Step-by-Step Guide to Sending Your First Public Testnet Transaction

This lesson will guide you through the fundamental process of interacting with a public blockchain. You will learn how to acquire free test currency from a public faucet, use it to send a transaction between two wallets, and verify your activity on a public block explorer. We will use the Sepolia testnet, the MetaMask wallet, and a block explorer (Etherscan in this demonstration).

### Step 1: Acquiring Testnet ETH from a Faucet

Before you can send a transaction, you need currency to pay for it. On a testnet, this currency has no real-world value and can be obtained for free from a service called a **faucet**. A faucet is a developer tool that distributes small amounts of testnet tokens to users for testing purposes.

1.  **Locate a Faucet**: A reliable, curated list of testnet faucets can be found in the `README.md` file of the Cyfrin `blockchain-basics-cu` GitHub repository. We will use the **"Main (Sepolia): Sepolia GCP Faucet"** provided by Google Cloud for this demonstration.
2.  **Request Funds**: Navigate to the faucet's webpage. You will need to provide your wallet address to receive the funds.
    -   Open your MetaMask browser extension and ensure you have "Account 1" selected.
    -   Click on your address (e.g., `0x7c7T2...8987F`) to copy it to your clipboard.
    -   Paste this address into the input field on the faucet website.
    -   Click the button to receive your testnet ETH, which in this case is **"Receive 0.05 Sepolia ETH"**.
3.  **Faucet Requirements**: Please note that this specific Google Cloud faucet requires you to be logged into a Google account. If you prefer not to, the GitHub repository lists several other faucets with different requirements.
4.  **Confirm Receipt**: After the faucet processes your request, you will see a confirmation message like "Drip complete." To see the funds in your wallet, return to MetaMask, click the network dropdown (which may default to "Ethereum Mainnet"), and switch to the **"Sepolia"** network. Your balance for Account 1 should now reflect the **0.05 SepoliaETH** you just received.

### Step 2: Verifying the Faucet Transaction on a Block Explorer

Every transaction on a public blockchain is recorded on an immutable, public ledger. We can view this ledger using a **block explorer**, which is a web application that allows anyone to search and view all blockchain data, including transactions, addresses, and blocks. For Ethereum and its testnets, the most popular explorers are Etherscan and Blockscout. This demonstration uses Etherscan.

1.  **Navigate to Etherscan**: Go to the Etherscan website specifically for the Sepolia testnet: `sepolia.etherscan.io`.
2.  **Search Your Address**: Copy your "Account 1" wallet address from MetaMask again. Paste this address into the main search bar on the Etherscan homepage and press Enter.
3.  **Analyze the Transaction**: Etherscan will display a page with all the details for your address.
    -   The "Overview" section will confirm your balance of 0.05 ETH.
    -   Under the "Transactions" tab, you will see an entry for the funds you just received. It will show a value of `0.05 ETH` being transferred **from** the faucet's address **to** your address.
    -   Every transaction is identified by a unique **Transaction Hash (TxHash)**. Clicking on this hash will take you to a detailed view of that specific transaction, showing its status, the block number it was included in, the exact timestamp, and the transaction fee paid.

### Step 3: Sending Your Own Transaction

Now that you have testnet ETH, you can perform your own transaction. We will send a portion of these funds from your "Account 1" to your "Account 2".

1.  **Prepare the Transaction**:
    -   In MetaMask, switch to "Account 2". Copy its address (e.g., `0x51d83...AB81D`).
    -   Switch back to "Account 1", which holds the funds.
2.  **Execute the Transaction**:
    -   From Account 1, click the **"Send"** button.
    -   In the recipient field, paste the address for "Account 2".
    -   In the amount field, enter `0.01`. It is crucial to send an amount less than your total balance. Every transaction on the network requires a **transaction fee**, also known as a gas fee, which you must have enough ETH left over to cover.
    -   Click through the next steps in MetaMask, carefully reviewing the details: the sender, the recipient, the amount, and the estimated network fee.
    -   Click **"Confirm"** to broadcast your transaction to the network.
3.  **Confirm the Result**: In the "Activity" tab of MetaMask, the transaction will briefly show as "Pending" before changing to "Confirmed".
    -   The balance of "Account 1" will decrease, now showing approximately **0.04 SepoliaETH**.
    -   Switch to "Account 2" in MetaMask. You will see its balance is now **0.01 SepoliaETH**, confirming the transfer was successful.

### Step 4: Final Verification on the Block Explorer

Finally, let's verify our own transaction on the public ledger, just as we did with the faucet transaction.

1.  **Return to Etherscan**: Go back to the Etherscan page for "Account 1" and refresh it.
2.  **Review the New Transaction**: You will now see two transactions listed. The most recent one will show a transfer of 0.01 ETH. Notice the transaction is marked with an **"OUT"** label, clearly signifying that funds were sent _from_ this address.
3.  **Explore the Details**: As before, you can click on the new transaction's unique hash to explore all of its specific details, from the exact gas fee paid to the block it was included in. This confirms your transaction is now a permanent part of the Sepolia testnet's history.

## Understanding Gas: The Fuel of the Ethereum Network

If you've ever sent a transaction on a blockchain like Ethereum, you've likely encountered terms like "Transaction Fee" and "Gas Price" on block explorers. These elements are fundamental to how the network operates, determining how quickly your transaction is processed and how much it costs. This lesson will break down what Gas is, how it's priced, and how it all comes together to form your final transaction fee.

### What is Gas? A Measure of Computational Effort

To understand Gas, let's use an analogy. Imagine the blockchain is an incredibly busy digital delivery service. Every action you take—sending tokens, minting an NFT, or interacting with a decentralized application—is like sending a parcel through this service.

Just as a physical delivery requires effort (fuel, time, and labor), processing a transaction on the blockchain requires computational effort from the computers running the network. A simple, lightweight parcel, like a letter, requires minimal effort. A large, heavy parcel requires significantly more.

In this analogy, **Gas is the unit used to measure this computational effort.**

A simple transaction, like sending Ether (ETH) from one wallet to another, is a standard, predictable operation. It requires a fixed amount of computational work, which is measured as **21,000 Gas**. This is the "lightweight parcel."

A more complex transaction, such as interacting with a sophisticated smart contract, involves more computational steps. It's the "heavy parcel" and therefore consumes a higher amount of Gas.

In short, Gas is the unit of measurement for the amount of computational power your transaction needs to be successfully processed by the network.

### What is Gas Price? The Cost of Network Priority

Continuing our delivery service analogy, if Gas is the weight of your parcel (the effort required), then the **Gas Price is the price you are willing to pay per unit of weight** (e.g., the price per kilogram). On Ethereum, Gas Price is typically measured in Gwei, a smaller denomination of ETH (1 Gwei = 0.000000001 ETH).

The network's "delivery trucks"—the nodes or validators who process transactions—are economically motivated. They will always prioritize the most profitable parcels first. This creates a dynamic marketplace for transaction priority.

Imagine two identical parcels that both require 21,000 units of effort (Gas).

-   **Sender A** offers to pay a high price per unit (a high Gas Price).
-   **Sender B** offers to pay a low price per unit (a low Gas Price).

A validator will pick up Sender A's transaction first because it is more profitable for them to process.

This system becomes especially important during times of high network congestion. When many people want to send transactions at the same time, it’s like a holiday rush for the delivery service. To ensure their transaction gets processed quickly and isn't left behind, users start offering higher Gas Prices. This "bidding war" drives up the average Gas Price for everyone on the network.

-   **Paying a high Gas Price** incentivizes validators to process your transaction quickly.
-   **Paying a low Gas Price** means your transaction is less attractive, and you may have to wait for network activity to quiet down before a validator picks it up.

### How to Calculate Your Total Transaction Fee

The total cost you pay for your transaction is called the **Transaction Fee**. The calculation is simple:

`Transaction Fee = Gas Used x Gas Price`

This formula multiplies the total computational effort required (Gas Used) by the price you agree to pay for each unit of that effort (Gas Price). The result is the total fee, paid in the network's native currency, needed to have your transaction included on the blockchain.

### Setting Your Gas Fees in Wallets and Block Explorers

This theory becomes practical when you look at a transaction on a block explorer or prepare a new one in a wallet like MetaMask.

On a block explorer transaction page, you will see a field like `Gas Limit & Usage by Txn`, which might show `21,000 / 21,000 (100%)`.

-   **Gas Used by Transaction (21,000):** This is the actual amount of computational effort the transaction consumed. For a standard ETH transfer, this is fixed.
-   **Gas Limit (21,000):** This is the maximum amount of Gas you authorized the transaction to use. It acts as a safety mechanism to prevent a faulty smart contract from draining all the ETH from your wallet.
-   **Gas Price:** The explorer also shows the specific Gas Price you paid, for example, `1.5 Gwei`.

The total **Transaction Fee** shown on the page is the result of multiplying these two values.

When you initiate a transaction in MetaMask, you have control over the Gas Price. MetaMask typically offers several presets:

-   **Low:** Sets a lower-than-average Gas Price. Choose this if you are not in a hurry and want to save on fees. Your transaction will likely take longer to confirm.
-   **Market (Default):** Sets a Gas Price based on the current network average. This offers a good balance between cost and speed and is recommended for most users.
-   **Aggressive:** Sets a higher-than-average Gas Price to incentivize validators to process your transaction almost immediately.
-   **Advanced:** Allows you to manually set your own Gas Price parameters.

These options give you direct control over the trade-off between transaction speed and cost.

### Who Receives the Gas Fee?

Blockchains like Ethereum are decentralized, meaning they aren't run by a single company. Instead, they are maintained by a global network of independent computers known as **nodes** (or **validators**).

These validators are responsible for processing transactions, bundling them into blocks, and adding them to the blockchain. To motivate them to perform this crucial work and secure the network, they need an economic incentive. The transaction fees you pay are their reward.

When you pay a gas fee, it goes directly to the validator who successfully includes your transaction in a new block.

### The Importance of a Blockchain's Native Currency

Every blockchain has a **native currency**, which is the primary, built-in cryptocurrency of that specific network. It is analogous to a country’s national currency, like the U.S. Dollar in the USA or the Pound Sterling in the UK.

Transaction fees are **always** paid in the blockchain’s native currency.

-   On the **Ethereum** network, the native currency is **Ether (ETH)**. All gas fees are paid in ETH, even if you are sending a different token like USDC or SHIB.
-   On the **Bitcoin** network, the native currency is **Bitcoin (BTC)**, and all transaction fees are paid in BTC.

You must always have a sufficient balance of the network's native currency in your wallet to cover the gas fees for any transaction you wish to make.

### Key Takeaways: Mastering Ethereum Gas Fees

To summarize, here are the essential concepts to remember:

-   Every transaction on a blockchain requires a **transaction fee**, commonly known as a gas fee.
-   This fee is an economic incentive paid to the **validators** who process transactions and secure the network.
-   Fees are always paid in the blockchain's **native currency** (e.g., ETH on Ethereum).
-   The transaction fee is calculated with the formula: **Gas Used × Gas Price**.
    -   **Gas** is the unit measuring the computational work needed for your transaction.
    -   **Gas Price** is the price you pay per unit of Gas, which fluctuates with network demand.
-   By adjusting the Gas Price in your wallet, you can choose to pay more for a faster transaction or pay less and wait longer for it to be confirmed.

## What Are Smart Contracts? A Technical Introduction

While you may have a high-level idea of what smart contracts are—trust-minimized, automated agreements—it's time to look under the hood. This lesson moves beyond the simple definition to explore what smart contracts actually look like, how they are created, and how they function as the fundamental building blocks of the Web3 world.

### The Core Concept: A Contract Written in Code

At its most fundamental level, a smart contract is an agreement where the terms are written in a programming language instead of traditional legal language. This code defines the rules and consequences of the agreement, just as a paper contract would, but with a key difference: the execution is automated and enforced by the blockchain network.

Think of it using a simple "if-then" statement.

Imagine a smart contract with a single rule coded into it: **"If John sends this contract 100 dollars, then send John 1 digital token."**

When John sends the $100 to the contract's address, the condition ("if") is met. The network verifies this action and automatically executes the outcome ("then"), sending the digital token to John’s wallet. There is no need for a middleman to process the transaction or a lawyer to enforce the terms; the code handles the entire process deterministically.

### From Programming Language to Blockchain Execution

To create this automated logic, developers write smart contracts in specialized programming languages. In the Ethereum ecosystem, the most popular and widely used language is **Solidity**. Another, less common language is Vyper. You do not need to know how to code in Solidity to understand its role.

Once a developer writes the contract's rules in Solidity, the human-readable code must be translated into a format the blockchain can understand. This process is called **compiling**. The compiled code, known as bytecode, can be executed by the blockchain's processing environment, such as the Ethereum Virtual Machine (EVM).

### A Look at Simple Smart Contract Code

To make this tangible, let’s examine a simplified piece of a smart contract written in Solidity:

```solidity
contract SimpleToken {
    function mintToken() public {
        // Code that creates tokens for whoever calls this function
    }
}
```

Let's break this down for a non-technical audience:

-   **Function:** The line `function mintToken() public` defines a **function**. Think of a function as a "button" on the contract that anyone can press.
-   **Calling a Function:** When a user interacts with the contract to "press the button," they are technically "calling the function."
-   **Automatic Execution:** When the `mintToken` function is called, the code inside its curly braces `{}` runs automatically and unconditionally.
-   **The Action:** The comment inside explains its purpose. In this case, calling the `mintToken` function would execute code that creates new tokens and sends them to the wallet address that initiated the call.

Fortunately, most of this complexity is hidden from the end-user. When you use a decentralized application (dApp), you interact with a familiar web interface with user-friendly buttons. Behind the scenes, clicking a button prompts your wallet to "call" the corresponding function on the smart contract for you.

### The Lifecycle of a Smart Contract

Creating and launching a smart contract on the blockchain involves three distinct steps:

1.  **Write:** A developer writes the smart contract code (e.g., in Solidity) on their local computer.
2.  **Compile:** The human-readable Solidity code is compiled into machine-readable bytecode.
3.  **Deploy:** The compiled code is sent in a transaction to the blockchain network. This step is called **deploying** the contract.

Deploying a contract is like publishing a book. You can write a manuscript at home, but it isn't available to the public until you officially publish it. Similarly, a smart contract only becomes a live, interactive program on the blockchain once it has been deployed.

### Properties of a Deployed Smart Contract

Once a smart contract is deployed, it is stored on every node in the network. This distributed nature gives it several powerful properties:

-   **Immutable:** The code cannot be changed or tampered with after deployment. The terms of the agreement are locked in.
-   **Transparent:** Anyone can view the contract's code and verify its logic on the blockchain.
-   **Always Available:** As long as the blockchain is running, the smart contract is available to be executed 24/7. It cannot be turned off or censored.

### Smart Contracts Have Their Own Addresses

Just as your crypto wallet has a unique public address to receive funds, every smart contract deployed to the blockchain is assigned its own unique **Smart Contract Address**.

-   **Wallet Address (e.g., `0x5392BD...`):** An identifier for a user-controlled account.
-   **Smart Contract Address (e.g., `0x4e59b4...`):** An identifier for a program living on the blockchain.

This address acts like a physical address for a building. To interact with a specific contract—to "press its buttons"—you must first send your transaction to its unique address.

### The Foundation for Everything in Web3

Smart contracts are not just a niche feature; they are the engine that powers nearly all activity on a programmable blockchain. Every innovative application you hear about is either a single smart contract or a complex system of interconnected smart contracts.

Examples include:

-   **NFTs:** An NFT is governed by a smart contract that defines its ownership, properties, and transfer rules.
-   **DeFi:** Protocols for lending, borrowing, and saving are all smart contracts that manage user funds according to coded rules.
-   **Decentralized Exchanges (DEXs):** These trading platforms are smart contracts that allow users to swap digital assets directly without a central intermediary.

To truly appreciate these use cases, we must first understand the environment where these contracts live. The next lesson will explore the mechanics of the blockchain itself—the transparent, immutable, and decentralized system that makes smart contracts possible.

# Blockchain Architecture

## Preparing for the Technical Core of Blockchain Architecture

Welcome to the next stage of your web3 journey. The section you are about to begin is the most technically intensive part of this entire course, focusing on the deep, foundational concepts of blockchain architecture. Before we dive in, it’s important to set the right expectations and equip you with a strategy for success.

This material is challenging, but it is also where a true, foundational understanding of the technology is built. Let's get you prepared.

### A Tailored Approach for Every Learner

We recognize that students come to this course with different backgrounds and goals. Your approach to this section should reflect your personal objectives.

-   **For Aspiring Developers:** This section is your foundation. The concepts we will cover are critical for building, debugging, and innovating in the web3 space. Pay close attention, but do not be discouraged if you don’t grasp everything on the first pass. This material is dense, and even seasoned developers revisit these core principles regularly.

-   **For Non-Developers (Sales, Marketing, Business Development, etc.):** Your primary goal here is different. You are not expected to achieve mastery of every technical nuance. Instead, focus on gaining familiarity with the terminology. When you hear concepts like "Proof of Stake" or a "51% attack" in a meeting, the goal is for it to "ring a bell." This familiarity will give you the context to understand conversations and the confidence to know where to look if you need a refresher.

### Our Guiding Principle: Familiarity Over Mastery

For all learners, the most important strategy is to aim for familiarity over complete mastery on your first attempt. You will encounter many new and complex terms. The immediate goal is not to memorize every definition but to begin building a "mental map" of the blockchain landscape.

This mental map helps you understand how different components fit together. Once you have this high-level structure in your mind, it becomes much easier to revisit a specific topic later and place it in the correct context.

Crucially, **do not get blocked**. If you find yourself stuck on a particularly difficult concept, it is perfectly acceptable to move on to the next lesson and come back later. Progressing through the course and building out the rest of your mental map is more valuable than getting stuck striving for 100% comprehension in this single, challenging section. Learning how to learn—knowing when to push through and when to circle back—is a vital skill in a rapidly evolving field like web3.

### Your Toolkit for Success

To help you navigate this material, we strongly encourage you to use all the resources at your disposal.

-   **Re-visit the Material:** It is completely normal to re-watch videos or re-read lessons. Repetition is key to absorbing complex information.
-   **Explore External Resources:** In the course resources section, you will find supplementary articles and links for deeper reading. The official Ethereum documentation, in particular, is an excellent place to go for detailed, authoritative explanations.
-   **Ask Questions:** If you get stuck, use the course's discussion forums. Your questions can help both you and your fellow students learn more effectively.
-   **Leverage AI Tools:** Modern AI chatbots can be fantastic learning aids. Don't hesitate to ask one to explain a concept in a different way or provide a simple analogy.

The lessons ahead will be demanding. We will explore concepts like **Proof of Stake**, **blockchain reorgs**, and **51% attacks**. So, buckle in, get yourself a snack and a coffee, and let’s begin building your deep understanding of blockchain architecture.

## Understanding Blockchain Consensus: The Core Problem of Agreement

In a decentralized network like a blockchain, thousands of computers operate without a central authority or coordinator. This raises a fundamental question: How do all of these independent participants agree on what is true? How do they all maintain an identical, verified record of transactions? This challenge is known as the **Consensus Problem**, and solving it is the key to how blockchains function.

To understand this, imagine you and your friends decide to track shared expenses in a notebook. If you are all in the same room, it's easy. When Alice pays Bob $10, everyone sees it, writes it down, and all the notebooks match.

Now, imagine you are all in different countries. Communication is slower and less reliable. Sarah might record "Alice -> Bob: $10," but Tom, who received the message slightly differently, might write "Alice -> Bob: $15." Mike, who missed the message entirely, has a blank page. How do you all reconcile your notebooks to create a single, shared source of truth? This coordination dilemma is precisely what a blockchain’s consensus mechanism is designed to solve.

To achieve this, a blockchain must address three core challenges:

1.  **Sybil Attacks (Sybil Resistance)**
2.  **Finality**
3.  **The Consensus Problem** (achieving agreement on the valid state)

Let's break down each of these foundational concepts.

### 1. Resisting Manipulation with Sybil Resistance

A **Sybil attack** is a security threat in a peer-to-peer network where a single malicious actor creates a large number of fake identities or nodes. By controlling this army of fake participants, they can gain disproportionate influence over the network.

In a blockchain, where each node can be seen as having a "vote" on the history of transactions, a Sybil attack is a critical threat. An attacker could theoretically spin up thousands of fake nodes they control. With this majority "vote," they could manipulate the network, approve fraudulent transactions, or censor legitimate ones. This is akin to one person stuffing a ballot box by pretending to be thousands of different voters.

A real-world example outside of crypto might be an online "best influencer" contest where votes are cast per email address. A malicious user could create hundreds of fake email addresses to cast an overwhelming number of votes for their chosen candidate, unfairly skewing the results.

To function, a public blockchain must be permissionless (allowing anyone to join) while simultaneously preventing such attacks. The solution is a **Sybil resistance mechanism**. These mechanisms don't make it impossible to run multiple nodes, but they make it prohibitively **expensive** to do so at a scale that could threaten the network.

The two most prominent Sybil resistance mechanisms are:

-   **Proof of Work (PoW)**: Used by Bitcoin, PoW makes participation expensive through computational effort. To participate in the network's consensus, a node (or "miner") must solve a complex mathematical puzzle that requires immense computing power and electricity. An attacker can create many identities, but they cannot fake the massive real-world cost of energy and hardware required to make those identities influential.
-   **Proof of Stake (PoS)**: Used by Ethereum, PoS makes participation expensive through a financial stake. To participate as a validator, a user must lock up a significant amount of the network's native cryptocurrency as collateral. An attacker is free to create multiple validator nodes, but they would need a vast amount of capital to stake for all of them. Furthermore, if they are caught acting dishonestly, their staked funds are forfeited ("slashed").

It's a common misconception to refer to PoW and PoS as consensus mechanisms themselves. Technically, they are the Sybil resistance components that are part of a larger consensus algorithm. They are the gatekeepers that ensure only those with a tangible, costly stake can participate in forming consensus.

### 2. Ensuring Permanence with Finality

**Finality** is the guarantee that once a transaction is confirmed and added to the blockchain, it is irreversible and can never be altered, reversed, or removed.

In a traditional financial system, a central authority like a bank has the final say. They can reverse transactions or correct errors because they are the ultimate arbiter of truth. In a decentralized network, there is no such authority. The network itself must establish rules to determine when a transaction is considered immutable.

This is a critical property. When you receive a payment on a blockchain, how long do you have to wait before you can be absolutely certain the funds are yours and the transaction cannot be undone? The point at which a transaction achieves this state of irreversibility is its point of finality. Different blockchains have different rules and timeframes for achieving this guarantee.

### 3. Solving the Consensus Problem

The Consensus Problem is the overarching challenge of getting all the computers in a distributed network to agree on the single, valid state of the blockchain. This involves agreeing on:

-   The correct order of transactions.
-   Which transactions are valid and which are fraudulent.
-   Which version of the blockchain is the one true, canonical chain.

The concepts of Sybil resistance and finality are essential tools for solving this broader problem. A Sybil resistance mechanism ensures that only legitimate, invested participants can propose and validate new blocks of transactions. The rules for finality ensure that once the network agrees on a block, that agreement is permanent. Together, these components allow a global, decentralized network to function with the reliability and integrity of a centrally coordinated system.

### Bitcoin vs. Ethereum: A Tale of Two Approaches

Both Bitcoin and Ethereum solve these core problems, but they use different Sybil resistance mechanisms to do so.

| Feature                        | Bitcoin                                                   | Ethereum                                               |
| ------------------------------ | --------------------------------------------------------- | ------------------------------------------------------ |
| **Sybil Resistance Mechanism** | Proof of Work (PoW)                                       | Proof of Stake (PoS)                                   |
| **How It's Made Expensive**    | Requires immense **computational power** and electricity. | Requires locking up a significant **financial stake**. |

By understanding these fundamentals—Sybil resistance, finality, and the overall consensus problem—you have grasped the core engineering breakthroughs that make decentralized networks possible. In our next lesson, we will dive deeper into the mechanics of Bitcoin's pioneering Proof of Work algorithm.

## How Proof of Work Blockchains Work

Proof of Work (PoW) is the foundational consensus mechanism that powers pioneering blockchains like Bitcoin. To truly understand how these networks function, it's essential to grasp key concepts like mining, computational power, and the cryptographic principles that ensure their security. This lesson breaks down the step-by-step process of how blocks are created, linked, and validated across a decentralized network.

### The Cryptographic Foundation: What is a Hash?

At the core of any blockchain is a cryptographic concept known as hashing. A hash is a unique, fixed-length string of characters generated from any piece of digital data. This is achieved by passing the data through a hash function, or algorithm.

For instance, the Bitcoin network uses the SHA256 (Secure Hash Algorithm 256-bit) algorithm. While other blockchains might use different algorithms, such as Keccak256 for Ethereum, the fundamental principles remain the same.

A hash has two critical properties:

1.  **Fixed Length:** Regardless of the size of the input data—whether it's a single character or an entire book—the output hash will always be the same length. For SHA256, this is a 256-bit string, commonly represented as 64 hexadecimal characters.
2.  **Determinism:** The same input will always produce the exact same output hash. Even the slightest change to the input data, like altering a single letter or adding a space, will result in a completely different and unpredictable hash. This makes hashes a reliable digital fingerprint for data.

### Building the Blocks: Mining and Proof of Work

A blockchain is composed of individual "blocks," which are essentially containers for data. A typical block contains several key pieces of information, including a block number, the data it holds (such as a list of transactions), and a special number called a **nonce**.

For a block to be considered valid and added to the chain, it must meet a specific condition set by the network's protocol. In Proof of Work, this condition forms a computational puzzle. A common rule is that the block's hash must start with a certain number of leading zeros.

This is where **mining** comes in. Mining is the process of finding a nonce that, when combined with the other data in the block and hashed, produces a valid hash that satisfies the network's rule. Since hashes are unpredictable, there is no shortcut to finding the correct nonce. Miners must use computational power to guess values one by one—a brute-force process that can require billions or trillions of attempts.

This intensive guessing game is the "work" in Proof of Work. When a miner finally finds a valid nonce, the block is considered "mined" and solved. This process is computationally expensive, which is a key feature that secures the network.

### Linking the Chain: How Blockchains Ensure Immutability

Individual blocks are secured together in a chronological chain using hashes. Each new block in the chain must contain the hash of the block that came immediately before it. This reference is often stored in a field labeled "Prev" for "previous hash."

The very first block in a chain, known as the **Genesis Block**, is unique because it has no preceding block; its "Prev" field is typically set to all zeros. Every subsequent block is cryptographically linked to the one before it, creating an unbreakable historical record.

This linking mechanism is what makes a blockchain **immutable**, or tamper-evident. If an attacker attempts to alter the data in a historical block—for example, Block #4—its hash will instantly change. Because this new hash no longer matches the "Prev" value stored in Block #5, Block #5 becomes invalid. This invalidation creates a cascade effect, breaking every single block that follows it in the chain.

To successfully alter a past transaction, an attacker would not only need to re-mine the altered block but also re-mine every subsequent block in the chain to restore its validity. This would require an extraordinary and usually prohibitive amount of computational power.

### Decentralization in Action: The Distributed Ledger and Consensus

The security of a Proof of Work blockchain is amplified by its decentralized nature. Instead of being stored in a central location, copies of the blockchain ledger are distributed across a global network of independent participants, often called nodes or peers. Each peer maintains their own identical copy of the chain.

This distributed structure creates a robust system for achieving consensus. If a malicious actor tries to tamper with their local copy of the blockchain, their version will immediately fall out of sync with the rest of the network.

Blockchains use a consensus rule to determine the one true state of the ledger. The most common rule in PoW is the **"Longest Chain Rule."** The network will always consider the longest valid chain—the one with the most accumulated computational work (or blocks)—as the official version.

If an attacker on Peer A alters a block, their chain becomes invalid. The other nodes, Peer B and Peer C, will continue building on their valid, longer chain. Peer A's fraudulent version is ignored and rejected by the network. For the attacker's chain to be accepted, they would need to re-mine their altered blocks and then continue to outpace the entire rest of the network combined, an attack that would require controlling over 51% of the network's total hashing power.

### Putting It All Together: Transactions, Finality, and Forks

In a real-world blockchain like Bitcoin, the "data" stored within each block is a list of financial transactions. Securing this data with the mechanisms described above prevents fraud, such as double-spending or altering transaction amounts.

The nodes that participate in the mining process are called **miners**. They compete to be the first to solve the computational puzzle for the next block. The successful miner is rewarded with newly created cryptocurrency (e.g., Bitcoin) and any transaction fees included in the block. This **block reward** incentivizes miners to contribute their computational power to secure the network.

A transaction isn't considered instantly secure. It achieves **finality** through a process of **confirmations**. A transaction gets one confirmation when it is included in a mined block. Each subsequent block added to the chain provides another confirmation. On the Bitcoin network, a transaction is generally considered irreversible after **6 confirmations**, as the energy and cost required to reverse six blocks of history is astronomical. This is known as probabilistic finality.

Occasionally, two miners might solve a block at nearly the same time, creating two competing valid chains. This event is called a **fork**. The network resolves this fork by following the Longest Chain Rule. Whichever chain has the next block added to it first becomes the longest, and all nodes will discard the shorter, "orphaned" chain and adopt the longer one as the single source of truth.

<!--
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

## Setting up MetaMask for Ethereum Transactions

In this lesson, we will learn how to make a transaction on a test Ethereum blockchain using MetaMask, a popular cryptocurrency wallet.

### Visiting Ethereum Website

-   Go to the Ethereum website [ethereum.org](https://ethereum.org).

### Understanding Blockchains

-   We will make our first transaction on a test Ethereum blockchain.
-   This process works the same across all EVM (Ethereum Virtual Machine) compatible blockchains and layer 2 solutions like Arbitrum, Ethereum, ZKsync, etc.
-   EVM compatibility will be explained later.

### Setting up MetaMask Wallet

To set up a wallet, we really just need to follow these steps:

1. To send a transaction on EVM chains, set up a wallet. We'll use MetaMask as it's one of the most popular and easiest wallets to start with.
2. Go to [MetaMask](https://metamask.io).
3. Install the MetaMask extension for your browser (e.g., Chrome, Firefox, or Brave).
4. Once installed, you’ll see the extension in the top-right corner of your browser.
5. Click "Get Started".
6. Select "Create a New Wallet".
7. Agree to help MetaMask improve (optional).
8. Create a password. Make sure it’s secure.

    > **Note**: This wallet will be for development purposes, so you may use a weaker password. But never put real money into this wallet. Treat it as a real wallet to familiarize yourself with good wallet safety.

### Secret Recovery Phrase (Master Key)

MetaMask is going to provide you with a secret recovery phrase. This is a series of 12 words generated when you first set up MetaMask. Ultimately this phrase will allow you to recover your wallet and funds within, should you ever lose access.

This recovery phrase (sometimes referred to as a mnemonic) is your master key, so keep it safe. Write it down, store it in a safe deposit box, or use a secure password manager. Some even engrave their phrase on a metal plate.

> **Warning**: If anyone gets access to your secret recovery phrase, they can access and take all your funds. No one, including the MetaMask team, can help you recover your wallet if you lose the phrase.

1. Watch the Video offered by MetaMask detailing how to keep your wallet secure.
2. Select "Secure My Wallet".
3. Write down your secret recovery phrase and save it securely.
4. Confirm by re-entering your phrase.
5. Click "Got it" after creating your wallet.

> **Note AGAIN:** This wallet will be your **development wallet** do not add real funds!

### Understanding the MetaMask Interface

From this point, you should be able to see your MetaMask interface. It should look something like this:

<img src='./images/first-transaction/first-transaction1.png' alt='first-transaction1' />

You can Pin MetaMask to the top of your browser for easy access to this view in future.

A couple things to note:

1. In MetaMask, you can create multiple accounts. Each account has a different address. You can do this by selected `Create Account` from the menu in the top right.
2. All accounts created in MetaMask share the same secret phrase but have different private keys.

    **Note**: Access to the secret phrase grants control to all accounts, while access to a private key only grants control to a single account.

### Selecting a Network

Near the top of the MetaMask interface, you’ll see “Ethereum Mainnet”. Click on it to see all the networks that MetaMask can access.

Ethereum Mainnet is a live blockchain where real money is used. For the purposes of this course, we're not going to be working with Ethereum Mainnet. Instead, we'll be leveraging a testnet, a development chain used for creating and testing smart contracts.

In addition to this, we'll also be covering how to test and deploy on a _local_ chain, which we'll quickly learn is the _preferred_ way to test our code in most circumstances!

By toggling the `show test networks` option, we can see which testnets come included by default.

<img src='./images/first-transaction/first-transaction2.png' alt='first-transaction2' />

We're able to switch networks simply by clicking on any network on the available list. Try out Sepolia!

> Do note - Testnets change often, they're run out of the goodness in people's hearts. If a particular testnet is unavailable or changes, please checkout the course GitHub repo or the section Updates area on Updraft for the latest testnet.

Just like Mainnets, testnets have blockexplorers available to us as well. We can navigate to **[Sepolia Etherscan](https://sepolia.etherscan.io/)** to see records of all the transactions that are happening on Sepolia.

### First Transaction

In order to experience your first transaction, we're going to navigate to a `faucet`. Faucets are services which allow you to claim some free `testEth` (in our case SepoliaEth) and use it in development.

**[Sepolia Faucet](https://faucets.chain.link/sepolia)**

<img src='./images/first-transaction/first-transaction3.png' alt='first-transaction3' />

From this page you can connect your wallet with the click of a button. Once clicked, agree to the terms of service and select `MetaMask`.

<img src='./images/first-transaction/first-transaction4.png' alt='first-transaction4' />

Your MetaMask should pop up and give you the option to select your account, following by a confirmation to connect your wallet.

<img src='./images/first-transaction/first-transaction5.png' alt='first-transaction5' />

<img src='./images/first-transaction/first-transaction6.png' alt='first-transaction6' />

In order to request testnet native tokens (like SepoliaEth) you'll need to verify your GitHub account. Once that's done, you should be ready to send your request!

<img src='./images/first-transaction/first-transaction7.png' alt='first-transaction7' />

After a brief delay we should see something like this!

<img src='./images/first-transaction/first-transaction8.png' alt='first-transaction8' />

I encourage you to click the transaction hash, you'll be brought to Sepolia Etherscan and provided a tonne of information about the details of your transaction. Additionally, you should be able to open up your MetaMask wallet and confirm you did indeed receive your requested Sepolia Eth!

<img src='./images/first-transaction/first-transaction9.png' alt='first-transaction9' />

Try toggling your MetaMask wallet between networks now, you'll notice that it's only on Sepolia that you've gained your test ETH. If you want to practice further, there are additional testnet blockchains with faucets available for you to try.

### Transaction Details

Taking a brief look at some of the details of our transaction on Etherscan, we're given a lot of insight. Understanding these properties is a fundamental part of being a blockchain developer. Some of the basic details include:

-   Transaction Hash - This is a unique identifier for our transaction
-   From - The originating address of the transaction request
-   To - The address a transaction was sent to
-   Value - Any funds included with the transaction
-   Gas - The cost of the transaction to execute, we'll be looking into gas more closely in the next lesson.

<img src='./images/first-transaction/first-transaction10.png' alt='first-transaction10' />

## Introduction to Gas

In this lesson, we will discuss important concepts ranging from transaction fees and gas prices, mining incentives, computational measures in transactions, to hands-on experience of sending a transaction in Ethereum’s test network.

Let's jump right in!

### Transaction Fee and Gas Price: What are they?

<img src='./images/intro-gas/intro-to-gas1.png' alt='intro-to-gas1' />

While inspecting an Ethereum transaction, two terms invariably catch the glance: "transaction fee" and "gas price". Let's clarify what they are and why they matter.

The `transaction fee` is the amount rewarded to the block producer for processing the transaction. It is paid in Ether or GWei. The `gas price`, also defined in either Ether or GWei, is the cost per unit of gas specified for the transaction. The higher the gas price, the greater the chance of the transaction being included in a block. [`Wei, Gwei, and Ether Converter`](https://eth-converter.com/)

> Gas price is not to be confused with gas. While gas refers to the computational effort required to execute the transaction, gas price is the cost per unit of that effort. [`Gas and Gas Fees`](https://ethereum.org/en/developers/docs/gas/)

When we click on "more details" in a transaction overview, we can see further information including the `Gas Limit and Usage by transaction`.

Now, let's address an important question: who gets these transaction fees and why?

### The Role of Nodes in Blockchain

Blockchains are run by a group of different nodes, sometimes referred to as miners or validators, depending on the network. These miners get incentivized for running the blockchain by earning a fraction of the native blockchain currency for processing transactions. For instance, Ethereum miners get paid in Ether, while those in Polygon get rewarded in MATIC, the native token of Polygon. This remuneration encourages people to continue running these nodes.

### Understanding Gas in Transactions

In the context of transactions, gas signifies a unit of computational complexity.

The higher a transaction's complexity, the more gas it requires. For instance, common transactions like sending Ether are less complex and require relatively small amounts of gas. However, more sophisticated transactions like minting an NFT, deploying a smart contract, or depositing funds into a DeFi protocol, demand more gas due to their complexity.

The total transaction fee can be calculated by multiplying the gas used with the gas price in Ether (not GWei). Therefore, `Transaction fee = gasPrice * gasUsed`.

### Hands-on: Sending an Ethereum Transaction

In any blockchain, making a transaction requires the payment of a transaction fee (in terms of the native token) to the blockchain nodes processing that transaction. Let's take an example of a transaction using the MetaMask extension, a popular Ethereum wallet.

Here are the steps:

1. Open MetaMask and click "Expand View".
2. Choose the account to use for the transaction.
3. Click on "Send".
4. Select "Transfer between my accounts".
5. Enter the account to send the Ether to, and the amount you wish to send.
6. Click "Next". MetaMask will automatically calculate the gas fee for you. The total amount to be paid is the sum of the Ether value you're sending and the gas fee.

Something of note, if you click the `market` link in MetaMask, you'll be shown some optional settings for gas in the transaction. You may wonder _Why would I choose to spend more gas?_

A simplified explanation of this is: if lots of people are trying to process transactions at the same time, the space on a given block is competitive, gas prices are increased to throttle and prioritize transactions during congestion.

1. Click "Confirm".

The transaction will now appear in the Activity tab of MetaMask. After a short while, the transaction gets processed, and you can view its details in a block explorer like Etherscan.

You have now executed your first blockchain transaction!

Despite its simplicity, knowing how to process transactions with MetaMask is vital and empowers you to interact with protocols on the Ethereum network and other blockchains. However, to fully understand Ethereum and the blockchain landscape, it's crucial to delve into the details behind these transactions and the fundamental mechanics of blockchains.

Remember, mastering the nuances of blockchain transactions and understanding the mechanics behind Ethereum will enable you to become a powerful developer in the decentralized world.

## How do blockchains work

In this lesson, we're going to break down blockchains, the process and the technology itself using a widely-praised and accessible demo available [here](https://andersbrownworth.com/blockchain/).

### Understanding Hash Functions

At its simplest, a hash is a unique, fixed-length string that serves to identify any piece of data. When you input any kind of data into a hash function, it produces a hash. In this demo, the hash algorithm we'll focus on is SHA-256.

<img src='./images/how-do-blockchains-work/how-do-blockchains-work1.png' alt='how-do-blockchains-work1' />

If I add `Mohammadreza Alirad` to our `SHA-256` algorithm, it will:

1. Convert the letters to numbers
2. Convert the numbers to a fixed-length “string” or “hash”

`Mohammadreza Alirad` gets converted to `8b343f541c502f5dccb064438a9fc82f516abab6a8adac81fb99f1c51a0beaa5`

Ethereum, uses its own version of a hashing algorithm (Keccak256) that isn't exactly SHA-256 but belongs to the SHA family. This doesn't change things significantly here as we're primarily concentrating on the concept of hashing.

In the application, whatever data you enter into the data section, undergoes processing by the SHA-256 hash algorithm resulting in a unique hash.

> For example, when I input my name as "Mohammadreza Alirad," the resulting hash uniquely represents "Mohammadreza Alirad." The fascinating aspect is, no matter how much data is input, the length of the generated hash string remains constant.

### Understanding Blocks

Now that we've grasped the concept of hashing and fixed-length string, let's inspect the structure of a blockchain. A collection of "blocks."

<img src='./images/how-do-blockchains-work/how-do-blockchains-work2.png' alt='how-do-blockchains-work2' />

A block takes the same data input, but instead of a singular data field, a block is divided into 'block', 'nonce', and 'data.' All three are then run through the hash algorithm, producing the hash for that block. As a result, even a minor change in the data leads to an entirely different hash, hence, invalidating the block.

In essence, mining involves the computational trial and error process of finding an acceptable value to produce a hash which typically follows a certain pattern, such as starting with four zeros. The value found, which satisfies this criterion, is known as the 'nonce'.

The problem or criteria a miner has to solve will vary from blockchain to blockchain, but the concept is the same.

### The Inherent Beauty of Blockchain: Immutability

In a blockchain, which is essentially a sequence of blocks, each block is comprised of the previous elements - a block number, a nonce and data - as well as `the hash of the previous block`

<img src='./images/how-do-blockchains-work/how-do-blockchains-work3.png' alt='how-do-blockchains-work3' />

What this means in practice is that any changes to data, in any block of the chain, will invalidate every proceeding block, until they are recalculated, or re-mined.

> **Genesis Block:** This is the first block in a blockchain.

### Decentralized Distribution

Now, if a single entity were to control the blockchain, they could conceivably change any data they want, and then re-mine, or re-validate subsequent blocks. This is bad.

_Enter Decentralized Distribution._

<img src='./images/how-do-blockchains-work/how-do-blockchains-work4.png' alt='how-do-blockchains-work4' />

The crux of blockchain's power lies in its decentralization or distributed nature. Under this system, multiple entities or "peers" run the blockchain technology, each holding equal weight and power. In the event of disparity between the blockchains run by different peers (due to tampering or otherwise), the majority hash wins, as the majority of the network agrees on it.

Nodes that don't agree with the majority effectively fork the network, continuing on their own with their own history.

### Interplay of Blockchain & Transactions

Until now we've been considering the data passed in a block to be a random string of text, but the reality is - this data can be anything. In the token and coinbase sections of this demo you can see how each block is comprised of a number of transactions that all get hashed together. Any edits to any of these transactions is going to invalidate the chain!

<img src='./images/how-do-blockchains-work/how-do-blockchains-work5.png' alt='how-do-blockchains-work5' />

every transaction, block, and indeed the whole blockchain itself comes down to understanding the concept of a hash. This unique fixed-length string that is intrinsically linked with the original data. We've also underscored the importance of decentralization and highlighted how the concept of immutability plays into the system's security.

## Signing Transactions

To help understand the fundamentals of how concepts like public and private keys as well as signing transactions, we'll again be leveraging an incredible resource by **Anders Brownworth** available **[here](https://andersbrownworth.com/blockchain/public-private-keys/)**

### Public and Private Keys

In this lesson, all the pieces we learnt about with MetaMask should start coming together.

Understanding the relationship between private and public keys is essential to grasping the concept of blockchain transactions. In essence, a private key is a randomly generated secret key used to sign all transactions.

The private key is then passed through an algorithm (the **[Elliptic Curve Digital Signature Algorithm](https://en.wikipedia.org/wiki/Elliptic_Curve_Digital_Signature_Algorithm)** for Ethereum and Bitcoin) to create the corresponding public key. Both the private and public keys are central to the transaction process. However, while the private key must remain secret, the public key needs to be accessible to everyone.

When we send a transaction to the blockchain, we're passing a private key. This allows others to verify the transaction through the generated public key.

<img src='./images/signing-transactions/signing-transactions1.png' alt='signing-transactions1' />

### How does Transaction Signing Happen?

When we sign a transaction on the blockchain, we're digitally signing some data with our private key. The hashing algorithm used makes it impossible for something to derive your private key from a message signature.

<img src='./images/signing-transactions/signing-transactions2.png' alt='signing-transactions1' />

This signing method allows anyone to verify the validity of a transaction by comparing the message signature to a user's public key!

<img src='./images/signing-transactions/signing-transactions3.png' alt='signing-transactions3' />

### Importance of Hiding Private Keys

Your MetaMask account's private key is accessible through `Account Details` > `Show Private Key`. You'll be asked to provide a password, again underscoring the importance of keeping this key safe.

Anyone with access to your private key can perform and sign transactions, on your behalf consequently making it absolutely vital to safeguard private keys.

> **Note:** As an interesting side note, wallet addresses, like the one MetaMask provided to you, are actually derived from your public key. A public key is passed through the Ethereum Hashing Algorithm, the last 20 bytes of the resulting hash is the address!

We discovered that transactions on the blockchain are signed using a user's `private key`. The generated `message signature` can then be verified by anyone through a comparison to a user's `public key`.

**KEEP YOUR PRIVATE KEY SECURE!**

-   Private Keys allow someone to sign a transaction, they should be kept secret and secure.

We learnt that `public keys` are generated by using the **[Elliptic Curve Digital Signature Algorithm](https://en.wikipedia.org/wiki/Elliptic_Curve_Digital_Signature_Algorithm)** on a user's private keys.

In addition to this, Ethereum addresses are derived from public keys by hashing a user's public keys with the Keccak256 algorithm.

The deeper we go, the more complicated things get, but you're doing great and we still have a ways to go. In the next lesson we'll look again at gas and investigate some of the more low level interactions of gas in a blockchain ecosystem.

## Gas In Depth

### Transactions and Gas

In this lesson we're going to take an even closer look at `gas`, how it functions and the purpose it serves on the blockchain.

Don't stress if this topic sounds complex; gas can absolutely be a confusing topic, but the more experience you gain and more examples we go through, it'll start to become clear.

**Note:** What we're covering here is applicable to Ethereum post implementation of **[EIP-1559](https://eips.ethereum.org/EIPS/eip-1559)** wherein gas limits, priority fees and the discussed burn mechanism were all introduced.

### Transaction Breakdown

Before we continue, there are a couple important terms to understand.

```Solidity
Wei:  1,000,000,000 Wei  = 1 Gwei (Gigawei)
Gwei: 1,000,000,000 Gwei = 1 Eth
```

<img src='./images/gas-in-depth/gas-in-depth1.png' alt='gas-in-depth1' />

_Reference the above image, the labelled sections will be detailed below_

**1. Transaction Fee:** This is calculated as Total `Gas Used * Gas Price` where `Gas Used` represents the computational units required to perform the work and `Gas Price` is comprised of a `Base` and `Priority Fee`

**2. Gas Limit:** This is the maximum amount of gas allowed for the transaction. This can be set by the user prior to sending a transaction.

In Metamask, you can navigate to `Market > Advanced > Edit Gas Limit` in order to set this value.

<img src='./images/gas-in-depth/gas-in-depth2.png' alt='gas-in-depth2' />

**3. Base Gas Fee:** The base fee of a transaction, represented in Gwei. Remember, this is cost per gas.

There are a couple important points to note regarding the Base Fee

-   The fee is burnt as of EIP-1559. Burning serves to remove the value from circulation, combating inflation on the protocol. The amount burnt can be seen beneath the `Base Fee` in the image above.
-   The fee is dynamic, under EIP-1559, if a block is more than 50% full, the `Base Gas Fee` is increased for the next block. Likewise, if a block is less then 50% full, the fee decreases. This serves to balance network demand and capacity.

**4. Max Gas Fee:** This is the maximum cost per cast the transaction has been configured to allow. This can again be configured prior to sending a transaction.

**5. Max Priority Fee:** Again, configurable prior to sending a transaction, this represents the maximum `tip` we're willing to give miners. This incentivizes the inclusion of our transaction within a block.

**6. Block Confirmations:** These are he number of blocks which have been mined or validated which have been confirmed to contain your transaction. The more confirmations the more sure we can be of the transaction's validity.

### Wrap Up

Lets recap some of what we've learnt about transactions on the blockchain!

We learnt that every transaction has a unique `transaction hash` that uniquely identifies the transaction on chain.

Pulling up a transaction in a block explorer like Etherscan can provide us a tonne of additional information, including:

-   The block which contains the transaction
-   The time stamp of when the transaction was requested
-   Where the transaction is originating
-   Where the transaction is being sent
-   The value included in a transaction

From here we can also see details about the `transactions fees` and `gas` costs.

`Gas` is a measure of computation required to perform a task, the cost of a transaction is derived from a `Gas Price` (made of `Base` and `Priority Fees`) and the amount of `gas` used.

We learnt that a `Gas Limit` can be set before a transaction is set and that the `Base Fee` on all Ethereum transactions is actually `burnt`, in order to reduce inflation and stabilize the network economy.

We also discovered that the Base Fee goes up and down depending on the congestion of a block. If a block is >50% full, the fee goes up, <50% and the fee goes down.

## Blockchain Fundamentals

### Traditional Networks vs Blockchain

Traditionally, when you run an application be it a website or something that connects to a server you are interacting with a centralized entity. This is the opposite of what you may recall from our distributed blockchain example, in that the server is controlled and run by a single centralized group.

Blockchains, as we saw, run on a network of independent nodes. In our previous example, each of the `Peers` was representative of an independent `node` operator. The term `node` typically refers to a single instance of a decentralized system, Peer A would be a `node`. This network, this combination of these nodes interacting with each other is what creates a blockchain. What makes these networks so potent, is that anybody can join. All anyone needs is a little bit of hardware and you can participate in securing a blockchain network. You could go to GitHub and start operating a node in a few seconds!

In the traditional world applications are run by centralized entities and if that entity goes down or is malicious or decides that they want to shut off - they just can. They're the ones that control everything.

Blockchains, by contrast, don't have this problem. If one node or one entity that runs several nodes goes down, since there are so many other independent nodes running, it doesn't matter, the blockchain and the system will persist so long as there is at least one node always running. Luckily for us, the most popular chains like Bitcoin and Ethereum have thousands and thousands of nodes. Malicious nodes are kicked from the network, or even punished in some cases. Majority rules when it comes to the blockchain.

This gives blockchains this incredibly potent immutability trait where nothing can be changed or corrupted so in essence we can think of a blockchain as a decentralized database. In the case of Ethereum it has an extra additional feature where it also can do computation in a decentralized manner now.

### Consensus

Let's talk consensus. This includes `Proof of Work` and `Proof of Stake`. You've probably heard these terms before and they're really important to how these blockchains work.

The `mining` feature of our previous blockchain example was an example of `Proof of Work`

`Proof of Work` and `Proof of Stake` fall under this umbrella of `consensus`. And `consensus` is a really important topic when it comes to blockchains.

> [`Consensus`](https://ethereum.org/en/developers/docs/consensus-mechanisms/) is defined as the mechanism used to reach an agreement on the state or a single value on the blockchain especially in a decentralized system.

Very roughly, a consensus protocol in a blockchain or decentralized system can be broken down into two pieces: a chain selection algorithm and a sybil resistance mechanism. Mining, or Proof of Work, is a sybil resistance mechanism. This is what Bitcoin currently uses.

`Proof of Work` is known as a sybil resistance mechanism because it defines a way to figure out who is the block author or which node did the work to mine a block. Sybil resistance is a blockchain's ability to defend against users creating a large number of pseudo-anonymous identities to gain a disproportionately advantageous influence over said system.

As mentioned, there are two primary types of sybil resistance:

-   Proof of Work
-   Proof of Stake

### Proof of Work

[`Proof of work`](https://ethereum.org/en/developers/docs/consensus-mechanisms/pow/) is a system of sybil resistance used in many blockchains, in its essence a miner needs to go through a very computationally heavy process (mining) to find the block's answer. As a result, it doesn't matter how many additional nodes you're running, each node is obligated to do this work in order to receive a reward. The playing field is kept fair.

> **Note:** Some blockchains may make their riddle or their block answer intentionally hard, or intentionally easy to adjust the block time - which is the average time it takes to mine a block. Blocktime is proportional to how difficult these algorithms are.

Proof of Work needs to be combined with a `chain selection rule` to create `consensus`.

A `chain selection rule` is implemented as a means to determine which blockchain is the _real_ blockchain. Bitcoin (and prior to the merge, Ethereum), both use something called `Nakomoto Consensus`. This is a combination of Proof of Work (Etherum has since switched to Proof of Stake) and the `longest chain rule`.

In the `longest chain rule`, the decentralized network decides that whichever chain has the most number of blocks will be the valid, or _real_ blockchain. When we saw `block confirmations` in Etherscan earlier, this was representing the number of blocks ahead of our transaction in the longest chain.

> You'll sometimes hear people use **Proof of Work** to describe a consensus mechanism, but it's a little bit inaccurate, it's really the combination of sybil resistance _and_ chain selection that create consensus.

`Proof of Work` also serves as a means to determine who receives transaction fees as we discussed earlier. These transaction fees are paid by whomever initiates the transaction. In a Proof of Work system, every node is competing against eachother to solve the block problem first. The first node to solve the problem gets paid the transaction fees accumulated in the block they mine. In addition to this, miners are also paid a `block reward`, the `block reward` is given by the blockchain itself.

> If you've previously heard of the Bitcoin Halving - this is the concept of the block reward being cut in half roughly every 4 years.

Block rewards are in the blockchains native currency - Bitcoin = BTC, Ethereum = ETH. This effectively increases the amount of that cryptocurrency in circulation.

### Blockchain Attacks

There are two major types of attacks that exist in the blockchain space.

-   Sybil Attack - When a user creates a number of pseudo-anonymous accounts to try to influence a network.
-   51% attack - Occurs when a single entity possesses both the longest chain and majority network control. This would allow the entity to `fork` the chain and bring the network onto the entities record of events, effectively allowing them to validate anything.

Blockchains are very democratic. The bigger a blockchain is, the more decentralized, the more secure it becomes.

I encourage you to look into running a node yourself to increase the security of the network!

Proof of Work does come with drawbacks. For example, Proof of Work consumes a LOT of electricity. When you have thousands of nodes all working as hard as they can to solve a block problem the energy consumption is HUGE and as such, so is the potential environmental impact.

With the above in mind, many protocols are choosing the shift to a different consensus mechanism that is more environmentally friendly. The most popular of which is...

### Proof of Stake

In contrast to trying to solve a block problem, [`Proof of Stake`](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/) nodes put up some collateral that they are going to behave honestly aka they `stake`. If a node is found to be misbehaving, it's stake is slashed. This serves as a very effective sybil resistance mechanism because for each account, the validator needs to put up more stake and misbehaving risks losing all that collateral.

> In a Proof of Stake system, `miners` are known as `validators`. They aren't actually mining blocks, they're validating other nodes.

Unlike in Proof of Work, where each node is racing to solve the block problem first, in Proof of Stake, validators are pseudo-randomly chosen to propose the next block and other nodes will validate it.

Proof of Stake of course comes with its own Pros and Cons.

Pros:

-   great sybil resistance mechanism
-   great for the environment, much less energy

Cons:

-   seen as less decentralized due to upfront staking costs

This raises the question of _how decentralized is decentralized enough?_ and I think I need to leave that to the community to decide.

### Layer 1 and Layer 2

I want to briefly touch on the concepts of Layer 1 and Layer 2 networks here as well.

1. `Layer 1` solutions: This refers to base layer blockchain implementations like Bitcoin or Ethereum.
2. `Layer 2` solutions: These are applications added on top of a layer one, like [Chainlink](https://chain.link/) or [Arbitrum](https://arbitrum.io/).

Layer 2s like Arbitrum and Optimism are special in that they're trying to solve the problem of scalability. These protocols leverage something called `rollups`. We won't go too deep, but the idea is that the protocols bundle their transactions to be processed by a Layer 1.

## L1s L2s and Rollups

### Blockchain layers

A **Layer 1 (L1)** blockchain is the base layer of the blockchain ecosystem, where nodes help the chain to reach consensus. It operates without any additional plugins and is often referred to as the _settlement layer_. Examples of L1 chains include Bitcoin, BNB Chain, Solana, and Avalanche. In this course, we primarily focus on Ethereum, which serves as the **hub** of the Ethereum ecosystem. Applications directly deployed on Ethereum, like Uniswap, are not considered L2s but rather dApps on L1.

A **Layer 2** is any application built on outside an L1 blockchain that _hooks back into it_. There are different types of Layer 2, for example **Chainlink**, a decentralized Oracle networks and event indexing networks like **The Graph**, which enable applications to access on-chain data. But the most popular type of L2 is the **rollup**, or **L2 chain**.

### Rollups

**Rollups** are L2 scaling solutions that enable to increase the number of transactions on Ethereum by bundling multiple transactions into one, reducing gas costs.

<img src='./images/layers-rollups/layers-rollups1.png' alt='layers-rollups1' />

Rollups help solve the blockchain trilemma, which states that a blockchain can only achieve two out of three properties: _decentralization_, _security_, and _scalability_. In the case of Ethereum, **scalability** is sacrificed as it can only process approximately 15 transactions per second. Rollups, on the other hand, aim to enhance scalability without compromising security or decentralization.

<img src='./images/layers-rollups/layers-rollups2.png' alt='layers-rollups2' />

#### How Rollups Work

When a user [submits a transaction](https://docs.zksync.io/zk-stack/concepts/transaction-lifecycle) to a rollup, an **operator** (a node or entity responsible for processing transactions) picks it up, bundles it with other transactions, compresses them, and submits the batch back to the L1 blockchain. This process allows for efficient handling of transactions as gas costs associated with the transaction, are split among all the users that submitted the transactions in the batch.

There are two types of rollups, Optimistic and Zero-Knowledge rollups. The main difference between the two lies in how each rollup verifies the validity of the transactions.

### Optimistic Rollups

They assume that off-chain transactions are _valid by default_. Operators propose the **valid state** of the rollup chain, and during a **challenge period**, other operators can challenge potentially fraudulent transactions by computing a **fraud proof**.

This **fraud proof process** involves the operator engaging in a _call and response interaction_ with another operator to identify and isolate a specific computational step. This specific step is then executed on the Layer 1 blockchain: if the result differs from the original state, it indicates that the transaction was fraudulent. When the fraud proof succeeds, the rollup will re-execute the entire batch of transactions correctly, and the operator responsible for including the incorrect transaction will be penalized, usually by losing staked tokens (_slashing_).

### Zero-Knowledge (ZK) Rollups

ZK rollups use validity proofs, known as _zk proofs_, to verify transaction batches. In this process, the **prover** (operator) generates a zk proof to show that their inputs (the transactions) satisfy this equation. A **verifier** (an L1 contract) then checks this proof to ensure that the output matches the expected result. The solution that the prover uses to demostrate that their input satisfies the mathematical equation in the zk proof is commonly referred as the **witness**.

### Extra Links

-   [`Replay attacks`](https://www.cyfrin.io/blog/replay-attack-in-ethereum)
-   [`Sybil attacks`](https://www.cyfrin.io/blog/understanding-sybil-attacks-in-blockchain-and-smart-contracts)
-   [`Double-spending`](https://www.cyfrin.io/blog/understanding-double-spending-in-blockchain)
-   [`Zero-knowledge proofs`](https://ethereum.org/en/zero-knowledge-proofs/)

## Centralized Sequencers

In blockchain and cryptocurrency networks, the role of a **sequencer** is crucial for ordering and bundling transactions. Sequencers are operators that are responsible for organizing how transactions are processed. In many roll-up solutions, sequencers are centralized, controlled by a single entity.

### Centralization risks

**Censorship and Manipulation**. Centralized sequencers have the power to selectively block or delay specific transactions. For example, users might experience blocked withdrawal transactions, preventing them from accessing their funds. Additionally, centralized control enables the manipulation of transaction order for personal gain.

**Operational Downtime**. If a centralized sequencer experiences downtime, all transaction processing can halt. This means no transactions, including withdrawals, can be processed until the sequencer is back online.

To mitigate the issues associated with centralized sequencers, projects like **zkSync** are working towards _decentralizing_ their sequencer operations, distributing control among multiple entities or nodes.

## Rollup Stages

A Layer 2 (L2) chain's maturity is evaluated based on specific properties and categorized into **stages**. The [L2B team](https://l2beat.com/scaling/summary) provides an opinionated assessment to encourage a progression towards a greater decentralization.

### Rollup Stages

1. **Stage 0**: In this initial stage, the rollup's governance is largely in the hands of the operators and a security council, ensuring that critical decisions and actions are overseen by a _trusted group_. The open-source software allows for the reconstruction of the state from L1 data, ensuring transparency and accessibility. Users in this stage have an exit mechanism that allows them to leave the rollup within seven days. However, this often requires actions from an entity/operator.

2. **Stage 1**: In this stage, governance evolves to be managed by _smart contracts_, although the _security council_ still plays an important role (e.g. solving bugs). At this stage, the proof system becomes fully functional, enabling decentralized submission of validity proofs. The exit mechanism is improved, allowing users to exit independently without needing operator coordination.

3. **Stage 2**: In this final stage, the rollup achieves full decentralization with governance entirely managed by smart contracts, removing the need for operators or council interventions in everyday operations. The proof system at this stage is permissionless and the exit mechanism is also fully decentralized. The security council's role is now strictly limited to addressing any errors that occur on-chain, ensuring that the system remains fair without being overly reliant on centralized entities.

### ZKSync Risk Analysis

In the [L2Beat summary](https://l2beat.com/scaling/summary) it's possible to see the actual stage of each rollup:

<img src='./images/rollup-stages/rollup-stages1.png' alt='rollup-stages1' />

Currently, [Zksync Era](https://l2beat.com/scaling/projects/zksync-era) is operating as a `Stage 0` rollup. In the dedicated page on L2, we can find a risk analysis:

-   **Data Availability**: refers to the ability to reconstruct the L2 state from L1 data, ensuring that anyone can verify and rebuild the L2 state if necessary.

-   **State Validation**: involves verifying the legitimacy of a set of bundled transactions. For ZK Sync, this is done using zero-knowledge proofs through an algorithm known as PLONK (Permutations over Lagrange-bases for Oecumenical Noninteractive arguments of Knowledge).

-   **Sequencer Failure**: describes the ability to process transactions even if the sequencer is down. In ZK Sync, transactions can still be submitted to L1, though not necessarily enforced immediately.

    > 🗒️ **NOTE**
    >
    > The sequencer is the operator responsible for _ordering_ user transactions and often _batching_ them before committing them to Layer 1.

-   **Proposer Failure**: describes the ability to process transactions even if the proposer is down. In this case, ZK Sync will halt all withdrawals and transactions executions.

-   **Exit Window**: In the current ZK Sync stage, there is no window for exit during unwanted upgrades.

The stages of rollups provide a framework for assessing and encouraging the maturity and decentralization of L2 chains. Understanding these stages and their requirements is crucial for evaluating the progress and risks associated with different rollups.

## Making Your First Transaction On zkSync

In this lesson, we will execute a transaction on the **zkSync testnet**, also known as _zkSync Sepolia_ or _zkSync Era_ testnet. We will start by adding zkSync Sepolia to MetaMask, followed by bridging funds to this network, and finally verifying the transaction details.

### Adding zkSync Sepolia to MetaMask

1. **Add the Network**: search for "zkSync Sepolia Testnet" on [Chainlist](https://chainlist.org/), connect it to your wallet, and add the network by following the confirmation dialogs. Ensure testnets are included in your search.
2. **Check Balance**: you can view your Sepolia balance on MetaMask or on [zkSync Era Sepolia Block Explorer](https://sepolia.explorer.zksync.io/). To view your account summary you can copy your MetaMask address and paste it into the Block Explorer.

### Bridging Funds

Our first transaction involves receiving funds. There are two ways to receive funds on zkSync:

1. **Using a Faucet**: This method requires the use of APIs or GitHub sign-in.

2. **Bridging**: Our recommended method, that involves transferring funds from one chain (Sepolia) to another (zkSync Sepolia). There are two types of bridging mechanisms:

    - **Locking and Unlocking**: Tokens are locked on the source chain and unlocked on the destination chain.
      <img src='./images/zksync-transaction/zkSynk-transaction1.png' />
    - **Minting and Burning**: Tokens are burned on the source chain and minted on the destination chain. The bridge protocol must control the token supply to manage this process. An example is [CCTV](https://www.circle.com/en/cross-chain-transfer-protocol) by the Circle team, where USDC is burned and minted to facilitate bridging.
      <img src='./images/zksync-transaction/zkSynk-transaction2.png' />

3. **Get Sepolia ETH**: Use the [recommended faucet](https://cloud.google.com/application/web3/faucet/ethereum/sepolia) to obtain Sepolia ETH. With 0.05 Sepolia ETH, you're ready to transfer to zkSync Sepolia.

    - Note: If you encounter a message requiring 0.001 ETH on the mainnet, wait 10-20 minutes before trying again.

4. **Use the zkSync Bridge**: Visit the [zkSync bridge](https://portal.zksync.io/bridge) and ensure you are on the testnet. Connect MetaMask to the bridge and confirm a transaction (e.g., 0.025 Sepolia ETH).

5. **Verify the Transaction**: Check the transaction on the zkSync Sepolia block explorer by pasting your wallet address into the search bar to see the transaction details and status.
    - **Transaction Status**: Once processed, you can view the transaction information, including its _status_.
    - **Finality**: As per the [zkSync documentation on finality](https://docs.zksync.io/zk-stack/concepts/finality), this term refers to the time from sending the transaction to when it is considered settled. On Ethereum, this takes about 13 minutes, but on zkSync it can take approximately 24 hours.
      During this period, transactions are displayed **instantly** in the UI and can be further transferred, but full finality should be awaited to ensure they are fully received and validated using ZK proofs.

## Why zkSync

At Cyfrin, we're committed to providing the best tools and platforms to excel as a smart contract developer. This course is proudly sponsored by ZKsync, a leading solution we believe in and use ourselves. Here's why we're choosing ZKsync Era, a layer 2 ZK roll-up, for our smart contract deployment throughout this course.

### Key Reasons to Use ZKsync Era

🔒 **Security**: ZKsync Era inherits its security directly from Ethereum. This means if Ethereum detects an issue and rolls back, ZKsync Era will follow. Transactions are legitimate and authentic thanks to cryptographic validity proofs.

🛠️ **EVM Compatibility**: ZKsync Era is compatible with Ethereum Virtual Machine (EVM). Although it compiles smart contracts into Era VM bytecode rather than EVM bytecode, this transition is seamless. You can deploy your Solidity-written smart contracts on ZKsync Era with minimal adjustments.

🔑 **Ethereum Wallet Support**: ZKsync supports Ethereum wallets out of the box. You can continue using your existing Ethereum wallet, like MetaMask, without creating a new one. Your address remains the same across both Ethereum and ZKsync Era, simplifying your user experience.

💸 **Low Cost and Scalability**: One of the standout features of ZKsync Era is its low transaction costs due to the transactions bundling. This not only reduces gas fees but also ensures scalability as the network grows. By deploying on ZKsync, your protocol will remain efficient and cost-effective even as the number of users increase.
-->
