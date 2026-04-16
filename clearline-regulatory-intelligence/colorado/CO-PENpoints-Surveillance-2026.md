# PENpoints Dispatch: Colorado Surveillance Technology & Security Compliance — 2026

**Document Type:** PENpoints Dispatch — Focused Operational Deep Dive  
**Jurisdiction:** Colorado (CO)  
**Version:** 1.0 — April 2026  
**Rule Basis:** 1 CCR 212-3 Rule 3-225, Rule 3-235 (eff. Jan 5, 2026) | 2025 Enforcement Report (02/19/2026)  
**Compiled by:** ClearLine Regulatory Intelligence  

---

> *"The camera system you installed in 2017 is not the compliance system your 2026 footprint requires. And the AI surveillance tool your vendor is pitching? There is no MED guidance on it. Yet. That's the penumbra."*

---

## Why This PENpoint Matters

Security compliance in Colorado cannabis has been table-stakes since day one. But in 2025–2026, two converging forces have made it a priority enforcement domain:

1. **Facility expansion outpacing security updates**: The 2025 Enforcement Report shows camera-coverage findings spiked 23% year-over-year, largely driven by operators who expanded cultivation canopy, processing capacity, or retail configurations without updating their security plans.

2. **Emerging technology gap**: AI-assisted surveillance tools — license plate readers, behavioral analytics, facial recognition systems — are being marketed aggressively to cannabis operators. The 1 CCR 212-3 framework does not address these technologies. That absence is the penumbra.

---

## The Rule Framework

### Core Security Obligations — Rule 3-225 (1 CCR 212-3)

**(A) Camera Coverage Requirements:**
- All exterior entry and exit points
- All interior areas where marijuana is stored, handled, or sold
- All point-of-sale locations
- All areas where marijuana is weighed, packaged, or labeled
- Coverage must be continuous, with no blind spots in required areas

**(B) Retention Requirements:**
- Minimum 40-day footage retention
- Retention must be maintained even during outages — systems must have adequate storage capacity
- MED may request footage access at any time within the retention window

**(C) Visitor Log Requirements:**
- Log every visitor: name, date, time in/out, purpose, badge number issued, escort employee name
- Log must be maintained in a format accessible for immediate inspector review
- No visitor in restricted areas without escort — escort name in log

### Alarm System Obligations — Rule 3-235

- 24/7 central monitoring through a licensed monitoring company
- Panic buttons at all point-of-sale and cash-handling locations
- Motion detection coverage of all storage areas
- Alarm system must be operational during all business and non-business hours
- Alarm response protocol documented and staff-trained

---

## The Enforcement Trends — 2025

The 2025 Enforcement Report (02/19/2026) highlights the following security-specific findings:

| Finding Category | % of All CAPs | Primary Cause |
|---|---|---|
| Camera blind spots | 23% | Facility expansion without security update |
| Video retention failures | 11% | DVR storage misconfiguration / compression |
| Visitor log deficiencies | 18% | Incomplete fields; off-premises storage |
| Alarm system gaps | 8% | Monitoring contract lapses |
| Restricted area access without badge | 14% | Training failures; temporary staff |

**Key pattern**: The majority of security findings in 2025 were not deliberate noncompliance — they were systems that had not kept pace with facility changes or were misconfigured in ways operators didn't know about until an inspector identified them.

---

## The Expansion-Security Gap Problem

### The Pattern

The most common security compliance failure in 2025 followed this sequence:

1. Operator files and receives approval for a premises modification (canopy expansion, new processing room, retail reconfiguration)
2. Construction and permitting complete — new space is operational
3. Security plan on file with MED reflects the pre-modification layout
4. New space has no camera coverage or insufficient coverage
5. MED inspector during unannounced visit identifies the gap

### Why It Happens

Premises modifications are typically managed by operations or real estate teams. Security plan updates require a separate MED filing. The two processes don't always run in parallel. The result is a compliant modification with a noncompliant security configuration.

### The Fix

Treat security plan updates as a required part of every premises modification workflow — not a follow-up task. The security plan update should be filed with or immediately after the modification approval. Create a checklist trigger: no new space is operationally activated until the security plan is updated and camera coverage is verified.

---

## The AI Surveillance Technology Gap

### What Is Being Marketed to Colorado Operators

Technology vendors are actively marketing to cannabis operators:

- **License Plate Recognition (LPR)**: Captures and logs all vehicles entering the premises. Can interface with METRC manifest data to verify delivery vehicles.
- **Behavioral Analytics**: AI systems that analyze camera feeds for "anomalous behavior" — flagging potential theft or unauthorized access patterns.
- **Facial Recognition**: Identity verification at entry points, particularly for restricted access areas or high-value storage.
- **Predictive Security Analytics**: Pattern recognition across historical security events to forecast risk periods.

### The Regulatory Gap

None of these technologies are addressed in 1 CCR 212-3. MED has issued no guidance on:
- Whether AI surveillance tools must be disclosed to MED
- Whether AI-generated security logs count as visitor log equivalents
- Whether biometric data collected by cannabis facilities is subject to Colorado biometric privacy law (SB 24-182)
- What happens to AI-generated footage or data in an MED records request

### The Privacy Layer — SB 24-182

