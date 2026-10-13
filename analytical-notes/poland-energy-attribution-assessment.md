
# Attribution Assessment: December 2025 Polish Cyberattacks

## Assessment scope

This note evaluates the publicly reported attribution of the coordinated cyberattacks against Polish renewable-energy installations, a combined heat-and-power facility, and a manufacturing company on 29 December 2025.

**Primary source:** SRC-006 — CERT Polska, *Energy Sector Incident Report - 29 December 2025*.

**Related incidents:** INC-002, INC-003, INC-004.

## 1. Reported attribution

CERT Polska associates the attacks with an activity cluster publicly identified under several names:

- Static Tundra — Cisco
- Berserk Bear — CrowdStrike
- Ghost Blizzard — Microsoft
- Dragonfly — Symantec

These names are reproduced as presented by CERT Polska. Their precise equivalence across vendors has not been independently evaluated in this project.

## 2. Technical evidence

CERT Polska reports a high degree of overlap between infrastructure used in the December 2025 attacks and infrastructure associated with the previously documented activity cluster.

The reported similarities include:

- Compromised virtual private servers
- Compromised routers
- Network traffic patterns
- Characteristics of anonymisation infrastructure

These findings provide a technical basis for associating the operation with the previously tracked cluster.

However, this assessment has not independently reproduced the underlying infrastructure analysis or established the uniqueness of the reported overlaps.

## 3. Behavioural consistency

CERT Polska notes that the cluster has previously demonstrated an interest in the energy sector and capabilities relevant to industrial environments.

The targeting and destructive activity observed in Poland are consistent with those characteristics.

Behavioural consistency provides contextual support but is not sufficient on its own to establish actor identity.

CERT Polska identifies this as the first publicly described destructive activity attributed to the cluster. Consequently, the destructive nature of the operation should not be treated as an established historical signature of that actor.

## 4. Attribution layers

### Technical activity

The destructive attacks and their operational consequences are documented by CERT Polska's incident investigation.

### Activity-cluster association

CERT Polska reports technical infrastructure overlaps supporting association with Static Tundra and the other named cluster labels.

### Russian state organisational attribution

Cisco Talos (SRC-007) assesses Static Tundra as a Russian state-sponsored cyberespionage actor associated with Energetic Bear and the Russian FSB's Center 16. This provides historical attribution context for the activity cluster identified by CERT Polska.

The evidence must be evaluated in two distinct stages:

1. CERT Polska (SRC-006; CLM-006) associates the December 2025 Polish attacks with the Static Tundra activity cluster through reported infrastructure overlaps.
2. Cisco Talos (SRC-007; CLM-007) provides historical research connecting Static Tundra to Russian state-sponsored activity.

Together, these findings support a preliminary assessment that the Polish attacks are associated with a historically Russian state-linked activity cluster.

However, Cisco Talos published its research before the December 2025 attacks. Its findings do not independently corroborate CERT Polska's incident-specific attribution, and the evidence evaluated in this project does not establish that FSB Center 16 directed the December operation.

## 5. Alternative explanations and limitations

The available evidence does not yet allow this project to exclude all alternative explanations, including:

- Reuse of compromised infrastructure by different operators
- Shared infrastructure or tooling between activity groups
- Incomplete visibility into the full attack infrastructure
- Differences in how security vendors define and track activity clusters

These are analytical possibilities, not findings that any particular alternative occurred.

## 6. Preliminary assessment

**Technical incident occurrence:** Supported by CERT Polska's investigation.

**Association with the named activity cluster:** Credible reported attribution, supported by CERT Polska's described infrastructure analysis.

**Independent attribution to a specific Russian state organisation:** Not established within this assessment.

**Overall analytical confidence in cluster association:** Moderate (provisional).

This confidence level reflects the available technical explanation and the source's incident-response expertise, balanced against the absence of independent reproduction of the attribution evidence.

It does not represent a confidence assessment that a specific Russian intelligence service directed the operation.

## 7. Outstanding collection requirements

1. Examine the complete infrastructure-attribution evidence in CERT Polska's technical report.
2. Identify independently published technical reporting about the same December 2025 operation.
3. Evaluate historical reporting linking the named cluster to Russian state activity.
4. Distinguish independent corroboration from reports repeating CERT Polska's conclusions.
5. Reassess attribution confidence when additional evidence is available.

## 8. Sources

- SRC-006 — CERT Polska, *Energy Sector Incident Report - 29 December 2025*, published 30 January 2026.
  https://cert.pl/en/posts/2026/01/incident-report-energy-sector-2025/  
- SRC-007 — Cisco Talos, *Russian state-sponsored espionage group Static Tundra compromises unpatched end-of-life network devices*, published 20 August 2025.
  https://blog.talosintelligence.com/static-tundra/

---

## 9. Attribution update — 11 October 2026

