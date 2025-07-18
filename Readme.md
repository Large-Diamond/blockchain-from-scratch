Blockchain From Scratch
Learn how blockchain works by building one step by step—in Rust.

If you get stuck, check the solutions branch for completed code.

Table of Contents
Some parts are optional and can be skipped if you're short on time. These are marked with a *.

Chapter 1: State Machines
We begin by understanding what a state machine is and how to build a few examples. We don’t talk about blockchains or consensus yet. The examples range from simple learning tools to more realistic systems used in actual blockchains.

Part 1 - Switch State Machines – Two very basic examples to learn the core idea.
Part 2 - Laundry Machine – A playful example showing clean and dirty laundry states.
Part 3* - ATM – A simplified version of an ATM, showing how more complex state machines work.
Part 4* - Accounted Currency – A realistic model for cryptocurrencies like Ethereum and Polkadot.
Part 5 - Digital Cash – A realistic system like the ones used by Monero, Dogecoin, or Litecoin.

Chapter 2: Blockchain
We build up the blockchain data structure, starting with a basic hash-linked list, and grow it into a full blockchain with headers, bodies, and consensus information. This is the most important chapter.

Part 1 - Header Chain – A simple chain with no real logic or state.
Part 2 - Extrinsics and State – We add state and transactions (called extrinsics).
Part 3 - Consensus – We add a basic proof-of-work system.
Part 4 - Batched Extrinsics – We split blocks into headers and bodies and allow multiple extrinsics per block.
Part 5 - Fork Choice – We discuss how to choose the “real” chain when there are forks.
Part 6 - Rich State – We show how blockchain state isn’t stored in blocks directly and introduce the genesis (starting) state.

Chapter 3: Consensus
We define consensus more formally and revisit proof-of-work in this context. We also look at other types like proof-of-authority and touch briefly on proof-of-stake.

Part 1 - Proof of Work – We redo proof-of-work using our new consensus setup.
Part 2* - Dictator – A simple system where one authority decides all blocks.
Part 3 - Proof of Authority – We build several authority-based systems, some real, some for fun. We also mention proof-of-stake briefly.
Part 4* - Even Only – A look at unusual or made-up consensus rules.
Part 5* - Interleave – (Work in progress) Mixing different consensus rules across blocks.
Part 6 - Forking – How to switch consensus rules during a fork in the blockchain.

Chapter 4: Blockchain Framework and Client
Still being worked on. In this chapter, we’ll make our blockchain fully flexible so you can plug in different state machines and consensus rules. We’ll also build a real blockchain client that can handle importing/exporting blocks, making new blocks, managing a transaction pool, and picking the best chain. Finality might come later too.

License
This project is licensed under the GPL-3 or later.
