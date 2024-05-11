# ConcertTicketPro
This is a README profile for a ticketing system project built using Web3 and smart contracts. The goal of this project is to create a `decentralized ticketing system` that allows users to purchase, sell, and verify tickets securely and transparently.
## Usage
Concert and event organisers are able to utilize our ticketing system
- All tickets include private information such as private
## Feature
- Mint NFT: Users can mint NFTs by paying the specified price as set by the contract owner.
Set Maximum NFTs: The contract owner can set the maximum number of NFTs that can be minted.
- Withdraw: The contract owner can withdraw the contract balance.
- Refund NFTs: The contract owner can refund NFTs to users, transferring the refund amount and burning the NFTs.
- Frondend application: The frontend application interacts with the contract functions by connecting to MetaMask. Users can connect their MetaMask wallet to the application and execute contract functions such as minting NFTs and refunding NFTs.
## Web3.js
## Smart Contract Function
- mintNFT: Allows users to mint NFTs by paying the specified price.
- setMaxNFTs: Sets the maximum number of NFTs that can be minted.
- withdraw: Allows the contract owner to withdraw the contract balance.
- refund: Allows the contract owner to refund NFTs to users.
- transferOwnership: Overrides the transferOwnership function to restrict ownership transfer.
- Frontend Components
- app.js: Initializes the MoralisProvider for connecting to MetaMask.
- index.js: Handles MetaMask connection status, enabling Web3, and executing contract functions.
Getting Started
To deploy and interact with the contract, follow these steps:
## Get Started
Deploy the contract on the Ethereum blockchain using a tool like Remix or Truffle.
Install the required dependencies for the frontend application.
Update the contract address and function details in the frontend code.
Run the frontend application and connect your MetaMask wallet.

