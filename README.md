#  Chainlink 101 Lottery

> Note! This has recently been updated for the new Chainlink VRF API. `userProvidedSeed` is no longer needed. 


## Requirements

- NPM
- Truffle
- truffle chainlink smartcontractkit/box

## Installation

1. Install dependencies by running:

```bash
npm install

# OR...

yarn install
```

## Deploy

For deploying to the kovan network, Truffle will use `truffle-hdwallet-provider` for your mnemonic and an RPC URL. Set your environment variables `$RPC_URL` and `$MNEMONIC` before running:

```bash
truffle migrate --network kovan --reset
```

## Test

```bash
truffle test 
```
