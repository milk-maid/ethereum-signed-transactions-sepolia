# Ethereum Signed Transactions on Sepolia using Alchemy SDK

This project demonstrates how to send a signed Ethereum transaction on the Sepolia testnet using the Alchemy SDK and Node.js.

## Setup Instructions

### Prerequisites

- Node.js installed
- Alchemy account for the API key
- A Sepolia testnet wallet with some ETH

### Steps

1. Clone the repository:

```bash
git clone https://github.com/yourusername/ethereum-signed-transactions-sepolia.git
cd ethereum-signed-transactions-sepolia
```

#### Install dependencies

```bash
npm install
```

#### Configure environment variables

```bash
Rename .env.example to .env
```

_Fill in the TEST_PRIVATE_KEY and TEST_API_KEY in the .env file with your actual keys._

#### Run the script

```bash
node index.js
```

### Output

You will receive a link to the Sepolia Etherscan for the signed transaction in your terminal