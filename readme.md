![2048 Banner](https://ibb.co.com/qMRRB0Wj)

# 2048
A Web3 3D puzzle game built with Unity and integrated with BNB Smart Chain (BSC) via Idos Games SDK. Players merge cubes, strategize moves, and earn on-chain rewards.

Unlike the classic 2D version, here you will play with 3D cubes, which adds an extra layer of challenge and interest. 

The goal is to move cubes in 3D space, merging identical ones to form higher value cubes. A merge is possible only when cubes are next to each other. Each turn the player can move a cube into one of the free positions on the field. If no valid moves remain, the game ends.

---

## Technology Stack
- **Blockchain:** BNB Smart Chain 
- **Smart Contracts:** Solidity ^0.8.2+  
- **Game Client:** Unity (C#)  
- **Game SDK:** Idos Games Engine SDK (authentication, server functions, Web3 integration)  
- **Backend:** Node.js + Idos API  
- **Development Tools:** Unity 6.2, Unity C#, OpenZeppelin libraries  

---

## Supported Networks
- **BNB Smart Chain Mainnet** (Chain ID: 56)  

---

## Contract Addresses

| Network     | Token Contract ($ASTD)                     | Platform Pool Contract                       | Notes            |
|-------------|--------------------------------------------|----------------------------------------------|------------------|
| BNB Mainnet | `0xe89BAc897D64eE75b298782850e224A97664da14` | `0xe3E1c58CDb6A681001b98C41b4F0334CDdd7C44a` | Live deployment  |

---

## Features
- 🔗 **Idos Games SDK** – seamless wallet login, server-side verification, and blockchain sync  
- 🎮 **Unity Gameplay** – fast-paced space shooter with tournaments and leaderboards  
- 🪐 **On-Chain Rewards** – play-to-earn mechanics using $2048 token. Players are able to deposit/withdraw native token and NFT's (nfts not deployed yet)

---

## Notes

This repository mainly contains the **core game files** and the **IDOS Games SDK**, which provides the backend and all blockchain-related functions on **BNB Chain**.

🔗 IDOS Games SDK Repository: [IDOS Games SDK](https://github.com/iDos-Games/iDos-Games-Engine-Unity-SDK)  

### Proof of Deployment on BNB Chain
- Token Contract: [`0xe89BAc897D64eE75b298782850e224A97664da14`](https://bscscan.com/token/0x16AcFCD79FFbafE8da1848962C886FC168D4F821)  
- Platform Pool Contract: [`0xe3E1c58CDb6A681001b98C41b4F0334CDdd7C44a`](https://bscscan.com/address/0xe3E1c58CDb6A681001b98C41b4F0334CDdd7C44a)
- Game web page (built-in token buy/sell (BSC chain) directly on the website) (https://idosgames.com/en/app/?id=XD839K7Z)
