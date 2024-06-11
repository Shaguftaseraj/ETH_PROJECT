# Metacrafters Project: Solidity Smart Contract for "MyToken"

## Overview / Description

A token system with minting and burning features is offered by the Solidity smart contract MyToken. Public variables like balances mapping, total supply, token name and abbreviation, and so forth are included. While the burn function makes sure the sender's balance is enough for the burn operation, the mint function boosts the owner's balance by a specified amount.

## The contract includes the following key features:

@ Public Variables :

Token_name: A string representing the token's name ("Sui").

Token_Abbreviation: A string representing the token's abbreviation ("SUI").

Total_Supply: An unsigned integer representing the total supply of the tokens, initialized to 0.

@ Balances Mapping :

balances: A mapping from addresses to their respective balances, allowing tracking of token balances for each address.

@ Mint Function :

The mint function takes two parameters: owner (an address) and value (an unsigned integer).

It increases the Total_Supply by the given value.

It increases the balance of the owner address by the same value.

@ Burn Function :

The burn function also takes two parameters: sender (an address) and value (an unsigned integer).

It ensures that the sender's balance is sufficient for the burn operation using the require statement.

It decreases the Total_Supply by the specified value.

It decreases the balance of the sender address by the same value.

# Beginning

You may use Remix, an online Solidity Integrated Development Environment (IDE), to run and interact with this application. 
The steps to begin going are as follows:

# Execution Instructions

To deploy and interact with the "Sui" contract using Remix, follow these steps:

## Step-by-Step Instructions

1. Set Up Remix IDE
   
    i. Open Remix: Go to Remix IDE.
   
2. Create a New File

     i) New File: In the file explorer on the left, click the "Create New File" button (document icon with a plus sign).
   
     ii) Name the File: Enter a name like MyToken_sui.sol and press Enter.
   
3. Paste the Smart Contract Code
   
     i) Paste Code: Copy the provided MyToken Solidity code ( )and paste it into the new file MyToken_sui.sol.
