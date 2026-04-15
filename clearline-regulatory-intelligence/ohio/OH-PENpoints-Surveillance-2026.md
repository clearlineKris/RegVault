# PENpoints Dispatch: Ohio Security & Surveillance Compliance — 2026

**Document Type:** PENpoints Dispatch  
**Jurisdiction:** Ohio (OH)  
**Version:** 1.0 — April 2026  
**Rule Basis:** Ohio Admin. Code 3780-3-06, 3780-3-07; ODCC 2025–2026  
**Compiled by:** ClearLine Regulatory Intelligence  

---

> *"Ohio has the strictest video retention requirement in the active green states — 90 days. Most security systems aren't configured for it. That's where the compliance gap lives."*

---

## The Ohio Security Compliance Framework

### Ohio Admin. Code 3780-3-06 — Premises Security
- **(A)**: Camera coverage — all entry/exit, all storage, all sales areas, all processing areas, all cultivation areas, all loading/unloading
- **(B)**: **90-day minimum footage retention** — Ohio's requirement is twice Colorado's (40 days) and three times Nevada's (30 days)
- **(C)**: Visitor log — date, time, name, purpose, escort employee name; accessible for immediate inspector review
- **(D)**: Annual security plan filed with ODCC
- **(E)**: Security plan update required within 30 days of any material premises modification

### Ohio Admin. Code 3780-3-07 — Alarm Systems
- 24/7 central monitoring by licensed monitoring company
- Panic buttons at all POS and cash-handling locations
- Motion detection in all storage and cultivation areas
- Documented alarm response protocol

---

## The 90-Day Retention Gap — The Number One Ohio Security Finding

### Why It Happens
Most commercial cannabis DVR/NVR systems are sold and configured with default retention settings of 30–60 days at standard resolution. Ohio's 90-day requirement means operators must:
1. Specify 90-day retention when purchasing/configuring their system
2. Calculate the actual storage capacity required at their camera count and resolution
3. Verify through actual footage retrieval, not just vendor assurance

### The Math
A facility with 20 cameras recording at 1080p (HD), 24/7:
- Approximate storage per camera per day: 20–30 GB (depending on motion detection compression)
- 20 cameras × 25 GB × 90 days = **45 TB minimum storage**
- Many systems are provisioned with 8–16 TB, which covers 30–40 days at this resolution

### What ODCC Inspectors Are Doing
ODCC security reviews include a footage retrieval test — inspectors request footage from a specific date 85–88 days prior to the inspection. If the footage is unavailable, the finding is a retention violation, not a storage question.

### The Fix
- Calculate your required storage capacity against your camera count and resolution
- Add a 15–20% buffer above the minimum calculation
- Implement automated storage alerts when capacity falls below 20% reserve
- Test footage retrieval from Day 88 monthly
- UPS (uninterruptible power supply) on DVR/NVR to prevent outage-based gaps

---

## Camera Coverage Requirements — Ohio 2026

### Required Coverage Areas

| Area | Camera Required | Ohio Standard |
|---|---|---|
| All exterior entry/exit points | ✅ | Full coverage, no blind spots |
| Retail sales floor | ✅ | All customer interaction areas |
| All storage/vault areas | ✅ | Including all inventory access points |
| Processing/extraction rooms | ✅ | All work surfaces in restricted areas |
| Cultivation canopy | ✅ | All rows/zones |
| Loading/unloading areas | ✅ | Full coverage during operation |
| Cash counting/handling areas | ✅ | All cash-handling surfaces |
| Break rooms, HR areas | ❌ | Not required |

### The Expansion-Coverage Gap Problem
Ohio operators expanding their facilities under adult-use growth face the same pattern documented in Colorado: expansion outpaces security updates.

**Under Admin. Code 3780-3-06(E)**: Any material premises modification requires a security plan update within 30 days. "Material modification" includes new cultivation rooms, expanded processing areas, added retail configurations, and new access points.

---

## Visitor Log Compliance — Ohio Standard

Ohio's visitor log requirements under Admin. Code 3780-3-06(C) require:

| Field | Required |
|---|---|
| Visitor full name | ✅ |
| Date | ✅ |
| Time in / time out | ✅ |
| Purpose of visit | ✅ |
| Badge number issued | ✅ |
| Escort employee name | ✅ |

**Ohio adds one requirement not always present in other states:** the log must be accessible for **immediate review** during an unannounced inspection. A digital log is strongly preferred — paper logs stored off-premises or in back offices fail this requirement.

---

## AI Surveillance Technology — Ohio Landscape

Ohio Admin. Code 3780-3-06 addresses physical security requirements but does not address AI-assisted surveillance tools (license plate recognition, behavioral analytics, facial recognition). The ODCC has not issued guidance on these technologies.

### Ohio-Specific Privacy Consideration
Ohio does not currently have a comprehensive biometric data privacy statute equivalent to Colorado's SB 24-182. However:
- Ohio's current data privacy framework (HB 376, pending/enacted 2024) may create disclosure obligations for biometric data collection
- Federal Biometric Information Privacy Act (BIPA) considerations for employees
- Consult legal counsel before deploying facial recognition in employee access areas

### Security Tech Decision Matrix — Ohio

| Technology | ODCC Guidance | Privacy Risk | Recommendation |
|---|---|---|---|
| Standard CCTV (90-day compliant) | ✅ Clear | Low | Required — implement correctly |
| DVR/NVR with 120-day buffer | ✅ Supported | Low | Recommended — exceeds minimum |
| License Plate Recognition (LPR) | ❌ No guidance | Low–Medium | Document policy; no ODCC framework |
| Behavioral analytics AI | ❌ No guidance | Medium | Caution — no ODCC framework |
| Facial recognition | ❌ No guidance | Medium–High | Legal review required before deployment |
| Cloud video backup | ❌ Partial guidance | Medium — data sovereignty | Retain local copy; verify 90-day local compliance |

---

## Compliance Hardening Checklist — Ohio Security

- [ ] Camera coverage audit current against full Ohio facility footprint
- [ ] Security plan on file with ODCC; updated within 30 days of any material modification
- [ ] DVR/NVR storage capacity calculated for 90-day retention at current camera count + resolution
- [ ] Footage retrieval from Day 88 tested and confirmed
- [ ] UPS on DVR/NVR system installed
- [ ] Alarm system central monitoring contract current and verified
- [ ] Panic buttons at all POS and cash-handling locations
- [ ] Visitor log — digital preferred — with all required fields mandatory
- [ ] Staff training on restricted access, visitor escort, and badge requirements documented
- [ ] Annual security plan review completed and filed with ODCC

---

## Cross-References

- 📜 LOTL baseline: [OH-LOTL-Stack-2026.md](./OH-LOTL-Stack-2026.md) Section 3
- 💼 Executive summary: [OH-Penumbrant-Executive-Brief-2026.md](./OH-Penumbrant-Executive-Brief-2026.md) Domain 2
- 📋 Transition playbook: [OH-Rule-Transition-Playbook-2026.md](./OH-Rule-Transition-Playbook-2026.md)
- 📷 CO comparative: [../colorado/CO-PENpoints-Surveillance-2026.md](../colorado/CO-PENpoints-Surveillance-2026.md)
- 🤖 AI Tooling Prompts: [../ClearLine-OS-Agent-Prompts-2026.md](../ClearLine-OS-Agent-Prompts-2026.md)

---

> Not legal advice. Consult qualified counsel. Built from the floor up. Human in the Loop.
