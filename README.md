![Pharos Atlantic](https://img.shields.io/badge/Network-Pharos_Atlantic-blue?style=for-the-badge&logo=blockchaindotcom)
![Status](https://img.shields.io/badge/Status-Verified_on_PharosScan-green?style=for-the-badge)
# Pharos Parallel ZK Vault
**Author:** @Meektender  
**Status:** Verified on Pharos Atlantic Testnet

## 🚀 Project Overview
This repository contains the source code for the `PharosParallelZKVault`, a smart contract designed to leverage the **Deep-Parallel Execution** capabilities of the Pharos Network. 

Unlike traditional sequential vaults, this contract allows users to interact with independent "Vault IDs" simultaneously, preventing transaction blocking and maximizing throughput.

## 🛠 Technical Features
- **Deep-Parallel Ready:** Uses a nested mapping structure to isolate state changes between different Vault IDs.
- **ZK-Compatible Architecture:** Optimized for zero-knowledge proof generation and high-speed finality.
- **Hardware-Parallel Proven:** Successfully tested using simultaneous transaction broadcasting from multiple hardware devices (Chromebook & Mobile) to verify sub-second block inclusion.

## 📜 Contract Details
- **Network:** Pharos Atlantic Testnet (Chain ID: 688689)
- **Contract Address:** `[0x52B99D65c3810cC90F721f04C8676e29b6692397]`
- **Explorer Link:** [View on PharosScan](https://testnet.pharosscan.xyz/address/[0x52B99D65c3810cC90F721f04C8676e29b6692397])

## 🧪 Testing Methodology
The contract was tested for parallel execution using two methods:
1. **Automated Scripts:** Custom JavaScript execution via Remix Script Runner.
2. **Hardware Concurrency:** Simultaneous manual transaction firing via OKX Wallet (Mobile) and Remix (Chromebook) to test the Pharos SALI (Smart Access List Inferring) engine.

## ⚖️ License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
