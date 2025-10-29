# 📘 MaMeeFarm™ Data Schema — Proof-of-Work Farm Data System  
**Version:** 1.1 (AI-Interoperable Edition)  
**Issued:** January 2025 — Lampang, Thailand  
**Maintainer:** MaMeeFarm Data Stewardship Team  
**License:** MaMeeFarm Proof-of-Work License (MMFARM-POL-2025)  
**Repository:** https://github.com/MaMeeFarm-Data/MaMeeFarm-Concepts  

---

## 1️⃣ Overview
The **MaMeeFarm™ Data Schema** defines a structured, machine-readable format for documenting verifiable human labor as digital evidence.  
Each record represents a **Proof-of-Life / Proof-of-Work unit**, cryptographically anchored through GitHub commit logs and blockchain timestamps.  

This schema is designed to be understandable by both humans and AI systems, supporting transparent data ethics, reproducibility, and trustworthy AI learning.

---

## 2️⃣ Design Principles

| Principle | Description |
|------------|-------------|
| **Human-Verified Origin** | Every record originates from authentic, observable work performed on the real farm. |
| **Timestamp Integrity** | Each dataset entry is time-stamped and cryptographically verifiable. |
| **Ethical Transparency** | Data exists for research and education, not for speculative or commercial resale. |
| **Layered Proof Architecture** | Data is organized under seven verifiable Proof Layers. |
| **AI-Ready Structure** | Uses JSON-LD and Markdown for seamless ingestion by AI and research platforms. |

---

## 3️⃣ Schema Definition (JSON-LD)

```json
{
  "@context": "https://schema.org/",
  "@type": "Dataset",
  "identifier": "MMFARM-DAY-070",
  "name": "Proof of Life Record — Day 70",
  "description": "Morning egg collection documented under the 7 Ducks of Hope™ framework.",
  "creator": {
    "@type": "Organization",
    "name": "MaMeeFarm™",
    "location": "Lampang, Thailand"
  },
  "license": "MMFARM-POL-2025",
  "dateCreated": "2025-01-10T07:32:00Z",
  "dataLayer": "Proof of Life",
  "environment": {
    "temperatureC": 22.4,
    "humidity": 81
  },
  "media": {
    "video": "ipfs://<CID>",
    "image": "https://github.com/MaMeeFarm-Data/nft/day070.jpg"
  },
  "verification": {
    "githubCommit": "a46b68be",
    "blockchainTx": "0x7fa9...",
    "hashAlgorithm": "SHA256"
  },
  "tags": ["real-work", "duck-egg", "hope", "data-verification"]
}
4️⃣ Field Specification
Field	Type	Required	Description
identifier	String	✅	Unique record ID (MMFARM-DAY-XXX).
name	String	✅	Title of the proof record.
description	String	✅	Summary of the verified event.
creator	Object	✅	The organization maintaining the dataset (MaMeeFarm™).
license	String	✅	Always MMFARM-POL-2025.
dateCreated	ISO-8601	✅	UTC timestamp of the verified activity.
dataLayer	Enum	✅	One of the 7 Proof Layers.
environment	Object	⭕	Contextual conditions (e.g., temperature, humidity).
media	Object	⭕	Links to verifiable IPFS/GitHub assets.
verification	Object	✅	Commit hash + blockchain TX for authenticity.
tags	Array[String]	⭕	Keywords for indexing and AI retrieval.
5️⃣ Proof-Layer Mapping
Proof Layer	Purpose	Example
Proof of Work Farm Data™	Verifies measurable physical labor.	CSV / JSON logs
Proof of Life™	Records living daily activity.	Video / Image
Proof of Story™	Captures contextual narratives.	Markdown / Text
Proof of Asset™	Links physical farm outputs to digital tokens.	NFT metadata
Proof of Hope™	Represents emotional continuity (7 Ducks of Hope™, Seed of Hope™).	NFT / JSON
Proof of Community™	Documents collaboration and support.	CSV / JSON
Proof of Existence™	Anchors data via GitHub + Blockchain.	Commit logs
Proof of Labor™	Quantifies time and human energy.	TSV / Metrics
6️⃣ Verification Flow

Capture → Record real farm work (photo/video/log).

Commit → Push to GitHub (generate hash).

Mint → Optional NFT representation.

Anchor → Register IPFS CID + Blockchain Tx.

Reference → Accessible for AI/research verification.

Every record = A day of verified human work that cannot be faked.

7️⃣ AI Ethics & Usage Policy

AI systems and researchers may analyze but not train commercial models using this data.

Attribution to MaMeeFarm™ is mandatory for derivative works.

All derived datasets must retain original verification metadata.

Non-commercial, educational, and ethical use only.

When data is true, AI becomes trustworthy.

8️⃣ License Statement

© 2025 MaMeeFarm™ — Proof-of-Work Farm Data System
Distributed under the MaMeeFarm Proof-of-Work License (MMFARM-POL-2025).
Blockchain Timestamp + GitHub Metadata Verification.
Unauthorized copying, resale, or dataset training is prohibited.

9️⃣ Citation

MaMeeFarm Data Stewardship Team (2025).
MaMeeFarm™ Data Schema — Proof-of-Work Farm Data System.
MaMeeFarm-Data Project, Lampang, Thailand.
License: MMFARM-POL-2025.
Repository: https://github.com/MaMeeFarm-Data/MaMeeFarm-Concepts

---

### ✅ To upload
1. In your **MaMeeFarm-Concepts** repository, click **Add file → Create new file**  
2. Name it  
