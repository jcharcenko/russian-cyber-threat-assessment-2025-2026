# Intelligence Collection Plan

**Project:** Russian State-Linked Cyber Operations Against European Critical Infrastructure  
**Assessment Period:** 1 January 2025 – 30 September 2026  
**Methodology:** CTI & OSINT Analytical Standard v1.0  
**Status:** Revised collection plan — proposed for implementation  
**Version:** 2.0  
**Change Control:** DEC-001, methodology/decision-history.md  

## 1. Purpose

This collection plan governs the targeted verification and analysis of three selected cyber operations affecting European critical infrastructure or supporting industrial suppliers.

The objective is to develop an evidence-led comparative cyber threat intelligence assessment suitable for publication, rather than to construct an exhaustive dataset of Russian cyber operations across Europe.

Collection remains directed by PIR-01 to PIR-05 as defined in methodology/intelligence-requirements.md.

## 2. Collection Objectives

The revised collection process will:

1. Verify the chronology, affected organisations and operational consequences of each selected case.
2. Evaluate reported Russian state-linked attribution and the underlying supporting evidence.
3. Distinguish attacker objectives from demonstrated activity and impact.
4. Extract incident-specific technical findings, including evidenced TTPs and ATT&CK mappings.
5. Seek independent corroboration, competing accounts and plausible alternative explanations.
6. Evaluate source reliability and information credibility.
7. Produce case-level judgements and carefully bounded comparative defensive implications.

Routine discovery of unrelated incidents and comprehensive country-by-country or quarter-by-quarter coverage are outside the active collection objective.

## 3. Selected Cases and Priority Evidence Gaps

### Case 01 — Poland: Coordinated Energy-Sector Attacks, December 2025

**Incident records:** INC-002, INC-003 and INC-005.

Treat these records as components of a coordinated operation, not as three independent campaigns.

**Priority collection questions:**

- What does original reporting establish about the chronology, affected systems and operational effects?
- Which facilities experienced attempted disruption, confirmed compromise or verified interruption?
- How do CERT Polska, ESET, Dragos and other relevant sources differ in their actor assessments?
- Which attribution statements concern the wider operation and which concern specific components?
- What technical evidence supports documented destructive activity and defensive effectiveness?
- Are seemingly independent reports based on the same underlying investigation?

### Case 02 — Ukraine: UAC-0212 Industrial Supplier Campaign, January–February 2025

**Incident record:** INC-008.

**Priority collection questions:**

- Which organisations and industrial supplier categories were reportedly targeted?
- What activity occurred within the assessment period, as distinct from earlier campaign context?
- Which initial access, execution, malware and post-compromise behaviours are documented?
- Which targets were approached, compromised or investigated, and what distinctions can be supported?
- What evidence supports a relationship to UAC-0002/Sandworm, and what remains source attribution?
- Is there evidence of actual downstream effects on critical-infrastructure operators, or only a plausible supply-chain risk?

Do not equate supplier targeting with demonstrated compromise of downstream critical infrastructure.

### Case 03 — Sweden: District-Heating Incident, Spring 2025

**Incident record:** INC-006.

**Priority collection questions:**

- What does the original Swedish government disclosure establish about the reported incident?
- Can the incident date, affected organisation or operational circumstances be independently established?
- What evidence supports the reported attempted destructive activity and its outcome?
- What evidence, if any, independently supports attribution or Russian state direction?
- Are there relevant victim, regulator, technical or Russian official accounts?
- Can the case support a substantive technical assessment, or only a qualified analysis of public attribution and reporting limitations?

If sufficient technical evidence remains unavailable, retain the case as a limited-evidence comparison rather than inventing technical findings. Reconsider its role before publication if the available record cannot support meaningful analysis.

## 4. Collection Streams

### Stream A — Official Reporting

Sources include national CERT/CSIRT bodies, cybersecurity agencies, government statements, intelligence and law-enforcement publications, European institutions, Ukrainian authorities and relevant Russian official accounts.

Prioritise original incident reporting, official attribution, victim identification, operational effects and documented claims or denials.

Official statements establish the issuing organisation's position but do not independently prove the underlying allegation.

### Stream B — Technical Intelligence

Sources include original incident-response investigations, security-vendor reports, malware research, infrastructure analysis, vulnerability research, academic publications and MITRE ATT&CK documentation.

Prioritise technical findings directly linked to the selected cases.

Do not transfer historical actor capabilities to an incident without supporting evidence. Record whether ATT&CK mappings are explicitly reported, analyst-mapped or inferred.

### Stream C — Specialist and Regional Reporting

Sources include cybersecurity journalism, regional reporting, investigative publications, victim statements and relevant geopolitical or security analysis.

Prioritise independent operational-impact reporting, chronology, conflicting interpretations and local context.

Trace material claims to their original sources wherever possible.

### Stream D — Social and Alternative Media OSINT

Sources include public researcher accounts, social-media posts, Telegram channels, GitHub repositories, technical forums and public threat-actor statements.

Use these sources to identify verifiable evidence, leads and competing claims.

Unverified statements remain attributed claims or collection leads, not confirmed incident findings.

## 5. Source Selection and Evaluation

Prioritise sources by:

1. Relevance to the selected cases and PIRs.
2. Proximity to original evidence.
3. Direct knowledge and demonstrated expertise.
4. Transparency of supporting evidence.
5. Independence from other reporting.
6. Availability of verifiable technical or operational detail.
7. Relevance to the assessment period and geographic scope.

Evaluate source reliability (A–F) and information credibility (1–6) separately under the Admiralty system.

Do not assign reliability grades solely on nationality, political alignment or institutional category.

Source diversity is desirable but does not substitute for evidentiary independence.

## 6. Incident Inclusion and Scope Control

The original incident dataset remains preserved.

