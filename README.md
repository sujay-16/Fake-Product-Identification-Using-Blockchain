Fake Product Identification using Blockchain
Overview

This project is a decentralized application (DApp) that detects and prevents counterfeit products using blockchain technology. It ensures product authenticity by storing product details on a blockchain, making them immutable and verifiable.

Users can:

Register products on the blockchain
Verify product authenticity
Track ownership and product details securely
Tech Stack
Blockchain Framework: Truffle
Local Blockchain: Ganache
Smart Contracts: Solidity
Frontend: HTML, CSS, JavaScript
Web3 Integration: Web3.js
Wallet: MetaMask
Prerequisites

Make sure you have the following installed:

Node.js (Recommended: v14–18)
npm
Truffle
Ganache
MetaMask Extension
Chromium-based browser (Chrome recommended)
Installation & Setup
1. Clone the Repository
git clone https://github.com/sujay-16/Fake-Product-identification-using-blockchain.git
cd Fake-Product-identification-using-blockchain
2. Install Dependencies
npm install
Running the Project
Step 1: Start Ganache
Open Ganache
Create a new workspace
Add truffle-config.js
Ensure:
Port: 7545
Network ID: 5777
Step 2: Configure MetaMask
Open MetaMask
Add a new network:
Network Name: Ganache Local
RPC URL: http://127.0.0.1:7545
Chain ID: 1337
Import an account using a private key from Ganache
Step 3: Compile Smart Contracts
truffle compile
Step 4: Deploy Contracts
truffle migrate
Step 5: Run the Application
npm run dev
Open browser at: http://localhost:3000
Connect MetaMask to the application
Features
Product registration on blockchain
Tamper-proof data storage
Product authenticity verification
Decentralized trust mechanism
Project Structure
├── contracts/        # Solidity smart contracts
├── migrations/       # Deployment scripts
├── src/              # Frontend files
├── test/             # Test cases
├── truffle-config.js # Truffle configuration
Notes
Make sure Ganache is running before deploying contracts
MetaMask must be connected to the same network
Do not use mainnet or real funds for testing
Future Improvements
QR code integration for product scanning
Mobile app support
Integration with supply chain systems
Enhanced UI/UX
License

This project is for educational purposes. You can modify and use it as needed.
