---
title: Chapter 4 - Impacts, risks and case studies
---

# Chapter 4 - Impacts, risks and case studies

## Overview 
This chapter evaluates the expected benefits and measurable impacts of a **Trusted Websites** system,
contrasts it with related systems (email spam filtering and platform verification), and examines practical risks and mitigations through realworld case studies.
It outlines the statistical metrics to monitor, and the governance and technical controls required to limit harms introduced by centralisation.

---

## Expected impact and key metrics
- **Reduction in new malicious sites:** A pre‑verification barrier would raise the cost and risk for attackers,
potentially reducing successful malicious launches substantially.  
- **Shortened harm windows:** Continuous monitoring and rapid revocation aim to cut average exposure from days or weeks to hours.  
- **Elevated baseline trust:** Consistent browser signalling should increase user confidence and economic activity tied to trusted sites.

### Key metrics to track:
- **Prevented attacks:** measured reduction in phishing, malware and financial fraud incidents attributable to web access.  
- **Time to remediation:** median time from detection to revocation or remediation.  
- **Complaint volume:** change in reported harmful site encounters.  
- **FP/FN rates:** false positive and false negative rates for verification decisions.  
- **Adoption and inclusion:** percentage of sites verified across sectors and regionally, and uptake by small operators.

### Modelling and evaluation:
- Use pre‑rollout baselines, A/B pilots and scenario modelling (Monte Carlo or sensitivity analysis)
  to estimate harms avoided and to stress test policy thresholds.

---

## Comparative analysis: spam filtering and platform verification
- **Email spam filtering:** reactive, statistical and heuristic. It reduces noise but struggles with evasion and still misclassifies legitimate messages.
- Trusted Websites flips this model, favouring identity bound, proactive gating rather than post‑hoc detection.  
- **Platform verification (badges):** platforms create trust signals inside silos.
- They demonstrate that identity signals raise confidence, but they face scale, inclusivity and operational cost limits.
- Trusted Websites generalises the signal to the open web and requires interoperable standards and browser support.

### Lessons to carry forward:
- Combine automated detection with human review for edge cases.  
- Invest in usability so signals are meaningful, not confusing.  
- Plan for adversary adaptation and maintain a continuous improvement loop.

---

## Case studies and precedents
- **Australian Gatekeeper PKI:** shows hierarchical trust and accredited issuers work for sensitive services; governance and liability models are instructive for sectoral rollouts.  
- **EU eIDAS:** federated standards plus mutual recognition can enable cross border trust while preserving national sovereignty.  
- **Aadhaar and Estonia e‑Residency:** illustrate scale and the centrality of privacy protections; they highlight the importance of public trust and strong legal safeguards.  
- **Platform verification programmes (LinkedIn, Twitter, Facebook):** demonstrate signalling value and operational burden; they also show scalability and inclusion tensions.

### Synthesis:
- Borrow accreditation, revocation practices and mutual recognition from PKI and eIDAS.  
- Use platform lessons for UX and operational scaling.  
- Prioritise robust privacy and oversight mechanisms learned from national ID programmes.

---

## Risks, mitigations and governance implications

### Primary risks:
- **Centralisation and political misuse:** a single or dominant authority risks overreach or capture.  
- **Censorship and chilling effects:** mandatory verification could disadvantage dissenting voices or minority views.  
- **Technical failure and attack surface:** DDoS, credential compromise or supply chain attacks could have systemic effects.  
- **Economic exclusion:** fees and compliance burdens risk excluding small operators and marginalised communities.  
- **False positives/negatives:** misclassification harms legitimate actors or fails to stop sophisticated adversaries.

### Mitigations:
- **Federation and redundancy:** distribute trust and decisioning across accredited national and sectoral verifiers.  
- **Multistakeholder oversight:** independent boards, civil society representation and published transparency reports.  
- **Appeals and accountable redress:** timely, independent appeals with clear remediation pathways.  
- **Tiered and subsidised models:** low cost or nonprofit tracks for small, community and culturally important sites.  
- **Robust security practices:** geo‑distributed infrastructure, short token TTLs, hardened key management, pen tests and bug bounties.  
- **Human rights by design:** explicit policies for journalists, whistleblowers and sensitive speech;
mechanisms for verified anonymous publication via accountable intermediaries.

---

## Summary
A **Trusted Websites** system promises substantial reductions in common web harms and a stronger baseline of user trust,
but it introduces serious governance, equity and technical risks. The practical path is iterative: measure rigorously,
pilot in high risk sectors, adopt federated models, embed strong oversight and human rights protections, and build affordable tracks for inclusion.
Chapter 5 lays out the economic considerations, scalability planning and a phased roadmap for pilots and broader adoption.

---

### 📖 Continue Reading  

➡️ [Next: Chapter 5 - Economics, Scalability, and Path Forward](Ch5-Economics-scalability-and-path-forward.md)  
⬅️ [Back: Chapter 3 - Architecture, Workflow, and Governance](Ch3-Architecture-Workflow-and-Governance.md)  
[🏛️ Back to Index](index.md)
