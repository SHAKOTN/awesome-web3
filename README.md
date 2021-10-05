# Long list of web3 related resources
> List of blockchain/web3 related resources. This includes different protocols, tools, libraries, concepts, wallets

## Table of contents
- [Key concepts](#concepts)
- [Blockchains](#blockchains)
    - [Bitcoin](#bitcoin)
        * [Libraries and tools](#bitcoin-libraries-and-tools)
        * [Wallets](#bitcoin-wallets)
    - [Ethereum](#ethereum)
        * [Ethereum basics](#ethereum-basics)
        * [Ethereum 2.0](#ethereum-2)
        * [Tools](#ethereum-libraries-and-tools)
        * [Tutorials](#ethereum-tutorials)
        * [Wallets](#ethereum-wallets)
    - [Cardano](#cardano)
        * [Cardano basics](#cardano-basics)


## Concepts
- [Proof of Work](https://en.wikipedia.org/wiki/Proof_of_work)
- [Proof of Stake](https://en.wikipedia.org/wiki/Proof_of_stake)

## Blockchains

## Bitcoin
![](images/bitcoin.png)

Bitcoin is a digital or virtual currency created in 2009 that uses peer-to-peer technology to facilitate instant payments.

- [Bitcoin](https://bitcoin.org/en/) - A father of all blockchains. Bitcoin development on [Github](https://github.com/bitcoin)
- [Script](https://en.bitcoin.it/wiki/Script) - Writing smart contracts on Bitcoin is possible, however, not that simple
- [Lightning Network](https://lightning.network/) - L2 scaling solution for Bitcoin protocol, aimed to solved scalability problem
- [Bitcoin fees calculator](https://bitcoinfees.net/) - Bitcoin fees calculation

### Bitcoin Libraries and Tools
- [bitcoinjs](https://github.com/bitcoinjs/bitcoinjs-lib) - A javascript Bitcoin library for node.js and browsers

#### Bitcoin Wallets:
- [Exodus](https://www.exodus.com/) - Popular bitcoin hot wallet


## Ethereum
![](images/ethereum-logo-landscape-purple.png)
[Ethereum](https://ethereum.org/en/)  is a blockchain platform with its own cryptocurrency, called Ether (ETH) or Ethereum, and its own programming language, called Solidity. 

### Ethereum Basics

- [Ethereum Book](https://github.com/ethereumbook/ethereumbook) - best way to dive deep into Ethereum ecosystem and learn about all key concepts, runtime and EVM
- [Solidity](https://github.com/ethereum/solidity) - Ethereum native language to write smart contracts
- [Vyper](https://github.com/vyperlang/vyper) - Ethereum another native language for smart contracts development. Used less frequently than solidity
- [EVM](https://ethereum.org/en/developers/docs/evm/) - Ethereum turing-complete virtual machine, runtime environment to execute smart contracts
- [Ethereum Gas Station](https://ethgasstation.info/) - Ethereum gas price estimator to predict gas consumption for smart contracts execution
- [Polygon](https://github.com/maticnetwork) - L2 scaling solution for Ethereum. Most widely used as of 2021
- [Arbitrum](https://github.com/OffchainLabs/arbitrum) - Another L2 scaling solution for Ethereum
- [Etherscan](https://etherscan.io/) - Ethereum blockchain explorer


### Ethereum 2
Long term goal of switching from Proof of Work to Proof of Stake
- [Beacon Chain](https://ethereum.org/en/eth2/beacon-chain/) - Beacon chain is a parallel Eth chain that supports Proof of Stake consensus
- [Sharding](https://eth.wiki/en/sharding/sharding-roadmap) - More of upcoming Ethereum sharding

### Ethereum Libraries and tools

Javascript:
- [web3js](https://github.com/ChainSafe/web3.js) - One of the best libraries to interact with Ethereum network through JSON-RPC
- [etherjs](https://github.com/ethers-io/ethers.js/) - Another great library to use with Ethereum
- [ganache-cli](https://github.com/trufflesuite/ganache-cli-archive) - Ganache command line utility tool

Python:
- [web3py](https://github.com/ethereum/web3.py) - Python library for Ethereum inspired by web3js
- [brownie](https://github.com/eth-brownie/brownie) - Python-based development and testing framework for smart contracts on Ethereum
- [py-evm](https://github.com/ethereum/py-evm) - Python implementation of EVM

Tools:
- [Hardhat](https://github.com/nomiclabs/hardhat) - Modern Ethereum development environment
- [Truffle](https://github.com/trufflesuite/truffle) - Another Ethereum development environment
- [Ganache](https://github.com/trufflesuite/ganache) - Ethereum simulator for local(not only) development

### Ethereum Tutorials:
- [Cryptozombies](https://cryptozombies.io/en/) - Beginner guide to Ethereum development using smart contracts
- [Ethereum Dev Speed Run](https://medium.com/@austin_48503/%EF%B8%8Fethereum-dev-speed-run-bd72bcba6a4c) - An article with everything you need to start with Ethereum
- [Solidity by example](https://solidity-by-example.org/) - Intro to Solidity with simple examples

### Ethereum Wallets:
- [Metamask](https://metamask.io/) - Most popular Ethereum hot wallet
- [Exodus](https://www.exodus.com/) - Another popular Ethereum hot wallet


## Cardano
![](images/cardano.png)

[Cardano](https://cardano.org/) is a decentralized blockchain platform launched in 2017 by Ethereum co-founder Charles Hoskinson. Smart contracts launched in September 2021 and infrastracture is WIP.

### Cardano basics

- [Cardano smart contracts](https://github.com/cardano-foundation/docs-cardano-org/blob/main/explainers/cardano-explainers/smart-contract-exp.md) - what are cardano smart contracts
- [Marlowe](https://docs.cardano.org/marlowe/learn-about-marlowe) - native language to write smart contracts on Cardano
