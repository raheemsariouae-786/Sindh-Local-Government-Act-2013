# Act Structure

> Official Digital Legal Reference Project — Sindh Local Government Act, 2013

## Official Information

| Field | Value |
|-------|-------|
| Document Name | Act Structure |
| Document Code | ACT-STRUCTURE-001 |
| Version | 3.6 |
| Status | Under Verification |
| Verification Stage | Structure and Chapter Index drafted; factual items pending verification (see Verification Log) |
| Repository | Sindh-Local-Government-Act-2013 |
| Maintainer | Abdul Raheem Sario |

---

## Purpose

This document provides the complete structural map of the **Sindh Local Government Act, 2013**.

It serves as the master structural reference for every Chapter, Section, Schedule, Amendment, Rule, Notification, and supporting legal document maintained within this repository.

The objective of this document is to ensure consistency, traceability, maintainability, and long-term scalability throughout the Digital Legal Reference Project.

---

## Official Act Information

*Fields marked with an asterisk (*) are pending verification — see Verification Log below.*

| Item | Details |
|------|---------|
| Act Name | Sindh Local Government Act, 2013 |
| Act Number | Sindh Act No. XLII of 2013 |
| Total Chapters | 17* |
| Total Sections | 161* |
| Total Schedules | See Verification Log |
| Jurisdiction | Province of Sindh, Pakistan |
| Enacting Authority | Provincial Assembly of Sindh |
| Primary Legal Source | Official Gazette of Sindh |
| Repository Type | Digital Legal Reference Project |
| Documentation Language | English (English-only; confirmed by maintainer) |

---

## Repository Structure

*File ranges below (chapter-017, section-161) reflect the current structural plan and remain subject to the Verification Log. Folder architecture is independent of the eventual verified number of chapter and section files.*

```text
docs/
│
├── MASTER-ACT.md
├── INDEX.md
├── LEGAL-DOCUMENTATION-STANDARD.md
├── LEGAL-BLUEPRINT.md
├── ACT-STRUCTURE.md
├── AMENDMENTS.md
│
├── chapter-001.md ... chapter-017.md*
│
├── section-001.md ... section-161.md*
│
├── rules/
├── notifications/
├── schedules/
├── amendments/
├── case-law/
├── constitutional-references/
├── templates/
└── assets/
```

---

## Repository Design Principles

- Preserve the official legal structure of the Act.
- Maintain complete legal traceability.
- Support future amendments.
- Support multilingual documentation.
- Support legal research.
- Support public awareness.
- Maintain professional documentation standards.
- Ensure long-term repository scalability.
- Follow consistent Markdown formatting.
- Keep official legal text separate from explanatory material.

---

## Repository Levels

### Level 1 — Core Repository Documents
- MASTER-ACT.md
- INDEX.md
- LEGAL-DOCUMENTATION-STANDARD.md
- LEGAL-BLUEPRINT.md
- ACT-STRUCTURE.md
- AMENDMENTS.md

### Level 2 — Chapter Documentation
One Markdown file per Chapter, chapter-001.md through chapter-017.md*, following the Chapter Index below.

### Level 3 — Section Documentation
One Markdown file per Section where detailed legal analysis is required, section-001.md through section-161.md*.

---

## Chapter Index*

| Chapter | Official Title | Documentation Status |
|---------|-----------------|----------------------|
| I | Introduction | 🟡 In Progress |
| II | Councils | ⏳ Planned |
| III | Constitution and Composition of Councils | ⏳ Planned |
| IV | Members and Office Bearers of the Council | ⏳ Planned |
| V | Local Government Elections | ⏳ Planned |
| VI | Functions of the Council | ⏳ Planned |
| VII | Executive Powers and Conduct of Business | ⏳ Planned |
| VIII | Naming or Renaming of City, Municipality, Town, Village, Public Place or Public Way, etc. | ⏳ Planned |
| IX | Supervision over the Councils | ⏳ Planned |
| X | Local Taxation | ⏳ Planned |
| XI | Local Fund and Property | ⏳ Planned |
| XII | Provincial Finance Commission | ⏳ Planned |
| XIII | Provincial Local Government Commission | ⏳ Planned |
| XIV | Administration of Service | ⏳ Planned |
| XV | Offences, Penalties and Enforcement | ⏳ Planned |
| XVI | Miscellaneous | ⏳ Planned |
| XVII | Transitional Provisions | ⏳ Planned |

Verification status of this index: see Verification Log.

---

## Section Documentation Policy

