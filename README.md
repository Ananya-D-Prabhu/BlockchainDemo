# <h1> ⛓️Blockchain Demo🔗 </h1>
Interactive Blockchain Demo: An interactive, educational web application that demonstrates how blockchain technology works. Learn about proof-of-work mining, transactions, consensus mechanisms, and distributed ledgers through hands-on exploration.

<br><br>

# 🌟 Features
## ⛓️‍💥Core Blockchain Functionality
⛏️ Proof-of-Work Mining - Real cryptographic hash calculations with adjustable difficulty

🔐 SHA-256 Hashing - Each block secured with cryptographic hashing

🔗 Immutable Chain - Blocks linked together through previous hash references

✅ Chain Validation - Automatic verification of blockchain integrity

⏱️ Timestamps - Each block records its creation time

<br><br>

## 🛜 Network & Peers
👥 Multi-Peer System - Each peer maintains their own independent blockchain

💰 Individual Balances - Calculated from complete transaction history

🔄 Consensus Mechanism - Longest chain rule for network synchronization

🌐 Decentralized Network - Simulate a distributed blockchain network

<br><br>

## 📩 Transaction Management
💸 Send Transactions - Transfer coins between peers

📋 Transaction Pool - Pending transactions waiting to be mined

💵 Transaction Fees - Incentivize miners with fees

📊 Transaction History - View all transactions in each block

<br><br>

## 🤓 User Experience
🎓 Interactive Tutorial - 6-step guided learning experience

🎨 Modern UI - Beautiful gradients and smooth animations

📱 Responsive Design - Works on desktop and mobile devices

⌨️ Keyboard Shortcuts - Quick actions for power users

🔍 Block Explorer - View complete blockchain for any peer

<br><br>

## 🚀 Live Demo
<a href="https://ananya-d-prabhu.github.io/BlockchainDemo/">View Blockchain Demo</a>

<br><br>

## 🎯 Learning Objectives
This demo helps you understand:

How blocks are created - Through proof-of-work mining

How transactions work - From pending pool to confirmed blocks

How chains are validated - Cryptographic hash verification

How consensus works - Longest chain rule

How mining incentivizes - Rewards and transaction fees

How decentralization works - Multiple independent peers

<br><br>

## 🛠️ Technologies Used
HTML5 - Structure and content

CSS3 - Styling with modern gradients and animations

Vanilla JavaScript - No frameworks, pure blockchain implementation

Font Awesome - Icons for beautiful UI

<br><br>

## 📋 Prerequisites
No installation required! This is a pure client-side application that runs entirely in your browser.

Any modern web browser (Chrome, Firefox, Safari, Edge)

No backend server needed

No dependencies or npm packages

<br><br>

## 🏃 Quick Start
Download and Run Locally

Clone the repository

bash   git clone https://github.com/Ananya-D-Prabhu/BlockchainDemo.git
   cd blockchain-demo

Open in browser

bash   # Simply open index.html in your browser
   open index.html  # macOS
   start index.html # Windows
   xdg-open index.html # Linux

<br><br>

## 🎮 How to Use
Getting Started

Click "Start Interactive Demo" to begin the tutorial
Follow the step-by-step guide shown at the top
Use navigation buttons to move between tutorial steps

Basic Operations
Mining Blocks

Click "Mine New Block" to solve proof-of-work puzzle
Watch as the nonce increments to find valid hash
Earn 100 coins as mining reward

Sending Transactions

Select a recipient from the dropdown
Enter amount and transaction fee
Click "Send Payment"
Transaction goes to pending pool
Mine a block to confirm transaction

Managing Peers

Click on peer cards to switch between different peers
View their blockchain using the chain icon
Sync chains to adopt the longest valid chain
Add new peers with the "Add Peer" button

<br><br>

## ⌨️ Keyboard Shortcuts
Ctrl + Enter - Mine a new block

Ctrl + N - Next tutorial step

Ctrl + P - Previous tutorial step

Escape - Close modal windows

<br><br>

## 🧪 Understanding the Code
Block Class
Represents a single block in the blockchain:

Calculates cryptographic hash
Implements proof-of-work mining
Stores transactions and metadata

Blockchain Class
Manages the entire chain:

Creates genesis block
Validates chain integrity
Handles pending transactions
Implements consensus rules

Peer Class
Represents network participants:

Maintains own blockchain
Calculates balance from transactions
Can sync with other peers
