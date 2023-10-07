# Token_MerkleProofs
This repository contains a smart contract that implements
a Merkle-tree for distributing airdrops
to various addresses based on a predetermined whitelist.

The contract hashes the address and the respective
airdrop amount for each eligible address into a Merkle root.
During the distribution process, claimers provide an address 
which is then confirmed as a leaf in the Merkle root, 
allowing them to claim their airdrop.