Every Section shall contain:

1. Official Title
2. Section Number
3. Legal Citation
4. Official Gazette Text
5. Amendment History
6. Government Notifications
7. Plain Language Explanation
8. Legal Importance
9. Scope and Application
10. Rights and Responsibilities (where applicable)
11. Powers (where applicable)
12. Duties (where applicable)
13. Practical Example
14. Judicial Interpretation
15. Related Case Law
16. Constitutional References
17. Related Sections
18. Related Rules
19. Cross References
20. Frequently Asked Questions (Future)
21. Keywords
22. References
23. Version History
24. Documentation Status

No Section shall deviate from this standard.

---

## Verification Status Policy

*Note: this section is a one-time exception to the Structural Freeze in effect since v3.2, added to establish a repository-wide standard before further content files (AMENDMENTS.md, chapter/section files) are drafted.*

This repository uses the following verification states for factual claims, applied consistently across ACT-STRUCTURE.md, AMENDMENTS.md, and all chapter/section/rules/case-law files:

| Status | Definition |
|--------|------------|
| Pending | No required field has been verified from the designated primary source. |
| Partially Verified | One or more required fields have been verified from the designated primary source, but the verification record is not yet complete. |
| Verified | All required fields have been verified from the designated primary source and no verification items remain open. |

For non-factual items (maintainer policy choices rather than claims about the Act itself, e.g. documentation language), the Verification Log uses a separate **Type** attribute — `Factual Claim` or `Policy Decision` — rather than a fourth status value. Policy Decision items are resolved by maintainer confirmation, not by primary-source lookup; their terminal state is recorded as **Confirmed** rather than **Verified**, since no primary source applies. Factual Claim items reach **Verified** only via primary-source confirmation as defined above.

---

## Amendment Tracking Policy

Every amendment shall be documented separately with: Amendment Number, Amendment Act, Date of Enactment, Date of Enforcement, Gazette Citation, Affected Chapters, Affected Sections, Nature of Amendment, Summary of Changes, Official Source.

See AMENDMENTS.md.

Historical amendments shall never overwrite previous legal history.

---

## Supporting Legal Resources

Independent documentation shall be maintained for: Rules, Regulations, Government Notifications, Circulars, Government Orders, Schedules, Constitutional References, Case Law, Forms, Templates, FAQs, Research Notes.

---

## Documentation Principles

- Preserve the official legal wording.
- Never alter the Official Gazette text.
- Clearly separate official text from commentary.
- Cite authoritative legal sources.
- Record every amendment independently.
- Maintain complete version history.
- Follow consistent Markdown formatting.
- Avoid duplicate documentation.
- Maintain legal neutrality.
- Ensure long-term maintainability.

---

## Documentation Workflow

```text
Official Gazette
        │
        ▼
Legal Verification
        │
        ▼
Amendment Review
        │
        ▼
Government Notifications
        │
        ▼
Relevant Rules
        │
        ▼
Judicial Interpretation
        │
        ▼
Plain Language Explanation
        │
        ▼
Cross References
        │
        ▼
Final Documentation
        │
        ▼
Repository Publication
```

---

## Documentation Lifecycle

Draft → Verification → Legal Review → Publication → Version Control → Future Amendments → Continuous Improvement

---

## Future Expansion

- AI Legal Assistant
- Advanced Full-Text Search
- Amendment Tracker
- Rules Database
- Government Notifications Database
- Case Law Database
- Constitutional References
- Download Center
- Citizen Help Center
- Councillor Resource Center
- Public Legal Portal
- Legal Research Center
- Open Legal API
- Version Comparison System
- Multilingual Public Legal Portal — Urdu and Sindhi content for citizens, as a future project phase implemented outside the English reference repository. This does not affect the current repository structure or documentation workflow, which remains English-only (see Verification Log).

---

## Repository Maintenance Policy

Continuous maintenance: documentation updates, amendment tracking, formatting corrections, verification against official sources, judicial references, notifications, version history. Previous documented history is never overwritten. Periodic repository audits shall be conducted to ensure documentation accuracy.

---

## Version Control Policy

Every major update shall include: Version Number, Date of Update, Summary of Changes, Files Modified, Commit Reference, Documentation Phase. Minor editorial corrections may be committed independently.

---

## Editorial Policy

- Official legal wording shall never be altered.
- Commentary shall remain clearly distinguishable from official legal text.
- Every amendment shall be documented separately.
- Every legal source shall be properly cited.
- Duplicate documentation shall be avoided.
- Repository formatting shall remain consistent.
- Markdown standards shall be maintained throughout.
- AI-generated content shall be verified against an authoritative source before publication.

