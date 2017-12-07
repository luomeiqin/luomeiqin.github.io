---
layout: post
title: Blockchain transaction performance
categories: [blockchain, p2p]
description: some word here
keywords: blockchain
---
The performance of blockchain includes several aspects such as p2p network communication, the efficiency of encryption and decryption, consensus mechanism, transaction verification mechanism and so on.
 ### P2P network
The efficiency of P2P network communication is very important to the performance. First of all, in order to maximize the trading performance, it is recommended that you use a consortium  blockchain instead of a public blockchain. If your application is a high-frequency trading application, you may experience poor user experience if you run a public blockchain based on Bitcoin or Ethereum. Because the public blockchain such as Bitcoin has workd wide p2p network ,resulting in a natural limit to transaction performance. while the consortium blockchain, we can specify the physical configuration of the node machine and the number of nodes, and try to connect with high-speed network, you can greatly improve the transaction performance.
 
### The efficiency of Encryption and Decryption for blockchain

In the age of the internet there are several cryptosystems, however the so called public-key cryptography (also called “asymmetric cryptography”) is the one used in blockchain in order to encrypt and sign the transactions. We know that there are RSA, DSA, elliptic curve algorithm. The blockchain generally use elliptic curve algorithm, including ECDSA and SCHNORR, as well as the country secret algorithm (SM2 elliptic curve public key cryptosystem, SM3 cryptographic hash algorithm, SM4 block cipher algorithm). Among then, Bitcoin blockchain uses more elaborate asymmetric cryptosystem, called Elliptic Curve Digital Signature Algorithm (ECDSA). the signature algorithm used by bitcoin is ECDSA, while Schnorr signature verifies faster than ECDSA signature, and this signature size can be smaller and supports multiple signatures recursively.Another technological component of a blockchain is the cryptographic hash function,such as SHA family algorithm, MD5, SCRYPT, RIPEMD, WHIRLPOOL, CUCKOO HASH, HAVAL, Tiger, LYRA2, Equihash, Hashimoto, Dagger and Ethash. These algorithms are used in series or in parallel. As commercial applications generally do not consider the issue of mining ,but pay more attention to performance issues. it is  recommended that you base on SHA256 algorithm commonly. However, There is not one Encryption algorithm which is the most efficient in all applications. Moreover Efficiency is not the most important measure when it comes to Encryption algorithms.We cannot use a  algorithm just because it is the most efficient.We have to consider other measures such as security,reliability,world wide acceptance etc.
 
### Consensus Mechanism: 
A poor performance would happen , based on the design of the consensus algorithm, it may require more time under certain 
conditions for consensus to converge. These conditions could be dynamic where other nodes have turned malicious or a network partition may delay messages that are exchanged between nodes. Therefore , there are some typical consensus algrithom that is used in different blockchain: PoW to PoS to DPoS and various Byzantine fault tolerance algorithms. Those consensus mechanisms do continually to innovate. blockchain platform performance has also been significantly improved. Under the consensus mechanism similar to DPoS or PBFT, the blockchain transaction is validating rapidly and the transaction throughput almost meets the existing financial transaction scale.  In some private blockchain case, the performance reaches tens of thousands of transactions per second, almost meets most of the business needs.  

### Transaction Verification
From the perspective of transaction verification mechanism, there are several optimization methods:
 
1. Sharding, the general idea is that each node only handles part of the transaction, such as part of the account initiated transactions, hence, reduce the node's computing and storage burden.
 
2. Lightning Network and State Channels, these two strategies solve  scalability of blockchain , being capable of millions to billions of transactions per second across the network, by transacting and settlingout off the blockchain. 
 
Bitcoin,Ethereum, Ripple ,HyperLedger fabric and Corda, each of  this blockchain, there throughput and other performance improvements have been greatly enhanced through consensus algorithm innovation and consortium blockchain deployment, hence,  current delays up to seconds and throughput up to 10 million Per second. The storage requirements of a single node can also be optimized accordingly. Thus,  performance bottlenecks have been gradually broken through.


