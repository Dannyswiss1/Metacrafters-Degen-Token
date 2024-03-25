# Degen Token Contract

## Description
This Solidity smart contract implements the Degen Token (DGN), an ERC-20 compliant token with additional functionalities for minting, burning, transferring, and redeeming tokens for specific items. The contract also inherits functionalities from OpenZeppelin's ERC20, Ownable, and ERC20Burnable contracts.

## Contract Details
- **Name:** Degen Token
- **Symbol:** DGN
- **Decimals:** 0

## Key Features
1. **Minting:** The contract owner can mint new Degen tokens and distribute them to specified addresses.
2. **Burning:** Token holders can burn their Degen tokens, reducing the total supply.
3. **Transferring Tokens:** Token holders can transfer tokens to other addresses.
4. **Redeeming Tokens:** Token holders can redeem tokens for specific items, including Official Degen NFTs, Degen T-Shirts, and OG status in the Degen Discord.
5. **View Store Items:** Users can view available items for purchase.

## Usage
- **Mint Tokens:** Use the `mint` function to create new Degen tokens.
- **Transfer Tokens:** Use the `transferTokens` function to transfer tokens to other addresses.
- **Burn Tokens:** Use the `burnTokens` function to burn Degen tokens.
- **Redeem Tokens:** Use the `redeemTokens` function to redeem tokens for specific items.

## Requirements
- Solidity Compiler 0.8.20
- OpenZeppelin Contracts v4.3.0

