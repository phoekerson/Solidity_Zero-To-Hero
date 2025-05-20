# 🪙 Decentralized Pool Smart Contract

A **decentralized crowdfunding contract** (Decentralized Pool) built in Solidity and deployed using Foundry. This smart contract allows users to create a pool with a funding goal and a time duration. Participants can contribute ETH until the goal is reached or the time runs out.

## ✨ Features

- ✅ Create a crowdfunding pool with a target goal and time limit
- ✅ Allow multiple users to contribute ETH
- ✅ Automatically track whether the goal is reached or time is up
- ✅ Deployment via Foundry script (`Deploy.s.sol`)

## 🛠️ Tech Stack

- [Solidity ^0.8.30](https://docs.soliditylang.org/)
- [Foundry (forge)](https://book.getfoundry.sh/)
- Script deployment using `forge script`
- Local testing with `anvil` or any forked RPC provider


---

## 🔐 Environment Variables

Create a `.env` file in the root directory:


---

## 🧪 Compile the Project

```bash
forge build

anvil

forge script script/Deploy.s.sol:MyScript --fork-url http://127.0.0.1:8545
🙋‍♂️ Author
👨‍💻 Mintoumba Caleb
🔗 Pseudonym: Phoekerson
🏫 Developer and CM at Africa Blockchain Community
🌐 Passionate about Web3, Mobile Development & AI

