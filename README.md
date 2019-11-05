<p align="center">
    <img src="./img/logo.png" width="550" />
    <br><br>
    <a href="https://github.com/orbitdb/orbit-db" alt="OrbitDB">
        <img src="./img/orbitv.svg" />
    </a>
    <a href="https://outlierventures.io" alt="Convergence ready">
        <img src="./img/convergence.svg" />
    </a>
    <br><br>
    A decentralised exchange on OrbitDB.
    <br><br>
    <i>An app in the Convergence Stack.</i>
</p>

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

See the readme in the front-end folder (`dex-front`) for testing and building for production.
