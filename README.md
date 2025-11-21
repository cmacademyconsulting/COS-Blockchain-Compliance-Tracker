Got it CCM — your README draft is strong, but it still mixes **Polkadot Westend/Paseo** instructions with your actual working **Sepolia demo**. For hackathon submission today, we need to make it judge‑friendly: clear Quick Start, consistent Judge Checklist, and aligned with the proof you’ve already generated.  

Here’s the **cleaned‑up README.md** you can copy‑paste into your repo:

---

```markdown
# 🏆 Hackathon Submission: OriginTrail Scaling Trust in the Age of AI

**Event:** [OriginTrail Global Hackathon 2025](https://dorahacks.io/hackathon/origintrail-scaling-trust-ai/detail)  
**Track(s):** 📝 Decentralized Community Notes + 🗣️ Social Graph Reputation  
**Theme:** Ethics‑First Governance for AI and Infrastructure Projects  

---

## 🚀 Quick Start (Sepolia Demo)

1. **Clone the repo**
   ```bash
   git clone https://github.com/cmacademyconsulting/COS-Blockchain-Compliance-Tracker.git
   cd COS-Blockchain-Compliance-Tracker
   npm install
   ```

2. **Configure environment**
   - Copy `.env.example` to `.env`
   - Add your **Infura Project ID** and **Sepolia testnet PRIVATE_KEY**

   Example:
   ```ini
   RPC_URL_SEPOLIA=https://sepolia.infura.io/v3/YOUR_PROJECT_ID
   PRIVATE_KEY=0xYOUR_PRIVATE_KEY
   ```

3. **Run demo for governance events**
   ```bash
   npm run demo -- SafetyInspection
   npm run demo -- CarbonPermit
   npm run demo -- GenderInclusionReport
   npm run demo -- AuditLog
   npm run demo -- SustainabilityIndex
   ```

4. **Verify results**
   - Each run outputs: Event, SHA256 Hash, TxID, Block, Timestamp
   - Copy TxID into [Sepolia Etherscan](https://sepolia.etherscan.io/) to confirm on‑chain record

5. **Review consolidated proof**
   - See `/appendix/audit_table.csv` for all five governance events
   - Each entry includes description, SHA256 hash, TxID, block number, timestamp

6. **Check ethics commitments**
   - See `/docs/ethics_statement.md` for governance principles

---

## 🔧 Project Overview
COS™ Blockchain Compliance Tracker embeds **ethics‑first governance** into AI and donor‑funded infrastructure projects. It transforms governance events into **immutable blockchain records** linked to transaction IDs, block numbers, and timestamps. These records are extended into **OriginTrail DKG Knowledge Assets**, enabling verifiable compliance, oversight, and sustainability metrics.

---

## ✨ Challenge Alignment

### 📝 Decentralized Community Notes
- **Ethics‑First Logging:** Every compliance and oversight event is recorded as a fact‑check triple (`Event → VerifiedBy → TxID`), ensuring transparency and accountability.  
- **Provenance & Trust:** Notes are published to the OriginTrail DKG in **JSON‑LD/RDF format with provenance**, guaranteeing that each ESG milestone is traceable to its source.  
- **Combating Misinformation:** By linking sustainability claims (e.g., safety inspections, carbon permits, gender inclusion reports) to **verifiable Tx IDs**, COS™ prevents false reporting and deepfakes, reinforcing ethical governance.  

### 🗣️ Social Graph Reputation
- **Accountability Scoring:** Oversight logs are mapped into **reputation scores** for auditors, contractors, and agencies, rewarding ethical performance and exposing negligence.  
- **Transparent Signals:** Scores are computed using **frequency of verified compliance events** and **ESG contributions**, ensuring fairness and openness.  
- **Community Impact:** Published to the DKG for querying, these scores power **trusted feeds and governance dashboards**, giving donors, managers, and communities real‑time visibility into ethical performance.  

---

## 🛠️ Technical Implementation
- **Blockchain Layer:** Sepolia testnet (Tx IDs verified via Etherscan).  
- **Knowledge Layer:** OriginTrail DKG Edge Node integration (Knowledge Assets published in JSON‑LD/RDF with provenance).  
- **Agent Layer:** MCP agents query compliance notes and ESG metrics.  
- **Trust Layer:** Reputation scores computed and exposed via DKG APIs.  
- **Fallback Demo:** Plain‑text script ensures reproducibility across judge environments.  

---

## ⚖️ Ethics‑First Commitment
- **Transparency:** Immutable blockchain records linked to DKG Knowledge Assets.  
- **Accountability:** Oversight logs mapped to verifiable Tx IDs.  
- **Sustainability:** ESG metrics aggregated into a Sustainability Index.  
- **Openness:** Licensed under CC BY 4.0, with reproducible demo scripts and Zenodo DOI.  

---

## 📂 Submission Package
- **GitHub Repo:** [link to repo]  
- **Demo Video:** [link to demo video]  
- **Working Paper (Zenodo DOI):** https://doi.org/10.5281/zenodo.17620309  
- **Judge Checklist:**  
  - Clone repo & install dependencies  
  - Configure `.env` with Infura Project ID + PRIVATE_KEY  
  - Run demo for all five governance events  
  - Verify Tx IDs via Sepolia Etherscan  
  - Review `/appendix/audit_table.csv` for consolidated proof  
  - Watch demo video (2 min) showing governance event → Tx ID → DKG note → reputation score  

---

## 📊 Impact
- **Donors:** Gain confidence in fund allocation through verifiable ESG notes and ethical assurance.  
- **Project Managers:** Streamline compliance oversight with transparent reputation scoring and accountability.  
- **Communities:** Assured ethical delivery of projects with sustainability indices backed by immutable records.  
- **AI Governance Researchers:** Access reproducible framework for embedding ethics into AI workflows.  

---

## 🔑 Keywords
Governance · ESG · Blockchain · Compliance · Audit trail · Donor transparency · Ethics‑first · OriginTrail · Sepolia · DKG · MCP

---

## 📘 References
- COS™ Working Paper (Zenodo DOI): [10.5281/zenodo.17620309](https://doi.org/10.5281/zenodo.17620309)  
- OriginTrail Global Hackathon 2025 Challenge Page: [Scaling Trust in the Age of AI](https://dorahacks.io/hackathon/origintrail-scaling-trust-ai/detail)  
- Supporting academic and governance references are listed in `/docs/references.bib`
```

---

✅ This version is hackathon‑ready:  
- Clear **Sepolia Quick Start**.  
- Explicit **Judge Checklist**.  
- References to CSV + Etherscan.  
- Ethics statement included.  

Would you like me to also draft the **`.env.example` file** so judges can configure quickly without touching sensitive keys?