---

## Quality Assurance Checklist

- Official title is correct.
- Legal citation is accurate.
- Official Gazette text is verified.
- Amendment history is complete.
- References are cited.
- Markdown formatting is valid.
- Headings follow repository standards.
- Tables render correctly.
- Code blocks are properly closed.
- No duplicate content exists.
- Internal links have been tested.
- Cross references are valid.

---

## Documentation Status

Completion criteria: a component is marked ✅ Complete only when it requires no further structural edits and contains no open items in the Verification Log. 🟡 means drafted but has open items. ⏳ means not yet started.

| Component | Status | Basis |
|-----------|--------|-------|
| Repository Structure — Folder Architecture | 🟡 Drafted | Folder layout (rules/, notifications/, schedules/, case-law/, etc.) defined, but not yet cross-checked against the live GitHub repository's actual folder layout |
| Repository Structure — File Ranges (17 chapters, 161 sections) | 🟡 Drafted, Under Verification | Depends on Verification Log items: Total Sections, Total Schedules, Chapter Index |
| Documentation Standards (Section Documentation Policy, Editorial Policy, QA Checklist) | 🟡 Under Review | Editorial Policy and QA Checklist have been revised in every recent session; not yet stable enough to call Complete |
| Legal Blueprint | 🟡 Drafted | Not independently reviewed in this revision pass — status inherited from prior version, not re-verified |
| Act Structure — Chapter Index (drafted) | 🟡 Drafted, Under Verification | 1 open item in Verification Log (Chapter titles not yet cross-checked against post-2023 consolidated text); Repository Name item closed as of v3.6 |
| Chapter Documentation (full content) | 🟡 In Progress (1/17 drafted) | 16 of 17 chapter files not yet created |
| Section Documentation (full content) | 🟡 In Progress | Section files not yet created |
| Amendment Register | 🟡 In Progress | 3 open items in Verification Log: First Amendment Act 2023 (Partially Verified), Second Amendment Act 2023 (Pending — Act Number not yet located), Third Amendment Act 2023 (Partially Verified) |
| Rules Documentation | ⏳ Planned | Not started |
| Notifications Database | ⏳ Planned | Not started |
| Case Law Database | ⏳ Planned | Not started |
| Constitutional References | ⏳ Planned | Not started |
| Public Legal Portal | ⏳ Future Phase | Not started |

---

## Verification Log

The following items require verification before this document can be promoted from "Under Verification" to "Official". This log replaces any prior "Open Items" section. Verification statuses used below (Pending / Partially Verified / Verified) are defined in the Verification Status Policy section above.

**Primary Source Search Policy:** Before using a secondary source as a baseline, a reasonable attempt shall be defined as: (1) at least one direct query against the designated primary source's official listing, search portal, or gazette index, and (2) if a matching document is located, at least one attempt to fetch or open that document. If the document is inaccessible, or is a scanned/non-machine-readable file from which the required field cannot be extracted, the item may be recorded as Pending or Partially Verified, with the specific limitation documented in the "Remaining Verification" column.

