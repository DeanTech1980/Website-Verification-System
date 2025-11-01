---
title: FAQ
description: Frequently asked questions
author: Dean John Weiniger
layout: default
---
# Frequently Asked Questions

## How does this differ from SSL/TLS?
This proposal focuses on contextual, policy driven trust signals for websites rather than solely certificate issuance. It complements TLS rather than replacing it.

## What about browser vendor coordination?
Browser vendors are a stakeholder; the design emphasises standardisation of UI primitives and an interoperable registry API to encourage adoption.

## Who benefits and who bears the costs?
Users gain clearer safety signals; enterprises and high-risk sectors benefit first. Verification costs fall on site operators but can be mitigated by tiered fees, subsidies, or not‑for‑profit providers.

## How does verification work end to end?
An accredited verifier performs identity and technical checks, issues a signed credential, publishes it to a discoverable registry, and browsers validate that credential at load time with caching and revocation checks.

## Who operates the Central Verification Authority (CVA)?
Multiple governance models are possible: single global authority, federated national authorities, or a hybrid. The project recommends a multi‑stakeholder governance body with independent auditors and appeal mechanisms.

## How are censorship and political abuse prevented?
Mitigations: distributed/federated issuers, strong legal safeguards, transparent policies, independent oversight, appeal channels, and technical safeguards (multi-party attestations, transparency logs).

## How will legacy sites migrate?
Phased migration with pilots in high-risk sectors, grace periods, migration tooling, and incentives (subsidies, simplified checks) to avoid excluding small actors.

## How will costs be handled for small sites and non-profits?
Options include tiered fees, subsidised verification, community or non‑profit verifiers, and automation to reduce operational overhead.

---

_Last updated: 2025-11-01_