### New evidence

SRC-009 records a UK NCSC announcement published on 13 July 2026 stating that the UK and EU member states formally attributed the December 2025 cyberattack against Poland's energy infrastructure to Russia's FSB Centre 16.

CLM-010 captures this announcement as an official government attribution statement.

This information was not incorporated into the original preliminary assessment above.

### Analytical significance

The government attribution adds an important evidentiary category to the assessment:

1. CERT Polska (SRC-006) reports technical infrastructure overlaps linking the December operation to a previously tracked activity cluster.
2. Cisco Talos (SRC-007) provides historical reporting associating Static Tundra with Russian state-sponsored activity and FSB Centre 16.
3. UK NCSC (SRC-009) reports a formal UK and EU attribution of the December 2025 Polish energy attack to FSB Centre 16.

The third finding is not merely another historical association. It is an explicit government attribution concerning the December 2025 operation.

### Evidence limitations

The NCSC announcement does not publicly disclose the complete intelligence and forensic basis for the attribution.

The project has not established whether the participating governments relied on independent investigations, shared intelligence, CERT Polska findings, or some combination of these.

Consequently, the announcement strengthens the publicly documented attribution case without independently resolving all technical attribution uncertainties.

Its precise applicability to each facility recorded as INC-002, INC-003, INC-004 and INC-005 also remains to be assessed.

### Updated assessment

**Technical incident occurrence:** Supported by CERT Polska's investigation.

**Association with the named activity cluster:** Supported by CERT Polska's reported technical infrastructure analysis; Moderate analytical confidence.

**Formal Russian state organisational attribution:** Established as a reported UK and EU government position identifying FSB Centre 16.

**Independent forensic verification of that attribution within this project:** Not established.

**Overall assessment:** The December 2025 Polish energy operation is now subject to explicit formal government attribution to FSB Centre 16. This materially strengthens the publicly documented attribution case, although the underlying intelligence is not fully inspectable and incident-level attribution boundaries remain unresolved.

### Incident-to-claim traceability — 12 October 2026

CLM-006 is linked in the incident dataset to INC-002 (renewable-energy installations), INC-003 (attempted destructive attack against a combined heat-and-power facility), and INC-004 (manufacturing company). These links record CERT Polska's reported association of the coordinated operation with the named activity cluster; they do not independently verify incident-level Russian state organisational control or direction.

INC-005, the separately reported second combined heat-and-power facility, remains supported by its incident-specific technical and operational-impact claims CLM-008 and CLM-009. The CLM-006 cluster association has not been automatically extended to that facility.

CLM-010 records the broader formal UK/EU government attribution of the December 2025 Polish energy operation to FSB Centre 16. Its precise applicability to individual facilities, and the independence of the underlying intelligence and forensic evidence, remain unresolved in this assessment.

### Further collection requirements

- Obtain and evaluate the multinational advisory referenced by the NCSC.
- Determine whether additional governments published separate attribution statements or technical evidence.
- Establish which individual Polish incidents fall within the scope of the formal attribution.
- Reassess confidence after evaluating the independence and specificity of the supporting evidence.

**Additional source:** SRC-009 — UK NCSC, *UK and Allies urge critical sectors to improve defences against Russian intelligence targeting*, 13 July 2026.

https://www.ncsc.gov.uk/news/uk-and-allies-urge-critical-sectors-to-improve-defences-against-russian-intelligence-targeting

## Assessment status

Preliminary attribution assessment. Further corroboration required.

---

## Attribution update — 13 October 2026: ESET and Dragos evidence

### Purpose and continuity

This append-only update incorporates two additional technical attribution perspectives concerning the coordinated cyberattacks against Polish energy infrastructure on 29 December 2025.

It supplements, rather than replaces, the earlier CERT Polska assessment and the 11 October 2026 update concerning formal UK/EU government attribution.

The original findings remain preserved as part of the project's analytical decision history.

### Additional registered sources and claims

**SRC-018 / CLM-018 — ESET Research**

ESET reports detecting and blocking three DynoWiper samples deployed against a Polish energy organisation on 29 December 2025. ESET attributes the destructive activity to Sandworm with medium confidence, citing malware and operational similarities to previously investigated activity, including ZOV.

ESET did not observe the initial access stage and acknowledges the possibility of collaboration between different threat actors. Its technical findings support the reported attempted destructive execution but do not independently establish Sandworm responsibility.

The apparent correspondence with INC-003, the attempted destructive attack against a Polish combined heat-and-power facility, is plausible but not confirmed. CLM-018 therefore has no incident ID assigned.

**SRC-019 / CLM-019 — Dragos**

Dragos reports direct incident-response involvement relating to the December 2025 Polish energy-sector attacks and assesses ELECTRUM responsibility with moderate confidence.

