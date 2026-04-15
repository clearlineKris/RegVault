# PENpoints Dispatch: Pennsylvania Security & Surveillance Compliance — 2026

**Document Type:** PENpoints Dispatch  
**Jurisdiction:** Pennsylvania (PA)  
**Version:** 1.0 — April 2026  
**Rule Basis:** 28 Pa. Code § 1141.25 (Grower/Processor); 28 Pa. Code § 1141.53(i) (Dispensary); OMM 2024–2026  
**Compiled by:** ClearLine Regulatory Intelligence  

---

> *"Pennsylvania's 90-day retention standard applies to every Grower/Processor and every dispensary location. Multi-location dispensary organizations need to run the storage math for every location in the portfolio. One non-compliant location is a portfolio finding."*

---

## Pennsylvania Security Framework

### 28 Pa. Code § 1141.25 (Grower/Processor) and § 1141.53(i) (Dispensary)
- Camera coverage: all entry/exit, all storage, all sales, all cultivation, all processing, all loading/receiving
- **90-day minimum footage retention**
- Visitor log: all non-employee visitors; name, date, time, purpose, escort
- 24/7 central alarm monitoring

---

## Multi-Location Portfolio Math

Pennsylvania's Dispensary Organization structure means a single organization may have up to 5 locations, each independently required to maintain 90-day retention. This is not a single infrastructure question — it is a per-location infrastructure question multiplied across the portfolio.

**The cumulative risk:** An operator who has verified 90-day retention at 4 of 5 locations has a compliance gap. OMM inspections do not audit portfolios — they audit individual locations. But a finding at one location can trigger portfolio-level review.

---

## Storage Capacity Reference

| Cameras | Resolution | Daily Storage (est.) | 90-Day Minimum |
|---|---|---|---|
| 10 | 1080p | 10–15 GB/camera | 9–14 TB |
| 20 | 1080p | 10–15 GB/camera | 18–27 TB |
| 30 | 1080p | 10–15 GB/camera | 27–41 TB |
| 10 | 4K | 25–40 GB/camera | 23–36 TB |

*Motion-detection compression reduces these estimates; always verify against your specific system configuration.*

---

## Coverage Requirements Matrix

| Area | Required | Pennsylvania Standard |
|---|---|---|
| All exterior entry/exit | ✅ | Full coverage |
| Dispensary/retail sales floor | ✅ | All POS and patient interaction areas |
| Vault/storage | ✅ | All access points |
| Processing/manufacturing | ✅ | All work surfaces |
| Cultivation canopy (G/P) | ✅ | All rows/zones |
| Loading/receiving | ✅ | During operation |

---

## Security Tech Decision Matrix — Pennsylvania

| Technology | OMM Guidance | Privacy Risk | Recommendation |
|---|---|---|---|
| Standard CCTV (90-day compliant) | ✅ Clear | Low | Required per location |
| NVR with 120-day buffer | ✅ Supported | Low | Recommended for aging systems |
| Cloud video backup | ❌ No guidance | Medium | Local copy required; 90-day local compliance |
| License Plate Recognition | ❌ No guidance | Low–Medium | Document policy |
| Facial recognition | ❌ No guidance | High | Legal review required |

**Pennsylvania privacy note:** Pennsylvania does not have a comprehensive biometric privacy statute comparable to BIPA, but employee-facing biometric systems should be reviewed under HIPAA considerations where patient information may intersect (dispensary settings).

---

## Compliance Hardening Checklist — Pennsylvania Security

- [ ] Every dispensary organization location audited individually for 90-day retention compliance
- [ ] DVR/NVR storage capacity calculated per location at current camera count + resolution
- [ ] Footage retrieval from Day 85 tested at every location
- [ ] Hardware age verified at every location — systems >4 years should have hard drives reviewed
- [ ] Camera coverage current at every location vs. current floor plan
- [ ] 24/7 alarm monitoring contract current; all locations verified
- [ ] Visitor log — digital preferred; all required fields; accessible for immediate OMM review
- [ ] Annual security review completed and documented per location

---

## Cross-References

- 📜 LOTL baseline: [PA-LOTL-Stack-2026.md](./PA-LOTL-Stack-2026.md) Section 3
- 💼 Executive brief: [PA-Penumbrant-Executive-Brief-2026.md](./PA-Penumbrant-Executive-Brief-2026.md) Domain 3
- 📷 CO comparative: [../colorado/CO-PENpoints-Surveillance-2026.md](../colorado/CO-PENpoints-Surveillance-2026.md)
- 🤖 AI Tooling Prompts: [../ClearLine-OS-Agent-Prompts-2026.md](../ClearLine-OS-Agent-Prompts-2026.md)

---

> Not legal advice. Consult qualified counsel. Built from the floor up. Human in the Loop.
