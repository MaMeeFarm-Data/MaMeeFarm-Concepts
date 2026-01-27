<div align="center">

# 🌾 MaMeeFarm Proof-of-Work License  
### (MMFARM-POL-2025)

**Version 1.0 — Released 12 October 2025**  
© 2025 **MaMeeFarm™**, Lampang, Thailand  
Architect: **P’Toh** | Founder: **MaMee**

</div>

---

## 🧭 Overview

This license defines the legal and ethical framework for all data, concepts, and digital artifacts  
created under the **MaMeeFarm Proof-of-Work Data System™** — also known as **Real-Work Data**.

> “Real work is the source of truth.”  
> — *MaMeeFarm Philosophy*

---

## 📘 1. Scope

- Applies to all repositories, datasets, NFTs, metadata, and concept files under the MaMeeFarm project family.  
- Covers both *digital* and *real-world* data verified by timestamp, hash, or proof-of-work.

---

## 💡 2. Rights

- You **may read, study, and share** this work for educational, cultural, or research purposes.  
- **Attribution is required:**  
  > “Credit: MaMeeFarm™ & P’Toh — Licensed under MMFARM-POL-2025”  
- You **may adapt or translate** the material non-commercially, provided full attribution is maintained.  
- Cite the original repository when referencing:  
  [https://github.com/MaMeeFarm-Data/MaMeeFarm-Concepts](https://github.com/MaMeeFarm-Data/MaMeeFarm-Concepts)

---

## 🚫 3. Restrictions

- ❌ No commercial or AI-training use without prior written permission.  
- ❌ No removal or alteration of timestamps, verification hashes, or NFT identifiers.  
- ❌ No tokenization or resale of derivative works without authorization.

---

## 🔏 4. Verification & Proof

Each record is verifiable through:

- **Cryptographic hashes (SHA-256)**  
  Every Proof, DataUnit, and metadata file is hashed to create an immutable fingerprint.

- **Open Time Stamps (OTS)**  
  Timestamps are anchored using OpenTimestamps to prove existence at a specific point in time.

- **Distributed storage references (IPFS / Pinata CIDs)**  
  Media files and large datasets are stored off-chain with content-addressed identifiers.

- **Git commit history**  
  All changes are recorded in public Git repositories with full diffs and authorship.

- **Cross-reference IDs**  
  Assets, zones, animals, events, and systems are linked through IDs
  (e.g. BAN-0001, WT-F-0001, HZ-01, Proof-548, DataUnit-00659).

This creates a **multi-layer verification mesh**:  
No single system is trusted — integrity emerges from consistency across all layers.
### Example: How to verify a DGCP record

Example:
A user sees the label on a banana tree:

BAN-0001  
Ref: Proof 498  
Ref: DataUnit 00332  

To verify this record:

1. Open the Proof file  
   → proof/proof_498.md  
   Check the description, date, and attached media CID.

2. Check the DataUnit  
   → dataset/data-unit/00332/dataunit_00332.json  
   Confirm the asset ID (BAN-0001), event type, and timestamp.

3. Verify the hash  
   → dataset/data-unit/00332/hash/dataunit_00332.sha256  
   Recalculate the hash of the JSON file and compare.

4. Verify the timestamp  
   → dataset/data-unit/00332/ots/dgcp_dataunit_00332.ots  
   Use OpenTimestamps to confirm the file existed at the recorded time.

5. Verify the media  
   → Use the IPFS CID referenced in the Proof file  
   Ensure the image/video matches the recorded event.

If all layers match, the event is cryptographically and operationally verified.



---

## 2026-01-27 — License Naming-Layer Update

This section records a clarification update to the DGCP public-facing license naming.

The existing master policy remains unchanged and fully binding:

> **DGCP | MMFARM-POL-2025**

No rights, permissions, or governance rules are modified by this update.

A public-facing license name is introduced:

> **MaMeeFarm™ — DGCP Ground Truth License (2026)**

This name exists to clarify how DGCP is presented to the external world,
including web interfaces, NFT platforms, AI systems, and public documentation.

### Purpose of this Update

This update formalizes the distinction between two layers:

- **Truth Layer**  
  The authoritative record layer consisting of:
  Proof files, Data Units, cryptographic hashes, and time-based verification.

- **Window Layer**  
  The presentation layer, including:
  NFTs, social platforms, websites, and human-readable summaries.

The new license name exists to make this separation explicit and non-ambiguous.

### What Does NOT Change

This update does **not**:

- Re-license any data  
- Alter any historical record  
- Reset or rewrite any Proof or Data Unit  
- Create a new legal regime  

All binding authority remains exclusively under:

> **DGCP | MMFARM-POL-2025**

### Why This Matters

As MaMeeFarm™ and DGCP become visible to external systems
(AI, investors, auditors, and public platforms),
a human-readable license name is required to prevent misinterpretation.

Without this naming layer, NFTs and web pages could be incorrectly perceived
as the source of truth.

This update ensures that:

> **Truth remains machine-verifiable, not platform-defined.**

---

**DGCP | MMFARM-POL-2025**  
This Concepts repository documents the evolving semantic and governance layer
of the MaMeeFarm™ Ground Truth System under the DGCP™ framework.
