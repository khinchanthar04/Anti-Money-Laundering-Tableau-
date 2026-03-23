# Anti-Money Laundering & Transaction Monitoring
### Case Study: Kim & Lee

**Khin Chan Thar**

---

## 📌 Overview

This project applies Anti-Money Laundering (AML) principles and transaction monitoring techniques to a real-world-style case study involving a suspicious transaction network centred on the entity **Kim & Lee**. It covers the three stages of money laundering, how transaction monitoring systems work, and a network-level investigation to identify fund flows, anomalies, and key middlemen.

---

## 📝 Background: What is AML?

AML refers to the laws, regulations, and procedures designed to prevent criminals from disguising illegally obtained funds as legitimate income. The three classic stages of money laundering are:

| Stage | Description |
|---|---|
| **Placement** | Dirty money enters the economy via bank deposits, often in smaller amounts below reporting thresholds |
| **Layering** | Funds pass through multiple domestic and offshore transactions to obscure the audit trail |
| **Integration** | Laundered proceeds re-enter the financial system as clean money with an apparent legitimate origin |

Financial institutions combat this using **Know Your Customer (KYC)** and **Customer Due Diligence (CDD)** processes to verify identities and flag suspicious activity.

---

## 🔎 How Transaction Monitoring Works

Transaction monitoring follows a risk-based approach with eight interconnected functions:

1. **Data Collection & Integration** — Gather transaction data from banking systems, payment processors, and external providers
2. **Transaction Screening** — Screen each transaction against predefined rules, risk criteria, and external watchlists
3. **Risk-Based Scoring** — Assign risk scores based on customer risk profiles and transaction history to prioritise review
4. **Pattern Detection & Analysis** — Identify abnormal behaviour deviating from a customer's typical transaction patterns
5. **Alert Generation** — Flag suspicious transactions and route them to investigators
6. **Investigation & Case Management** — Review flagged transactions, gather account history, and identify involved parties
7. **Suspicious Activity Reporting (SAR)** — File detailed reports with regulators when a transaction is confirmed suspicious
8. **Continuous Monitoring & Improvement** — Use feedback loops and periodic audits to refine detection and maintain regulatory compliance

---

## 🖧 Case Study: Kim & Lee's Transaction Network

### 🌐 Network Overview
The investigation maps the full transaction network of Kim & Lee, tracking funds sent and received across a group of connected parties. The network analysis uses **averages** rather than raw sums to establish a stable baseline of normal financial behaviour since deviations from this baseline signal potential anomalies.

### ༄ Money Flow
Kim & Lee transacted with the following counterparties:
- **Jerry**
- **Tony**
- **Jane**
- **Tom**
- **Sherren**
- **Sunil**

### 🕵 Identifying the Middlemen

A key focus of the investigation is identifying which parties acted as **middlemen** who are usually those that are handling the highest volume of intermediary transactions:

| Party | Transaction Count |
|---|---|
| **Jerry** | 4 |
| Tony | 3 |
| Jane | 3 |
| Sherren | 3 |
| Tom | 2 |
| Sunil | 1 |

**Jerry** is identified as the primary middleman by transaction count, followed by Tony, Jane, and Sherren. The concentration of activity through a small number of intermediaries is a classic indicator of layering behaviour in money laundering networks.

---

## 📝 Key Takeaways

- Foreign and multi-hop transactions significantly complicate audit trails and are a primary vehicle for the layering stage.
- Average-based baselines are more effective than sum-based approaches for detecting behavioural anomalies in AML monitoring.
- Network mapping of counterparties reveals structural patterns (hub-and-spoke flows, repeated intermediaries) that rule-based systems alone may miss.
- Middleman identification is critical since high transaction counts through a single intermediary warrant immediate escalation and SAR filing.

---

## 📂 Project Structure

```
├── 14684190_KhinChan_AML.pptx   # Full presentation and network visualisations
├── 14684190_KhinChan_AML.twbx   # Tableau
└── README.md                     # This file
```

---

## Author

**Khin Chan Thar**  
Anti-Money Laundering & Transaction Monitoring — Case Study Project
