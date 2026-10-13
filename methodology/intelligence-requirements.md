# Intelligence Requirements

**Project:** Russian State-Linked Cyber Operations Against European Critical Infrastructure
**Assessment Period:** 1 January 2025 – 30 September 2026
**Status:** Revised scope — three selected case studies
**Methodology:** CTI & OSINT Analytical Standard v1.0
**Change Control:** DEC-001, methodology/decision-history.md

## 1. Primary Intelligence Question

What do three selected, publicly documented cyber operations reveal about Russian state-linked targeting of European critical infrastructure, the methods employed, observed operational consequences, attribution uncertainty and defensive implications during 2025–2026?

The assessment is a comparative analysis of selected cases, not a comprehensive survey of Russian cyber operations across Europe.

## 2. Assessment Scope

### Geographic Scope

The geographic scope encompasses European critical-infrastructure organisations and supporting suppliers, explicitly including:

- European Union member states.
- Ukraine.
- United Kingdom.
- Norway.
- Relevant European partner countries.

The core cases concern Poland, Ukraine and Sweden. Wider European activity may be considered where it directly informs the selected cases, but does not expand the core case-study selection.

### Threat Actor Scope

The assessment considers:

- Actors linked to Russian state agencies by documented attribution.
- Cyber operations attributed by identifiable sources to Russian state-linked groups.
- Proxy actors where evidence supports a specific relationship to Russian state interests or direction.

Russian-speaking cybercriminals, politically aligned hacktivists and groups merely claiming Russian affiliation are not automatically considered state-linked.

Reported attribution must be distinguished from independently corroborated evidence and the project's own analytical judgements.

### Assessment Period

1 January 2025 – 30 September 2026.

Earlier activity may provide historical context but must not be counted as activity occurring within the assessment period. Reports published after the period may be used when they provide evidence concerning activity within it. Incident dates, disclosure dates and publication dates must be distinguished.

### Selected Case Studies

1. **Polish energy-sector attacks, December 2025:** INC-002, INC-003 and INC-005, assessed as components of a coordinated operation rather than three independent campaigns.
2. **Ukrainian industrial supplier campaign, January–February 2025:** INC-008, examining industrial supplier targeting, documented intrusion activity and suspected downstream critical-infrastructure objectives.
3. **Swedish district-heating incident, spring 2025:** INC-006, examining reported attempted disruption, government attribution and the limitations of unavailable public forensic evidence.

Other existing research records are retained for provenance and possible context but do not automatically qualify as core case-study evidence.

## 3. Priority Intelligence Requirements

### PIR-01: Threat Actors and Attribution

What evidence supports Russian state-linked attribution in each selected case, and where does attribution remain uncertain or disputed?

**Key Intelligence Questions:**

- Which actors or clusters were identified by each reporting source?
- What incident-specific technical evidence supports or challenges those identifications?
- Are attribution assessments independent or derived from overlapping investigations?
- Where do government attribution statements exceed what public technical evidence independently establishes?
- Can actor responsibility and specific Russian state direction be distinguished?
- What alternative explanations remain plausible?

### PIR-02: Targeting and Objectives

Which critical-infrastructure operators or supporting suppliers were targeted, and what objectives and operational consequences can be established?

**Key Intelligence Questions:**

- What organisations, infrastructure, industrial functions or suppliers were reportedly targeted?
- Which activity involved attempted access, confirmed compromise, destructive actions or verified operational disruption?
- What evidence supports espionage, sabotage, prepositioning or supply-chain access objectives?
- Where is attacker intent inferred rather than demonstrated?
- What consequences for service availability, industrial processes, safety or business continuity were verified?
- How do reporting gaps affect conclusions about the scale and severity of each case?

### PIR-03: Technical Tradecraft

Which tactics, techniques and procedures were documented in the selected operations?

**Key Intelligence Questions:**

- What initial access methods, malware, vulnerabilities and infrastructure were documented?
- What evidence supports persistence, lateral movement, command and control, or destructive activity?
- Which behaviours justify incident-specific MITRE ATT&CK Enterprise or ICS mappings?
- Which technical observations are direct findings, publisher reports or analyst inferences?
- What telemetry and detection opportunities follow from documented behaviour?
- Where does insufficient forensic evidence prevent technical conclusions?

### PIR-04: Competing Perspectives and Evidence

How do government, victim, technical-research and relevant Russian official accounts compare for the selected operations?

**Key Intelligence Questions:**

- What attribution claims, denials, alternative explanations or material disagreements were published?
- Which claims are supported by independently observable evidence?
- Are apparently corroborating reports genuinely independent?
- Where do actor classifications or incident-impact assessments differ?
- What relevant perspectives were sought but could not be located or verified?
- How do source reliability, information credibility and evidentiary limitations affect the resulting judgements?

### PIR-05: Comparative Findings and Defensive Implications

What supported operational lessons emerge from comparing the three selected cases?

**Key Intelligence Questions:**

- Which access, disruption or resilience issues recur across the selected cases?
- Which apparent similarities are weakened by differences in evidence quality or operational context?
- What monitoring, detection, incident-response and continuity measures are relevant to the documented activity?
- What implications follow for European critical-infrastructure operators and supporting suppliers?
- Which conclusions apply only to a particular case and cannot be generalised?
- Which unresolved developments merit continued monitoring?

## 4. Analytical Boundaries

The assessment will not:

- Infer Russian state involvement solely from language, geography or political alignment.
- Treat claims of responsibility or official attribution as independently proven facts.
- Conflate attempted compromise with confirmed compromise or attempted disruption with verified operational impact.
- Count components of the coordinated Polish operation as independent campaigns.
- Present historical actor TTPs as observed behaviours in the selected incidents.
- Assign MITRE ATT&CK techniques without incident-specific supporting evidence.
- Infer Europe-wide prevalence, trends or operational frequency from three selected cases.
- Treat absence of public forensic evidence as proof that an incident did not occur.
- Present unsupported predictions as established intelligence findings.

The Swedish case will receive evidentiary weight proportionate to its available reporting. Its inclusion does not imply technical or attribution confidence equivalent to the Polish or Ukrainian cases.

## 5. Intended Outputs

1. Full comparative, evidence-led CTI assessment suitable for PDF publication.
2. Concise executive intelligence brief.
3. Professionally presented GitHub repository containing the publication and supporting research.
4. Preserved source, claim, incident and TTP datasets with traceable evidence relationships.
5. LinkedIn publication introducing the research and linking to the report and repository.

## 6. Methodological Reference

This project follows CTI & OSINT Analytical Standard v1.0.

Source reliability and information credibility are evaluated separately using the Admiralty Code (A–F / 1–6).

Analytical judgements use High, Moderate or Low confidence with supporting rationale and explicit limitations.

The revised scope is documented in DEC-001. Historical research and Git commit history are preserved; the narrower publication does not retrospectively invalidate or delete earlier work.
