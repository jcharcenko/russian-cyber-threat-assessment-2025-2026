# Source Reliability Calibration Review — 12 October 2026

**Project:** Russian State-Linked Cyber Activity in Europe, 2025–2026  
**Review date:** 2026-10-12  
**Status:** Completed preliminary calibration; further validation outstanding  
**Related project steps:** 188–195  
**Affected records:** SRC-001–SRC-016  
**Methodological reference:** CTI & OSINT Analytical Framework v1.0.0

## 1. Purpose

This note documents a potential source-evaluation consistency issue identified during the investigation and the subsequent review of the existing Admiralty reliability grades.

It preserves the analytical reasoning, decisions, limitations and outstanding actions without retrospectively changing the original source assessments.

## 2. Issue Identified

On 12 October 2026, the source register contained sixteen records (SRC-001–SRC-016), all assigned Admiralty source reliability grade B — Usually reliable.

The uniform grading raised a concern that source reliability might be insufficiently differentiated across government agencies, cybersecurity research organisations, legal authorities and affected operators.

Uniform grades do not themselves demonstrate incorrect evaluation. However, repeated use of the same grade warrants examination for potential default grading, institutional-reputation bias or conflation of source reliability with information credibility.

## 3. Methodological Review

The investigation's methodology/source-evaluation.md and methodology/collection-plan.md were reviewed alongside standards/source-evaluation.md in the CTI & OSINT Analytical Framework v1.0.0.

The existing methodology already requires consideration of:

- Source identity, provenance and historical accuracy.
- Relevant expertise and access to information.
- Transparency of collection and analytical methods.
- Corrections, inaccuracies and possible conflicts of interest.
- Information credibility assessed separately from source reliability.
- Independent corroboration and source dependencies.
- Analytical confidence assessed separately from Admiralty grades.

The methodology also specifies that unfamiliar or insufficiently assessable sources may receive F — Reliability cannot be judged, and that Grade A must not be assigned automatically to official or established organisations.

**Finding:** The existing methodology is substantially adequate. The principal concern relates to its application and the completeness of individual reliability justifications, not an identified deficiency in the grading definitions.

## 4. Source Reassessments

Five sources representing different reporting categories were examined during Steps 190–194.

| Source ID | Publisher | Category | Existing grade | Review outcome |
|---|---|---|---|---|
| SRC-006 | CERT Polska / NASK | National incident-response authority | B | Retain |
| SRC-007 | Cisco Talos | Commercial technical research | B | Retain |
| SRC-004 | US Department of Justice | Government/legal | B | Retain |
| SRC-015 | La Poste Groupe | Affected operator | B | Retain provisionally |
| SRC-011 | Government Offices of Sweden | Government/policy | B | Retain provisionally |

### SRC-006 — CERT Polska

The assessment identified relevant incident-response expertise, institutional accountability and direct investigative involvement in the December 2025 Polish energy-sector incidents.

However, an independent systematic assessment of historical reporting accuracy was not completed. Technical findings and attribution to Static Tundra require separate claim-level evaluation.

**Decision:** Retain B.

### SRC-007 — Cisco Talos

The assessment identified established technical research capabilities, documented investigative reporting and relevant network-security expertise.

Commercial interests and reliance on external government findings for portions of historical attribution were considered. These factors do not automatically reduce source reliability, but source dependencies must remain explicit.

**Decision:** Retain B.

### SRC-004 — US Department of Justice

The DOJ is authoritative concerning its own prosecutorial announcements and legal actions. The underlying criminal allegations must nevertheless be distinguished from judicial findings.

The review did not establish a sufficient basis for either an upgrade to A or a downgrade to C.

**Decision:** Retain B.

### SRC-015 — La Poste Groupe

The affected operator has direct access to information about its own service availability, operational disruption and response.

Its public reporting is less transparent regarding underlying technical telemetry, and no systematic historical accuracy review was completed. Commercial and reputational incentives were also recognised.

**Decision:** Retain B provisionally.

### SRC-011 — Government Offices of Sweden

