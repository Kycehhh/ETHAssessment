# MyToken Smart Contract

A simple ERC20-like token smart contract developed in Solidity, designed for minting and burning tokens, with updates to the total supply and individual balances.

## Description

This project implements a straightforward ERC20-like token smart contract. It includes essential features for minting new tokens and burning existing ones, while updating the total supply and individual balances accordingly. This contract can be deployed on an Ethereum network and interacted with using the provided functions.

## Getting Started

### Installing

* Download the project from the repository.
* No additional modifications are required to the files/folders.

### Executing program

* Deploy the contract to an Ethereum network using a tool like Remix or Truffle.
* Interact with the contract using the provided functions.

#### Minting Tokens
1. Use the `mint` function to create new tokens.
* `_to`: Address to receive the newly minted tokens.
* `_value`: Number of tokens to be minted.

#### Burning Tokens
2. Use the `burn` function to destroy tokens.
* `_from`: Address from which tokens will be burned.
* `_value`: Number of tokens to be burned.
* Ensures the `_from` address has sufficient balance to burn the specified amount.

## Help

For any issues or common problems, ensure:
* The address used in the burn function has enough balance to burn the specified amount.
* The contract is properly deployed on the Ethereum network.

## Authors

Allen Kyle Sabilala  
[@Kycehhh](https://github.com/Kycehhh)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
