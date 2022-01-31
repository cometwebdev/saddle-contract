## Installation

```bash
$ npm i
```

## Usage

### Build

```bash
$ npm run build
```

### Test

```bash
$ npm test
```

### Coverage

```bash
$ npm run coverage
```

### Deploying contracts to localhost Hardhat EVM

```bash
$ npm run start
```
You can connect to this RPC server via `http://localhost:8545` with chain ID of 31337

### Deploying contracts to local fork of Mainnet

In order to successfully fork the mainnet, `ALCHEMY_API` must be set to a valid URL in the `.env` file.
```
ALCHEMY_API="https://eth-mainnet.alchemyapi.io/v2/XXXXXXXXXXXX"
```

```bash
$ npm run fork
```
You can connect to this RPC server via `http://localhost:8545` with chain ID of 1.

### Deploying contracts to Ropsten

In order to successfully deploy to Ropsten, `ALCHEMY_API_ROPSTEN` must be set to a valid URL in the `.env` file.
MNEMONIC_TEST_ACCOUNT must be set and the accounts must have some rEth for successful deployments.
```
ALCHEMY_API="https://eth-ropsten.alchemyapi.io/v2/XXXXXXXXXXXX"
MNEMONIC_TEST_ACCOUNT="seed phrase"
```

