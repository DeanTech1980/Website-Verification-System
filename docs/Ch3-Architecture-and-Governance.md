---
title: Chapter 3 - Architecture and Governance
description: Defines the technical architecture.
author: Dean John Weiniger
layout: default
---

# Chapter 3 - Architecture and Governance

## Overview
This chapter defines the technical architecture, the end‑to‑end verification lifecycle and the governance models needed to operate a Trusted Websites regime at scale. It balances practical engineering choices (latency, caching, revocation) with institutional design (central, federated or hybrid authorities) and outlines operational safeguards to protect rights and inclusion.

---

## Central Verification Authority models
- **Single global authority:** one supranational body sets standards, issues credentials and operates the authoritative Good List. Pros: uniformity; Cons: single point of political risk and failure.  
- **Federated national authorities:** accredited national or regional bodies perform vetting under shared technical standards and mutual recognition agreements. Pros: respects sovereignty and local law; Cons: interoperability and parity challenges.  
- **Hybrid model:** a core set of global standards and a minimal central coordination layer, with accredited national and sectoral verifiers executing onboarding and audits.

### Roles and responsibilities
- **Standards and policy:** define identity, technical hygiene, acceptable content boundaries and appeals rules.  
- **Issuance and revocation:** vet operators, bind credentials to domain control and identity evidence, revoke on violation.  
- **Audit and oversight:** independent auditors, transparency reports and an oversight board with multi stakeholder representation.  
- **Operational security:** hardened key management, incident response and secure developer practices.

---

## Core technical components
- **Authoritative registry:** a tamper resistant database of verified sites, credential metadata and revocation state.  
- **Credential issuance service:** signs short lived, cryptographically bound credentials (verifiable credentials or extended x.509 variants) after successful KYS checks.  
- **Browser integration layer:** a privacy preserving API for browsers to check verification status, with local caching and revocation push mechanisms.  
- **Monitoring and telemetry:** automated scanners, anomaly detection, and human review queues for flagged sites. Telemetry must be aggregated and privacy preserved.  
- **Third party API gateway:** scoped endpoints for accessibility tools, enterprise controls and research access under strict privacy and rate limits.

---

## Browser integration and UX
- **Check flow:** on navigation, the browser validates a cached token and, when needed, queries the CVA with minimal identifiable data.  
- **Caching and TTLs:** tokens are short lived to limit exposure from credential compromise but aggressively cached to avoid user perceptible latency.  
- **Revocation delivery:** combination of push notifications, short token TTLs and regional mirrors to ensure near real time enforcement.  
- **User signals:** standardised, accessible UI states (verified; not verified; temporary exception) with clear guidance for users and operators.  
- **Fallbacks:** documented, auditable exception paths for emergency access, research, or protected anonymous publication.

---

## Verification lifecycle and workflows
- **Onboarding**
  1. Operator registers and provides identity evidence and domain control proof.  
  2. Automated technical checks (TLS, headers, basic vulnerability scans).  
  3. Policy and content screening for sectoral constraints where applicable.  
  4. Human review for flagged or high-risk applications.  
  5. Credential issuance with explicit scope and TTL.

- **Continuous compliance**
  - Ongoing automated scans for content change, malware, abuse patterns and regressions.  
  - Scheduled renewal workflows requiring re‑affirmation of identity and security posture.  
  - Event‑driven reviews triggered by incident reports or anomaly detection.

- **Revocation and remediation**
  - Immediate suspension for critical violations with clear remediation windows.  
  - Provisional suspension for suspected issues pending expedited review.  
  - Transparent remediation steps and documented appeal timelines.

---

## Governance, oversight and rights protections
- **Multistakeholder oversight:** governance board including civil society, technical experts, browser vendors, industry and government representatives.  
- **Transparency:** published criteria, anonymised enforcement logs, and regular transparency reports.  
- **Independent appeals:** an independent review panel to handle disputes, with published timetables and anonymised case outcomes.  
- **Human rights safeguards:** policy tests to protect journalists, whistleblowers and dissidents, including accountable intermediaries and special case vouching mechanisms.  
- **Privacy by design:** minimise personal data collection, store only required evidence and apply retention limits and access controls.

---

## Operational safeguards and assurance
- **Third party audits:** regular security and process audits by accredited independent firms.  
- **Pen tests and red teams:** continuous adversarial testing and public bug bounties.  
- **Distributed architecture:** geo‑distributed mirrors, regional decision nodes and robust DDoS protection.  
- **Tiered accreditation:** affordable, not‑for‑profit or subsidised tracks for small operators and community services to reduce exclusion risk.

---

## Implementation roadmap and pilots
- **Phase 0:** design standards, legal review and stakeholder consultation.  
- **Phase 1:** pilot in high-risk sectors (finance, healthcare, critical infrastructure) with a narrow scope and measurable KPIs.  
- **Phase 2:** federated rollouts with national authorities and accredited verifiers, usability studies and inclusion pilots for small operators.  
- **Phase 3:** broad public rollout, continuous evaluation and iterative policy updates guided by audits and impact metrics.

---

## Summary
Chapter 3 lays out a feasible technical pattern and governance posture: centre technical coordination around interoperable standards, delegate vetting to accredited verifiers where appropriate, bake privacy and human rights protections into every workflow, and validate assumptions through staged pilots with independent oversight.

---

### 📖 Continue Reading  

➡️[Next: Chapter 4 - Impacts, Risks, and Case Studies](Ch4-Impacts-risks-and-case-studies.md)  
⬅️[Back: Chapter 2 - Trusted Website concept](Ch2-Trusted-Website-concept.md)  
[🏛️ Back to Index](index.md)

---

_Last updated: 03-11-2025_
