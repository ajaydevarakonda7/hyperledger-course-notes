## Growing interest in hyperledger technologies
Advent of personal computers has caused a rise in server client architectures. 

Computing started with mainframes. Then cloud computing came along and cause distributed hardware resources but still \
application level centralization existed. Distributed systems like blockchain "give explicit control of digital assets \
to end-users and remove the need to trust any third-party servers and infrastructure" (copied from muneeb ali's post).

## DLT
Distribute ledger technologies = block chain technologies + smart contracts

DLTs existed even before bitcoin, but bitcoin =

convergence(
1. timestamping transactions, 
2. p2p networks, crypto,
3. shared computational power,
4. new consensus algo
)

But bitcoin does not support smart contracts.

In summary, `distributed ledger technology` generally consists of three `basic components`:

1. A `data model`, that captures the current state of the ledger
2. A `language of transactions` that changes the ledger state
3. A `protocol` used to build consensus among participants around which transactions will be accepted, and in what order, by the ledger.

## Blockchains
Block chain = chronological chain of blocks. Each block is timestamped.

Chain Core, Corda, Quorum, and IOTA are examples of blockchains available.

### Bitcoin block
A Block has four pieces of metadata:

1. The reference to the previous block
2. The proof of work, also known as a nonce
3. The timestamp
4. The Merkle tree root for the transactions included in this block (Merkle tree is explained next).

## Merkle tree
