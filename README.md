# MyToken Smart Contract
This project is a straightforward ERC20-like token smart contract developed in Solidity. The contract includes features for minting and burning tokens, with updates to the total supply and individual balances.

## Features:
- Public variables to store token details (name, abbreviation, total supply)
- Mapping to track balances
- Mint function to create new tokens
- Burn function to destroy tokens, with balance checks


## Functions:
mint:
- Allows the creation of new tokens.
 Parameters:
 - _to: Address to receive the newly minted tokens
 - _value: Number of tokens to be minted
  
burn:
- Enables the destruction of tokens.
Parameters:
 - _from: Address from which tokens will be burned
 - _value: Number of tokens to be burned

## Conditions:
Ensures the _from address has sufficient balance to burn the specified amount

## Usage:

- Deploy the contract to an Ethereum network.
- Use the mint function to generate new tokens.
- Use the burn function to destroy tokens, ensuring the address has enough balance.


