# PENpoints Dispatch: Michigan Security & Surveillance Compliance — 2026

**Document Type:** PENpoints Dispatch  
**Jurisdiction:** Michigan (MI)  
**Version:** 1.0 — April 2026  
**Rule Basis:** CRA Administrative Rules R 420.502, R 420.503; CRA Enforcement 2024–2025  
**Compiled by:** ClearLine Regulatory Intelligence  

---

> *"Michigan has the same 90-day retention standard as Ohio. It has the same storage math problem. And it has something Ohio doesn't: a market full of security systems installed in 2020 that have never been audited since."*

---

## Michigan Security Framework

### R 420.502 — Premises Security
- Camera coverage: all entry/exit, all storage, all cultivation, all sales, all loading/unloading
- **90-day minimum footage retention**
- Visitor log with name, date, time, purpose, escort
- Annual security plan filed with CRA
- Security plan update required within **14 days** of any material premises change

### R 420.503 — Alarm Systems
- 24/7 central monitoring
- Panic buttons at POS and cash handling
- Motion detection in all storage and cultivation areas

---

## The 90-Day Retention Problem in Michigan's Context

Michigan has an additional wrinkle Ohio doesn't: a large population of security systems installed in 2019–2021 during the rapid licensing ramp. Many of these systems:
- Were configured for 30-day retention
- Have not been audited since installation
- Are running on original hard drives that may be degrading
- Were provisioned for the original facility footprint, not subsequent expansions

**The Michigan-specific risk:** An operator who expanded in 2022–2023 but never updated their security system is operating with camera coverage gaps AND retention capacity gaps simultaneously.

---

## Coverage Requirements Matrix

| Area | Required | Michigan Standard |
|---|---|---|
| All exterior entry/exit | ✅ | Full coverage |
| Retail sales floor | ✅ | All POS + interaction areas |
| Vault/storage | ✅ | All access points |
| Processing rooms | ✅ | All work surfaces |
| Cultivation canopy | ✅ | All rows/zones |
| Loading/unloading | ✅ | During operation |
| Cash handling | ✅ | All cash surfaces |

---

## Security Tech Decision Matrix — Michigan

| Technology | CRA Guidance | Privacy Risk | Recommendation |
|---|---|---|---|
| Standard CCTV (90-day compliant) | ✅ Clear | Low | Required — implement correctly |
| DVR/NVR with 120-day buffer | ✅ Supported | Low | Recommended |
| Cloud video backup | ❌ Partial | Medium | Retain local copy; verify 90-day local compliance |
| License Plate Recognition | ❌ No guidance | Low–Medium | Document policy |
| AI behavioral analytics | ❌ No guidance | Medium | Caution |
| Facial recognition | ❌ No guidance | High | Legal review required |

**Michigan privacy note:** Michigan does not have a comprehensive biometric privacy statute, but employee-facing biometric systems raise BIPA-adjacent considerations. Consult counsel before deploying facial recognition in any employee access control context.

---

## Visitor Log — Michigan Standard

| Field | Required |
|---|---|
| Visitor full name | ✅ |
| Date | ✅ |
| Time in / time out | ✅ |
| Purpose of visit | ✅ |
| Badge number issued | ✅ |
| Escort employee name | ✅ |

Michigan requires visitor logs accessible for immediate CRA review — digital log preferred over paper stored off-floor.

---

## Compliance Hardening Checklist — Michigan Security

- [ ] DVR/NVR system: 90-day storage capacity calculated and verified at current camera count + resolution
- [ ] Footage retrieval tested from Day 88
- [ ] Security systems installed pre-2022 audited against current facility footprint
- [ ] Camera coverage gaps from expansions identified and closed
- [ ] Security plan filed with CRA; updated within 14 days of any material change
- [ ] Alarm monitoring contract current
- [ ] Panic buttons at all POS + cash handling
- [ ] Visitor log — digital, all required fields, accessible for immediate review
- [ ] Annual security plan review completed

---

## Cross-References

- 📜 LOTL baseline: [MI-LOTL-Stack-2026.md](./MI-LOTL-Stack-2026.md) Section 3
- 💼 Executive brief: [MI-Penumbrant-Executive-Brief-2026.md](./MI-Penumbrant-Executive-Brief-2026.md) Domain 4
- 📷 CO comparative: [../colorado/CO-PENpoints-Surveillance-2026.md](../colorado/CO-PENpoints-Surveillance-2026.md)
- 🤖 AI Tooling Prompts: [../ClearLine-OS-Agent-Prompts-2026.md](../ClearLine-OS-Agent-Prompts-2026.md)

---

> Not legal advice. Consult qualified counsel. Built from the floor up. Human in the Loop.
