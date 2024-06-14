ICO Marketplace
This project is a simple Initial Coin Offering (ICO) marketplace developed using Solidity for smart contracts, Hardhat for deployment and testing, and React.js for the frontend. It allows users to purchase tokens with Ether during the ICO.

Features
Token Minting: Mint a specified number of tokens during deployment.
Token Purchase: Users can purchase tokens by sending Ether to the ICO contract.
Withdraw Funds: The owner can withdraw collected Ether from the ICO contract.


Setup and Installation
Prerequisites
Node.js
npm or yarn
Hardhat
MetaMask or any other Ethereum wallet
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/ico-marketplace.git
cd ico-marketplace
Install dependencies:
bash
Copy code
npm install
Compile the smart contracts:
bash
Copy code
npx hardhat compile
Deploy the smart contracts:
bash
Copy code
npx hardhat run scripts/deploy.js --network hardhat
Start the React frontend:
bash
Copy code
cd ico-frontend
npm install
npm start
Usage
Open your browser and navigate to http://localhost:3000.
Connect your Ethereum wallet (e.g., MetaMask).
View your token balance and purchase tokens by entering an amount in ETH and clicking "Buy Tokens".
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the existing code style and include appropriate tests.

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/your-feature).
Create a new Pull Request
