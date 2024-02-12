# MyToken

## Description
This is a simple token contract written in Solidity. The contract includes basic token functionalities such as minting and burning tokens.

## Features
1. **Token Details**: The contract has public variables that store the details about the token - Token Name (`META`), Token Abbreviation (`MTA`), and Total Supply (initially `0`).
2. **Balances**: The contract maintains a mapping of addresses to their respective balances.
3. **Mint Function**: The contract includes a `mint` function that takes an address and a value as parameters. This function increases the total supply by the specified value and increases the balance of the provided address by the same amount.
4. **Burn Function**: The contract also includes a `burn` function that works opposite to the `mint` function. It takes an address and a value as parameters. This function deducts the specified value from the total supply and from the balance of the provided address, provided the balance of the address is greater than or equal to the amount to be burned.

## Usage
To mint tokens, call the `mint` function with the recipient's address and the amount to be minted. To burn tokens, call the `burn` function with the address and the amount to be burned.

