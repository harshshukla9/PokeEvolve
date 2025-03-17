# Pokémon NFT Game

A blockchain-based Pokémon-inspired NFT game where players can collect, evolve, and battle with Pokémon NFTs on the Core blockchain.

![Pokémon NFT Game Banner]![Screenshot from 2025-03-18 02-45-37](https://github.com/user-attachments/assets/44301383-8f9a-4146-8ef8-c35b752791af)


## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Smart Contracts](#smart-contracts)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Game Mechanics](#game-mechanics)
- [Screenshots](#screenshots)
- [Demo](#demo)
- [Future Development](#future-development)
- [License](#license)

## 🌟 Overview

This project brings the nostalgic world of Pokémon to the blockchain through NFTs. Players can collect unique Pokémon, evolve them to stronger forms, and will soon be able to battle with other players. Built on Core testnet with a Next.js frontend, the game provides an interactive and engaging experience for both crypto enthusiasts and Pokémon fans.

## ✨ Features

- **NFT Collection**: Mint and collect unique Pokémon as NFTs
- **Collection Gallery**: Browse your Pokémon with detailed stat displays
- **Evolution System**: Evolve your Pokémon to stronger forms
- **Stats View**: See detailed attributes of your Pokémon with visual stat bars
- **Battle Arena** (Coming Soon): Battle with other trainers for NFT stakes

## 🛠️ Tech Stack

### Frontend
- **Framework**: Next.js
- **UI Components**: shadcn/ui components
- **Styling**: Tailwind CSS
- **Web3 Integration**: Thirdweb SDK

### Backend
- **Blockchain**: Core Testnet
- **Smart Contract**: ERC-1155 based Pokémon NFT contract
- **Contract Development**: Solidity

## 📝 Smart Contracts

Our smart contract is deployed on the Core Testnet. It implements:

- ERC-1155 standard for batch NFT management
- Evolution mechanics
- Battle mechanics (upcoming)
- Claim functionality

**Contract Address**: `[0x498246853BEBd1d029B6E35a0f6CCB8Ec428410B]`

## 🚀 Getting Started

### Prerequisites

- Node.js v16+ 
- npm or yarn
- MetaMask or another Web3 wallet

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/pokemon-nft-game.git
cd pokemon-nft-game
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Create a `.env.local` file in the project root:
```
NEXT_PUBLIC_THIRDWEB_CLIENT_ID=[Your Thirdweb Client ID]
NEXT_PUBLIC_CONTRACT_ADDRESS=[Your Contract Address]
```

4. Run the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## 📁 Project Structure

```
pokemon-nft-game/
├── app/                    # Next.js app directory
│   ├── page.tsx            # Home page
│   ├── battle/             # Battle arena (coming soon)
│   └── collection/         # NFT collection view
├── components/             # UI components
│   └── ui/                 # shadcn/ui components
├── client.ts               # Thirdweb client configuration
├── public/                 # Static assets
└── ...
```

## 🎮 Game Mechanics

### Collection

Players can mint or purchase Pokémon NFTs. Each Pokémon comes with its own unique attributes:
- HP
- Attack
- Defence
- Special Attack
- Special Defence
- Speed
- Total

### Evolution

Certain Pokémon can evolve into stronger forms. The evolution process:
1. Select an eligible Pokémon
2. Click the "Evolve" button
3. Confirm the transaction
4. Once processed, your Pokémon will evolve!

Not all Pokémon can evolve - specific ID numbers are eligible for evolution.

### Battle Arena (Coming Soon)

The upcoming battle feature will allow players to:
1. Select 3 Pokémon from their collection
2. Enter the battle arena to be matched with opponents
3. Battle based on Pokémon attributes
4. Winners receive one random NFT from the opponent's team
5. Losers transfer one random NFT to the opponent

**⚠️ High Stakes Gameplay**: Choose your battle team wisely!

## 📸 Screenshots

### Collection Page
![Collection Page]
![Screenshot from 2025-03-18 02-45-45](https://github.com/user-attachments/assets/1e1c124b-2c40-4b61-bd5e-b96cc7ef568c)
![Screenshot from 2025-03-18 02-46-02](https://github.com/user-attachments/assets/10afe0b0-ab26-4997-9f4a-7cb56e0c29fd)
![Screenshot from 2025-03-18 02-46-07](https://github.com/user-attachments/assets/b502c903-3d08-40fb-89ba-fdac40b6d730)
![Screenshot from 2025-03-18 02-46-14](https://github.com/user-attachments/assets/8505fd9f-5583-4733-b060-9c51af03c514)
![Screenshot from 2025-03-18 02-46-20](https://github.com/user-attachments/assets/7a243260-8cd5-4092-bbf2-d4af2e8f59d0)
![Screenshot from 2025-03-18 02-46-32](https://github.com/user-attachments/assets/47e66aa7-5630-4cac-9c67-cd6979d1e860)
![Screenshot from 2025-03-18 02-46-43](https://github.com/user-attachments/assets/b88b42f3-b6cd-4abd-9c65-4a466f438f46)
![Screenshot from 2025-03-18 02-46-49](https://github.com/user-attachments/assets/212d205b-3a78-47d3-b1f3-d915539eeabe)
![Screenshot from 2025-03-18 02-46-56](https://github.com/user-attachments/assets/f439d6e0-c2f6-47bb-92af-c3c32064e8e2)
![Screenshot from 2025-03-18 02-47-04](https://github.com/user-attachments/assets/f852a309-3387-4f3d-a0e6-8546c3c20c8c)





### Battle Arena (Coming Soon)
![Battle Arena](https://placeholder-for-battle-screenshot.png)
![Screenshot from 2025-03-18 02-47-04](https://github.com/user-attachments/assets/13459289-f248-4c4c-9a6f-c63a0f2035e0)


## 🎥 Demo

Check out our demo video to see the game in action:

https://youtu.be/T5gkbzAaNAk

## 🔮 Future Development

- **Battle System**: Complete implementation of the battle mechanics
- **Marketplace**: Buy/sell/trade Pokémon with other players
- **Training**: Improve your Pokémon's stats through training
- **Tournaments**: Weekly competitions with special rewards
- **Mobile App**: Native mobile experience

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Connect With Us

[Add your social media or contact information here]

## Acknowledgements

- Pokémon is a trademark of Nintendo/Game Freak
- This is a fan project and not affiliated with the official Pokémon franchise
- Thanks to the Core blockchain team and Thirdweb for their developer tools
