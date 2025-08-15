# First Cryptocurrency
ERC20 token developed in Solidity with OpenZeppelin. CriptoReal features a fixed supply of 1,000 tokens (18 decimals) and showcases best practices in the secure and efficient design of smart contracts for the Ethereum network. Ideal as a professional blockchain portfolio example.

💰 First Cryptocurrency – CriptoReal
📋 Project Overview

CriptoReal is an ERC20 token built in Solidity using OpenZeppelin, featuring a fixed supply of 1,000 tokens (18 decimals). Designed as a professional example of secure and efficient smart contract development for the Ethereum network.

✨ Key Features

💱 ERC20 Standard – Fully compliant with the ERC20 interface

🔒 Fixed Supply – 1,000 tokens minted at deployment, no further minting allowed

📦 18 Decimals – Standard precision for Ethereum-based tokens

🛡 OpenZeppelin Security – Reusable, audited code for robust security

⚡ Instant Deployment – Ready for testing, demonstration, or integration

🧠 Smart Contract Details
Constructor
constructor(string memory name_, string memory symbol_) ERC20(name_, symbol_) {
    _mint(msg.sender, 1000 * 1e18);
}


Parameters:

name_ → Token name (e.g., "CriptoReal")

symbol_ → Token symbol (e.g., "CRL")

Behavior:

Mints 1,000 tokens to the deployer’s address upon contract creation

🛠 Technologies Used

Solidity 0.8.24

OpenZeppelin ERC20

Remix IDE (Ethereum)

Remix VM (Cancún)

🚀 Deployment & Testing Steps

Open Remix IDE

Create a new file CriptoReal.sol and paste the contract code

Compile with Solidity 0.8.24

Deploy using Remix VM (Cancún) in the Deploy & Run Transactions panel

Provide token name and symbol in constructor parameters

Verify minted supply via totalSupply()

✅ Basic Testing

Check Initial Supply: totalSupply() returns 1000 * 10^18

Verify Balance: balanceOf(deployer) matches total supply

Transfer Tokens: Use transfer() to send tokens between addresses

🔮 Future Improvements

Add burn functionality for token destruction

Implement access control (e.g., Ownable) for admin-only operations

Deploy to Ethereum Testnet (Goerli, Sepolia)

Create an interactive frontend dApp in React.js

📜 License

Licensed under LGPL-3.0-only

👨‍💻 Author

Blockchain Developer: Alejandro Gómez

GitHub: Alejandro10J95

LinkedIn: Alejandro Gómez Martínez

🚀 Open to collaborations and blockchain opportunities!
