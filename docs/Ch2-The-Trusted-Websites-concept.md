---
title: Chapter 2 - The Trusted Websites concept
---

# Chapter 2 - The Trusted Websites concept

## Overview
This chapter surveys prevailing website authentication practices, explains their limits, and introduces the Trusted Websites paradigm that shifts the default from after‑the‑fact blocking to proactive, browser native verification.

---

## HTTPS and SSL/TLS - the foundation
HTTPS (SSL/TLS) is the baseline for secure web traffic. Certificates issued by Certificate Authorities (CAs) bind a domain to keys, enable encryption, and let browsers warn about misconfiguration. These protections are essential but limited:
- HTTPS confirms domain control and encrypts transport, not the legitimacy of content or operator intent.
- Weak validation processes, CA compromises and human error have produced high impact failures.
- Relying on the CA ecosystem alone leaves gaps that motivated actors can exploit.

---

## Certificate Authorities - role and limits
CAs underpin the current trust model but present structural risks:
- Hundreds of root CAs with varying oversight dilute trust assumptions.
- Historical compromises (for example, high profile incidents) show systemic fragility.
- Decentralised root store models make it possible for less‑scrutinised issuers to vitiate trust, including in adversarial or state sponsored scenarios.

---

## Application security standards and post‑deployment checks
Standards and frameworks (for example, OWASP ASVS) provide robust post‑deployment checks and development best practice. They reduce exploitable defects but do not prevent malicious or harmful sites from being published in the first place. ASVS style controls are complementary to, but distinct from, gatekeeping verification.

---

## Blacklists and community trust tools
Community and industry blacklists aggregate reports of harmful or fraudulent sites. Their characteristics:
- Reactive: sites are listed only after detection or harm.
- Fragmented: different lists apply different criteria and geographical coverage.
- Latency and inconsistency mean users remain exposed during the window between site launch and listing.

---

## Why these approaches leave users exposed
- The web’s current model treats safety as an outcome of detection and remediation rather than precondition for public access.
- Attackers exploit low friction domain registration, automated hosting and weak onboarding to launch harmful sites rapidly.
- Fragmented signalling (padlocks, warnings, scattered blocklists) creates user confusion and inconsistent protection.

---

## The Trusted Websites concept
Trusted Websites re‑frames access: only pre‑verified, continuously monitored sites are accessible by default. Key attributes:
- **Pre‑launch vetting:** identity, technical hygiene and policy checks before credential issuance.
- **Time limited credentials:** short lived, renewable credentials bound cryptographically to site identity.
- **Continuous compliance:** automated scanning and periodic revalidation, with rapid revocation on violation.
- **Browser native enforcement:** browsers query verification status and surface clear, standardised UI (colour states, icons, explicit messages).
- **Fallback and appeal:** documented exception paths and appeals to avoid unnecessary exclusion.

---

## Comparative snapshot
- Current model: decentralised CAs, HTTPS for encryption, blacklists for after‑the‑fact blocking.
- Trusted Websites: identity bound credentials, central or federated verification authority, browser enforcement that defaults to safety.

---

## Precedents and analogies
- App stores and government registries demonstrate that pre‑screening at scale is possible and can raise baseline trust.
- Platform verification badges show strong signalling value but are siloed; Trusted Websites aims to generalise that signal across the open web.
- Emerging browser APIs and verifiable credential standards provide technical building blocks that make a browser integrated Trusted List feasible.

---

## Summary
Current standards secure transport and assist detection but do not deliver universal, pre‑emptive assurance. The Trusted Websites paradigm builds on existing identity and credentialing work to make verification a proactive, browser enforced requirement - improving protection while introducing new governance, inclusion and technical design questions that later chapters address.

---

### 📖 Continue Reading
⬅️ [Back: Chapter 1 - Introduction and Context](Ch1-Introduction-and-context.md)  
➡️ [Next: Chapter 3 - Architecture, Workflow, and Governance](Ch3-Architecture-Workflow-and-Governance.md)  
[🏛️ Back to Index](index.md)

