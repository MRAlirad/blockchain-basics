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

A **Layer 2 (L2)** is a blockchain built *on top of* an underlying Layer 1, most commonly Ethereum. L2s like **Arbitrum**, **Optimism**, and **zkSync** act as express lanes built above our congested Ethereum highway.

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

*   **Ethereum Mainnet** has a Chain ID of **1**.
*   **Sepolia Testnet** has a Chain ID of **11155111**.

Your wallet uses the Chain ID to ensure it is communicating with the correct network for every transaction you sign. You can find the Chain ID and other connection details for hundreds of blockchains on websites like `chainlist.org`.

As we move forward, remember that repetition is the mother of skill. You don't need to memorize every name and number today. These core concepts—the multi-chain world, L1s, L2s, Mainnets, Testnets, and Chain IDs—will be revisited and reinforced throughout your journey.

## What Is the Blockchain Oracle Problem?

Before we explore one of the most fundamental challenges in Web3, let's quickly recap two core concepts. First, a blockchain is a decentralized, trustless source of truth. It's a shared ledger distributed across many nodes, ensuring that no single entity has control. This creates a transparent, permissionless, and censorship-resistant system.

Second, smart contracts are decentralized, unbreakable agreements that live on the blockchain. They are programs that execute deterministically based on their code, without needing an intermediary to enforce the rules. In essence, the code itself is the law.

These two technologies create a powerful, self-contained, and secure digital world. However, their greatest strength—their secure isolation—is also their greatest limitation.

### The Blockchain's Isolated World

By design, blockchains and the smart contracts that run on them are isolated systems. They can only read and interact with data that is already on the blockchain, or **on-chain**. This includes things like account balances, token transfers, or the state of other smart contracts.

They have no native capability to access any external, real-world data, often called **off-chain** data. This creates a significant problem because for smart contracts to be truly useful in real-world agreements, they often need information from outside their digital walls. Consider these examples:

*   A decentralized insurance contract needs weather information to pay out a claim for a flood.
*   A DeFi lending protocol needs real-time stock and cryptocurrency prices to manage collateral.
*   A prediction market needs to know the final score of a sports game or the results of an election to settle bets.
*   A supply chain application needs confirmation that a package has been delivered.

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

*   **On-chain Component:** The core smart contract logic that lives on the blockchain, providing decentralization, security, and transparency.
*   **Off-chain Component:** The real-world data and computation provided by a Decentralized Oracle Network.

This hybrid model combines the best of both worlds: the tamper-proof security of the blockchain and the rich data and functionality of the real world. Today, most major Web3 protocols, from DeFi to blockchain gaming, use this hybrid architecture. In fact, the term "smart contract" is now often used interchangeably with "hybrid smart contract" because this model is essential for creating powerful, real-world applications.

### Chainlink: The Industry-Leading Oracle Network

**Chainlink** is the industry-standard, modular, and decentralized oracle network that provides the critical infrastructure to solve the oracle problem. One of its key strengths is that it is **blockchain-agnostic**, meaning its services can be integrated with many different blockchains, including Ethereum, Avalanche, Polygon, zkSync, and more. This makes learning Chainlink a highly transferable skill for any Web3 developer.

Chainlink provides a suite of essential services that enable hybrid smart contracts, including:

*   **Data Feeds:** Provide highly reliable, real-time financial market data, such as `Price Feeds`, which are the backbone of the DeFi ecosystem.
*   **Automation:** Allows for the automated execution of smart contract functions based on predefined triggers, such as time intervals, without relying on a centralized server.
*   **Verifiable Random Function (VRF):** Provides a source of provably fair and verifiable randomness, which is impossible for a blockchain to generate on its own. This is crucial for blockchain gaming, NFTs, and any application requiring unpredictable outcomes.
*   **Cross-Chain Communication:** Enables smart contracts on one blockchain to send messages and interact with smart contracts on another, connecting the fragmented Web3 ecosystem.

By solving the oracle problem, Decentralized Oracle Networks like Chainlink are the critical link that allows blockchains to securely interact with the real world, unlocking the full potential of smart contracts.

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
