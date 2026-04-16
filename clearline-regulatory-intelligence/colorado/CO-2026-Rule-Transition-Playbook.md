# Colorado 2026 Rule Transition Playbook

**Document Type:** Rule Transition Playbook  
**Jurisdiction:** Colorado (CO)  
**Version:** 1.0 — April 2026  
**Rule Basis:** 1 CCR 212-3, effective January 5, 2026 | Bulletin 26:01 (01/23/2026) | 2025 Enforcement Report (02/19/2026)  
**Compiled by:** ClearLine Regulatory Intelligence  

---

> *"Rule transitions are where compliance gaps get created — not out of bad intent, but because the old muscle memory doesn't automatically update when the new rule drops. This playbook maps the gaps."*

---

## Purpose

This playbook documents every material rule change in Colorado's January 5, 2026 1 CCR 212-3 revision, tracks the implementation status and enforcement horizon for each change, and provides operator action items. It is designed to be used as a living document through the 2026 license year.

Pair with:
- 📜 [CO-LOTL-Stack-2026.md](./CO-LOTL-Stack-2026.md) — full citation baseline  
- 🌑 [CO-Penumbrant-Prose-2026.md](./CO-Penumbrant-Prose-2026.md) — enforcement gray zones  
- 💼 [CO-Penumbrant-Executive-Brief-2026.md](./CO-Penumbrant-Executive-Brief-2026.md) — executive synthesis  

---

## Part 1: 2026 Rule Change Registry

### Change 1: License Transfer Notification Window — Rule 2-205

| Field | Detail |
|---|---|
| **Previous Rule** | 20-day pre-sale notification to MED required |
| **New Rule** | 30-day pre-sale notification to MED required |
| **Effective Date** | January 5, 2026 |
| **Citation** | 1 CCR 212-3, Rule 2-205 |
| **Enforcement Status** | Active — no grace period documented |
| **Operator Impact** | License transfer timelines extend; LOIs and purchase agreements must account for the additional 10 days |
| **Action Required** | Update your M&A / license transfer checklist and any standard LOI templates to reflect 30-day notification |

---

### Change 2: Delivery Operator Requirements — Rule 2-260 (NEW)

| Field | Detail |
|---|---|
| **Previous Rule** | No retail delivery operator category existed |
| **New Rule** | Retail Delivery Operator license category created with specific requirements: geofencing, manifest protocol, badged drivers |
| **Effective Date** | January 5, 2026 |
| **Citation** | 1 CCR 212-3, Rule 2-260 |
| **Enforcement Status** | License active; MED inspection framework expected Q3 2026 |
| **Operator Impact** | New license category — operators delivering must hold this license or face unlicensed activity citation |
| **Action Required** | (1) Verify your delivery operations hold the Rule 2-260 license. (2) Implement geofencing solution with logging capability. (3) Train drivers on municipal routing restrictions. (4) Build METRC transfer protocol for delivery-specific workflows. |

#### Security Tech Decision Matrix — Delivery Operations

| Technology/System | MED Requirement | Implementation Status | Risk Without |
|---|---|---|---|
| Geofencing (any compliant platform) | ✅ Required — Rule 2-260 | Must be active before delivery | License violation |
| Geofence logging / audit trail | ✅ Implied by compliance mandate | Logging must be retained | Cannot demonstrate compliance |
| METRC transfer (pre-departure) | ✅ Required — Rule 3-115 | Non-negotiable | Transfer violation |
| Driver badge (state MED) | ✅ Required — Rule 2-260 | In effect | Badging violation |
| Municipal routing map | ✅ Required by municipal overlay | Must be current | Municipal violation |
| Customer age verification protocol | ✅ Required | Must be documented | Sale to minor risk |
| Failed delivery resolution protocol | ⚠️ Not specified | Build your own — document it | Uncharted territory |

---

### Change 3: QR Code Traceability on Product — Rule 3-1015

