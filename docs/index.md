---
title: Website Verification System
description: Proposal to replace blacklists with Trusted lists.
author: Dean John Weiniger
layout: default
---

# 🌐 Website Verification System

<p align="left">
  <img src="https://img.shields.io/badge/🔐%20Website-Trusted-98FB98?style=flat">
  <img src="https://img.shields.io/badge/📄%20Type-Concept%20Paper-FFD580?style=flat">
  <img src="https://img.shields.io/badge/🛡️%20Focus-Cyber%20Security-87CEFA?style=flat">
  <img src="https://img.shields.io/badge/🌏%20Made%20in-Melbourne%20Australia-FFB6C1?style=flat">  
  <img src="https://img.shields.io/badge/📜%20License-CC%20BY%204.0-lightgrey.svg?style=flat">  
</p>

**Building trust on the web:** _A concept paper exploring a proactive, browser integrated trust model for a website
verification system. It explores replacing fragmented blacklists with a proactive **“Trusted Websites”** model,
supported by browser integrated trust signals and centralised or federated governance to strengthen cyber security,
digital identity, and online safety._

---

## 📖 Full Report - Chapters

- [Ch1 – Introduction](Ch1-Introduction.md)  
- [Ch2 – Trusted Website Concept](Ch2-Trusted-Website-concept.md)  
- [Ch3 – Architecture and Governance](Ch3-Architecture-and-Governance.md)  
- [Ch4 – Impacts, Risks, and Case Studies](Ch4-Impacts-risks-and-case-studies.md)  
- [Ch5 – Economics, Scalability, and Path Forward](Ch5-Economics-scalability-and-path-forward.md)

---

##  📑 Quick Version

