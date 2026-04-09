# 🎮 Gaming Assets Smart Contract (Soroban - Stellar)

## 📌 Project Description

The **Gaming Assets Smart Contract** is a decentralized system built on **Soroban (Stellar’s smart contract platform)** that enables players to securely manage their in-game assets on-chain.

This contract acts as a **blockchain-based inventory system**, allowing players to own, transfer, and verify digital gaming assets without relying on centralized servers.

---
<img width="1240" height="659" alt="image" src="https://github.com/user-attachments/assets/cda21352-74ba-46e4-bdb4-25341151c1be" />


## 🚀 What it does

* 🎯 Allows players to **mint unique gaming assets**
* 🔄 Enables **secure transfer of assets** between players
* 📦 Stores **asset metadata on-chain**
* 🔍 Provides **asset lookup functionality**

---

## ✨ Features

* 🔐 **Authentication-based ownership** (only asset owners can transfer)
* 🎮 **Decentralized inventory system**
* ⚡ **Lightweight & efficient Soroban contract**
* 🔄 **Peer-to-peer asset transfers**
* 🧩 **Simple and extensible design**

---

## 🛠️ Tech Stack

* **Soroban SDK (Rust)**
* **Stellar Blockchain**

---

## 📂 Smart Contract Functions

### 1. 🪙 `mint_asset`

Creates a new asset for a player and stores its metadata.

### 2. 🔁 `transfer_asset`

Transfers an asset securely from one player to another.

### 3. 🔍 `get_asset`

Fetches metadata of a specific asset owned by a player.

---

## 🔗 Deployed Smart Contract

**Contract Address:**

```
CCFUTB3KGUJLQUN545DFLOQU5P2MOG4SO3G6Y5A7QDLSWXUKMKHEAK4K
```

👉 You can interact with this contract using:

* Soroban CLI
* Stellar SDKs
* Custom frontend applications

---

## ⚙️ How to Use (Basic Flow)

1. **Mint Asset**

   * Call `mint_asset(player, asset_id, metadata)`

2. **Transfer Asset**

   * Call `transfer_asset(from, to, asset_id)`

3. **Fetch Asset**

   * Call `get_asset(player, asset_id)`

---

## 📌 Example Use Cases

* 🎮 In-game item ownership (skins, weapons, collectibles)
* 🃏 NFT-style gaming assets
* 🏆 Achievement badges
* 🧾 Player inventory tracking

---

## 🚧 Future Improvements

* 🖼️ Rich metadata support (JSON / IPFS)
* 🛒 Marketplace for buying & selling assets
* 💎 Asset rarity & leveling system
* 🌐 Frontend integration (React + Wallet)
* 🪪 NFT standard compatibility (SEP-41)

---

## 🧑‍💻 Author

Developed by **Aunkush Bose**

---

## 📜 License

This project is open-source and available under the MIT License.
# gaming-assets
