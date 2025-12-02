---
layout: default
title: Alchemy - Section 1
---

# Blockchain and Crypto

- Tools used to build, test, deploy, and interact with programs are known as **smart contracts**.
- What is the purpose of blockchain?
  - It allows a network of computers to agree on a common state of data.
  - No one person should be able to control the process.
- Satoshi Nakamoto is the creator of the blockchain:
  - *Crypto presented a HUGE flaw, which is trust. Since crypto would rely on a decentralized network to process the transaction, how could we trust that the bookkeeper would process the transaction, not steal the funds, not update the balance sheet with false information? There were a lot of security flaws with crypto coins until Nakamoto released the white paper on a new technology called blockchain.*
- *Smart contract* is when you take code, decentralize it, and make it available on the blockchain for usage. The nodes on the network will enforce its proper usage. This code will **always** run the way it is programmed to run.
- A **hash function** is a function that will take an input and turn it into a fixed-size output.

## Example

| **Input**           | **Input Size**        | **Output**     | **Output Size** |
|---------------------|------------------------|----------------|------------------|
| `52`                | 8 bytes                | `0x41cf...`    | 32 bytes         |
| `"happy times"`     | 22 bytes               | `0xd6bf...`    | 32 bytes         |
| `monalisa.jpg`      | 875,000 bytes          | `0x7cde...`    | 32 bytes         |
| `worldseries.mp4`   | 1.6e+10 bytes          | `0x9c0e...`    | 32 bytes         |

- Notice how the input size is bigger from top to bottom; however, the output size remains the same. No variation.
- There are a ton of different hash functions, but the main ones used in blockchain are **cryptographic hash functions**.
- A cryptographic hash function must have five specific properties:
  - **Deterministic**: one specific input must always map to the same specific output.
  - **Pseudorandom**: It is not possible to guess the output based on the output of similar inputs.
  - **One-way**: If someone gives you an output, you cannot feasibly guess the input without brute-force guessing.
  - **Fast to compute**: It must be a quick calculation.
  - **Collision-resistant**: The chance of two different inputs producing the same output should be infinitesimally small.

## Homework

Try using this SHA-256 online tool. Can you prove to yourself each one of these properties?

- [HASH TOOL](https://emn178.github.io/online-tools/sha256)