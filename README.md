# React example app

This example provides a minimal setup to get [@txnlab/use-wallet-react](https://github.com/TxnLab/use-wallet/tree/v3/packages/use-wallet-react) working in a Vite React app with TypeScript.

## Project README

### Introduction
This project leverages the Algorand blockchain to build a decentralized application. The following instructions will guide you through the setup process.

### Prerequisites
Ensure you have Node.js and npm installed on your machine. This project requires the Algorand JS SDK and other dependencies listed below.

### Installation

#### Install Dependencies
First, install the Algorand JS SDK package:

```sh
npm install algosdk
```

Next, install one of the framework adapters or the standalone core library based on your project requirements:

##### For React:
```sh
npm install @txnlab/use-wallet-react
```

##### For Vue:
```sh
npm install @txnlab/use-wallet-vue
```

##### For Solid.js:
```sh
npm install @txnlab/use-wallet-solid
```

##### Core Library:
```sh
npm install @txnlab/use-wallet
```

#### Wallet-Specific Dependencies
Some wallets require additional packages. Install the corresponding packages for your wallet provider as listed below:

| Wallet Provider   | Package(s)                                             |
|-------------------|--------------------------------------------------------|
| Defly Wallet      | `@blockshake/defly-connect`                            |
| Pera Wallet       | `@perawallet/connect`                                  |
| WalletConnect     | `@walletconnect/sign-client`, `@walletconnect/modal`   |
| Lute Wallet       | `lute-connect`                                         |
| Magic             | `magic-sdk`, `@magic-ext/algorand`                     |
| Kibisis           | `@agoralabs-sh/avm-web-provider`                       |

### Example Commands
To install all required packages, run:

```sh
npm install algosdk @txnlab/use-wallet-react @blockshake/defly-connect @perawallet/connect @walletconnect/sign-client @walletconnect/modal lute-connect magic-sdk @magic-ext/algorand @agoralabs-sh/avm-web-provider
```

### Usage
After installing the dependencies, you can start using the Algorand blockchain functionalities in your project. Refer to the documentation of each package for detailed usage instructions.

### Additional Resources
- [Algorand Developer Portal](https://developer.algorand.org/)
- [Algorand JS SDK Documentation](https://github.com/algorand/js-algorand-sdk)


