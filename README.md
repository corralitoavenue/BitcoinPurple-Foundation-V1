
# 🚀 BitcoinPurple FoundationV1 Pool

**FoundationV1 Pool** is a high-performance mining pool built in Node.js, designed for stability, speed, and efficient management of UTXO-based mining operations.

It is optimized for self-hosted environments and allows fast deployment with minimal dependencies.

---

## ⚙️ Features

- ⚡ High-performance pool architecture  
- 🔗 Stratum server support  
- 🧠 Intelligent worker management  
- 📡 Direct RPC node integration  
- 🪶 Lightweight Node.js implementation  
  

---

## 🧩 Requirements

- Node Version Manager (NVM)  
- Node.js v12.22.12  

---

## 📥 Installation

### Install NVM (if not installed)

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

Then reload your shell:

source ~/.bashrc

---

### Install Node.js

nvm install 12.22.12  
nvm use 12.22.12  

---

### Start the pool

./start.sh

---

## 📡 Quick Start

nvm use 12.22.12  
node start.js  

---

## ⚠️ Important Notes

- Designed for Linux environments  
- Ensure your RPC node is fully synced and properly configured  
- Update config.js before starting the pool  
- Do not use Node versions other than 12.22.12  

---

