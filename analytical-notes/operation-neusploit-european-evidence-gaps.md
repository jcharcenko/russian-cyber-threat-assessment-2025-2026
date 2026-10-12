# Operation Neusploit — European Evidence Gaps and Incident Inclusion Review

**Project:** Russian State-Linked Cyber Activity in Europe, 2025–2026  
**Review date:** 12 October 2026  
**Status:** Preliminary analytical assessment — further collection required  
**Related PIRs:** PIR-01, PIR-02, PIR-03, PIR-04  
**Sources:** SRC-012; SRC-013  
**Claims:** CLM-013; CLM-014; CLM-015  
**Collection lead:** LEAD-005  
**Incident ID:** Not assigned

## 1. Purpose

Document the evidence currently supporting Operation Neusploit's reported targeting of European countries, the unresolved source-independence questions, and the reasons for deferring inclusion in the main incident dataset.

This note records the analytical position reached during project Steps 158, 160, 163 and 165–167. It does not constitute independent confirmation of victim compromise or Russian state operational direction.

## 2. Source reporting

### SRC-012 — CERT-UA

CERT-UA reported late-January 2026 malicious Office documents exploiting CVE-2026-21509 and identified three additional documents whose content, URLs and characteristics indicated targeting of organisations in EU countries.

The reviewed material does not identify the three EU-targeted organisations or establish successful compromise of those organisations.

CERT-UA attributes the wider activity to UAC-0001 (APT28). This remains the issuing authority's attribution assessment.

### SRC-013 — Zscaler ThreatLabz

Zscaler's Operation Neusploit report identifies Ukraine, Slovakia and Romania as targeted countries and describes Romanian- and Slovak-language lures, geographically restricted payload delivery and technical payload chains involving MiniDoor, PixyNetLoader and Covenant.

These findings support an assessment of attempted geographic targeting. They do not independently establish successful compromise of a named Slovak or Romanian organisation.

Zscaler attributes the operation to APT28 with high confidence. That is the publisher's confidence assessment, not an independently established judgement by this project.

## 3. Cross-source evidence and dependence

The reports overlap in their descriptions of CVE-2026-21509 exploitation, malicious Office documents, Covenant-related activity and Filen-based command-and-control mechanisms.

Some reported document names and technical artefacts also overlap.

Zscaler provides substantial technical malware analysis beyond the information recorded from CERT-UA. However, the extent to which each organisation independently obtained and analysed the shared samples remains unresolved.

The existence of two technical publications must not be treated as proof of two independent evidence streams.

In particular, the relationship between CERT-UA's three additional EU-directed documents and Zscaler's Slovakia/Romania targeting evidence has not been established at sample or recipient level.

## 4. Follow-up collection: Steps 165–167

### Step 165 — Initial European source search

An initial search identified CERT-EU reporting that discussed Operation Neusploit and referenced Zscaler's findings.

CERT-EU's repetition of Zscaler's targeting assessment does not independently corroborate Slovak or Romanian victim activity.

### Step 166 — Slovakia

Targeted searches of Slovak national cybersecurity reporting, including SK-CERT and the National Security Authority, did not locate an original incident-specific report confirming an affected Slovak organisation.

This is a bounded negative search finding, not evidence that no Slovak organisation was targeted or affected.

### Step 167 — Romania

Targeted searches of Romanian cybersecurity reporting, including the National Cyber Security Directorate (DNSC), did not locate an original incident-specific investigation confirming a Romanian organisational victim of Operation Neusploit.

A third-party allegation of Romanian government compromise was not accepted because supporting original incident evidence was not established.

The absence of a located public report does not exclude non-public incidents or investigations.

## 5. Incident inclusion assessment

The campaign falls within the project's assessment period. Original sources have been reviewed, and the reported APT28 association is documented.

The outstanding inclusion issue is whether the available evidence sufficiently establishes activity affecting an organisation or infrastructure within the defined European geographic scope.

Country-specific lures and geographically restricted infrastructure indicate targeting intent but do not alone demonstrate delivery, execution or compromise affecting a European organisation.

**Decision:** Defer registration in the main incident dataset. Retain the campaign under LEAD-005 pending further evidence.

This is an evidence-sufficiency decision rather than a finding that the campaign had no European victims.

## 6. Analytical judgement and confidence

**Judgement:** Operation Neusploit reportedly included attempted targeting of users in Slovakia and Romania during January 2026.

**Analytical confidence:** Moderate.

**Basis:** Zscaler's original technical reporting on country-specific lures and delivery restrictions, together with geographically consistent but not demonstrably independent CERT-UA reporting on EU targeting.

**Limitations:** Named European recipients, delivery outcomes, successful exploitation, organisational compromise, exfiltration and independent attribution evidence remain unresolved.

No inference of Russian state operational control is made solely from the APT28 label or the publishers' attribution assessments.

## 7. Outstanding collection requirements

1. Identify original Slovak or Romanian incident reports, victim disclosures or national CERT investigations.
2. Obtain evidence linking malicious documents or delivery infrastructure to specific European recipients or infrastructure.
3. Compare available sample hashes, document names, URLs and payload chains between SRC-012 and SRC-013.
4. Establish whether CERT-UA and Zscaler independently acquired the relevant samples and telemetry.
5. Seek incident-specific evidence supporting or challenging the reported APT28 attribution.
6. Reassess incident inclusion if new evidence establishes European organisational targeting or impact.

## 8. Decision history

- **Step 158:** Cross-source comparison identified substantial technical overlap and unresolved evidentiary independence.
- **Step 160:** Moderate-confidence assessment of reported attempted targeting in Slovakia and Romania.
- **Step 163:** Incident inclusion deferred pending sufficient European organisational evidence.
- **Step 164:** LEAD-005 registered to track outstanding collection requirements.
- **Step 165:** Initial European search found derivative CERT-EU reporting but no independently confirmed victim.
- **Step 166:** Slovak national-source search produced no original incident-specific corroboration in the examined material.
- **Step 167:** Romanian national-source search produced no original incident-specific corroboration in the examined material.
- **Step 168:** Evidence-gap documentation proposed; no change to existing claims or incident status.

## 9. Review trigger

Reopen this assessment when original victim-level evidence, independently obtained technical evidence, or substantive new national CERT reporting becomes available.

Until then, CLM-013 through CLM-015 retain their recorded assessments and LEAD-005 remains open.

## 10. References

- SRC-012 — CERT-UA, CERT-UA#19542, 1 February 2026: https://cert.gov.ua/article/6287250
- SRC-013 — Zscaler ThreatLabz, Operation Neusploit, 2 February 2026: https://www.zscaler.com/blogs/security-research/apt28-leverages-cve-2026-21509-operation-neusploit
- CERT-EU — February 2026 Cyber Brief (derivative campaign reporting): https://cert.europa.eu/publications/threat-intelligence/cb26-03/

**Research note:** This document records the scope and conclusions of prior collection steps. It is not an exhaustive inventory of every Slovak or Romanian publication, and the negative search results are not proof of absence.
