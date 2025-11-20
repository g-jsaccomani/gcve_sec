# Google Cloud VMware Engine (GCVE) Security Hardening
## Zero-Trust Architecture, NSX-T Microsegmentation & CMEK Encryption Baseline

---
**Author:** Joabson Saccomani ([@jsaccomani](https://github.com/g-jsaccomani))
**Role:** Cloud Security Consultant
**LinkedIn:** [linkedin.com/in/jsaccomani](https://www.linkedin.com/in/jsaccomani)
*Copyright © 2026 Google LLC / Joabson Saccomani. All rights reserved. Distributed under the Apache License 2.0.*


Production-ready infrastructure as code, policy manifests, and security hardening baseline for **Google Cloud VMware Engine (GCVE)** environments.

---

## Scope & Architecture

1. **Perimeter Security**: Private Service Access (PSA) and VPC Service Controls (VPC-SC) perimeters.
2. **Microsegmentation**: NSX-T Distributed Firewall (DFW) default-deny rulesets.
3. **Storage Encryption**: vSAN encryption with Customer-Managed Encryption Keys (CMEK) on Cloud KMS.
4. **Audit & Threat Detection**: Centralized telemetry streaming into Google SecOps (Chronicle SIEM).

---

## Repository Structure

```text
gcve_sec/
 docs/
    gcve_zero_trust_security_reference.md   # Zero-Trust security reference guide
 tdd/
    gcve-security-tdd-v3.md                 # Technical Design Document
 templates/                                  # IaC and YAML policy templates
 .gitignore
 CODE_OF_CONDUCT.md
 LICENSE
 README.md
 SECURITY.md
```

---

---
**Author:** Joabson Saccomani ([@jsaccomani](https://github.com/g-jsaccomani))
**Role:** Cloud Security Consultant
**LinkedIn:** [linkedin.com/in/jsaccomani](https://www.linkedin.com/in/jsaccomani)
*Copyright © 2026 Google LLC / Joabson Saccomani. All rights reserved. Distributed under the Apache License 2.0.*


<!-- Checkpoint: 2025-11-19 - sec(nsx-t): deploy micro-segmentation firewall rules for customer core banking tier -->

<!-- Checkpoint: 2025-11-20 - docs(architecture): update hybrid connectivity security baseline for client architecture board -->
