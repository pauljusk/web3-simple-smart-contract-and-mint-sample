# A simple examle of smart contract deployment and mint

## Intructions

To set up the back-end follow the next steps:

```bash
# install dependencies
npm install
```

Update env variables with information from metamask and aclchemy.
Start the server locally:

```bash
# compile and deploy smart contract
npx hardhat compile
npx hardhat --network goerli run scripts/deploy.js

# mint smart contract
node scripts/mint-nft.js
```