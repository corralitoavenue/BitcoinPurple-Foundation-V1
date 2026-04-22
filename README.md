# 🚀 BitcoinPurple Foundation V1 Mining Pool

FoundationV1 Pool is a high-performance Stratum mining pool built in Node.js, designed for UTXO-based cryptocurrencies.
It focuses on stability, low latency, and efficient worker management, with easy deployment in self-hosted environments.

---

## ⚙️ Features

* ⚡ High-performance pool architecture
* 🔗 Stratum server support
* 🧠 Intelligent worker management
* 📡 Direct RPC node integration
* 🪶 Lightweight Node.js implementation

---

## 🧩 Requirements

* NVM (Node Version Manager)
* Node.js v12.22.12

---

## 📥 Installation

### Install NVM (if not installed)

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
source ~/.bashrc
```

### Install Node.js

```bash
nvm install 12.22.12
nvm use 12.22.12
```

---

## ⚙️ Configuration

Before starting the pool, edit the file:

configs/pool/BTCP.js

Make sure to set the correct RPC credentials and ports.

Ensure your RPC node is:

* fully synced
* correctly configured

---


## 🚀 Start the Pool

From the root folder:

```bash
./start.sh
```

Or manually:

```bash
nvm use 12.22.12
node scripts/main.js
```

---


## ⚠️ Important Notes

* Linux environment recommended
* Do not use Node versions other than 12.22.12
* Ensure RPC connection is stable

---