Colorado's 2024 biometric data privacy law (SB 24-182) creates an additional compliance layer for operators considering facial recognition:
- Collection of biometric identifiers requires a written policy
- Notice to individuals whose data is collected
- Data retention and destruction obligations
- MED has not addressed the intersection of SB 24-182 and cannabis surveillance

### The Security Tech Decision Matrix

| Technology | MED Guidance | Privacy Risk | Operational Value | ClearLine Posture |
|---|---|---|---|---|
| Standard CCTV (upgrade/expand) | ✅ Clear rules | Low | High — direct compliance need | Recommended |
| DVR/NVR with 60-day retention buffer | ✅ Supported | Low | High — exceeds minimum, reduces risk | Recommended |
| License Plate Recognition (LPR) | ❌ No guidance | Low–Medium | Medium — delivery verification value | Caution — document policy |
| Behavioral analytics AI | ❌ No guidance | Medium | Medium — supplemental security only | Caution — no MED framework |
| Facial recognition | ❌ No guidance | High — SB 24-182 triggers | Medium | Do not deploy without legal review |
| Predictive analytics dashboard | ❌ No guidance | Low | Low–Medium | Optional — not MED-reportable currently |
| Cloud-based video storage | ❌ Partial — data sovereignty question | Medium | Medium — accessibility benefit | Evaluate data location; retain local copy |

---

## The 40-Day Retention Misconfiguration Problem

The 40-day retention requirement sounds simple. In practice, operators are failing it because:

- **DVR storage compression**: Default compression settings on many commercial DVR systems reduce footage quality (and effective storage duration) without operator knowledge. An inspector requesting footage from Day 38 may find it has overwritten.
- **Multi-camera capacity mismatch**: Adding cameras to an existing DVR without increasing storage means each camera's footage overwrites faster.
- **Power outage gaps**: A facility power outage without UPS backup can leave a retention gap — footage from before the outage is preserved, but the gap itself becomes a compliance concern.
- **Cloud upload delays**: Some systems that sync to cloud storage have 24–48 hour upload delays; if local storage overwrites before cloud sync completes, footage is permanently lost.

**Hardening Checklist for Retention Compliance:**
- [ ] Calculate storage capacity at current camera count and resolution — verify 45-day buffer (not just 40-day minimum)
- [ ] Test footage retrieval from Day 38 and Day 40 monthly
- [ ] UPS (uninterruptible power supply) installed on DVR/NVR
- [ ] Cloud sync verified daily if cloud backup is used
- [ ] Storage expansion triggered automatically when capacity falls below 20% buffer

---

## Visitor Log Compliance — The Paper Trail Still Matters

Despite the availability of digital visitor management systems, many Colorado facilities still use paper logs — and many paper logs are failing inspection. The 2025 Enforcement Report showed visitor log deficiencies in 18% of corrective action plans.

**Required Fields (Minimum) Under Rule 3-225(C):**

| Field | Required | Common Failure Mode |
|---|---|---|
| Visitor full name | ✅ | Nickname / first name only |
| Date | ✅ | Missing on multi-day pages |
| Time in | ✅ | Incomplete during busy periods |
| Time out | ✅ | Often missing — not completed at departure |
| Purpose of visit | ✅ | "Vendor" or "meeting" — too vague |
| Badge number issued | ✅ | Not assigned systematically |
| Escort employee name | ✅ | Missing most frequently |

**Recommendation**: Implement a digital visitor management system with mandatory fields and automatic timestamp. Paper logs are not prohibited, but they fail at scale. The log is a security instrument — treat it accordingly.

---

## Compliance Hardening Checklist — Security

- [ ] Camera coverage audit completed against current facility footprint (not original layout)  
- [ ] Security plan on file with MED reflects all 2025–2026 premises modifications  
- [ ] DVR/NVR storage capacity verified for full 40-day retention at current camera count  
- [ ] Footage retrieval from Day 38–40 tested and confirmed  
- [ ] UPS installed on DVR/NVR system  
- [ ] Alarm system central monitoring contract current and verified  
- [ ] Panic buttons installed at all POS and cash-handling locations  
- [ ] Visitor log — digital preferred — with all required fields mandatory  
- [ ] All AI/biometric surveillance tools reviewed for SB 24-182 compliance before deployment  
- [ ] Staff training on restricted access, visitor escort, and badge requirements current  
- [ ] Annual security audit documented and on file  

---

## Cross-References

- 📜 Statutory baseline: [CO-LOTL-Stack-2026.md](./CO-LOTL-Stack-2026.md) Section 3  
- 🌑 Enforcement gray zones: [CO-Penumbrant-Prose-2026.md](./CO-Penumbrant-Prose-2026.md)  
- 💼 Executive summary: [CO-Penumbrant-Executive-Brief-2026.md](./CO-Penumbrant-Executive-Brief-2026.md) Domain 5  
- 📋 Rule transition playbook: [CO-2026-Rule-Transition-Playbook.md](./CO-2026-Rule-Transition-Playbook.md)  
- 🤖 AI Tooling Prompts: [../ClearLine-OS-Agent-Prompts-2026.md](../ClearLine-OS-Agent-Prompts-2026.md)  

---

> Not legal advice. Consult qualified counsel. Built from the floor up. Human in the Loop.
