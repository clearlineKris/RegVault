# PENpoints Dispatch: New York Security & Surveillance Compliance — 2026

**Document Type:** PENpoints Dispatch  
**Jurisdiction:** New York (NY)  
**Version:** 1.0 — April 2026  
**Rule Basis:** 9 NYCRR § 116.8; OCM/CCB Enforcement 2023–2026  
**Compiled by:** ClearLine Regulatory Intelligence  

---

> *"New York has 90-day retention. New York City's licensed dispensaries are the highest-camera-count retail operations in the program — flagship locations with 25+ cameras, in some cases. The storage math is real and the stakes are high."*

---

## New York Security Framework

### 9 NYCRR § 116.8 — Premises Security
- Camera coverage: all entry/exit, all storage, all sales, all cultivation, all processing, all loading/receiving
- **90-day minimum footage retention**
- Visitor log: name, date, time, purpose, escort
- Security plan on file with OCM; updated within 30 days of material change
- 24/7 central alarm monitoring

---

## New York City Retail — The High-Camera-Count Problem

New York City's licensed dispensaries are among the most heavily monitored retail cannabis operations in the country. Flagship locations in Manhattan, Brooklyn, and Queens often have:
- 20–35+ cameras covering interior and exterior
- Multiple POS stations requiring individual coverage
- Large retail footprints with complex ceiling geometries
- External cameras covering sidewalk approach per OCM and NYPD considerations

**The math problem at NYC scale:** A 30-camera NYC flagship at 1080p = approximately 55–70 TB minimum for 90 days. Most security systems are not provisioned to this scale without explicit engineering.

---

## Coverage Requirements Matrix

| Area | Required | New York Standard |
|---|---|---|
| All exterior entry/exit | ✅ | Full coverage |
| Retail/dispensary floor | ✅ | All POS + customer interaction areas |
| Vault/storage | ✅ | All access points |
| Processing/extraction | ✅ | All work surfaces |
| Cultivation canopy | ✅ | All rows/zones |
| Loading/receiving | ✅ | During operation |
| Cash handling | ✅ | All cash surfaces |

---

## Security Tech Decision Matrix — New York

| Technology | OCM Guidance | Privacy Risk | Recommendation |
|---|---|---|---|
| Standard CCTV (90-day compliant) | ✅ Clear | Low | Required — engineer to NYC scale if applicable |
| DVR/NVR with 120-day buffer | ✅ Supported | Low | Recommended |
| Cloud video backup | ❌ No guidance | Medium | Local copy required; 90-day local compliance |
| License Plate Recognition | ❌ No guidance | Low–Medium | Document policy |
| AI behavioral analytics | ❌ No guidance | Medium | Caution — NY privacy landscape active |
| Facial recognition | ❌ No guidance | High | New York State privacy law review required |

**New York privacy note:** New York has an active privacy law landscape. The New York Privacy Act (various legislative iterations) and NYC-specific biometric privacy ordinances (N.Y.C. Admin. Code § 22-1202) impose disclosure and consent requirements for biometric data collection in commercial establishments. Review before deploying any face-recognition or biometric system in New York.

---

## Visitor Log — New York Standard

| Field | Required |
|---|---|
| Visitor full name | ✅ |
| Date | ✅ |
| Time in / time out | ✅ |
| Purpose of visit | ✅ |
| Badge number | ✅ |
| Escort employee name | ✅ |

Digital format preferred; accessible for immediate OCM review.

---

## Compliance Hardening Checklist — New York Security

- [ ] Camera coverage audit against current facility footprint
- [ ] Storage capacity calculated specifically for New York location's camera count and resolution
- [ ] DVR/NVR system provisioned for 90-day retention at full camera count
- [ ] Footage retrieval from Day 85 tested and confirmed
- [ ] Security plan filed with OCM; updated within 30 days of material modifications
- [ ] Alarm monitoring contract current and active
- [ ] Panic buttons at all POS + cash handling locations
- [ ] Visitor log — digital, all required fields, accessible for immediate OCM review
- [ ] NYC-specific: biometric privacy disclosure reviewed before any AI surveillance deployment

---

## Cross-References

- 📜 LOTL baseline: [NY-LOTL-Stack-2026.md](./NY-LOTL-Stack-2026.md) Section 3
- 💼 Executive brief: [NY-Penumbrant-Executive-Brief-2026.md](./NY-Penumbrant-Executive-Brief-2026.md) Domain 3
- 📷 CO comparative: [../colorado/CO-PENpoints-Surveillance-2026.md](../colorado/CO-PENpoints-Surveillance-2026.md)
- 🤖 AI Tooling Prompts: [../ClearLine-OS-Agent-Prompts-2026.md](../ClearLine-OS-Agent-Prompts-2026.md)

---

> Not legal advice. Consult qualified counsel. Built from the floor up. Human in the Loop.
