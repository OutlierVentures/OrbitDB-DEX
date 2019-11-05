# OrbitDB DEX

This repositry covers the code produced as part of the OrbitDB decentralized exchange (DEX) research project. The DEX has three parts:

## Requirements

- Node.js
- Truffle

## Install

Install node modules:

```sh
cd order_book
npm install --unsafe-perm=true
cd ../dex-front
npm install --unsafe-perm=true
```

Boot up an Ethereum node and deploy tokens to use on the exchange:

```sh
cd smart_contracts
truffle compile
truffle migrate
```

## Run

Start the app:
```sh
cd dex-front
npm start
```

See the readme in the front-end folder

1. Front-end: [code](https://github.com/IC3RE/orbitdb-dex/tree/master/dex-front)
2. Order book: [code](https://github.com/IC3RE/orbitdb-dex/tree/master/order_book)
3. Smart contracts: [code](https://github.com/IC3RE/orbitdb-dex/tree/master/smart_contracts)
