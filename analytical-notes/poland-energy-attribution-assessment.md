
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


## Assessment status

Preliminary attribution assessment. Further corroboration required.
