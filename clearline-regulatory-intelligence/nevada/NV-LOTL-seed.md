# Nevada LOTL Stack — Seed Volume

**Document Type:** LOTL Stack — Letter of the Law (Seed)  
**Jurisdiction:** Nevada (NV)  
**Version:** Seed 1.0 — April 2026  
**Rule Basis:** NAC Chapter 678A; NRS Chapter 678A; CCB Regulations; Nevada Cannabis Compliance Board  
**Compiled by:** ClearLine Regulatory Intelligence  

---

> *"Nevada runs one of the most heavily-inspected cannabis markets in the country. The Strip demands volume; the CCB demands precision. From the floor up — this seed volume starts with what every NV operator must know."*

---

## Seed Volume Purpose

This is a seed document — a foundational LOTL framework for Nevada cannabis operations, establishing the citation architecture and core obligation structure for full volume development. It captures primary statutory and regulatory anchors, identifies key 2025–2026 updates, and flags the NV-specific compliance pressures that distinguish this market from other regulated states.

For comparative reference, see the Colorado full stack: [../../colorado/CO-LOTL-Stack-2026.md](../../colorado/CO-LOTL-Stack-2026.md)

---

## Nevada Regulatory Framework Overview

Nevada's cannabis regulatory authority rests with the **Cannabis Compliance Board (CCB)**, established under NRS Chapter 678A. The CCB operates a dual-track system: adult-use retail and medical cannabis, with overlapping licensing categories and shared seed-to-sale tracking infrastructure.

Key characteristics of the NV framework:
- **Mandatory distributor model**: Cultivators and manufacturers cannot sell directly to retailers; distribution through a licensed distributor is required
- **Tourism-driven retail volume**: Las Vegas dispensaries serve one of the highest per-transaction volumes in the country — compliance infrastructure must scale accordingly
- **CCB active enforcement posture**: Nevada has one of the highest enforcement-to-operator ratios in the country; the CCB's 2025 Annual Report reflects active corrective action activity across all license categories

---

## Section 1: Licensing Framework

### 1.1 License Categories (NRS 678A)

| License Type | Governing Statute/Regulation | Key Obligation |
|---|---|---|
| Adult-Use Retail | NRS 678A.300 | CCB licensure + municipal approval |
| Medical Cannabis Dispensary | NRS 678C | Dual license with CCB registration |
| Cannabis Cultivation | NRS 678A.290 | Plant count limits; canopy reporting |
| Cannabis Production (MIP) | NRS 678A.295 | Extraction method disclosure to CCB |
| Cannabis Distribution | NRS 678A.285 | Mandatory for all product movement |
| Cannabis Testing Laboratory | NRS 678A.310 | Nevada Department of Agriculture coordination |
| Cannabis Delivery | NRS 678A.305 | Residential delivery; CCB permit required |

### 1.2 Core Licensing Obligations

- Annual renewal with CCB — 60-day pre-expiration filing window (NAC 678A)
- Municipal/county license required alongside state CCB license
- Ownership disclosure — all beneficial owners of ≥ 5% interest disclosed
- Background check for all principal officers and owners
- Financial source documentation — proof of lawful source for capitalization

---

## Section 2: Seed-to-Sale Tracking

### 2.1 METRC in Nevada

Nevada operates METRC as its seed-to-sale system under CCB oversight. Core obligations mirror Colorado's framework with NV-specific variances:

- **Plant tag assignment**: At propagation (clone/seed)
- **Harvest batch creation**: Same-day requirement
- **Transfer manifest**: Must precede vehicle departure; routed through licensed distributor
- **Retail POS integration**: METRC API push required

### 2.2 NV-Specific METRC Consideration: The Distributor Layer

Nevada's mandatory distribution model creates an additional METRC touchpoint: every product transfer passes through a licensed distributor before reaching retail. Each distributor transfer requires:
- A separate METRC transfer event
- A new transfer manifest
- A new set of testing holds (if applicable)

The distributor layer creates compliance risk at the handoff point — discrepancies between cultivator/producer METRC entries and distributor manifests are a documented enforcement trigger.

---

## Section 3: Security Requirements

- **Camera coverage**: All areas where cannabis is present, all entry/exit, all POS
- **Retention**: 30-day minimum (shorter than Colorado's 40-day requirement)
- **Visitor protocols**: Escort required; log maintained
- **Alarm systems**: 24/7 monitoring required; CCB notification within 24 hours of alarm event

### NV-Specific Pressure: High-Volume Retail Security

Las Vegas strip dispensaries serving 500+ customers per day face a structural tension: pharmaceutical-grade security requirements (restricted access, camera coverage) against tourist-friendly retail design. The CCB does not provide retail design flexibility — requirements are applied uniformly regardless of volume.

---

## Section 4: Pesticide Compliance

Nevada's pesticide framework parallels Colorado's EPA-registered only requirement, administered through the Nevada Department of Agriculture (NDA) and CCB. NV does not have a separate cannabis-specific pesticide list — operators must comply with:
- EPA registration requirements
- NDA pesticide use regulations
- CCB product safety requirements

The absence of a Colorado-style explicit prohibited compound list creates interpretive ambiguity in Nevada — the penumbrant analysis is in [NV-Penumbrant-Prose-seed.md](./NV-Penumbrant-Prose-seed.md).

---

## Section 5: Packaging & Labeling

- Universal symbol required on all products (NRS 678A.490)
- Child-resistant packaging required
- "For use only by adults 21 years of age and older" statement required
- THC content in mg per serving and per package required
- Licensed manufacturer name and CCB license number required

**NV-Specific**: Nevada imposes a strict tamper-evident seal requirement on all retail products — seals must be intact at point of sale and conspicuously broken before consumption.

---

## Section 6: Testing Requirements

Testing conducted through CCB-licensed testing facilities. Required panels include:
- Potency (cannabinoid profile)
- Microbial contamination
- Residual solvents (concentrates)
- Pesticide residues
- Heavy metals
- Moisture content

**NV-Specific Testing Note**: Product moving through the distributor layer may be retested at the distributor's discretion. CCB has not issued clear guidance on who bears the retesting cost — this is a documented gray area in the distribution compliance framework.

---

## Seed Volume: Expansion Priorities

This seed volume should be expanded to full LOTL Stack with:
1. Complete citation-level coverage of NAC Chapter 678A rules
2. CCB bulletin and guidance memo tracking (2025–2026)
3. Municipal overlay — Clark County and Reno-specific requirements
4. Transportation deep dive — distributor compliance framework
5. Testing transition notes — any 2026 NDA/CCB testing standard updates

---

## Cross-References

- 🌑 NV gray areas: [NV-Penumbrant-Prose-seed.md](./NV-Penumbrant-Prose-seed.md)  
- 💼 NV executive brief: [NV-Penumbrant-Executive-Brief-seed.md](./NV-Penumbrant-Executive-Brief-seed.md)  
- 🥬 NV field notes: [NV-Field-Notes-seed.md](./NV-Field-Notes-seed.md)  
- 📜 CO comparative full stack: [../../colorado/CO-LOTL-Stack-2026.md](../../colorado/CO-LOTL-Stack-2026.md)  
- 🌱 MN LOTL seed: [../../minnesota/MN-LOTL-seed.md](../../minnesota/MN-LOTL-seed.md)  
- 🤖 AI Tooling Prompts: [../../ClearLine-OS-Agent-Prompts-2026.md](../../ClearLine-OS-Agent-Prompts-2026.md)  

---

> Not legal advice. Consult qualified counsel. Built from the floor up. Human in the Loop.
