# PEXFI Project Description

## Table of Contents
1. [Overview & Vision](#1-overview--vision)  
2. [Market Research](#2-market-research)  
3. [Core Philosophy](#3-core-philosophy)  
4. [Key Features](#4-key-features)  
5. [Tokenomics](#5-tokenomics)  
   - [Fee Model](#fee-model)  
   - [Treasury](#treasury)  
   - [Utility](#utility)  
6. [Security & Trust Model](#6-security--trust-model)  
7. [Launch Strategy](#7-launch-strategy)  
8. [Roadmap & Community Governance](#8-roadmap--community-governance)  
9. [Fraud Mitigation](#9-fraud-mitigation)  
10. [Team & Status](#10-team--status)  

---

## 1. Overview & Vision

Today’s crypto trading happens on centralized exchanges (CEXes). These platforms act like traditional banks — freezing accounts, demanding sensitive documents, blocking users by country, and enforcing heavy regulations. They control who can access crypto and when, turning a borderless tool into a gated system.

**PEXFI exists to fix that.**

It’s a decentralized, peer‑to‑peer crypto‑to‑fiat marketplace where users trade directly with each other. No company holds your funds, no KYC is required, and open‑source smart contract escrows protect every trade. You stay in control of your keys, your privacy, and your value.

---

## 2. Market Research

The peer‑to‑peer crypto trading market shows strong demand, especially in regions with limited banking access or high remittance needs. Legacy and custodial platforms have captured this demand but carry significant downsides.

### Legacy & Centralized Competitors

- **LocalBitcoins**  
  Custodial with strict KYC. Shut down in 2023 under regulatory pressure.  
  *Peak Volume:* ~$2 B/year *Revenue:* ~$25 M/year  

- **Paxful**  
  Global reach but custodial escrow. Suspended operations in 2023 due to compliance challenges.  
  *Volume:* ~$1.6 B/year *Revenue:* ~$15–20 M/year  

- **Remitano**  
  Southeast Asia & Africa focus. Custodial dispute resolution.  
  *Volume (2018):* ~$3 B/year *Revenue:* Undisclosed  

- **Noones**  
  Custodial P2P platform. Suffered a $7.9 M hack in 2025 via Solana‑bridge exploit.  
  *Takeaway:* Partial decentralization can still be exploited.  

- **RoboSats**  
  Bitcoin/Lightning P2P via Tor. No KYC.  
  *Weaknesses:* Bitcoin‑only, technical UX hurdle, no fiat dispute mediation.  

- **Bisq**  
  Desktop‑only, multichain P2P. Uses bonded arbitrators.  
  *Weaknesses:* Complex UX, slow trades, limited fiat options.  

### Opportunity for PEXFI

Legacy platforms either shut down, impose KYC, or suffer hacks. PEXFI’s fully non‑custodial, open‑source, no‑KYC model fills the gap for censorship‑resistant, privacy‑focused fiat ramps.

---

## 3. Core Philosophy

- **Non‑Custodial**: You always hold your funds; smart contracts only escrow a trade amount.  
- **Censorship‑Resistant**: Entirely on‑chain, no central server to seize or shut down.  
- **Privacy‑First**: No data collection, no KYC — wallet addresses only.  
- **Open‑Source**: All code verifiable on‑chain and via public repos.  

---

## 4. Key Features

- **Escrow Smart Contract**  
  Open‑source escrow that locks crypto until both sides confirm. Arbitrators can only approve or revert — never withdraw funds.

- **Reputation NFT**  
  Free, non‑transferable NFT per wallet tracks trade volume, completion rate, and disputes, helping peers assess trustworthiness.

- **KYC‑Free Trading**  
  Connect your wallet, agree on payment, and trade — no identity checks required.

- **IPFS Frontend**  
  Decentralized hosting for complete censorship resistance.

---

## 5. Tokenomics

### Fee Model

- **PEXFI Fee Discount**  
  Pay **0.25% per side** (maker/taker) when using PEXFI — a 50% discount from the standard 0.5% fee.  
  Calculated using the current PEXFI/USDT pool price.

- **Automatic Conversion**  
  If fees are paid in other tokens, the platform swaps them into PEXFI on a DEX, creating **consistent buy pressure**.

- **Fee Destination**  
  100% of fees (paid or converted) flow into the **Treasury** contract in PEXFI.

### Treasury

The Treasury accumulates PEXFI fees and allocates them for:

- **StakerRewards (50%)** — for arbitration/staking payouts  
- **ProtocolFund (40%)** — development, marketing, integrations  
- **OperationsFund (10%)** — audits, support, infrastructure  

### Utility

- **Trade Fee Discount**  
  Save on every trade using PEXFI.

- **Market Demand**  
  Fee conversion drives token buy pressure as volume grows.

- **Speculation**  
  Fixed supply, deflationary slashing burns, and growing utility attract holders.

- **NFT Badges**  
  Earn or purchase badge NFTs for your profile. Badges influence your ranking and visibility in trade catalogs, rewarding engagement and trust.

---

## 6. Security & Trust Model

- **Open Source Code**  
  All smart contracts and frontend are verifiable on‑chain.

- **Non‑Custodial**  
  No third‑party holds funds; only you and the escrow contract.

- **Manual Arbitrator Approval (Initial)**  
  Arbitrators are currently vetted and signed manually by the team for quality control.

- **No Data Collection**  
  No PII or metadata stored off‑chain; nothing to leak.

- **Multi‑layer Access**  
  Frontend on IPFS; fallback via Etherscan or local copies if blocked.

---

## 7. Launch Strategy

1. **Token Generation Event**  
   - Fixed supply minted; PEXFI‑only Uniswap pool seeded.  
   - Price set by user‑bonded USDT.

2. **Targeted Airdrop**  
   - Early testers, privacy advocates, defunct‑platform users.

3. **Incentivized Trading**  
   - Referral & rebate programs paid in PEXFI.

4. **Organic Growth**  
   - Community engagement, wallet integrations, regional ambassadors.

---

## 8. Roadmap & Community Governance

### Community Arbitrator Design

- **Current**: Arbitrators signed manually by the team.  
- **Goal**: Securely decentralize selection and training.  

**Community Input Needed On:**
- **Selection Mechanisms**: DAO‑based staking, on‑chain elections, reputation gating.  
- **Slashing & Appeals**: How to structure stake slashing and dispute appeals via governance.  
- **Education**: Certification/training modules for arbitrators on various fiat payment systems.  

---

## 9. Fraud Mitigation

1. **Payment Fraud**  
   - *Vector*: Fake or reversible payments.  
   - *Mitigation*: Encourage irreversible methods; arbitrator evidence review; reputation filtering.

2. **Seller Non‑Release**  
   - *Vector*: Seller holds crypto after fiat.  
   - *Mitigation*: On‑chain escrow; arbitrator enforcement; slashing.

3. **Arbitrator Collusion**  
   - *Vector*: Bribery or bias.  
   - *Mitigation*: Manual vetting (initial), future DAO slashing; multi‑arbitrator consensus.

4. **Identity Impersonation**  
   - *Vector*: Off‑platform scams.  
   - *Mitigation*: Wallet‑only trades; in‑app messaging only; on‑chain reputation NFTs.

5. **Front‑Running**  
   - *Vector*: Observing & re‑submitting orders.  
   - *Mitigation*: Optional commit‑reveal; hidden offer details.

6. **Spam/DoS**  
   - *Vector*: Fake trades, message floods.  
   - *Mitigation*: Small refundable fee to post; rate limits; reputation gating.

7. **Sybil Attacks**  
   - *Vector*: Multiple wallets farming airdrops/reputation.  
   - *Mitigation*: Volume‑based and time‑weighted reputation; graph‑analysis detection.
