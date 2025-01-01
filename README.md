<p align="center">
    <img src=".github/awesome-aiken.png" alt="Awesome Aiken" width="480"/>
    <br/>
    <strong>An collection of (curated) awesome <a href="https://aiken-lang.org" alt="aiken-lang.org"/>Aiken</a> libraries, DApps, tutorials & other cool stuff.</strong>
</p>

---

> [!TIP]
>
> Anything to contribute? [Make a pull request](https://github.com/aiken-lang/awesome-aiken/pulls) that adds your project to this list :heart:!

---

# Awesome Aiken

- [Libraries](#Libraries)
- [Dapps](#Dapps)
- [Tutorials/Examples](#tutorialsexamples)
- [Videos](#Videos)

## Libraries

#### Infrastructure

- [aiken-lang/setup-aiken](https://github.com/aiken-lang/setup-aiken) - A GitHub action for installing and using Aiken in Github Workflows

#### Standard library & extras 

- [aiken-lang/stdlib](https://github.com/aiken-lang/stdlib) - The official standard library
- [Cardano-Fans/acca](https://github.com/Cardano-Fans/acca) - Extensions to the standard library
- [SundaeSwap-finance/aicone](https://github.com/SundaeSwap-finance/aicone) - Several reusable Aiken libraries
- [LogicalMechanism/assist](https://github.com/logicalmechanism/assist) - A collection of specialized Aiken functions.
- [aiken-extra/*](https://github.com/aiken-extra) - A collection of additional aiken functions to build tests and help debug.

#### Cryptography 

- [ilap/bls](https://github.com/ilap/bls) - High-level BLS12-381 cryptographic functions 

#### Data-structures

- [aiken-lang/merkle-patricia-forestry](https://github.com/aiken-lang/merkle-patricia-forestry) - For working with modified Merkle Patricia Tries (on-chain & off-chain): a persistent & authenticated data structure to map between arbitrary keys and values.
- [anastasia-labs/aiken-linked-list](https://github.com/Anastasia-Labs/aiken-linked-list) - For working with onchain distributed linked lists (on-chain): each node in the linked list is represented by a single UTxO (and thus concurrency scales with utilization, the larger the linked list, the lower the probability of experiencing UTxO contention).
- [anastasia-labs/aiken-trie](https://github.com/Anastasia-Labs/aiken-trie) - For working with distributed tries (on-chain & off-chain): each trie is fully-contained within a UTxO, and it supports managing multiple distributed tries with a single validator.
  
#### Testing

- [aiken-lang/fuzz](https://github.com/aiken-lang/fuzz) - For writing Fuzzers (a.k.a generators) for property-based testing in Aiken 
- [sidan-lab/vodka](https://github.com/sidan-lab/vodka) - Offer validation utils and similar to offchain code building experience framework for unit testing.

## Dapps

#### DeFi

- [Sundae Swap V3](https://github.com/SundaeSwap-finance/sundae-contracts) - DEX
- [Minswap V2](https://github.com/minswap/minswap-dex-v2) - DEX
- [Minswap - Stableswap](https://github.com/minswap/minswap-stableswap) - DEX
- [Lenfi](https://github.com/lenfiLabs/lenfi-smart-contracts) - Lending and Borrowing
- [Levvy](https://levvy.fi/) - NFT based lending and borrowing
- [Danogo](https://danogo.io/) - Decentralized Bond Exchange
- [Mehen](https://mehen.io) - Fiat-backed stable coin
- [SundaeSwap Yield Farming v2](https://github.com/SundaeSwap-finance/sundae-yield-v2) - SundaeSwap Yield Farming v2 contracts

#### Marketplaces

- [Jpg Store](https://github.com/jpg-store/contracts-v3) - NFT Marketplace
- [Nebula](https://github.com/spacebudz/nebula/tree/main/contract/src/nebula) - A Cardano NFT marketplace contract including chain indexer and event listener for individual projects

#### Smart Wallets

- [Seedelf](https://github.com/logical-mechanism/Seedelf-Wallet) A Cardano Stealth Wallet

#### Governance

- [unLearn](https://github.com/Astodialo/unLearn) - Modular governance framework

#### Games

- [Tetrano](https://tetrano.net) - Tetris style puzzle game on Cardano

#### Misc

- [Fortuna](https://github.com/cardano-miners/fortuna) - A Smart Contract that mimics bitcoin proof of work
- [morbid](https://github.com/ariady-putra/morbid) - A dead-man's switch contract
- [Projected NFT Whirlpool](https://github.com/dcSpark/projected-nft-whirlpool) - A new protocol for the Paima Whirlpool vision to allow users from other ecosystems to naturally be able to use existing NFTs in games from other ecosystems while still maintaining custody
- [ENCOINS](https://github.com/encryptedcoins/encoins-core-aiken) - An NFT-based private transactions protocol

## Tutorials/Examples

- [Hello, World!](https://aiken-lang.org/example--hello-world) - Write and execute a smart contract on Cardano in 10 minutes
- [Vesting](https://aiken-lang.org/example--vesting) - Learn how to work with time
- [Gift Card](https://aiken-lang.org/example--gift-card) - Make gift cards using NFTs using Aiken and Deno fresh
- [Gift Card NextJS](https://github.com/adalicious/aiken-gift-card) - A similar gift card example but with NextJS
- [MeshJS smart contracts collection](https://github.com/MeshJS/mesh/tree/main/packages/mesh-contract/src) - A series of smart contracts  with full integration with MeshJS, offering code examples and explanations
- [Maestro Dapps Tutorials](https://github.com/maestro-org/dapp-platform-tutorials/tree/main/bets)
- [Logical Mechanism's Distributed Representation](https://github.com/logicalmechanism/distributed_representation) - A model semi-liquid `mint-lock-stake` DAO
- [Logical Mechanism's Convert Expression](https://github.com/logicalmechanism/convert-expression) - A novel variation of a Schnorr protocol
- [From Aiken to frontend deployment](https://meshjs.dev/guides/aiken) - A end-to-end guide from writing a Aiken smart contract, to creating transactions, to deploying a frontend to interact with it. See also [demo](https://aiken-next-ts-template.vercel.app/) and [repo](https://github.com/MeshJS/aiken-next-ts-template).
- [Cardano Capture The Flag](https://github.com/vacuumlabs/cardano-ctf) - A game where Cardano developers and enthusiasts can try to exploit purposely vulnerable smart contracts and learn about the most common security issues and how to prevent them.
- [Cardano Recorded Mint](https://github.com/keyan-m/cardano-recorded-mint) - A proof-of-concept for a minting script with historical record of all mints, and on-chain guarantee of uniqueness.
- [Common Design Pattens](https://github.com/Anastasia-Labs/aiken-design-patterns) - A collection of tried and tested modules and functions for implementing common design patterns.
  
## Videos

- [NerdOut's Aiken edition](https://www.youtube.com/watch?v=9wbQ33uzwsc&pp=ygUNQWlrZW4gY2FyZGFubw%3D%3D) - A high-level presentation of Aiken <sup> ~11 min</sup>
- [ReddSpark's beginner guide to Aiken](https://www.youtube.com/watch?v=-H5llvQdpRw&pp=ygUPcmVkZHNwYXJrIGFpa2Vu) - A guided 'Hello, World!' tutorial for Windows users <sup> ~50 min</sup>
- [Hello, World! with Demeter](https://twitter.com/i/status/1652846950251732993) - The 'Hello, World!' tutorial but using `cardano-cli` instead of `Lucid` <sup> ~19min</sup>