The final comparative assessment is limited to the three selected cases, unless a later documented decision explicitly changes that selection.

The selected cases must be grounded in identifiable original reporting of activity occurring within 1 January 2025 – 30 September 2026 and relevant to European critical infrastructure or supporting suppliers.

Reported attribution may be disputed, provided that the originating claims and evidentiary limitations are clearly identified.

Other incidents may be referenced for narrowly relevant context but must not silently become additional core case studies.

New unrelated incidents should not be added merely to expand the dataset or fill geographic or quarterly coverage gaps.

## 7. Collection and Verification Procedure

For each selected case:

**Step 1 — Identification:** Confirm the existing incident records and their scope.

**Step 2 — Original Source Retrieval:** Reinspect the original report, advisory, statement or technical publication.

**Step 3 — Source Registration:** Record source ID, publisher, title, URL, publication date, access date and category.

**Step 4 — Claim Extraction:** Record material claims and their supporting evidence or passages.

**Step 5 — Source Evaluation:** Apply Admiralty source reliability and information credibility separately.

**Step 6 — Corroboration:** Seek independent support, contradictions, alternative explanations and possible circular reporting.

**Step 7 — Technical Analysis:** Record incident-specific TTPs and justified ATT&CK mappings, distinguishing observation, source reporting and analytical inference.

**Step 8 — Incident Classification:** Confirm the relevant dataset records and distinguish attempted activity, confirmed compromise, destructive action and operational impact.

**Step 9 — Analytical Review:** Record case-level findings, unresolved questions, competing interpretations and confidence judgements.

Preserve source-to-claim-to-incident-to-TTP traceability throughout.

## 8. Attribution Assessment

Record attribution at three levels:

- **Reported attribution:** An actor or state relationship identified by an external source.
- **Supporting evidence:** Publicly inspectable material supporting, qualifying or challenging that identification.
- **Analyst judgement:** The project's independent conclusion, where evidence is sufficient.

A government attribution statement is evidence of that government's assessment, not automatic independent confirmation.

Do not infer state control from Russian language, political sympathy, claimed affiliation or pro-Russian alignment alone.

Where the available evidence is insufficient, preserve uncertainty rather than assigning an unsupported actor identity.

## 9. Data Management and Research Preservation

Maintain the existing structured records:

| Record | Purpose |
|---|---|
| source-register.csv | Source provenance and evaluation |
| claim-register.csv | Claims and corroboration |
| incident-dataset.csv | Incident and campaign records |
| ttp-mapping.csv | Documented technical behaviours |
| collection-leads.csv | Unresolved leads |
| coverage-matrix.csv | Historical collection coverage and documented gaps |
| analytical-notes/ | Detailed analytical findings and uncertainties |

Existing records must not be deleted merely because they fall outside the revised publication scope.

The append-only methodology/decision-history.md records significant research and methodological decisions.

Preserve historical findings and document any corrections transparently.

## 10. Limitations and Bias Controls

The assessment recognises that:

- Public reporting is incomplete and uneven across countries and sectors.
- Technical evidence may be classified, proprietary or unavailable.
- Official attribution may depend on non-public intelligence.
- Multiple publications may repeat a single original investigation.
- Observed operational impact may differ from attacker intent.
- The three cases have materially different evidentiary depth.
- A selected-case comparison cannot establish Europe-wide incident prevalence or frequency.

These limitations must be reflected in the findings, not confined to a general disclaimer.

## 11. Collection Completion and Publication Readiness

Collection will be considered sufficient to begin drafting when all of the following conditions are met for each selected case:

1. **Original evidence:** At least one identifiable original source has been inspected, with incident chronology and scope documented.
2. **Material claims:** Central attribution, targeting, technical and impact claims are registered or explicitly identified as unsupported.
3. **Corroboration:** Reasonable searches for independent confirmation and contradictory evidence have been performed and documented, including negative results.
4. **Source evaluation:** Material sources and claims have appropriate reliability, credibility and provenance assessments.
5. **Technical integrity:** Documented TTPs are traceable to incident evidence; unsupported mappings are omitted.
6. **Impact classification:** Attempted actions, confirmed compromises, destructive activity and verified operational effects are clearly distinguished.
7. **Attribution uncertainty:** Competing assessments and limits of public attribution evidence are recorded.
8. **Analytical review:** Each case has provisional findings, confidence levels, alternative explanations and unresolved questions.
9. **Cross-case readiness:** The available evidence can support at least a bounded comparison of operational consequences, attribution and defensive implications.

A criterion may be satisfied by explicitly documenting that reliable evidence is unavailable, provided the resulting analytical claim is appropriately limited. Missing evidence must never be treated as confirmation.

### Stop Rule

Once the above conditions are met, routine collection stops and report drafting begins.

Additional collection is permitted only when new evidence could materially change a central finding, resolve a significant contradiction, or correct a factual error.

There is no requirement to reach an arbitrary number of sources, incidents or ATT&CK mappings.

### Publication Gate

Before publication, verify factual claims, source links, dates, incident relationships, attribution wording, confidence judgements, citations and consistency between the PDF, executive brief and GitHub repository.

The Swedish case must undergo a specific evidence-sufficiency review before final inclusion as a substantive case study.

## 12. Review and Change Control

The assessment period and revised geographic scope follow methodology/intelligence-requirements.md.

Scope, case selection, inclusion criteria and material methodological changes require explicit approval and a new append-only decision entry.

DEC-001 documents the rationale for the transition from broad European collection to a three-case comparative assessment.

This collection plan does not retroactively invalidate the earlier research.

---

**Methodological Reference:** CTI & OSINT Analytical Standard v1.0

**Project:** Russian State-Linked Cyber Operations Against European Critical Infrastructure, 2025–2026
