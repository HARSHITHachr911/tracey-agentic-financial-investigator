# TRACEY

## Agentic Financial Investigation Layer:

Tracey is an Agentic AI-powered financial investigation layer designed to help users understand fragmented financial records and investigate transaction discrepancies across different sources.

Instead of simply showing that two amounts do not match, Tracey connects available evidence and investigates possible explanations for the discrepancy.

---

## The Problem:

Financial records are often scattered across multiple sources such as:

- Bank statements
- Digital payment records
- Invoices
- Refunds
- Settlement records
- Transaction screenshots
- Transfers between accounts

When these records do not match, users often have to manually compare them to understand what happened.

A discrepancy may be caused by a refund, settlement adjustment, duplicate transaction, timing difference, transfer between a user's own accounts, or missing information.

The challenge is not only detecting the difference.

**The challenge is understanding why it happened.**

---

##  Our Solution:

Tracey acts as an investigation layer above existing financial systems.

The user provides or authorizes relevant financial records, and Tracey:

1. Extracts transaction information
2. Normalizes the records
3. Connects related financial evidence
4. Detects discrepancies
5. Investigates possible explanations
6. Presents an evidence-backed result
7. Clearly identifies what remains unexplained

### Core Flow:

**Provide Records → Extract & Normalize → Connect Evidence → Detect Discrepancy → Investigate → Explain**

---

## What Makes Tracey Different?

Traditional financial tools generally focus on recording, displaying, reconciling or reporting transactions.

Tracey focuses on the **investigation layer**.

### Financial Evidence Graph:

Tracey connects related payments, settlements, refunds, invoices, bank credits and transfers into a connected evidence structure.

### Agentic Investigation:

Instead of simply flagging an anomaly, the investigation workflow follows relevant evidence to determine possible reasons behind it.

### Evidence-Backed AI:

Deterministic transaction matching and calculations provide the factual foundation, while AI is used to reason over the available evidence and explain the result.

### Uncertainty by Design:

If the available evidence is insufficient, Tracey does not invent an explanation. It identifies what remains unresolved.

---

## Target Users:

Tracey is designed to be useful across different financial scenarios:

- Small merchants
- Students
- Families
- Freelancers
- Professionals

The same investigation approach can be adapted to different financial records and workflows.

---

## Prototype:

The current prototype demonstrates the following flow:

**Home**
→ **Upload Records**
→ **Investigation**
→ **Evidence-backed Result**

The prototype uses fictional financial data and does not connect to real bank accounts or payment systems.

### Example Investigation

A fictional transaction trail may contain:

- Payment: ₹50,000
- Refund: ₹1,000
- Settlement adjustment: ₹700
- Bank credit: ₹47,800
- Unexplained difference: ₹500

Tracey presents the available evidence and identifies the remaining unexplained amount.

---

## Architecture:

The proposed system follows this high-level architecture:

**User & Authentication**  
↓  
**Data Ingestion & Processing**  
Financial records → extraction → normalization  
↓  
**Investigation & Analysis**  
Evidence graph → matching → reconciliation → anomaly detection  
↓  
**Evidence-Based Explanation**  
Findings → supporting evidence → confidence → explanation  

**Security & Trust** 
Consent • Encryption • Minimal Data Access • Audit Logs • User Control

> Tracey is designed for read-only financial investigation and does not require UPI PINs, OTPs, or banking passwords.

---

## Security & Trust:

Tracey is designed around privacy, controlled access and user consent.

Key principles include:

- Consent-based data access
- Data minimization
- Encryption in transit
- Controlled access
- Authentication and authorization
- Auditability
- No collection of UPI PINs or OTPs
- No direct movement of user funds
- Financial screenshots treated as evidence rather than automatically verified truth
- Use of synthetic data in the prototype



---

## Prototype Screens:

The current UI prototype is available in:

`/UI-prototype/`

It includes:

- Tracey Home
- Upload Records
- Investigation
- Result

---

## Technology:

The prototype and proposed architecture are designed to support:

- Modern web technologies
- OCR/document processing
- Transaction normalization
- Deterministic reconciliation
- Evidence graph representation
- Agentic AI investigation
- Secure data processing

Specific implementation technologies may evolve during the hackathon based on the requirements of the working prototype.

---

##  Future Scope:

Tracey can be extended toward:

- Authorized financial-data integrations
- Multilingual financial investigation
- Voice-assisted investigation
- Advanced transaction relationship detection
- Automated evidence collection
- Explainable investigation reports
- Broader personal and business financial workflows

---


