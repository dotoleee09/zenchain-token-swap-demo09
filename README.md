# ZenChain Token Swap Demo
A decentralized application (dApp) demonstrating cross-chain token swaps between ZenChain and Ethereum testnets, leveraging ZenChain’s EVM compatibility and interoperability.

## Features
- Connect to MetaMask for wallet integration.
- Swap `ZENToken` (ZenChain) for an Ethereum-based token.
- View transaction history.
- Responsive React-based frontend.

## Prerequisites
- Node.js (v16+)
- MetaMask browser extension
- ZenChain testnet RPC endpoint (see [ZenChain Docs](https://docs.zenchain.io))
- Ethereum Sepolia testnet RPC endpoint

## Installation
```bash
git clone https://github.com/your-username/zenchain-token-swap-demo.git
cd zenchain-token-swap-demo
npm install
npx hardhat compile
npx hardhat run scripts/deploy.js --network zenchain
npm start