Its public analysis focuses on distributed energy infrastructure, including remote terminal units, network devices and communications capabilities associated with renewable electricity generation.

CLM-019 is linked to INC-002 as the most directly relevant grouped incident. This does not establish ELECTRUM responsibility for every affected installation.

Dragos acknowledges CERT Polska's investigation. The independence of its underlying attribution evidence remains unresolved, and the detailed Dragos intelligence brief has not been confirmed as obtained or reviewed.

### Comparison with existing attribution assessments

**CERT Polska — SRC-006 / CLM-006:** Reports infrastructure and network-activity overlaps associating the coordinated attacks with the Static Tundra / Berserk Bear / Ghost Blizzard / Dragonfly activity cluster.

**ESET — SRC-018 / CLM-018:** Attributes the attempted DynoWiper destructive activity to Sandworm with medium confidence, relying on malware and operational similarities.

**Dragos — SRC-019 / CLM-019:** Attributes the Polish distributed-energy attacks to ELECTRUM with moderate confidence, citing its reported incident-response involvement and threat-activity analysis.

**UK NCSC — SRC-009 / CLM-010:** Reports formal UK and EU government attribution of the December 2025 Polish energy operation to Russia's FSB Centre 16.

These statements represent different evidentiary categories and investigative scopes. Their publication does not establish that the underlying attribution evidence is independent or that the named activity clusters correspond to three distinct perpetrators.

Historical overlap between ELECTRUM and Sandworm does not prove identical operators in this incident. Conversely, CERT Polska's Static Tundra assessment does not by itself invalidate ESET's or Dragos's findings.

### Alternative explanations

The available evidence permits several explanations that are not necessarily mutually exclusive:

1. One actor conducted the operation, with overlapping or insufficiently distinctive malware and infrastructure indicators producing different classifications.
2. Different actors participated in separate operational stages, such as access preparation and destructive execution.
3. Investigators examined different victims or components of a wider coordinated operation.
4. Differences in vendor activity-cluster definitions contributed to the apparent attribution discrepancy.

These remain hypotheses. The project has not established that any particular explanation occurred and does not assign probabilities to them.

### Updated analytical judgements

**High confidence:** The registered publications document materially different attribution assessments concerning the December 2025 Polish attacks.

**Moderate confidence:** The incident reporting supports a coordinated destructive operation affecting multiple Polish facilities and organisations.

**Moderate confidence:** CERT Polska's reported Static Tundra infrastructure association remains a credible technical assessment. ESET and Dragos provide additional relevant perspectives, but the exact relationship between their attribution evidence and CERT Polska's findings has not been independently resolved.

**Low confidence:** The publicly examined evidence enables this project to independently determine which Russian intelligence organisation directed each component of the operation.

The formal UK/EU attribution to FSB Centre 16 is an established government position concerning the operation. Its complete underlying intelligence and its applicability to each individual incident remain unavailable for independent verification.

The Low confidence judgement concerns independent resolution of organisational responsibility. It does not constitute a finding that the government attribution is false.

### Incident-level boundaries

- **INC-002:** Directly relevant to CERT Polska and Dragos reporting; CLM-019 records the Dragos attribution without establishing responsibility at every installation.
- **INC-003:** Potentially overlaps with ESET's DynoWiper observations; exact victim correspondence remains unconfirmed.
- **INC-004:** Retains the CERT Polska-reported cluster association; ESET and Dragos findings are not automatically extended to this manufacturing incident.
- **INC-005:** Remains a distinct CHP incident; neither the CERT Polska cluster attribution nor ESET/Dragos actor assessments are automatically applied without incident-specific evidence.

No existing incident record, source reliability grade, claim attribution status or MITRE ATT&CK mapping is changed by this analytical update.

### Outstanding collection requirements

1. Establish whether ESET's DynoWiper victim corresponds to INC-003.
2. Obtain and examine the detailed Dragos ELECTRUM intelligence brief, if publicly accessible.
3. Identify which Dragos observations are independent of CERT Polska's investigation.
4. Reconcile victim-level and operational-stage coverage across CERT Polska, ESET and Dragos.
5. Assess the applicability of the formal UK/EU FSB Centre 16 attribution to individual incidents.
6. Seek original technical evidence and alternative reporting, including relevant Russian, Ukrainian and independent perspectives, without treating derivative reporting as independent corroboration.

### Decision and status

**Decision dated 13 October 2026:** Retain the separate Static Tundra, Sandworm and ELECTRUM attribution claims. Do not select a single perpetrator classification or revise incident-level attribution without further evidence.

**Status:** Preliminary consolidated assessment; competing explanations and organisational responsibility remain unresolved.

**Source and claim references:** SRC-006, SRC-007, SRC-009, SRC-018, SRC-019; CLM-006, CLM-007, CLM-010, CLM-018, CLM-019.

