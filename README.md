# Basic Sample NFT Marketplace Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

# Features

Full stack NFT marketplace on Ethereum with Solidity, Polygon, IPFS, Next.js, Ethers.js, and Hardhat. User can create a NFT, list it on Marketplace and sell it.

## To run this project locally, follow these steps.

Clone the project locally, change into the directory, and install the dependencies:

### install using NPM
npm install

### Start the local Hardhat node
npx hardhat node

### With the network running, deploy the contracts to the local network in a separate terminal window
npx hardhat run scripts/deploy.js --network localhost

### Start the app

npm run dev
