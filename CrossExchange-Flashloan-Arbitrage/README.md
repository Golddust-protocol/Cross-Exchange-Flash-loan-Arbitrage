## Cross Exchange Arbitrage with Uniswap and Sushiswap using Hardhat

---

### Introduction

This repository contains a Solidity smart contract that facilitates cross-exchange arbitrage between Uniswap and Sushiswap decentralized exchanges (DEXs). The contract leverages the Hardhat framework for development and testing.

---

### Features

- Executes arbitrage between Uniswap and Sushiswap DEXs
- Utilizes Hardhat for smart contract development and testing

---

### Setup

Follow the steps below to set up and test the cross-exchange arbitrage contract:

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/{whoever and whereever}
   ```

2. Navigate to the project directory:

   ```
   cd Uniswap-Sushiswap-Cross-Exchange-Arbitrage
   ```

3. Install dependencies:
   ```
   npm install
   ```

---

### Usage

#### Compile the Smart Contract

Compile the Solidity smart contract using Hardhat:

```
npx hardhat compile
```

#### Run Tests

Execute the automated tests to ensure the correctness of the smart contract:

```
npx hardhat test
```

#### Deploy the Contract

Deploy the compiled smart contract to your desired network:

```
npx hardhat run scripts/deploy.js --network <network_name>
```

Replace `<network_name>` with the target Ethereum network (e.g., `rinkeby`, `mainnet`, etc.).

#### Interact with the Contract

After deploying the contract, interact with it using your preferred Ethereum wallet or through the Hardhat console.

---

### Dependencies

- Solidity - [Solidity Documentation](https://docs.soliditylang.org/)
- Hardhat - [Hardhat Documentation](https://hardhat.org/)
- Ethereum - [Ethereum Documentation](https://ethereum.org/)

---

### Contributors

- [Your Name]
- [Pavan Ananth Sharma](https://github.com/PavanAnanthSharma)
- [SabariGanesh-K](https://github.com/SabariGanesh-K)

---

### License

This project is licensed under the [MIT License](LICENSE).

---
