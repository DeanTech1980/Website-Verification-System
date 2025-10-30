---
title: Chapter 1 - Introduction and context
---

# Chapter 1 - Introduction and context

## Overview
Across Australia and globally, the rapid growth of the internet has enabled powerful advances in information sharing, commerce and connection. Alongside these benefits, risks have escalated: unsafe websites proliferate, misinformation spreads quickly, and users routinely face threats ranging from phishing to sophisticated cyber‑attacks. Existing mechanisms like HTTPS and traditional Public Key Infrastructure (PKI) improve security, but they don’t fully address persistent threats, fragmented governance, or the evolving tactics of malicious actors.

---

## Vision
This proposal sets out a browser integrated, centralised global website verification system that treats every website as a digital entity requiring authenticated “citizenship” before participation. Rather than reacting to harm with scattered “bad lists”, it establishes a universal “Trusted Websites” list, making verification proactive and continuous and ensuring identity and compliance are in place before default access.

---

## Purpose of this report
This report examines feasibility by:
- **Assessing current standards:** HTTPS, PKI, blacklists and post deployment security verification practices.
- **Defining requirements:** Technical and procedural needs for continuous, proactive verification.
- **Evaluating impacts:** Statistical implications and comparisons (e.g. email spam filtering, platform verification).
- **Exploring governance:** National and international models required to steward a global regime.
- **Addressing complexity:** Digital identity, legislation, cybersecurity best practice, stakeholder impacts and practical hurdles.

---

## Why current approaches fall short
- **Scope limitation:** HTTPS encrypts traffic and binds domains, but doesn’t assert content legitimacy or operator intent.
- **Trust fragmentation:** Hundreds of root CAs, varied assurance levels and historical compromises dilute confidence.
- **Reactive posture:** Blacklists and community reporting flag harm only after incidents, leaving users exposed.
- **Operational gaps:** Post deployment checks (e.g. OWASP ASVS) validate controls but don’t prevent harmful site launches.

---

## The paradigm shift
- **From bad lists to a trusted list:** Default access only for pre‑verified, continuously vetted sites.
- **Continuous assurance:** Scheduled renewals, automated audits, incident based reviews and immediate revocation for violations.
- **Browser native enforcement:** Clear, consistent user signals and low latency credential checks at page load.

---

## Anticipated benefits and trade‑offs
- **Benefits:** Reduced exposure to malware, phishing, scams and harmful content; shorter windows of harm; higher baseline trust.
- **Trade‑offs:** Centralisation risks (overreach, censorship), equity concerns (cost and access barriers), performance and availability challenges, and the need to protect anonymous but accountable speech.
  
---

## Summary
Subsequent chapters cover current standards and the “Trusted Websites” concept; architecture, workflow and governance; expected impacts, risks and case studies; and the economics, scalability and path forward for piloting and adoption.

---

### 📖 Continue Reading  

➡️[Next: Chapter 2 - The Trusted Websites Concept](Ch2-The-Trusted-Websites-concept.md)  
[🏛️ Back to Index](index.md)
