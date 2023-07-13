# Alberto

A decentralized game when your population is your resource and win condition!

## Technical Info

### Frontend (Web3)

The main purpose of an application frontend is to expose data to external users. It can also provide entry points for the user to engage with functionality that mutates data and internal system state.

The Alberto frontend is located on /TBD and can be viewed in your browser. Here you can see the current state based on on-chain data, and interact with it indirectly using a traditional web2 backend.

### Backend

## On-chain

Alberto stores data on-chain in an NFT contract using [Crossmint](https://www.crossmint.com/). Crossmint provides public APIs to read on-chain data, and allows authorized minters to write data.

## Off-chain (traditional web2 backend)

Part of the power of web3, is the ability to leverage traditional web2 backends. To demonstrate this, I have abstracted data mutation (contract write methods) behind an HTTP API.
