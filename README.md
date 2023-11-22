# eth avaxassessment4

ETH+AVAX Assessment 4
#Overview
This program is a ERC20 token deployed on Avalanche Fuji Testnet and written in Solidity, a programming language used for developing smart contracts on the blockchain. The contract details are listed below :

Token Name: Degen

Token Symbol: DGN

Decimals: 10

Total Supply: 0 (initialized value)

Minting new tokens: The platform should be able to create new tokens and distribute them to players as rewards. Only the owner can mint tokens.

Transferring tokens: Players should be able to transfer their tokens to others.

Redeeming tokens: Players should be able to redeem their tokens for items in the in-game store.

Checking token balance: Players should be able to check their token balance at any time.

Burning tokens: Anyone should be able to burn tokens, that they own, that are no longer needed.

# Getting Started
Functionalities
'mint' function (only owner) to mint new DGN tokens.

'storeNftAccessory' function (only owner) to add new NFT items for redemption.

'balanceOf' function to check the token balance of a specific address.

'transfer' function to send DEGEN tokens from your address to another address.

'approve' function to allow another address to spend a specific amount of DEGEN tokens on your behalf.

'transferFrom' function to transfer DEGEN tokens on behalf of another address.

'burn' function to burn DEGEN tokens.

'redeem' function to redeem DEGEN tokens for NFTs.

'symbol' you can get the abbreviation of the token's name.

'name' you can know the name of the token.

'totalSupply' you can know the total amount of tokens present.

'decimals' you can know the total amount of decimal places present.

'owner' you can know the address of the owner.

# Executing program
(1) Make sure you are connected to the Avalanche Fuji Testnet in your Metamask and have some test AVAX.

(2) To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

(3) Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension. Copy and paste the code from DegenToken.sol file into your file:

(4) To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to latest solidity version (or another compatible version), and then click on the "Compile" button.

(5) After the code is compiled, go to the "Deploy & run transactions" tab and select injected provider as the environment and connect your Metamask account with the test AVAX.

(6) Select the your contract from the dropdown menu, and then click on the "Deploy" button.

(7) Once the contract is deployed, you can interact with it by calling the mint, burn function, transfer and much more.

Author
Fhiel 
GitHub: @fhielashley
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