The official government source is authoritative for statements made by Swedish authorities and relevant policy announcements.

The incident-specific information concerning the attempted attack against a heating plant originated from an accompanying government briefing rather than the written press release. Review of the briefing relied on auto-generated Swedish captions and cross-checking against an English translation.

The government's reported attribution assessment does not constitute independently verified forensic proof of Russian state direction.

**Decision:** Retain B provisionally.

## 5. Cross-Source Findings

### 5.1 Uniform grading

All sixteen sources were assigned B at the time of review. This is not inherently invalid, and the review did not identify sufficient evidence to justify changing the five grades examined individually.

The remaining eleven sources have not undergone an equivalent individual calibration during this review.

### 5.2 Historical reliability versus direct access

Several existing rationales emphasise publisher expertise, institutional standing and direct access to evidence.

These are relevant considerations but do not, by themselves, fully establish a historical record of usually reliable reporting.

### 5.3 Source reliability versus information credibility

A source's reliability must not be equated with the evidentiary strength of each claim.

For example:

- A government may reliably report that it issued an attribution without independently proving that attribution.
- A technical researcher may report original observations while relying on external findings for actor identification.
- An affected operator may directly document service disruption without establishing the perpetrator's identity.

### 5.4 Evidence accessibility

Restricted access to classified intelligence, proprietary telemetry or forensic records creates an evidence-verification limitation.

It must not automatically be treated as proof that the publisher is unreliable.

### 5.5 Source independence

Organisational independence does not necessarily establish independent underlying evidence.

SRC-015 and SRC-016 originate within the same corporate group. Their accounts must not automatically be counted as independent corroboration.

## 6. Decisions

The following decisions were reached during Steps 188–195:

1. Retain the existing source-evaluation methodology without amendment.
2. Do not automatically upgrade or downgrade sources based on institutional status.
3. Do not manufacture diversity in Admiralty grades.
4. Retain the five individually reviewed B grades, subject to the qualifications recorded above.
5. Do not treat the remaining eleven B grades as individually validated by this calibration.
6. Strengthen future source assessments through more explicit examination of historical reporting reliability where evidence permits.
7. Preserve separate assessments of source reliability, claim credibility, source dependencies and analytical confidence.
8. Revisit material source grades before publication or when contradictory evidence emerges.

No source-register changes were authorised or made as a result of this calibration.

## 7. Limitations and Unresolved Questions

This review was a focused methodological calibration, not a comprehensive independent audit of the historical accuracy of all sixteen publishers.

Outstanding questions include:

- Whether documented correction histories or independent evaluations justify changing individual grades.
- Whether the remaining eleven sources have sufficiently differentiated reliability rationales.
- Whether SRC-011's government briefing should receive a separate source-register entry to improve traceability.
- Whether further examination of operator reporting supports the provisional B assessment for SRC-015.
- Whether future collection identifies sources appropriately classified A, C, D, E or F.

The absence of identified inaccuracies must not be interpreted as proof of an error-free reporting history.

## 8. Future Review Triggers

Reassess relevant source grades when:

- Material contradictory evidence is identified.
- Documented inaccuracies, corrections or retractions become available.
- New information materially changes the assessment of a publisher's expertise, access or reporting record.
- A source becomes central to a high-impact analytical judgement.
- The project undergoes its final pre-publication evidence audit.

Any material regrading should include a specific rationale and preserve the prior assessment in the project decision history.

## 9. Final Analytical Judgement

**The uniform B grading represents a legitimate quality-assurance concern but is not, on the evidence examined, a confirmed methodological error.**

The five reviewed grades remain defensible working assessments. The completeness of historical reliability validation varies by publisher, and the other eleven grades remain subject to targeted review.

**Analytical confidence in this process finding: Moderate.** The judgement is supported by direct examination of the existing methodology and source-register rationales, but a comprehensive historical reliability audit has not been completed.

---

**Record type:** Methodological quality-control analytical note  
**Decision history:** Append-only; subsequent changes should be documented rather than silently replacing the original review.
