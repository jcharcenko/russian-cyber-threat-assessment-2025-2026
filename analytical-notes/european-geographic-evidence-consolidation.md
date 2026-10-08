
# European Geographic Evidence — Consolidated Assessment

**Assessment date:** 8 October 2026
**Status:** Preliminary
**Related incident:** INC-001
**Sources:** SRC-001, SRC-002, SRC-003
**Relevant requirement:** PIR-02

## Intelligence Question

What geographic conclusions about European infrastructure exposure and targeting are supported by the three principal technical reports on the APT28 / Forest Blizzard router compromise campaign?

## 1. UK NCSC — SRC-001

The NCSC describes router exploitation and DNS hijacking activity extending from 2024 into 2026.

It assesses the campaign as initially opportunistic, with subsequent filtering for users of potential intelligence value.

The advisory also reports interactive operations against a small number of MikroTik routers, often located in Ukraine, assessed as likely to be of intelligence value.

**Evidence classification:** Officially reported technical activity and intelligence assessment.

**Limitations:**
- Router location does not necessarily establish the location of an intended end-user target.
- The advisory does not identify individual organisations associated with the Ukrainian routers.
- No comprehensive European victim list or country-level impact figures are provided.

## 2. Black Lotus Labs — SRC-002

Black Lotus Labs reports observations involving:

- Nethesis firewalls located in Italy.
- A national identity platform in an unnamed European country.
- Connections involving European IT, hosting and smaller cloud service providers.

These observations provide more specific evidence of European infrastructure and service exposure.

**Limitations:**
- Infrastructure location and intended target location may differ.
- The identity and location of affected end users are not fully established.
- Connections alone do not demonstrate successful account compromise.

## 3. Microsoft Threat Intelligence — SRC-003

Microsoft reports global campaign activity affecting organisations and consumer devices across multiple sectors.

Its public report does not provide a country-by-country breakdown of confirmed European organisational victims.

**Limitations:**
- Global counts cannot be used as European victim totals.
- Global sector information cannot be presented as a verified European sector distribution.
- Microsoft's reporting does not independently validate every European geographic observation described by Black Lotus Labs.

## 4. Consolidated Findings

### Finding A — European infrastructure exposure

The reporting identifies activity involving infrastructure located in Italy and Ukraine, as well as European service-provider connections.

**Confidence: Moderate.**

### Finding B — European targeting

The NCSC describes selective activity involving routers in Ukraine. Black Lotus Labs reports connections involving European services, including a national identity platform.

These observations are consistent with potential European intelligence targeting, but do not establish a complete list of intended organisational targets.

**Confidence: Low to Moderate, depending on the specific observation.**

### Finding C — European victimisation

The available publications do not establish a reliable count of confirmed European organisational or account compromises.

**Confidence: Moderate in the assessment that published evidence is insufficient.**

## 5. Data Handling Decisions

For INC-001:

- Retain the campaign-level geographic scope.
- Do not assign a European victim count.
- Do not classify every European infrastructure observation as a confirmed victim incident.
- Record Italy and Ukraine as reported infrastructure locations, not automatically as locations of confirmed organisational compromises.
- Retain uncertainty about country-specific targeting and successful credential theft.

## 6. Further Collection Requirements

1. Seek national CERT reporting relating to Italy and Ukraine.
2. Identify any named European organisations publicly confirming compromise.
3. Distinguish router compromise from subsequent credential or account compromise.
4. Establish whether infrastructure observations from the three sources are independently corroborated.
5. Review the campaign dataset when verified country-specific incidents become available.

## Conclusion

The available technical reporting supports European infrastructure exposure and selected activity involving Ukrainian routers. It does not support a comprehensive European victim count or country-level distribution of confirmed organisational compromises.

The campaign should remain a single qualified record until distinct victim incidents can be supported by additional evidence.
