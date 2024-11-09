# Explanation

This repo contains functions for deriving mainnet keypairs for Bitcoin, EVM, and Solana chains from a 12 word mnemonic phrase. If you input the mnemonic from your existing crypto wallet (i.e. Phantom), you should recieve the same addresses.

It converts the mnemonic string into objects defined by the most popular, trusted, and maintained client libraries:
- EVM addresses are stored in the Wallet type from ethers
- Solana addresses are stored in the Keypair type from solana/web3.js
- Bitcoin addresses are stored in the ECPairInterface type from ecpair

# To Run hd-wallet.ts
1. ```npm install```
2. ```npx ts-node hd-wallet.ts```