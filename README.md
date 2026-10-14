# Big-Box Estimate: Retail Material Reconciliation Engine for Property Insurance

[![Origin: August 2020](https://img.shields.io/badge/Origin-August%202020-blue.svg)](https://github.com/gnarcisi/big-box-estimate)
[![Domain: Property Claims & Estimating](https://img.shields.io/badge/Domain-Catastrophe%20Claims%20%7C%20QA-orange.svg)](https://github.com/gnarcisi)
[![Evolution: Multimodal Scope AI](https://img.shields.io/badge/Evolution-Vision%20%2B%20API%20Reconciliation-brightgreen.svg)](https://github.com/gnarcisi)

> **The architectural genesis of automated retail price-matching and scope reconciliation in catastrophe insurance.**  
> Originally conceived in August 2020 to solve the critical friction between standardized carrier estimating platforms (Xactimate) and physical big-box retail supply-chain pricing (Home Depot, Lowe's).

---

## 1. The Operational Genesis (August 2020)

During a decade directing catastrophe operations and large-scale Quality Assurance (QA) audits at Citizens Property Insurance Corporation and nationwide deployments at Pilot Catastrophe Services, a fundamental structural inefficiency persisted:

1. **The Pricing Lag in Catastrophe Markets:** Following major hurricanes, local building materials (plywood, 2x4 framing lumber, roofing shingles, drywall, PVC conduit) experience severe post-event price spikes and localized shortages. Standard monthly estimating price lists lag real-time counter prices at local big-box building supply stores.
2. **Supplemental Friction & Delayed Payouts:** Policyholders and contractors submitting receipts from retail stores face weeks of manual review by desk adjusters attempting to match retail UPC barcodes and descriptions to Xactimate line-item codes (e.g. `DRY 1/2` or `RFG 240`).

**Big-Box Estimate** was founded on August 6, 2020 as an exploratory systems architecture to programmatically bridge this gap: ingesting retail store inventory/pricing APIs and reconciling them directly against insurance scope line items.

---

## 2. Architectural Evolution (2020 → 2026)

What began in 2020 as a tabular retail comparison prototype has evolved into an **Autonomous Multimodal Vision & Estimating Engine**:

```
[August 2020: The Foundation]
  - Manual item extraction & retail SKU scraping
  - Basic price-variance threshold reporting
  - Line-item mapping to big-box hardware catalogs
                            │
                            ▼
[2026: Autonomous Multimodal Vision & Telemetry Engine]
  - Multimodal Vision Segmentation: Ingests on-site property damage imagery and auto-segments structural loss components.
  - Dynamic Xactimate Line-Item Mapping: Maps segmented damage vectors directly to standardized unit-cost codes.
  - Real-Time Retail Telemetry Integration: Queries live supplier inventories and localized retail APIs to eliminate supplemental disputes and ensure rapid, fair indemnity settlement.
```

---

## 3. Core Functional Pillars

### A. Line-Item to SKU Normalization
- Normalizes proprietary Xactimate taxonomy (Category & Selector codes) against retail building material SKUs.
- Calculates geographic material price index variance (MPIV) to detect post-catastrophe surge pricing in real time.

### B. Automated Receipt & Invoice Ingestion
- Ingests paper and electronic receipts from major home improvement retailers.
- Parses item descriptions, quantities, and tax breakdowns, automatically generating audit-ready line-item reconciliation sheets for carrier QA teams.

### C. Multimodal Scope Expansion (Photo-to-Scope)
- Serves as the domain foundation for next-generation computer vision pipelines that evaluate field photos, verify repair scopes, and guarantee audit compliance before payment issuance.

---

## 4. Provenance & Engineering Context
- **Architect:** Gregory A. Narcisi  
- **Founding Commit:** August 6, 2020  
- **Specialization:** Principal AI Systems Evaluator & Catastrophe Systems Architect  
- **Contact:** gregnarcisi@gmail.com | [LinkedIn](https://www.linkedin.com/in/greg-narcisi)  
- **License:** MIT Open Source License
