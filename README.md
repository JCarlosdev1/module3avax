
# myToken Smart Contract

## Overview

This is a Solidity smart contract named `myToken` that implements an ERC20 token with additional functionalities like minting, burning, and ownership management. It extends the OpenZeppelin ERC20, ERC20Burnable, and Ownable contracts to leverage their existing functionalities.

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.

## Prerequisites

- [Solidity](https://docs.soliditylang.org/en/latest/)
- [OpenZeppelin Contracts](https://docs.openzeppelin.com/contracts/4.x/)

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd myToken
   ```

## Usage

1. Deploy the contract to your preferred Ethereum network.
2. Interact with the deployed contract using a tool like [Remix](https://remix.ethereum.org/) or your preferred Ethereum development environment.

## Contract Details

- **Name:** myToken
- **Version:** 1.0.0
- **Solidity Version:** ^0.8.0
- **License:** MIT

## Functions

### `constructor(string memory name, string memory symbol, uint256 initialSupply)`

- **Description:** Constructor to initialize the ERC20 token with a given name, symbol, and initial supply.
- **Parameters:**
  - `name` (string): The name of the token.
  - `symbol` (string): The symbol of the token.
  - `initialSupply` (uint256): The initial supply of tokens.

### `mint(address account, uint256 amount)`

- **Description:** Mints new tokens and assigns them to the specified account.
- **Parameters:**
  - `account` (address): The address to which tokens will be minted.
  - `amount` (uint256): The amount of tokens to mint.

### `burnFrom(address account, uint256 amount)`

- **Description:** Burns a specific amount of tokens from the specified account.
- **Parameters:**
  - `account` (address): The address from which tokens will be burned.
  - `amount` (uint256): The amount of tokens to burn.

### `transfer(address recipient, uint256 amount)`

- **Description:** Transfers tokens from the sender's address to the recipient's address.
- **Parameters:**
  - `recipient` (address): The address to which tokens will be transferred.
  - `amount` (uint256): The amount of tokens to transfer.

## Modifiers

### `onlyOwner`

- **Description:** Modifier to restrict access to functions only to the contract owner.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Disclaimer

This code is provided as-is, without any warranty or support. Use at your own risk.
