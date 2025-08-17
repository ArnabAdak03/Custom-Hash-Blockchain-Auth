# Custom Hash Blockchain Authentication (XDC Apothem)

This project demonstrates a decentralized authentication system using:
- A **custom cryptographic hash function**
- **Solidity smart contracts** (Remix + Hardhat)
- Deployment on **XDC Apothem Testnet**
- **MetaMask** for user verification
- A **React DApp frontend** for interaction

## 🚀 Features
- Custom hash integration (Python + JS)
- Secure authentication via smart contract
- Security attack testing (reentrancy, replay, gas)
- Local deployment with Hardhat
- Public deployment on Apothem testnet

## ⚙️ Setup Guide
```bash
# Install dependencies
npm install

# Compile contracts
npx hardhat compile

# Start local node
npx hardhat node

# Deploy contract
npx hardhat run scripts/deploy.js --network localhost
