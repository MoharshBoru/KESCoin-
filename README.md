# 💰 KESCoin – The Digital Kenya Shilling (KES)

KESCoin is a decentralized, Ethereum-based digital currency that represents the value of the **Kenya Shilling (KES)**. It is designed to bring financial inclusion, innovation, and digital freedom to Kenya and beyond. Powered by an ERC-20 smart contract, this project includes tools for deploying, transferring, and managing KES tokens securely.

> **Created by [MoharshBoru](https://github.com/MoharshBoru)** – Kenyan tech visionary leading digital innovation.

---

## 🌐 Technologies Used

- ⚙️ **Solidity** – Smart contract for KESCoin (ERC-20)
- 🐍 **Python** – Scripting with Web3.py for transfers
- 🌐 **Infura** – Ethereum node connection
- 🔐 **dotenv** – Secure environment variable management

---

## 🚀 Features

- ✅ Custom ERC-20 token named `KESCoin (KES)`
- ✅ Wallet script to send tokens programmatically
- ✅ `.env` example for secure key handling
- ✅ ABI interface included for integration
- ✅ Infura integration for fast blockchain connection

---

## 🧰 Folder Structure

KESCoin/ ├── contracts/ │   └── KESCoin.sol               # Solidity contract (ERC-20) ├── wallet/ │   └── send_kes_tokens.py        # Python token transfer script ├── KESCoin_ABI.json              # ABI for Web3 interaction ├── .env.example                  # Sample config (never upload real .env) ├── requirements.txt              # Python dependencies ├── .gitignore                    # Hides secrets and cache files └── README.md                     # Project overview (this file)

---

## ⚙️ How to Use

### 1. Clone this repository
```bash
git clone https://github.com/MoharshBoru/KESCoin.git
cd KESCoin

2. Install dependencies

pip install -r requirements.txt

3. Set up your .env file

Create a .env file in the root directory and add:

INFURA_PROJECT_ID=your_project_id_here
PRIVATE_KEY=your_private_key_here
ACCOUNT_ADDRESS=your_wallet_address_here
CONTRACT_ADDRESS=your_contract_address_here

4. Send KES Tokens

cd wallet
python send_kes_tokens.py


---

🛠 Requirements

Python 3.8+

Ethereum wallet with some ETH (for gas)

INFURA project ID

Deployed KESCoin contract on Sepolia or Mainnet



---

📦 Sample ABI File (KESCoin_ABI.json)

This is a simplified ABI to allow token transfers via Python script.

[
  {
    "constant": false,
    "inputs": [
      { "name": "_to", "type": "address" },
      { "name": "_value", "type": "uint256" }
    ],
    "name": "transfer",
    "outputs": [{ "name": "", "type": "bool" }],
    "type": "function"
  }
]


---

📄 License

This project is licensed under the MIT License
© 2025 MoharshBoru – use freely but responsibly.


---

🧭 Vision

> “Let us all unite for the sake of our Nation, let us all take the path of Change and say enough is enough, because the future is us.”



KESCoin is more than just a token — it's a movement to digitize Kenya’s economy and give financial power back to the people.
