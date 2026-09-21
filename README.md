# Web3 Crowdfunding Platform

A decentralized crowdfunding application that allows users to create fundraising campaigns and contribute funds directly through the blockchain.

The project explores how **Web3, blockchain, and Solidity smart contracts** can be used to create a transparent crowdfunding experience without relying entirely on a traditional centralized payment system.

## Overview

Traditional crowdfunding platforms typically rely on centralized servers to manage campaigns, contributions, and transactions.

This project uses blockchain technology to move key parts of that process onto a **smart contract**, allowing campaign data and transactions to be recorded on-chain.

Users can:

* Create crowdfunding campaigns
* Set fundraising goals and deadlines
* Browse active campaigns
* Contribute cryptocurrency to campaigns
* Track campaign progress
* Interact with the blockchain through their connected wallet

## Key Features

### Create Campaigns

Users can create a campaign by providing information such as:

* Campaign title
* Description
* Funding goal
* Deadline
* Campaign image

The campaign is registered through the smart contract and becomes available for other users to discover.

### Contribute to Campaigns

Users can connect their Web3 wallet and contribute funds directly to a campaign.

Transactions are processed through the blockchain rather than a traditional centralized payment flow.

### Campaign Progress

Each campaign displays its current fundraising progress, allowing contributors to see how much has been raised relative to the campaign's goal.

### Wallet Integration

The application connects to users' Web3 wallets to authenticate transactions and allow them to interact with the deployed smart contract.

## Tech Stack

### Frontend

* React
* JavaScript
* Vite

### Web3

* thirdweb
* Ethereum / EVM-compatible blockchain
* Solidity
* Smart Contracts

### Development

* npm
* Git

## How It Works

The application consists of a React frontend that communicates with a Solidity smart contract deployed on the blockchain.

```text
User
  ↓
React Frontend
  ↓
Web3 Wallet
  ↓
Smart Contract
  ↓
Blockchain
```

When a user creates a campaign or contributes to one, the frontend initiates a blockchain transaction through the connected wallet. The smart contract then handles the relevant transaction and campaign logic.

## Smart Contract Concepts

The project demonstrates several fundamental blockchain concepts, including:

* Smart contract development with Solidity
* Contract deployment
* Reading data from a blockchain
* Sending transactions through a Web3 wallet
* Managing campaign state on-chain
* Cryptocurrency-based contributions
* Blockchain transaction confirmation

## Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js
* npm
* A Web3-compatible browser wallet such as MetaMask

### Installation

Clone the repository:

```bash
git clone <your-repository-url>
```

Navigate to the project directory:

```bash
cd <project-directory>
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The application will be available at the local development URL provided by Vite.

## Environment Configuration

If the project requires environment variables, create a `.env` file in the project root and add the required configuration.

```env
VITE_THIRDWEB_CLIENT_ID=your_client_id
```

Do not commit private keys, wallet credentials, or other sensitive information to the repository.

## Deployment

The frontend can be built for production using:

```bash
npm run build
```

The generated application can then be deployed using a hosting platform or IPFS.

For Web3 functionality, the deployed frontend must be configured to interact with the appropriate deployed smart contract and blockchain network.



## What I Learned

This project provided hands-on experience with:

* Building a React application with Vite
* Integrating Web3 functionality into a frontend application
* Working with Solidity smart contracts
* Connecting a frontend to blockchain networks
* Handling wallet-based transactions
* Reading and updating blockchain state
* Designing user flows around asynchronous blockchain transactions

## Future Improvements

Potential improvements include:

* Campaign categories and search
* Campaign creator dashboards
* Donation history
* Transaction status and notifications
* Campaign ownership and management
* Improved error handling for failed transactions
* Support for additional blockchain networks
* More comprehensive smart contract testing

## Disclaimer

This project was created for educational and portfolio purposes to explore Web3 crowdfunding and blockchain-based application development. It is not intended to be used for handling real-world fundraising without appropriate security audits and additional safeguards.

```
```