| Field | Detail |
|---|---|
| **Previous Rule** | Batch/lot number required on label |
| **New Rule** | QR code linking to consumer-accessible batch COA required on all products manufactured after March 1, 2026 |
| **Effective Date** | March 1, 2026 (manufacturing date, not sale date) |
| **Citation** | 1 CCR 212-3, Rule 3-1015 (updated Jan 5, 2026) |
| **Enforcement Status** | Active — products manufactured from March 1 must have QR codes |
| **Operator Impact** | Label design changes required; QR destination must be accessible to consumers |
| **Action Required** | (1) Update label templates for all products. (2) Verify QR code links resolve to publicly accessible COA. (3) Audit inventory for products manufactured after 3/1 without QR codes — these are non-compliant for sale. |

---

### Change 4: ISO 17025 Testing Facility Deadline — Rule 5-110

| Field | Detail |
|---|---|
| **Previous Rule** | No accreditation deadline |
| **New Rule** | All licensed testing facilities must achieve ISO 17025 accreditation by July 1, 2026 |
| **Effective Date** | July 1, 2026 (deadline) |
| **Citation** | 1 CCR 212-3, Rule 5-110 |
| **Enforcement Status** | Deadline approaching — labs not accredited by July 1 face license revocation |
| **Operator Impact** | Product in testing at non-accredited labs after deadline cannot be released under Rule 5-125 |
| **Action Required** | (1) Verify accreditation status of all current testing lab relationships. (2) Establish backup lab relationship with confirmed-accredited facility. (3) Position testing volume at accredited backup starting May 2026. |

#### Testing Lab Transition Timeline

| Date | Action Item |
|---|---|
| Now (April 2026) | Verify accreditation status of all current labs |
| May 1, 2026 | Establish active relationship with at least one confirmed-accredited backup lab |
| May 15, 2026 | Begin routing 25–50% of testing volume through backup lab |
| June 1, 2026 | No new samples to any lab without confirmed accreditation timeline |
| June 15, 2026 | All samples submitted at accredited labs only |
| July 1, 2026 | Deadline — non-accredited labs lose MED license |

---

### Change 5: METRC Entry Window Reaffirmation — Bulletin 26:01

| Field | Detail |
|---|---|
| **Previous Guidance** | Same-day entry generally required; interpretation variable |
| **New Guidance** | Same-business-day entry required; MED will not accept overnight batch entries absent documented system outage |
| **Effective Date** | January 23, 2026 (bulletin date) |
| **Citation** | MED Bulletin 26:01 (01/23/2026) |
| **Enforcement Status** | Active — inspectors reviewing METRC audit logs against production records |
| **Operator Impact** | Multi-shift operations face highest exposure; late-night batches must be entered before end of operational day |
| **Action Required** | (1) Map every production step that generates a METRC entry obligation against your shift schedule. (2) Assign METRC entry responsibility to shift leads with end-of-shift accountability. (3) Implement outage reporting protocol per Bulletin 26:01. |

---

### Change 6: Manifest Discrepancy Enforcement — Bulletin 26:01

| Field | Detail |
|---|---|
| **Previous Guidance** | Manifest discrepancies reviewed case-by-case |
| **New Guidance** | Any discrepancy between paper manifest and METRC transfer is an automatic corrective action trigger |
| **Effective Date** | January 23, 2026 |
| **Citation** | MED Bulletin 26:01 (01/23/2026) |
| **Enforcement Status** | Active |
| **Operator Impact** | Zero-tolerance for manifest/METRC mismatch — eliminates historical "good faith" defense |
| **Action Required** | Implement a pre-departure manifest verification step — driver and dispatch both confirm paper manifest matches METRC before vehicle departs. |

---

### Change 7: CDPHE Eagle 20EW Enforcement Escalation

| Field | Detail |
|---|---|
| **Previous Guidance** | Eagle 20EW prohibited; corrective action on finding |
| **New Guidance** | First offense triggers mandatory product quarantine pending remediation testing |
| **Effective Date** | March 2026 (CDPHE Guidance Memo) |
| **Citation** | CDPHE Guidance Memo, March 2026 |
| **Enforcement Status** | Active |
| **Operator Impact** | A single test positive for myclobutanil triggers supply chain disruption-level enforcement, not just a corrective action |
| **Action Required** | (1) Confirm no myclobutanil products on premises. (2) Require supplier pesticide disclosures. (3) Add myclobutanil to pre-harvest test panel. |

