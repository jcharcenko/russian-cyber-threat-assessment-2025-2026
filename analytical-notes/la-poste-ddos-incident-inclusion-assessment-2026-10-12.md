# La Poste DDoS — Incident Inclusion Assessment

**Project:** Russian State-Linked Cyber Activity in Europe, 2025–2026  
**Review date:** 2026-10-12  
**Status:** Preliminary inclusion assessment completed; attribution unresolved  
**Related sources:** SRC-015; SRC-016; SRC-017  
**Related claims:** CLM-016; CLM-017  
**Incident dataset decision:** Do not create INC-007 at this stage  
**Relevant PIRs:** PIR-01; PIR-04

## 1. Purpose

This note documents the decision not to include the December 2025–January 2026 La Poste distributed denial-of-service (DDoS) activity in the main incident dataset at the present evidence threshold.

The exclusion is an analytical scoping decision. It does not establish that Russian-linked actors were uninvolved, nor does it diminish the reported operational impact on La Poste.

## 2. Documented Operational Activity

La Poste Groupe reported DDoS disruption beginning on 22 December 2025, affecting access to online postal and banking services. Its subsequent updates described partial restoration and renewed disruption on 1 January 2026.

La Banque Postale later reported that DDoS activity continued until 5 January 2026 and that core banking systems remained operational. Its retrospective account also described substantial traffic volumes and defensive response measures.

These accounts support the existence of operational disruption. However, SRC-015 and SRC-016 originate from the same corporate group and must not be counted as independent corroboration.

The available operator reporting does not identify a confirmed perpetrator.

**Evidence:** SRC-015; SRC-016; CLM-016.

## 3. Reported NoName057(16) Responsibility Claim

La Tribune reported on 24 December 2025 that NoName057(16) had published a Telegram responsibility claim concerning La Poste's digital-identity service.

The article also documented observations challenging the credibility of that claim:

- La Poste reportedly stated that its digital-identity service remained available, despite disruption to other services.
- Baptiste Robert of Predicta Lab questioned the correspondence between the claimed target and the principal reported disruption, as well as the timing of the claim.
- Pierre Delcher of Harfang Lab stated that La Poste websites had not been identified in observed NoName057(16) target-distribution activity.

These observations weaken the evidentiary value of the responsibility claim but do not conclusively disprove participation. DDoS effects can be intermittent, and the completeness of target-list monitoring has not been established.

The original Telegram message and its account provenance have not been independently authenticated. The underlying technical observations supporting the expert assessments have not been examined.

**Evidence:** SRC-017; CLM-017.

## 4. Attribution Assessment

The following propositions must remain separate:

1. **Reported claim:** NoName057(16) reportedly claimed responsibility for disruption of a specific La Poste service.
2. **Operational responsibility:** Available evidence does not establish that NoName057(16) conducted the wider La Poste DDoS operation.
3. **Russian state direction:** No reviewed incident-specific evidence establishes direction, tasking or operational control by Russian state authorities.

The group's pro-Russian orientation and historical activity are not sufficient to infer Russian state sponsorship of this incident.

**Analytical confidence:** Moderate that the presently reviewed evidence is insufficient for inclusion as Russian state-linked activity. Confidence in NoName057(16)'s actual operational responsibility remains Low.

These confidence statements concern different propositions and must not be conflated.

## 5. Competing Explanations

Several hypotheses remain compatible with the reviewed evidence:

- NoName057(16) conducted the wider operation.
- NoName057(16) conducted limited or separate activity but overstated its impact.
- NoName057(16) opportunistically claimed an unrelated disruption.
- Another unidentified criminal, activist or state-linked actor conducted the operation.

No reliable probabilities can presently be assigned to these hypotheses. None should be treated as established.

## 6. Incident Dataset Inclusion Decision

The incident meets the temporal, geographic and operational criteria for relevance:

- Activity occurred within the 2025–2026 assessment period.
- A European organisation was affected.
- DDoS disruption was reported by the affected operator.

However, the project specifically assesses Russian state-linked cyber activity affecting European organisations.

The currently reviewed evidence does not establish a sufficiently supported incident-specific link to a Russian state actor or to an actor credibly demonstrated to have conducted this operation.

**Decision:** Do not create INC-007 in `research/incident-dataset.csv` at this stage.

This decision should not be interpreted as disproving Russian involvement. It prevents a disputed attribution from being treated as an established incident characteristic or incorporated into state-linked activity trend calculations.

No incident-specific MITRE ATT&CK mapping is assigned.

## 7. Conditions for Reconsideration

Reconsider inclusion if additional evidence becomes available, particularly:

1. Authenticated original NoName057(16) communications with verifiable timing and target information.
2. Independent technical reporting connecting group-controlled infrastructure, tools or participating systems to the affected La Poste services.
3. Investigative findings that distinguish an actor's public claim from evidence of actual operational responsibility.
4. Credible government or technical attribution accompanied by sufficient incident-specific supporting detail.
5. New evidence clarifying whether the claimed digital-identity disruption was part of, separate from or unrelated to the wider DDoS activity.

Government attribution statements, if obtained, must be recorded as attributed assessments and evaluated separately from independently available technical evidence.

## 8. Source Dependencies and Limitations

- SRC-015 and SRC-016 are related operator accounts, not independent corroboration.
- SRC-017 combines original named expert interviews with reporting derived from operator statements and a purported actor communication.
- The original Telegram communication has not been independently authenticated.
- Underlying DDoS telemetry, complete target-distribution observations and investigative forensic findings are unavailable.
- A reported service being accessible during one observation window does not establish uninterrupted availability throughout the attack period.

## 9. Decision History and Follow-Up

**2026-10-12 — Preliminary assessment:** The La Poste DDoS activity should remain outside the main Russian state-linked incident dataset pending stronger attribution evidence.

**2026-10-12 — Documentation:** The decision was recorded in this analytical note without changing existing source, claim, incident or TTP records.

**Next action:** Retain SRC-015–SRC-017 and CLM-016–CLM-017 for traceability. Reassess incident inclusion only if materially new attribution evidence becomes available.

This note records the current judgement and its rationale. Any subsequent change should be documented as a new dated decision rather than silently overwriting the historical assessment.
