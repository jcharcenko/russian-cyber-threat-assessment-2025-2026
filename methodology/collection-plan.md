
# Intelligence Collection Plan

**Project:** Russian State-Linked Cyber Activity in Europe  
**Assessment Period:** 1 January 2025 – 30 September 2026  
**Methodology:** CTI & OSINT Analytical Standard v1.0  
**Status:** Initial Collection Plan  
**Version:** 1.0

## 1. Purpose

This collection plan defines the approach for identifying, obtaining, validating and recording publicly available information relevant to Russian state-linked cyber operations affecting European organisations.

Collection will be directed by the project's five Priority Intelligence Requirements (PIRs).

The objective is to develop a balanced, evidence-led dataset suitable for strategic, operational and technical cyber threat intelligence analysis.

## 2. Collection Objectives

The collection process will seek to:

1. Identify documented cyber operations within the assessment scope.
2. Establish reported threat actors and evaluate attribution evidence.
3. Record targeting patterns, affected sectors and apparent objectives.
4. Extract technical evidence, including TTPs, malware, vulnerabilities and infrastructure.
5. Identify competing official accounts and alternative explanations.
6. Evaluate source reliability and information credibility.
7. Identify recurring patterns and their defensive implications.

## 3. Collection Streams

### Stream A: Official Reporting

**Source categories:**

- National cybersecurity agencies and CERT/CSIRT organisations.
- European Union institutions and agencies.
- National law enforcement and intelligence agencies.
- Government advisories and official statements.
- Russian official government and agency statements.
- Ukrainian and other relevant national authorities.

**Collection priorities:**

- Confirmed or attributed incidents.
- Official attribution assessments.
- Affected organisations and sectors.
- Public technical advisories.
- Statements of responsibility, denial or alternative explanation.

Official statements will be treated as authoritative evidence of the issuing organisation's position, not automatically as proof of the underlying allegation.

### Stream B: Technical Intelligence

**Source categories:**

- Cybersecurity vendor threat intelligence reports.
- Incident-response investigations.
- Malware and infrastructure analysis.
- Vulnerability research.
- Academic and independent technical research.
- MITRE ATT&CK documentation.

**Collection priorities:**

- Initial access methods.
- Credential theft and persistence.
- Command-and-control activity.
- Lateral movement and privilege escalation.
- Collection, exfiltration and impact.
- Malware families, tooling and exploited vulnerabilities.
- Indicators of compromise where relevant.

Technical findings must be linked to specific incidents or campaigns.

Historical actor capabilities will not be presented as observed incident behaviour.

### Stream C: Specialist and Regional Reporting

**Source categories:**

- Cybersecurity journalism.
- Investigative reporting.
- European national and regional media.
- Russian-language independent and state-affiliated publications.
- Specialist geopolitical and security analysis.

**Collection priorities:**

- Identification of incidents not covered by major security vendors.
- Victim statements and organisational impact.
- Regional context.
- Chronological developments.
- Alternative accounts and disputed claims.

Important claims will be traced to their original reporting wherever possible.

### Stream D: Social and Alternative Media OSINT

**Source categories:**

- Public researcher accounts and social-media posts.
- Public Telegram channels.
- GitHub repositories.
- Relevant technical forums.
- Public statements by alleged threat actors.
- Other accessible OSINT material.

**Collection priorities:**

- Early incident reporting.
- Claims of responsibility.
- Public technical observations.
- Researcher discoveries.
- Contradictory or alternative reporting.

Unverified material will be recorded as a lead or claim and will not automatically qualify as a confirmed incident.

## 4. Source Selection Criteria

Sources will be prioritised according to:

1. Relevance to the intelligence requirements.
2. Proximity to original evidence.
3. Demonstrated expertise or direct knowledge.
4. Transparency of supporting evidence.
5. Independence from other reporting.
6. Availability of verifiable technical details.
7. Relevance to the assessment period and geographic scope.

Source diversity will be actively pursued to reduce selection bias.

No source will receive a reliability grade based solely on its country of origin, political alignment or organisational category.

