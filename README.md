# Eth-Avax-Module2
This Solidity smart contract, named "Assessment", implements a basic financial system allowing a designated owner to manage deposits and withdrawals of funds.

## Features

- `constructor(uint initBalance)`: Initializes the contract with an initial balance specified during deployment.
- `getBalance()`: Retrieves the current balance of the contract.
- `deposit(uint256 _amount)`: Allows the contract owner to deposit funds into the contract.
- `withdraw(uint256 _withdrawAmount)`: Allows the contract owner to withdraw funds from the contract, provided the balance is sufficient.
- `divide(uint a, uint b)`: Performs integer division of two input numbers.
- `modulo(uint a, uint b)`: Computes the remainder of the division between two input numbers.
- `increment(uint a)`: Increments the input number by 1.
- `decrement(uint b)`: Decrements the input number by 1.

## Prerequisites

- Solidity version 0.8.26 or compatible.
- Ethereum development environment (e.g., Remix, Truffle, Hardhat) for deployment and interaction.

## Usage

1. Deploy the smart contract, providing an initial balance.
2. As the contract owner, you can interact with the contract using the following functions:
   - Use `deposit` to add funds to the contract.
   - Use `withdraw` to withdraw funds, ensuring the contract has sufficient balance.
   - Utilize the mathematical functions for various calculations.

## Notes

- Make sure to keep your contract secure and protected from unauthorized access.
- This smart contract is provided under the "UNLICENSED" SPDX-License-Identifier, meaning it is not licensed for public use.



# Starter Next/Hardhat Project

After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/