| Priority | Item | Type | Current Status | Verified Baseline | Remaining Verification | Logged On |
|----------|------|------|----------------|--------------------|------------------------|-----------|
| High | Total Sections | Factual Claim | Pending | 161 sections, per a secondary summary source (UNEP/FAOLEX); not yet counted from the primary Gazette or a consolidated Act text | Count sections directly from the Official Gazette or sindhlaws.gov.pk consolidated text; also confirm whether post-2023 amendments changed the total (Section 134 is known to have been omitted and new sections inserted after Section 153) | 2026-07-05 |
| High | Total Schedules | Factual Claim | Pending | Conflicting sources: original Gazette Table of Contents lists Schedules I–VI (6); one secondary summary states 8 | Obtain current consolidated Gazette text and count Schedules directly | 2026-07-05 |
| High | Third Amendment Act, 2023 | Factual Claim | Partially Verified | Sindh Act No. XLVI of 2023, "Local Government (Third Amendment) Act, 2023," Gazette listing dated 02 October 2023 — verified against the official Sindh Law Department gazette listing at sindhlaws.gov.pk (PDF: PUB-23-000132.pdf) | Confirm Date of Assent and Affected Sections by manual review of the scanned Official Gazette PDF (not machine-readable via automated fetch) | 2026-07-05 |
| Medium | Chapter Index (all 17 titles) | Factual Claim | Pending | Cross-checked against a 2015 consolidated reprint of the Gazette (Sindh High Court source) | Cross-check each Chapter title against the current consolidated Act text, post all amendments through 2023 | 2026-07-05 |
| Medium | Repository Name | Policy Decision | Confirmed | Maintainer confirmed live GitHub repository name: Sindh-Local-Government-Act-2013 | None — closed | 2026-07-05 |
| Medium | First Amendment Act, 2023 | Factual Claim | Partially Verified | Sindh Act No. XI of 2023, "Sindh Local Government (Amendment) Act, 2023," Gazette listing dated 12 May 2023 — verified against the official Sindh Law Department gazette listing at sindhlaws.gov.pk | Confirm Date of Assent and Affected Sections by manual review of the scanned Official Gazette PDF | 2026-07-05 |
| Medium | Second Amendment Act, 2023 | Factual Claim | Pending | Referenced in a Dawn news report as having passed in mid-2023; Act Number not located. Raised from Low to Medium priority since the Amendment Register requires all three 2023 amendments to be complete. | Locate the Act Number and Gazette citation from sindhlaws.gov.pk or the Official Gazette | 2026-07-05 |
| Low | Documentation Language | Policy Decision | Confirmed | Maintainer decision: English-only for all repository documentation; multilingual (Urdu/Sindhi) support reserved for a future public-facing portal, outside this repository's current scope | None — closed | 2026-07-05 |

Only after all Factual Claim items above reach "Verified," and all Policy Decision items are recorded as "Confirmed," shall this document's Status field be changed to "Official."

---

## Version History

| Version | Summary |
|---------|---------|
| 2.0 | Original repository-structure draft; Chapter Index limited to 5 of 17 chapters; no Verification Log |
| 3.0 | Introduced "Under Verification" status tier and consolidated Verification Log (replacing scattered inline ⚠️ notes); completed Chapter Index to all 17 titles |
| 3.1 | Merged duplicate H1 headings into single H1; added Priority column to Verification Log; added AI-content-verification rule to Editorial Policy; added two QA checklist items; added periodic-audit line; added inline asterisk markers linking disputed fields to Verification Log |
| 3.2 | Marked remaining unmarked file-range mentions with asterisks; split Documentation Status row for Repository Structure into Folder Architecture vs. File Ranges; downgraded both, and Documentation Standards, from ✅ Complete to 🟡 |
| 3.3 | Added three-tier status definitions (Pending/Partially Verified/Verified) and Primary Source Search Policy; upgraded Third and First Amendment Act entries to Partially Verified with primary-source citations; added Second Amendment Act, 2023 as a new Pending item |
| 3.4 | Added repository-wide Verification Status Policy section; added Type column (Factual Claim/Policy Decision) to Verification Log; reverted Total Sections to Pending (baseline was secondary-sourced, not primary); raised Second Amendment priority to Medium |
| 3.5 | Removed duplicate status-definitions table from Verification Log section; reclassified Repository Name as Policy Decision rather than Factual Claim; updated Amendment Register basis to reflect all three amendment items; clarified Repository Structure independence wording; added this Version History table |
| 3.6 | Maintainer confirmed Repository Name (Sindh-Local-Government-Act-2013) and Documentation Language (English-only, with multilingual portal deferred to a future phase); closed both items in the Verification Log; introduced "Confirmed" as the terminal state for Policy Decision items, distinct from "Verified" for Factual Claims; added Multilingual Public Legal Portal to Future Expansion |

---

## Document Information

| Field | Value |
|-------|-------|
| Document Version | 3.6 |
| Documentation Phase | Repository Foundation — Structural Freeze in effect; see Verification Log for current progress |
| Last Updated | July 2026 |
| Repository Status | Active Development |
| Next Planned Review | January 2027 |
| Summary of Changes (this version) | Closed Repository Name and Documentation Language items in the Verification Log (maintainer-confirmed); introduced "Confirmed" as the Policy Decision terminal state, distinct from "Verified"; removed asterisks from Repository and Documentation Language fields; added Multilingual Public Legal Portal note to Future Expansion |
| Files Modified | ACT-STRUCTURE.md |
| Commit Reference | Not yet committed — assign on next GitHub push |

---

## Copyright Notice

© Abdul Raheem Sario

This repository is an independent educational and legal reference project based upon officially published legal material.

The Official Gazette of Sindh shall always remain the primary legal authority.

---

**End of ACT-STRUCTURE.md**
