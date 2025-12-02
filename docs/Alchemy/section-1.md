---
layout: default
title: Alchemy - Section 1
---


---
# Blockchain and Crypto
- Tools used to build, test, deploy, and interact with programs is known as **smart contracts**
- What is the purpose of blockcahin?
    - It allows a network of computers to agree on a common state of data
        - No one person should be able to control the the process
- Satoshi Nakamoto is the creator of the blockchain:
    - *Crypto presented a HUGE flaw, which is trust. Since crypto would rely on a decentralized network to process the transaction, how could we trust that the bookkeeper would process the transaction, not steal the fund, not update the balance sheet with false information, just a lot of security flaws with crypto coin, until Nakamoto released white pages on a new technology called blockchain
- *Smart Contract is when you take a code and decentralize it, and make it readily avail on blockchain for usage. The node on the network will enforce it's proper usage. This code will ALWAYS run the way it is programmed to run
- Hash function is a function that will take an input and turns it into a fixed size output
## Example
| **Input**           | **Input Size**        | **Output**     | **Output Size** |
|---------------------|------------------------|----------------|------------------|
| `52`                | 8 bytes                | `0x41cf...`    | 32 bytes         |
| `"happy times"`     | 22 bytes               | `0xd6bf...`    | 32 bytes         |
| `monalisa.jpg`      | 875,000 bytes          | `0x7cde...`    | 32 bytes         |
| `worldseries.mp4`   | 1.6e+10 bytes          | `0x9c0e...`    | 32 bytes         |
- Notice how the input size is bigger from top, down, however, the output size remains the same. No variation
- There are a TON of different hash function, but the main one used in blockchain are cryptographic functions. The cryptographic hash function must have five specific property
    - Deterministic: one specific input must always map to the same specific output
    - Pseudorandom: It is not possible to guess the output based off of the output of similar inputs 
    - One-way: If someone gives you an output you could not guess the input without guessing
    - Fast to Compute: It must be a quick calculation
    - Collision-resistant: The chance of a collision should be infinitesimally small

## Homework
Try using this sha256 online tool. Can you prove to yourself each one of these properties?
    - [HASH TOOL](https://emn178.github.io/online-tools/sha256)

