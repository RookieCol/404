# ERC404 NFT Marketplace Boilerplate

This repository contains a boilerplate for creating an NFT marketplace using Hardhat for smart contract development and a React frontend setup with Vite.

## Project Structure
```
contracts/
    Interface/
        IDN404.sol
    NFTMarketplace.sol
    Token.sol
    lib/
        N404.sol
frontend/
scripts/
    deployMarketplace.ts
    deployToken.ts
test/
    testMarketplace.ts
```

## Scripts

The following scripts are configured in `package.json` for convenience:

- `compile`: Compiles the smart contracts using Hardhat.
- `test`: Runs the tests for the smart contracts.
- `deploy:marketplace`: Deploys the marketplace contract to a specified network.
- `deploy:token`: Deploys the token contract to a specified network.
- `front`: Runs the React frontend development server.