- [📖 Introduction](#-introduction)
- [🔍 Existing Website Standards](#-existing-website-standards)
- [🪪 Centralised Authority Models](#-centralised-authority-models)
- [🌐 Browser Integrated Verification](#-browser-integrated-verification)
- [📄 Blacklist vs Trusted List](#-blacklist-vs-trusted-list)
- [🧩 Technical Architecture](#-technical-architecture)
- [🎯 Approval & Renewal](#-approval--renewal)
- [📈 Statistical Impact](#-statistical-impact)
- [🔁 Comparisons](#-comparisons)
- [🌏 Governance Models](#-governance-models)
- [📚 Case Studies](#-case-studies)
- [🔐 Cyber Security Standards](#-cyber-security-standards)
- [🪙 Challenges](#-challenges)
- [👥 Stakeholders](#-stakeholders)
- [💰 Economic Implications](#-economic-implications)
- [📦 Scalability](#-scalability)
- [✅ Conclusion](#-conclusion)

---

## 📂 Repository Structure

```text
global-website-verification-system/
├── .github/                                           # Workflows directory
│   └── workflows/
│       └── broken-links.yml                           # Check for broken links
│       └── pages.yml                                  # Starts the webpage service
├── docs/                                              # Documents for GitHub Pages
│   └── assets/                                        # Images, diagrams, charts
│   │   ├── css/
│   │   │   └── styles.scss                            # Styles sheet
│   │   └── diagrams/
│   │       ├── trust-flow.svg                         # Trust diagram
│   │       └── trust-flow.png
│   ├── ACCESSIBILITY.md                               # Accessibility check list
│   ├── CONTRIBUTING.md
│   ├── Ch1-Introduction-and-context.md                # First Chapter of Paper
│   ├── Ch2-The-Trusted-Websites-concept.md            #
│   ├── Ch3-Architecture-Workflow-and-Governance.md    #
│   ├── Ch4-Impacts-risks-and-case-studies.md          #
│   ├── Ch5-Economics-scalability-and-path-forward.md  # Last Chapter of Paper
│   ├── FAQ.md
│   ├── Website-Verification-System.docx               # Downloadable copies
│   ├── Website-Verification-System.pdf
│   ├── _config.yml                                    # Template config file
│   └── index.md                                       # Main Landing page
├── .gitignore                                         # Ignore file
├── CITATION.cff                                       # orcid and doi details
├── Gemfile
├── _config.yml                                        # Style Template
├── README.md                                          # Main project overview
├── LICENSE                                            # CC BY 4.0 License file
└── sitemap.xml                                        # Static sitemap
```

---

## 📖 Introduction

Across the globe, the exponential growth of the internet has facilitated profound advancements in digital information
sharing, commerce, and human connectivity. However, this hyper connected landscape also presents escalating risks:
unsafe websites proliferate, misinformation spreads rapidly, and users routinely face dangers ranging from phishing to
sophisticated cyber-attacks.

Traditional mechanisms such as **HTTPS** and **PKI** have improved security, but they fall short of addressing persistent
threats, fragmented governance, and evolving tactics. This paper proposes a **browser integrated, centralised global
website verification system** treating every website as a digital entity requiring authenticated “citizenship” before
participation.  

This report examines current authentication standards, technical requirements, statistical implications, comparative
frameworks, governance models, and the challenges of implementing such a transformative proposal.

---

## 🔍 Existing Website Standards

- **HTTPS / SSL/TLS**: encryption but weak validation.
- **Certificate Authorities**: fragmented, sometimes compromised.
- **OWASP ASVS**: useful but not gatekeeping.
- **Blacklists**: reactive, inconsistent, after the fact.

---

## 🪪 Centralised Authority Models

- **Single Global Authority**: one supranational body.
- **Federated National Entities**: each country governs its sites, interoperating globally.
- **Hybrid Model**: central rules, local vetting.

### 📰 Case studies:️

- **Australia’s Gatekeeper PKI**
- **EU eIDAS regulation**
- **Digital ID systems (e.g. Entra Verified ID, WebAuthn)**

---

## 🌐 Browser Integrated Verification

- Browser queries a **Central Verification Authority (CVA)** for site status.
- Only **Trusted sites** load without restriction.
- **Indicators**: colour coded bars, shield icons, explicit warnings.
- Fallback paths for appeals or temporary access.

---

## 📄 Blacklist vs Trusted List

| Aspect | Current Blacklists | Proposed Trusted List |
|--------|--------------------|-----------------------|
| Source | Multiple, fragmented | Central/federated authority |
| Update | After harm occurs | Proactive, continuous |
| Criteria | Known harm only | Strict vetting before launch |
| Coverage | Incomplete | Comprehensive |
| UX | Variable | Clear, browser‑native |
| False Positives/Negatives | Common | Reduced |
| Removal Impact | Site still exists | Site inaccessible |

---

## 🧩 Technical Architecture

- **CVA**: maintains verified sites database.
- **Browser Integration**: native enforcement.
- **Digital Credentials**: cryptographically bound.
- **Monitoring & Revocation**: continuous audits.
- **API Access**: for third‑party services.

### 🔧 Implementation strategy:

- Pilot rollouts in high‑risk sectors.
- Phased global expansion.
- Legacy migration with grace periods.
- Transparency and appeals processes.

---

## 🎯 Approval & Renewal

- **Initial Verification**: ID checks, due diligence, technical review.
- **Renewal**: annual re‑approval, continuous audits, incident-based reviews.
- **Comparisons**: LinkedIn/Facebook verification, platform level processes.

---

## 📈 Statistical Impact

- **Current harms:** phishing, scams, misinformation.
- **Expected outcomes:**
  - 80%+ reduction in malicious site emergence.
  - Harm windows reduced from weeks to hours.
  - Elevated baseline trust.
  - **Metrics:** prevented attacks, complaint volume, compliance KPIs, false positive/negative rates.

---

## 🔁 Comparisons

### 📩 Email Spam Filtering:

- **Spam filters** = reactive, statistical.
- **Trusted List** = proactive, identity based.

### 💻 Platform Verification:

- Social platforms use badges but siloed.
- **Global system** = unified, web wide trust.

---

## 🌏 Governance Models

- **National**: e.g. Australia’s Digital ID Act.
- **International**: ICANN, ITU, IGF - but limited scope.
- **Options**: new global body, binding treaty, or de facto standards via browser vendors.

---

## 📚 Case Studies

- **Australia’s Gatekeeper PKI**: hierarchical trust, strong oversight.
- **EU eIDAS**: cross‑border recognition.
- **National Digital IDs**: Aadhaar, Estonia e‑Residency.

---

## 🔐 Cyber Security Standards

- Must align with **ISO, NIST**, and national standards.
- **“Security by design”** embedded into browsers and sites.

---

## 🪙 Challenges

- **Centralisation risks**: censorship, abuse of power.
- **Technical**: scalability, latency, resilience.
- **Economic**: costs for small operators.
- **Free Expression**: risk of chilling speech.

---

## 👥 Stakeholders

- **Users**: safety vs access.
- **Website Owners**: trust vs compliance burden.
- **Governments**: oversight vs sovereignty.
- **Browser Vendors**: arbiters of trust.
- **Civil Society**: watchdogs for fairness.
- **Cyber Security Industry**: new opportunities, disrupted models.

---

## 💰 Economic Implications

- **Costs**: verification fees, compliance upgrades.
- **Benefits**: reduced fraud, billions saved globally.
- **Risks**: consolidation, exclusion of small players.

---

## 📦 Scalability

- **Distributed infrastructure**, caching, automated/manual audits.
- **Must be future proof for IoT**, decentralised domains, new threats.

---

## ✅ Conclusion

The vision of a browser integrated, centralised website verification system is both compelling and fraught with
complexity. Properly implemented, it offers transformative advantages in the fight against cybercrime, misinformation,
and online harm, while instilling a new era of digital trust and reliability.

By treating websites as digital citizens whose identities must be established and maintained, the system sets a far
higher bar for entry, deterring malicious actors and reducing harm to end users.

However, such centralisation presents profound risks: political overreach, market distortion, and new forms of
exclusion. The technical, economic, and organisational challenges, scalability, cost, speed, and equity, must be
addressed through staggered rollouts, robust oversight, multistakeholder engagement, and open technical standards.

Ultimately, the shift from a fragmented **blacklists** mindset to a universal **“Trusted List”** would constitute a paradigm
change. For this to succeed, not only must technology and process scale, but new forms of governance, accountability,
and international cooperation must be realised. Transparency, the balance of innovation with safety, and the assurance
of rights for all digital actors, including dissenting voices and marginalised communities, are the cornerstones upon
which a global system must be built.

A nuanced, staged approach, piloting in high‑stakes sectors, converging on common standards, and expanding only after
proven success, appears to be the most feasible path toward realising the vision of a safer, more trustworthy web for
all.

---

## 📘 Download Report 

- [MS Word version](Website-Verification-System.docx)  
- [PDF version](Website-Verification-System.pdf)

---

## 🤝 Contributing

We welcome feedback, ideas, and collaborators.  
Open an [issue](https://github.com/DeanTech1980/Website-Verification-System/issues) or submit a pull request.

---

## 📝 Author

Authored by **Dean John Weiniger**.  
With research and documentation support from **Microsoft Copilot**.

[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--4733--1421-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0003-4733-1421)  
[![Powered by Copilot](https://img.shields.io/badge/Powered_by-Microsoft_Copilot-8A2BE2?logo=microsoft&logoColor=white)](https://copilot.microsoft.com)

---

## 📜 Licence

### © 2025 **Dean John Weiniger**
This work is licensed under a **Creative Commons Attribution 4.0 International License**.  
[![CC BY 4.0](https://img.shields.io/badge/License-CC--BY--4.0-lightgrey?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)

### You are free to:

✅ **Share** - Copy and redistribute the material in any medium or format.  
✅ **Adapt** - Remix, transform, and build upon the material for any purpose, even commercially.

### Under the following terms:

🔗 **Attribution** - You must give appropriate credit, provide a link to the licence, and indicate if changes were made.

**Full licence text:** [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)

---

_Last updated: 03-11-2025_
