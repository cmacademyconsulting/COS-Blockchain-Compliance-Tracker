# 🌐 COS™ Blockchain Compliance Tracker
**Trust on Chain, Ethics in Action**

---

## 📖 Overview
COS™ is an ethics‑first blockchain compliance tracker that logs verifiable events with transaction IDs, block numbers, and audit tables. It is designed to scale trust in the age of AI by embedding governance and transparency directly into technical workflows.

---

## ❌ Problem
AI systems are rapidly shaping global decision‑making, yet they remain opaque, unverifiable, and vulnerable to misinformation. Without transparent governance, trust in AI cannot scale.

---

## ✅ Solution
COS™ transforms compliance events into immutable blockchain records, coupled with audit tables and academic‑grade documentation. This ensures transparency, provenance, and accountability across AI systems.

---

## 🚀 Key Features
- **Blockchain Auditability:** Immutable compliance records with verifiable Tx IDs and block references.  
- **Ethics‑First Governance:** Transparent methodology aligned with sustainability and accountability.  
- **Academic Integration:** Zenodo DOI, manifesto poster, and whitepaper for credibility.  
- **Open‑Source Accessibility:** Licensed under Apache 2.0 for global collaboration.  
- **Demo Assets:** Screenshots, audit tables, and narration scripts for reproducibility.  

---

## 🛠️ Quick Start

### Prerequisites
- [Node.js](https://nodejs.org/) v18 or later  
- [npm](https://www.npmjs.com/) (comes with Node.js)  
- Git (for cloning the repository)  
- An [Infura](https://infura.io/) Project ID (free account)

---

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/cmacademyconsulting/COS-Blockchain-Compliance-Tracker.git
   cd COS-Blockchain-Compliance-Tracker


---

## 🧪 Tested Session (Proof of Reproducibility)

The following session was executed on:

- **OS:** Windows 11  
- **Node.js:** v24.11.1  
- **npm:** v10.9.0  
- **Network:** Sepolia Testnet via Infura RPC  

### Commands Run
```bash
cd COS-Blockchain-Compliance-Tracker
npm install
npm run demo

🌐 Connected to: Sepolia Testnet
✅ COS™ Demo: Latest Block Number = 9667096
┌─────────┬───────────────┬────────────┬─────────┬────────────────────────────┐
│ (index) │ Event         │ TxID       │ Block   │ Timestamp                  │
├─────────┼───────────────┼────────────┼─────────┼────────────────────────────┤
│ 0       │ Audit Start   │ 0x123...   │ 9667096 │ 2025-11-20T07:11:24.446Z   │
└─────────┴───────────────┴────────────┴─────────┴────────────────────────────┘
Ethics-first governance: Transparency achieved.

## ✅ Judge Checklist
- [ ] Repo cloned successfully  
- [ ] Dependencies installed without error  
- [ ] `.env` configured with Infura Project ID  
- [ ] `npm run demo` executed  
- [ ] Blockchain audit table displayed with block number + timestamp  

## 🛠️ Troubleshooting

- **Error: `npm.ps1 cannot be loaded` in PowerShell**  
  → Run the demo in Command Prompt instead:  
  ```cmd
  npm.cmd run demo

---

### 2. Split Commands and Output in Tested Session
Right now, commands and output are in the same block. Separate them:

```markdown
### Commands Run
```bash
cd COS-Blockchain-Compliance-Tracker
npm install
npm run demo
🌐 Connected to: Sepolia Testnet
✅ COS™ Demo: Latest Block Number = 9667096
┌─────────┬───────────────┬────────────┬─────────┬────────────────────────────┐
│ (index) │ Event         │ TxID       │ Block   │ Timestamp                  │
├─────────┼───────────────┼────────────┼─────────┼────────────────────────────┤
│ 0       │ Audit Start   │ 0x123...   │ 9667096 │ 2025-11-20T07:11:24.446Z   │
└─────────┴───────────────┴────────────┴─────────┴────────────────────────────┘
Ethics-first governance: Transparency achieved.

## 👩‍⚖️ Judge Walkthrough
1. Clone the repo and enter the folder.  
2. Run `npm install`.  
3. Copy `.env.example` → `.env` and insert Infura Project ID.  
4. Run `npm.cmd run demo` in Command Prompt.  
5. Confirm blockchain audit table shows block number + timestamp.  

 ![COS Banner](assets/banner.png)
- [Whitepaper](docs/whitepaper.pdf)  
- [Manifesto Poster](docs/poster.png)  
- [Zenodo DOI](https://zenodo.org/record/xxxxxx)  


## 🎬 Demo Assets
- **Screenshots:**  
  ![Demo Output](assets/screenshots/demo_output.png)  
  ![Environment Setup](assets/screenshots/env_setup.png)  

- **Narration Script:**  
  A 2‑minute script is provided for demo recording (see `/docs/narration.md`).

## 📂 Repository Structure
COS-Blockchain-Compliance-Tracker/
├── demo.js                # Demo script
├── package.json           # Dependencies
├── .env.example           # Environment template
├── README.md              # Documentation
├── LICENSE                # Apache 2.0 license
├── assets/
│   └── screenshots/       # Demo proof images
└── docs/                  # Whitepaper, manifesto, narration script

## 📜 License
Licensed under [Apache 2.0](LICENSE).
