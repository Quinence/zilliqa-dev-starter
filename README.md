# Zilliqa Development Starter

This repository outlines how to get started with development on the Zilliqa Blockchain. It also lists tutorials, courses, and tools on Zilliqa development.

## What is Zilliqa?

Zilliqa is the first public blockchain built entirely on a sharded architecture that's scalable, secure, decentralised, fast and low-cost. To design smart contracts, Zilliqa uses Scilla — an intermediate-level smart contract language developed with contract safety being prioritized.

It is not strictly necessary to understand the design of Zilliqa architecture to start developing on Zilliqa. Nonetheless, the Zilliqa Design Story is an important read before diving deeper.

📖 Read [Part 1 (Network Sharding)](https://blog.zilliqa.com/https-blog-zilliqa-com-the-zilliqa-design-story-piece-by-piece-part1-d9cb32ea1e65), [Part 2 (Consensus Protocol)](https://blog.zilliqa.com/the-zilliqa-design-story-piece-by-piece-part-2-consensus-protocol-e38f6bf566e3), and [Part 3 (Making Consensus Efficient)](https://blog.zilliqa.com/the-zilliqa-design-story-piece-by-piece-part-3-making-consensus-efficient-7a9c569a8f0e).

## Getting started with testnet ZIL tokens

Like any common public Blockchain, Zilliqa has a testnet (for test and development) and a mainnet (the real Blockchain). Before any development, it is important to get accustomed to creating an account and getting some testnet ZIL tokens (tokens in Zilliqa are called ZIL).

🏁 The [developer wallet](https://dev-wallet.zilliqa.com/) is a great way to quickly create a new wallet. Once a wallet is created, use the ZIL faucet there to request free testnet ZILs. Be sure to save the wallet details (e.g. the keystore file) so that you can use this account at the later part of the development.

You may install [Zilpay](https://zilpay.io/) — the Zilliqa-backed web3 wallet that can be used with any decentralized apps (dApps) on Zilliqa. The Chrome extension can be used in Google Chrome and Chromium-based browsers (e.g. Brave). The accounts already created in the testnet can then be imported in Zilpay as well.

## Starting with smart contract development in Scilla

Learning the Scilla smart contract language is the first step of Blockchain development in Zilliqa. Like any smart contract language, Scilla has its own learning curve. However, there are great tools to aid the process.

🚀 Learn Scilla in a fun and interactive way at [LearnScilla](https://learnscilla.com/).

The [online IDE](https://ide.zilliqa.com/) for Scilla is a great place to design and test Scilla smart contracts. Pro tip: Use the testnet (and not simulated environment) in the IDE for a consistent experience.

🧵 A collection of smart contracts and design patterns can be found at:
- [Smart contracts from the IDE](https://github.com/Quinence/zilliqa-scilla-ide-contracts) with more details.
- [Examples and snippets](https://github.com/TheDrBee/oSCILLAtor) for best practices. 

## Interacting with the Zilliqa Blockchain

While the smart contracts can technically be deployed and interacted with from the online IDE, there are many other ways to interact with the Zilliqa Blockchain programmatically.

👐 The most popular is the [Zilliqa JavaScript Library](https://github.com/Zilliqa/Zilliqa-JavaScript-Library). It has first-class support for TypeScript, and allows to interact with the Zilliqa Blockchain from browser-side application frameworks (e.g. React) as well as any Node.js project (e.g. serverside).

[Zilpay also has an extensive API](https://zilpay.github.io/zilpay-docs/) whose signature is analogous to the Zilliqa JavaScript Library. It is also recommended when interacting with the Zilliqa Blockchain from client-side applications with dynamic user interactions (e.g. paying with Zilpay).
