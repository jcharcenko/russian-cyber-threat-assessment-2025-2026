
# Source Evaluation Methodology

**Project:** Russian State-Linked Cyber Activity in Europe  
**Standard:** CTI & OSINT Analytical Standard v1.0  
**Version:** 1.0  
**Status:** Approved methodology

## 1. Purpose

This document establishes a consistent framework for evaluating the reliability of intelligence sources, credibility of individual claims, independent corroboration and confidence in analytical judgements.

The objective is to ensure that findings are evidence-led, transparent, reproducible and resistant to confirmation bias.

## 2. Admiralty Code

The assessment uses the established Admiralty Code approach to intelligence evaluation.

Source reliability and information credibility are graded independently.

### 2.1 Source Reliability

| Grade | Classification |
|---|---|
| A | Completely reliable |
| B | Usually reliable |
| C | Fairly reliable |
| D | Not usually reliable |
| E | Unreliable |
| F | Reliability cannot be judged |

Source reliability is assessed by considering:

- Historical accuracy and reporting record.
- Expertise and access to relevant information.
- Transparency of collection and analytical methods.
- Previous corrections or documented inaccuracies.
- Possible conflicts of interest or reporting incentives.
- Availability of evidence supporting published claims.

Political affiliation, nationality or organisational category alone does not determine reliability.

An unfamiliar source should generally remain F until sufficient information is available to assess its reliability.

Grade A is reserved for exceptional circumstances and should not be assigned automatically to official or established sources.

### 2.2 Information Credibility

| Grade | Classification |
|---|---|
| 1 | Confirmed by other sources |
| 2 | Probably true |
| 3 | Possibly true |
| 4 | Doubtful |
| 5 | Improbable |
| 6 | Truth cannot be judged |

Information credibility is evaluated by considering:

- Supporting technical or documentary evidence.
- Independent corroboration.
- Consistency with established facts.
- Internal coherence and specificity.
- Contradictory reporting.
- Gaps in the available evidence.

A reliable source can publish incorrect information, while a source of unknown reliability can publish independently confirmed information.

Ratings must include a recorded justification.

## 3. Independent Corroboration

Corroboration requires separate evidence streams supporting the same material claim.

For example:

- Two independent technical investigations may provide corroboration.
- An official advisory and separate victim evidence may support corroboration.
- Multiple news articles quoting the same advisory do not constitute independent confirmation.

Sources must be checked for common origins, shared datasets and repeated reporting.

A source may be independent as an organisation without providing independent evidence.

## 4. Attribution Evaluation

The assessment distinguishes three elements:

**Reported attribution:** An external organisation attributes activity to a particular actor.

**Supporting evidence:** Publicly available information supporting or challenging that attribution.

**Analytical judgement:** The assessment's own conclusion regarding the strength of attribution.

Official attribution statements are evidence that an authority made the attribution. They do not automatically constitute independently verified proof of responsibility.

The same principle applies to official denials.

Where public evidence is insufficient to assess attribution independently, the report will retain the originating source's attribution language and disclose this limitation.

## 5. Competing Perspectives

Materially different accounts will be examined using consistent evidentiary criteria.

Relevant perspectives may include:

- Russian government and official agencies.
- European governments and institutions.
- Ukrainian authorities.
- Other affected governments.
- Independent technical researchers.
- Regional and investigative journalists.
- Public OSINT and alternative-media reporting.

Official statements are primary evidence of the issuing party's stated position.

They are not automatically proof of the underlying factual allegation or denial.

The assessment does not assume that competing positions are equally credible or that the truth necessarily lies between them.

## 6. Social Media and Unverified Claims

Public Telegram messages, social-media posts, forum discussions and claims of responsibility may provide valuable intelligence leads.

However, they must be clearly distinguished from independently verified findings.

Possible claim classifications include:

- Reported
- Corroborated
- Partially corroborated
- Disputed
- Unverified
- Contradicted

A claimed cyberattack should not be treated as a confirmed compromise without supporting evidence.

Unverified claims may remain in the collection-leads register.

## 7. Technical Evidence and MITRE ATT&CK

Technical findings must be linked to documented incidents or campaigns.

Each ATT&CK mapping must be classified as:

| Classification | Meaning |
|---|---|
| Explicitly reported | Incident-specific source explicitly reports the technique or supporting behaviour. |
| Analyst mapped | Documented behaviour supports a technique mapping made by the analyst. |
| Inferred | Technique is suspected but not demonstrated by incident-specific evidence. |

Inferred techniques must not be counted as observed TTPs.

Mappings must include the supporting source, behaviour description and ATT&CK technique identifier.

Techniques must be checked against the relevant MITRE ATT&CK documentation.

Historical actor profiles alone do not establish that a particular technique occurred during a specific campaign.

## 8. Analytical Confidence

Source grading is separate from confidence in the final analytical judgement.

The following confidence levels will be used:

### High Confidence

The judgement is supported by strong evidence, substantial independent corroboration and limited material contradictions.

### Moderate Confidence

The judgement has credible supporting evidence, but significant information gaps, source dependencies or plausible alternative explanations remain.

### Low Confidence

The judgement relies on limited, ambiguous, disputed or weakly corroborated information.

Confidence levels do not represent numerical probabilities and must not be used as substitutes for likelihood assessments.

Each major judgement must include a rationale and acknowledgement of material limitations.

## 9. Anti-Hallucination Controls

The following rules apply to AI-assisted research:

1. No material factual claim may enter the final report solely from AI-generated text or model memory.
2. Sources must be inspected before being used to support significant claims.
3. Search-result snippets alone are insufficient for final verification.
4. Original sources should be preferred over derivative reporting.
5. Dates, quotations, actor names, vulnerabilities, malware names and ATT&CK identifiers must be checked.
6. Missing evidence must not be invented or inferred as fact.
7. Contradictory evidence must be recorded rather than silently discarded.
8. Source ratings must not be adjusted to support a preferred conclusion.
9. Material information gaps must be disclosed.
10. Executive assessments and key judgements must undergo a final claim-by-claim evidence audit.

AI assistance may support searching, structuring, extraction, translation and analytical drafting, but the final assessment remains subject to evidence verification and analyst review.

## 10. Evidence Traceability

Every significant analytical claim must be traceable through the project records.

The intended structure is:

Analytical Judgement  
→ Supporting Claims  
→ Incident or Campaign Records  
→ Source Register  
→ Original Evidence

The source register and claim register will contain unique identifiers for cross-referencing.

Where original evidence cannot be accessed, the limitation must be recorded.

## 11. Publication Quality Control

Before publication, verify that:

- Material factual claims have identifiable sources.
- Source reliability and information credibility have been evaluated separately.
- Important claims have been assessed for independent corroboration.
- Competing material evidence has been examined.
- Attribution language accurately reflects the available evidence.
- Technical mappings reflect documented incident behaviour.
- Analytical confidence is supported by an explicit rationale.
- Charts and statistics accurately represent the underlying dataset.
- Reporting bias and collection limitations are disclosed.
- Unsupported claims have been removed or appropriately qualified.

## 12. Methodological References

The source-evaluation framework draws upon established intelligence evaluation practices.

Relevant references include:

- UK Ministry of Defence, *Joint Doctrine Publication 2-00: Intelligence, Counter-Intelligence and Security Support to Joint Operations*.
- NATO-style Admiralty Code source and information grading.
- MITRE ATT&CK knowledge base for technical behaviour classification.

The detailed operational procedures and decision rules in this document are project-specific implementations and should not be represented as official NATO requirements.

---

**Project Methodology:** CTI & OSINT Analytical Standard v1.0  
**Document Version:** 1.0
