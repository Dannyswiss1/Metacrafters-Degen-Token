# Degen Token Contract

## Description
This Solidity smart contract implements the Degen Token (DGN), an ERC-20 compliant token with additional functionalities for minting, burning, transferring, and redeeming tokens for specific items. The contract also inherits functionalities from OpenZeppelin's ERC20, Ownable, and ERC20Burnable contracts.

## Deployment Address
  0x50385d3fCe37B829ed0872a827d0df5BDE5B7ad7

## Snapshots
![Screenshot from 2024-03-26 23-33-01](https://github.com/Dannyswiss1/Metacrafters-Degen-Token/assets/137540755/68434b32-8cb2-4fe6-be9e-4a2e2870950a)

![Screenshot from 2024-03-26 23-33-22](https://github.com/Dannyswiss1/Metacrafters-Degen-Token/assets/137540755/31d30430-7d53-4535-ad83-9cd334b136ab)


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