## 5. Incident Inclusion Criteria

An incident or campaign may enter the main dataset when:

- Relevant activity occurred within the assessment period.
- The activity affected an organisation or infrastructure within the defined geographic scope.
- A Russian state link or documented proxy relationship is supported by identifiable evidence or attribution reporting.
- At least one original source can be inspected.
- Sufficient information exists to describe the reported or observed activity.

Disputed incidents may be included when their attribution status and limitations are clearly documented.

Cases failing these criteria will remain in a separate collection leads register.

## 6. Collection and Verification Procedure

For each potential incident:

**Step 1: Identification**

Identify the incident through official, technical, journalistic or OSINT reporting.

**Step 2: Original Source Retrieval**

Locate the original advisory, report, statement, publication or technical evidence.

**Step 3: Source Registration**

Record the source ID, publisher, title, URL, publication date, access date and source category.

**Step 4: Claim Extraction**

Extract relevant factual claims and identify their supporting passages or evidence.

**Step 5: Source Evaluation**

Apply Admiralty Code source reliability (A-F) and information credibility (1-6) separately.

**Step 6: Corroboration**

Identify independent supporting evidence, contradictions and possible circular reporting.

**Step 7: Technical Analysis**

Record documented TTPs and any justified MITRE ATT&CK mappings.

Distinguish explicitly reported, analyst-mapped and inferred techniques.

**Step 8: Incident Classification**

Determine whether the case qualifies for the main incident dataset or should remain a research lead.

**Step 9: Analytical Review**

Identify uncertainty, competing explanations and information gaps.

## 7. Attribution Assessment

Attribution will be recorded at three distinct levels:

- **Reported attribution:** An actor identified by an external source.
- **Supporting evidence:** Publicly available information supporting or challenging that attribution.
- **Analyst judgement:** The project's independent assessment, where sufficient evidence exists.

An official attribution statement will not automatically become an independently verified attribution.

Where available evidence is insufficient, the project will retain the originating source's attribution and explicitly acknowledge the limitation.

## 8. Data Management

The project will maintain the following structured records:

| File | Purpose |
|---|---|
| source-register.csv | Source identification, provenance and evaluation |
| claim-register.csv | Individual claims, supporting evidence and corroboration |
| incident-dataset.csv | Structured incident and campaign records |
| ttp-mapping.csv | Documented technical behaviours and ATT&CK mappings |
| collection-leads.csv | Potential incidents requiring further validation |
| analytical-notes/ | Detailed assessments, contradictions and analytical observations |

Each record will use a unique identifier.

Sources, claims, incidents and TTP mappings will be cross-referenced to preserve traceability.

## 9. Collection Limitations

The assessment recognises several limitations:

- Not all incidents become publicly known.
- Reporting visibility differs between countries and sectors.
- Some technical findings may remain classified or commercially restricted.
- Public attribution often relies on evidence that cannot be independently inspected.
- Reporting frequency does not necessarily correspond to actual operational frequency.
- Social-media claims may be inaccurate, misleading or deliberately deceptive.
- Multiple publications may repeat information from a single original source.

These limitations will be reflected in analytical conclusions.

## 10. Collection Completion Criteria

Collection may be considered sufficiently mature for initial analysis when:

- Every PIR has received targeted collection effort.
- Relevant official and independent sources have been examined.
- Major identified campaigns have been reviewed.
- Material competing perspectives have been sought and documented.
- Technical findings can be traced to specific sources.
- Significant corroboration gaps and reporting limitations are identified.
- The incident dataset has undergone initial quality review.

Collection completeness does not imply that every incident has been identified.

## 11. Review and Change Control

The collection plan may be revised when new evidence, intelligence gaps or methodological concerns justify a change.

Changes to the scope, inclusion criteria or collection methodology must be documented.

The original assessment period and geographic boundaries will remain unchanged unless explicitly revised.

---

**Methodological Reference:** CTI & OSINT Analytical Standard v1.0

**Project:** Russian State-Linked Cyber Activity in Europe, 2025–2026
