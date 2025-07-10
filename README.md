# Algorand-typescript-workshop

Interactive Algorand smart contract built with AlgoKit & TypeScript for a “Personal Bank” that lets users deposit & withdraw micro‑Algos, and stores your GitHub handle on‑chain in a named box.

---

## 🚀 Project Overview  
- **Contract Name:** PersonalBank  
- **Language:** TypeScript (Algorand TypeScript SDK)  
- **Framework:** AlgoKit CLI  
- **Network:** Algorand TestNet  
- **Application ID:** `742594298`  
- **Contract Address:** `T55V7MDMPGZKIX3ZAZUOFLKSHTD4AYWQ5QXGXMCS34R2FDJAAXUQF73I44`


## 🎯 Key Features  
- 💰 **Deposit & Withdraw:** Users can deposit micro‑Algos into the contract and withdraw their full balance.  
- 📦 **Box Storage:** Stores each depositor’s balance in a `BoxMap` keyed by account address.  
- 🔖 **GitHub Handle Box:** On deposit, records your GitHub username in a dedicated on‑chain box named `github`.  
- 🔒 **Secure & Auditable:** All actions occur via atomic grouped transactions ensuring funds and data integrity.  

---

## 🛠 Tools & Technologies  
- **AlgoKit CLI** for project scaffolding, compilation, and deployment  
- **@algorandfoundation/algorand-typescript** for writing TEAL‑style smart contracts in TypeScript  
- **Algorand TestNet** for public deployment  
- **Pera Wallet** or **Goal CLI** for signing & interacting with transactions  

---

## 📁 Repository Structure  
personal-bank-workshop/
├── smart_contracts/
│ └── personal_bank/
│ └── contract.algo.ts # TypeScript contract source
├── artifacts/ # Compiled TEAL & ABI spec
├── projects/ # AlgoKit workspace sub-projects
│ └── personal-bank/
│ └── .algokit/.env # TestNet mnemonic & config
├── workshop-submission.txt # Contains only: 742594298
└── README.md # (this file)


