# ConcertTicketPro
This is a README profile for a ticketing system project built using Web3 and smart contracts. The goal of this project is to create a `decentralized ticketing system` that allows event organisers to create and sell unique NFT ticketstickets securely and transparently. The NFT tickets are non-transferable and tied to the purchaser's wallet address, ensuring secure ownership and preventing fraud.
## Usage
1. Start the frontend development server: ``npm start``
2. Open your web browser and access the ticketing system at http://localhost:3000
3. If MetaMask is not installed, please install it before proceeding.
4. Connect MetaMask to your Ethereum account.
5. You will see a`Connect` button on the ticketing system page. Click it to connect your Ethereum account.
6. Once connected, you can execute the contract functions through the ticketing system interface.
## Feature
- `mintNFT()`: Allows users to mint NFTs by paying the specified price. It checks if the maximum number of NFTs has been reached, ensures that the user hasn't already minted an NFT, and verifies that the payment is sufficient. The function mints the NFT, assigns it to the user, sets the token URI, and increments the token ID.
- `withdraw()`: Allows the contract owner to withdraw the contract balance. The function transfers the contract's balance to the owner's address.
- `transferOwnership(address newOwner)`: Overrides the transferOwnership function from the Ownable contract to prevent ownership transfer.
- `transferFrom(address from, address to, uint256 tokenId)`: Overrides the transferFrom function from the ERC721 contract to prevent token transfers.


## Web3.js
The frontend of the ticketing system is built using React and Moralis, a Web3 development platform. The frontend code is located in the app.js and index.js files.
- app.js: Initializes the MoralisProvider for connecting to MetaMask.
- index.js: Handles MetaMask connection status, enabling Web3, and executing contract functions.
## Smart Contract
The NFT ticketing system smart contract is implemented using Solidity and OpenZeppelin libraries. The contract code is located in the MyNFT.sol file. Requirements:
- Solidity ^0.8.25
- OpenZeppelin Contracts: ERC721URIStorage, Counters, Ownable

## Smart Contract Function
- mintNFT: Allows users to mint NFTs by paying the specified price.
- setMaxNFTs: Sets the maximum number of NFTs that can be minted.
- withdraw: Allows the contract owner to withdraw the contract balance.
- refund: Allows the contract owner to refund NFTs to users.
- transferOwnership: Overrides the transferOwnership function to restrict ownership transfer.

To deploy and interact with the contract, follow these steps:
## Get Started
1. Deploy the contract on the Ethereum blockchain using a tool like Remix or Truffle.
2. Install the required dependencies for the frontend application.
3. Update the contract address and function details in the frontend code.
4. Run the frontend application and connect your MetaMask wallet.
## License
The NFT ticketing system project is licensed under the MIT License.
## User Interface
Please click in the link for our application user interface
https://app.uizard.io/prototypes/0jPxbWPzX5HLljqgeYYo/player/fullscreen
