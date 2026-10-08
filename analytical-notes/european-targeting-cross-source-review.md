
# European Targeting — Cross-Source Review

**Assessment date:** 8 October 2026
**Status:** Preliminary
**Related incident:** INC-001
**Sources reviewed:** SRC-002, SRC-003
**Relevant requirement:** PIR-02

## Intelligence Question

To what extent does Microsoft Threat Intelligence corroborate Black Lotus Labs' reporting about European targeting and victimisation in the FrostArmada campaign?

## 1. Black Lotus Labs — SRC-002

Black Lotus Labs reports observations involving network infrastructure in Italy, a national identity platform in an unnamed European country, and connections involving European IT, hosting and cloud service providers.

These observations indicate European infrastructure exposure and potentially affected services.

They do not independently establish the location or identity of every end user, intended target or successfully compromised account.

## 2. Microsoft Threat Intelligence — SRC-003

Microsoft reports identifying more than 200 affected organisations and 5,000 consumer devices in the wider campaign.

The report identifies government, information technology, telecommunications and energy among affected sectors.

Microsoft describes adversary-in-the-middle activity against Microsoft Outlook on the web domains and reports separate follow-on collection involving at least three government organisations in Africa.

The public article does not provide a European country-level breakdown of affected organisations or devices.

## 3. Cross-Source Comparison

### Campaign activity

Both sources describe router compromise, DNS manipulation and subsequent malicious network activity.

**Assessment:** Overlapping technical reporting supports the existence of the wider campaign.

### European geographic exposure

Black Lotus Labs provides specific European infrastructure and service observations.

Microsoft's public report does not independently confirm the same named European infrastructure observations.

**Assessment:** European exposure is supported by SRC-002, but precise geographic corroboration from SRC-003 is not established.

### Sectoral targeting

Microsoft identifies several sectors affected by the global campaign.

Black Lotus Labs identifies European service-provider and infrastructure connections.

**Assessment:** The two reports do not establish a verified European sector-by-sector victim distribution.

### European victim numbers

Neither source provides a sufficiently detailed, independently verifiable dataset of confirmed European organisational compromises.

**Assessment:** No European victim total can be calculated from these publications.

## 4. Analytical Judgements

**Judgement 1:** The campaign involved European infrastructure and service connections.

Confidence: Moderate, primarily based on SRC-002.

**Judgement 2:** Microsoft corroborates the wider technical campaign but does not independently establish Black Lotus Labs' specific European geographic findings.

Confidence: Moderate.

**Judgement 3:** The available public evidence is insufficient to quantify confirmed European organisational or account compromises.

Confidence: Moderate in the assessment of evidence insufficiency, not a claim that no compromises occurred.

## 5. Limitations

- Global impact figures must not be represented as European victim counts.
- Infrastructure geography and victim geography are distinct.
- Shared investigative relationships may limit independence.
- The absence of named European victims in SRC-003 does not establish an absence of European victims.
- Reported sectoral impact is global unless the source explicitly identifies a European subset.

## 6. Collection Requirements

1. Examine SRC-001 for specific European geographic evidence.
2. Seek national CERT reporting and victim disclosures.
3. Identify whether any European organisational compromises are independently confirmed.
4. Maintain separate fields for infrastructure location, target location and confirmed victim location in future incident-level records.

## Conclusion

Microsoft corroborates the wider router compromise and DNS hijacking campaign but does not provide sufficient public geographic detail to independently validate Black Lotus Labs' specific European observations.

INC-001 should retain qualified European geographic coverage without assigning unsupported country-level victim counts.
