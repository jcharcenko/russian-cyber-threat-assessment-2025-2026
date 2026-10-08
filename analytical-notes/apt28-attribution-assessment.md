
# APT28 / Forest Blizzard Attribution Assessment

**Assessment date:** 8 October 2026  
**Status:** Preliminary  
**Related claim:** CLM-002  
**Sources:** SRC-001, SRC-002, SRC-003

## Intelligence Question

What does the publicly available evidence establish about attribution of the router compromise and DNS hijacking activity to APT28 / Forest Blizzard and Russian GRU Unit 26165?

## Source Positions

### SRC-001 — UK NCSC

The NCSC attributes the reported activity to APT28 and assesses APT28 as almost certainly Russian GRU Unit 26165.

This is an official attribution assessment. The full underlying attribution evidence is not publicly available for independent reproduction.

### SRC-002 — Black Lotus Labs

Black Lotus Labs associates the FrostArmada activity with Forest Blizzard / APT28 and reports technical observations from its network visibility.

The research contributes evidence about the activity and infrastructure, but the independence of its attribution assessment requires further examination.

### SRC-003 — Microsoft Threat Intelligence

Microsoft reports router compromise and DNS hijacking activity associated with Forest Blizzard and Storm-2754.

Microsoft describes its own security observations. Its reporting supports further assessment of the threat-cluster attribution, but does not by itself establish the specific GRU unit attribution.

## Preliminary Analytical Judgements

**Judgement 1 — Technical activity**

The three sources provide overlapping reporting about router compromise, DNS manipulation and traffic redirection. Some observations derive from the reporting organisations' own telemetry.

**Confidence: Moderate.**

**Judgement 2 — Threat-cluster attribution**

Multiple sources associate the activity with Forest Blizzard / APT28. However, investigative collaboration and potentially shared evidence limit our ability to treat the attribution assessments as fully independent.

**Confidence: Not yet assigned.**

**Judgement 3 — GRU Unit 26165 attribution**

The NCSC explicitly identifies the Russian GRU unit. The complete supporting attribution chain has not been independently reproduced in this assessment.

**Confidence: Not yet assigned.**

## Alternative Explanations and Limitations

- Shared infrastructure or tradecraft alone may not uniquely identify an actor.
- Investigative collaboration may produce apparently independent but evidence-dependent reporting.
- Threat-cluster naming conventions are not necessarily equivalent across vendors.
- Public reporting may omit sensitive attribution evidence.
- Absence of publicly disclosed evidence is not evidence that investigators lack such evidence.

## Further Collection Requirements

1. Identify the specific attribution indicators disclosed by each source.
2. Establish whether Microsoft and Black Lotus Labs reached their attribution assessments independently.
3. Examine historical primary-source evidence linking APT28 to GRU Unit 26165.
4. Separate campaign attribution from the broader attribution of the APT28 threat cluster.
5. Reassess CLM-002 and consider splitting it into separate threat-cluster and organisational attribution claims.

## Assessment Status

Preliminary. No final attribution credibility grade or confidence level assigned.
