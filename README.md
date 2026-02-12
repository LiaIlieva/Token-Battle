# Multiplayer Blockchain Game  
**FastAPI · Pygame · Solidity · NFTs**

A real-time multiplayer game that combines a traditional game backend with decentralized blockchain-based asset ownership. Players connect over the internet, compete in real time, and own in-game weapons as **NFTs**, ensuring secure, transparent, and verifiable digital ownership.

This project explores how **blockchain technology can be integrated into game systems** to improve fairness, security, and trust compared to centralized architectures.

---

## 🚀 Project Overview

The game consists of:
- a **FastAPI backend** responsible for multiplayer logic and networking
- a **Pygame-based client** for real-time gameplay
- **Solidity smart contracts** that manage ownership of in-game assets (weapons)
- implemented **MetaMask authentication** for player wallet interaction

By decentralizing asset ownership, the system eliminates reliance on a central authority to validate items, reducing the risk of fraud and enabling transparent player-to-player interactions.

---

## 🧩 Key Features

- 🎮 **Real-time multiplayer gameplay**
- 🌐 **Online connectivity** via FastAPI + ngrok
- 🔐 **Blockchain-based asset ownership**
  - In-game weapons represented as NFTs
  - Ownership verified on-chain
- 🦊 **MetaMask wallet integration**
- 📜 **Smart contracts** written in Solidity
- 🧪 **Local blockchain testing** using Ganache & Brownie
- ☁️ **NFT metadata storage** via Pinata (IPFS)

---

## 🏗️ System Architecture
Pygame Client
│
│ REST / WebSocket Communication
▼
FastAPI Backend
│
│ Blockchain Interaction
▼
Smart Contracts (Solidity)
│
▼
Ganache (Local Testnet) / Polygon (Planned)


## 🔒 Why Blockchain?

Traditional multiplayer games store assets in centralized databases, making them vulnerable to:
- unauthorized modification
- duplicated items
- lack of transparency in item ownership

This project replaces centralized ownership with **decentralized smart contracts**, providing:
- provable ownership
- transparent asset transfers
- reduced trust requirements
- stronger security guarantees

---

## 🛠️ Technologies Used

- **Python**
- **FastAPI**
- **Pygame**
- **Solidity**
- **MetaMask**
- **Ganache** (local Ethereum testnet)
- **Brownie**
- **Pinata (IPFS)**
- **ngrok**

---

## ⚙️ Running the Project Locally

### Prerequisites
- Python 3.10+
- Node.js & npm
- MetaMask browser extension
- Ganache (local blockchain)
