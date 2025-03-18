# StudyFund: Alternative Educational Funding via Blockchain Crowdfunding

## Overview

**StudyFund** is a **decentralized educational funding protocol** designed to provide bursaries and scholarships for university students through **blockchain-powered crowdfunding**. It incentivizes donor participation using **raffle-based rewards**, ensuring **transparency, verifiability, and fairness** through **smart contracts**.

## Key Features

### 1. Blockchain-Based Fund Management
StudyFund is built on **EDUCHAIN** and leverages **smart contracts** for:
- **Donation processing**: Donors contribute funds in **USDT**.
- **Ticket allocations**: Each donation earns a raffle entry.
- **Prize distributions**: Uses **Verifiable Random Function (VRF)** to select winners.
- **On-chain fund tracking**: Ensures **full transparency** and **auditable transactions**.

### 2. Incentivized Giving Model
- Donors contribute a **minimum of 10 USDT**.
- Each donation earns **a raffle entry**, increasing the chance of winning.
- The **prize pool starts at 5,000 USDT** and scales with more donations.
- **Five winners and five runners-up** are randomly selected per round.

### 3. Smart Contract Fund Allocation
StudyFund ensures **secure and structured fund allocation**:
- **35%** → Prize pool (Top-heavy distribution model).
- **45%** → Student scholarships & bursaries.
- **20%** → Marketing, platform operations, and sustainability.

### 4. Guaranteed Payouts
- If donation targets **aren’t met**, a **5,000 USDT prize pool is still guaranteed**.
- A minimum of **2,000 USDT is allocated to scholarships**, ensuring financial aid.

---

## Technical Architecture

### Smart Contract Implementation
- **Programming Language**: Solidity
- **Contract Standards ERC-20**: for USDT integration.
- **Randomness Mechanism**: **Chainlink VRF** for provably fair raffle draws.

### Blockchain Infrastructure
- **Blockchain Network**: Deployed on **EDUCHAIN** for lower fees.
- **Storage**: 
  - **IPFS (InterPlanetary File System)** for document storage (e.g., academic transcripts).
  - **EDUCHAIN blockchain** for immutable transactions.

### Authentication & Student Access via **OCID (OpenCampus ID)**
- **OCID-based login** ensures a **decentralized and secure** way for students to access StudyFund.
- **Wallet-based authentication** to prevent identity fraud.
- **DID (Decentralized Identity)** layer for verifying students without requiring traditional email/password logins.
- **Single Sign-On (SSO) with OpenCampus ecosystem**, allowing students to use their OCID for accessing scholarships.

### Security Features
- **Multi-sig governance** to prevent unauthorized fund movement.
- **Time-locked transactions** for fund releases.
- **Verifiable on-chain audits** for full transparency.

---

## Student Scholarship Program

### Eligibility Criteria
- **University student** (verified via OCID and institutional records).
- Must submit **academic transcripts** for verification.
- Must maintain a **minimum 70% GPA**.

### Benefits for Approved Students
- **Tuition coverage** for the next semester.
- **Four-month bursary support**.
- **Soulbound NFT Scholarship Certificate** (Immutable record of financial aid).

---

## Transparency & Verification

- **Soulbound NFTs (ERC-721)** issued to recipients for tracking funding history.
- **University partnerships** to integrate **on-chain verifiable academic credentials**.
- **Full donation and payout history is available on-chain**.

---

## Growth & Engagement Strategies

- **Gamification** to boost donor participation.
- **Social media incentives** to increase engagement.
- **Community-driven fundraising** with **real-time blockchain transparency**.

---

## Inspiration Behind StudyFund

The **founder’s personal experience** with financial struggles during university inspired StudyFund. After losing a parent, they faced **significant tuition challenges**. StudyFund was created to **ensure no student faces financial hardship alone**.

---

## Development Roadmap

1. **Phase 1 - Smart Contract Development** ✅  
   - Deploy **donation and raffle system** with Chainlink VRF.  
   - Implement **Soulbound NFT issuance** for scholarships.  
   - **Integrate OCID authentication** for student login.

2. **Phase 2 - Platform Integration** 🔄  
   - Build a **user-friendly frontend (React, Next.js, Web3.js)**.  
   - Enable **on-chain scholarship application & verification**.  
   - Integrate **DID verification via OCID**.

3. **Phase 3 - DAO & Governance Model** 🔜  
   - Introduce **community governance (DAO) for fund allocation**.  
   - Implement **reputation-based voting** for student applications.

---

## Get Involved

💡 **Support education through blockchain!**  
📩 **Contact us:** studyfund@amp10.company
🌍 **Website:** www.studyfund.org 
🚀 **Join the movement!**