---

## Part 2: Implementation Calendar — 2026

| Month | Priority Action Items |
|---|---|
| **April 2026** | Audit METRC entry timing; verify lab accreditation status; confirm no Eagle 20EW in supply chain |
| **May 2026** | Establish backup lab relationship; begin routing test volume to accredited labs; update delivery geofencing documentation |
| **June 2026** | Route all testing through confirmed accredited labs; complete label QR code update for all product lines; conduct camera coverage audit |
| **July 1, 2026** | ISO 17025 deadline — all testing must be at accredited labs |
| **Q3 2026** | MED delivery operator inspections expected — complete delivery compliance documentation before then |
| **Ongoing** | Municipal overlay calendar; equity program documentation; weekly METRC reconciliation |

---

## Part 3: Gap Assessment Template

Use this template to assess your facility's current implementation status against each 2026 rule change:

| Rule Change | Implementation Status | Gap Identified | Owner | Target Completion |
|---|---|---|---|---|
| Rule 2-205 (Transfer notification) | ☐ Complete ☐ In Progress ☐ Not Started | | | |
| Rule 2-260 (Delivery operator) | ☐ Complete ☐ In Progress ☐ N/A | | | |
| Rule 3-1015 (QR code labeling) | ☐ Complete ☐ In Progress ☐ Not Started | | | |
| Rule 5-110 (Lab accreditation) | ☐ Complete ☐ In Progress ☐ Not Started | | | |
| Bulletin 26:01 (METRC timing) | ☐ Complete ☐ In Progress ☐ Not Started | | | |
| Bulletin 26:01 (Manifest match) | ☐ Complete ☐ In Progress ☐ Not Started | | | |
| CDPHE Memo (Eagle 20EW) | ☐ Complete ☐ In Progress ☐ Not Started | | | |

---

## Part 4: Documentation Retention Reference

| Document | Minimum Retention | Storage Location |
|---|---|---|
| METRC audit logs | MED access 3 years | METRC (state-held) + internal backup |
| Transfer manifests (paper) | 3 years | On-premises binder + digital scan |
| Pesticide application log | 3 years | On-premises binder + digital scan |
| Visitor log | 2 years (per Rule 3-225) | On-premises; accessible for inspection |
| Security footage | 40 days | DVR/NVR (verify no overwrite) |
| Testing COAs | 3 years | Digital archive; accessible by lot number |
| Employee badge records | Duration of employment + 2 years | HR file |
| IPM plan (current version) | Current + prior version | On-premises binder |
| License certificates | Current period | Posted + binder |

---

## Cross-References

- 📜 Statutory foundation: [CO-LOTL-Stack-2026.md](./CO-LOTL-Stack-2026.md)  
- 🌑 Enforcement gray zones: [CO-Penumbrant-Prose-2026.md](./CO-Penumbrant-Prose-2026.md)  
- 🥬 Floor-level view: [CO-Field-Notes-2026.md](./CO-Field-Notes-2026.md)  
- 💼 Executive synthesis: [CO-Penumbrant-Executive-Brief-2026.md](./CO-Penumbrant-Executive-Brief-2026.md)  
- 🔬 Pesticide deep dive: [CO-PENpoints-Pesticides-2026.md](./CO-PENpoints-Pesticides-2026.md)  
- 📷 Surveillance deep dive: [CO-PENpoints-Surveillance-2026.md](./CO-PENpoints-Surveillance-2026.md)  
- 📊 Pesticide matrix: [CO-Pesticide-Compliance-Matrix-2026.md](./CO-Pesticide-Compliance-Matrix-2026.md)  
- 🤖 AI Tooling Prompts: [../ClearLine-OS-Agent-Prompts-2026.md](../ClearLine-OS-Agent-Prompts-2026.md)  

---

> Not legal advice. Consult qualified counsel. Built from the floor up. Human in the Loop.
