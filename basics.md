# Ethereum Basics
- Ethereum is a decentralized platform for applications and smart contracts.
- It is a blockchain-based platform.
- It is a decentralized platform.
- On Ethereum, users can write applications and smart contracts.
- These applications are called DApps and they transact using digital curreny calle Ether(ETH).
- Ether is the currency used to transact on Ethereum.

## Blockchain
- Blockchain is a distributed database of records.
- It stores records of transactions.
- A blockchain is a ledger of records.
- It tracks and records the ownership of assets.
- Blochain's scalability and unique construction gives it properties of security and immutability.
- It makes it ideal for exchaning assets between two or more parties, without a central authority.
- The first assets on blockchain were cryptocurrency.
- Ethereum is a second generation blockchain, it not only manages its own native token, but also any type of asset that can be defined.
- Ethereum can also take action on transactions, with programs called smart contracts.
- [Ether Scan](https://etherscan.io/) is a blockchain explorer.
- Two kinds of assets, Ether and tokens.
- Ether is the currency used to transact on Ethereum.
- Tokens are digital assets that can be defined by the user.
- Dapps are web or enterprise applications that include application logic to invoke blockchain functions that implement trust intermediation.
- A smart contract is an immutable executable code representing the logic of a Dapp. The data variables and functions defined in a smart contract collectively represent the state and operations for enforcing an application’s (Dapp’s) rules for verification, validation, and recording on the blockchain.
- Node is a collective name for blockchain software and the machine or hardware on which it is installed for the participant of a decentralized system.
- An account represents a unique identity for a transacting entity. An account is needed to initiate a transaction.
- A network identifier identifies a blockchain network of nodes. Network ID #1, for example, is the main Ethereum public network; network ID #4 is a public network called Rinkeby (https://www.rinkeby.io), and so on. You’ll have to indicate the network by using its identifier while deploying your smart contract on the network. The participants on a given network will share a unified distributed ledger for recording their transaction details.
- The smart contracts are deployed in a sandbox environment such as a virtual machine (VM) hosted by a blockchain node. 
- The syntax of a smart contract is similar to a class in an OO (object-oriented) language. It contains data, functions, and rules for the execution of functions. 
- Calling or invoking a smart contract function generates the transactions that are recorded on the blockchain. 
- If any of the verification and validation rules fails, the function invocation is reverted. 
- But if the execution is successful, the generated transactions (Txs) are broadcast to the network for recording, 

## Transactions, Blocks and Chain of Blocks
- Applications initiate transactions and the execution of smart contract code. A simple cryptocurrency transfer between accounts, for example, generates a “send” transaction. The transactions generated are broadcast through the blockchain network and then gathered and recorded in the distributed immutable ledger.
- A set of transactions makes a block, and a set of blocks make a blockchain.
- A blockchain protocol defines the following, among other things:
     - The structure of a blockchain (transactions, blocks, and chain of blocks)
     - Fundamental algorithms and standards for encryption, hashing, and state management
     - Methods for implementing consensus and a consistent chain of blocks
     - Techniques for handling exceptions resulting in an inconsistent ledger
     - The execution environment for code on the blockchain and rules for maintaining consistency, correctness, and immutability in this context
