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

<!-- Checkpoint: 2025-11-27 - sec(pci-isolation): implement PCI-DSS tenant isolation rules in customer GCVE private cloud -->

<!-- Checkpoint: 2025-12-01 - sec(nsx-t): deploy micro-segmentation firewall rules for customer core banking tier -->

<!-- Checkpoint: 2025-12-04 - sec(pci-isolation): implement PCI-DSS tenant isolation rules in customer GCVE private cloud -->

<!-- Checkpoint: 2025-12-04 - refactor(perimeter-firewall): optimize egress gateway inspection policies for client workload -->

<!-- Checkpoint: 2025-12-05 - feat(bastion-iam): enforce context-aware IAP access to client GCVE management consoles -->

<!-- Checkpoint: 2025-12-07 - sec(nsx-t): deploy micro-segmentation firewall rules for customer core banking tier -->

<!-- Checkpoint: 2025-12-08 - fix(interconnect-sec): adjust dedicated interconnect MTU and IPsec encryption settings for client -->

<!-- Checkpoint: 2025-12-12 - feat(bastion-iam): enforce context-aware IAP access to client GCVE management consoles -->

<!-- Checkpoint: 2025-12-16 - fix(interconnect-sec): adjust dedicated interconnect MTU and IPsec encryption settings for client -->

<!-- Checkpoint: 2025-12-25 - docs(architecture): update hybrid connectivity security baseline for client architecture board -->

<!-- Checkpoint: 2025-12-26 - sec(pci-isolation): implement PCI-DSS tenant isolation rules in customer GCVE private cloud -->

<!-- Checkpoint: 2025-12-30 - feat(network-rules): configure distributed IDS/IPS profiles for external client migration -->

<!-- Checkpoint: 2026-01-06 - sec(pci-isolation): implement PCI-DSS tenant isolation rules in customer GCVE private cloud -->

<!-- Checkpoint: 2026-01-07 - feat(bastion-iam): enforce context-aware IAP access to client GCVE management consoles -->

<!-- Checkpoint: 2026-01-18 - refactor(perimeter-firewall): optimize egress gateway inspection policies for client workload -->

<!-- Checkpoint: 2026-01-18 - feat(bastion-iam): enforce context-aware IAP access to client GCVE management consoles -->

<!-- Checkpoint: 2026-01-20 - docs(architecture): update hybrid connectivity security baseline for client architecture board -->

<!-- Checkpoint: 2026-01-21 - feat(vcenter-sso): streamline vCenter SSO integration with Google Cloud Identity for client admins -->

<!-- Checkpoint: 2026-01-23 - sec(nsx-t): deploy micro-segmentation firewall rules for customer core banking tier -->

<!-- Checkpoint: 2026-01-27 - docs(architecture): update hybrid connectivity security baseline for client architecture board -->

<!-- Checkpoint: 2026-01-28 - refactor(perimeter-firewall): optimize egress gateway inspection policies for client workload -->

<!-- Checkpoint: 2026-01-30 - feat(network-rules): configure distributed IDS/IPS profiles for external client migration -->

<!-- Checkpoint: 2026-02-02 - docs(architecture): update hybrid connectivity security baseline for client architecture board -->

<!-- Checkpoint: 2026-02-02 - feat(vcenter-sso): streamline vCenter SSO integration with Google Cloud Identity for client admins -->

<!-- Checkpoint: 2026-02-05 - refactor(perimeter-firewall): optimize egress gateway inspection policies for client workload -->

<!-- Checkpoint: 2026-02-09 - docs(architecture): update hybrid connectivity security baseline for client architecture board -->

<!-- Checkpoint: 2026-02-09 - feat(vcenter-sso): streamline vCenter SSO integration with Google Cloud Identity for client admins -->

<!-- Checkpoint: 2026-02-10 - refactor(perimeter-firewall): optimize egress gateway inspection policies for client workload -->

<!-- Checkpoint: 2026-02-12 - sec(nsx-t): deploy micro-segmentation firewall rules for customer core banking tier -->

<!-- Checkpoint: 2026-02-16 - feat(vcenter-sso): streamline vCenter SSO integration with Google Cloud Identity for client admins -->

<!-- Checkpoint: 2026-02-17 - refactor(perimeter-firewall): optimize egress gateway inspection policies for client workload -->

<!-- Checkpoint: 2026-02-26 - docs(architecture): update hybrid connectivity security baseline for client architecture board -->

<!-- Checkpoint: 2026-03-01 - sec(nsx-t): deploy micro-segmentation firewall rules for customer core banking tier -->

<!-- Checkpoint: 2026-03-04 - docs(architecture): update hybrid connectivity security baseline for client architecture board -->

<!-- Checkpoint: 2026-03-14 - refactor(perimeter-firewall): optimize egress gateway inspection policies for client workload -->

<!-- Checkpoint: 2026-03-16 - feat(network-rules): configure distributed IDS/IPS profiles for external client migration -->

<!-- Checkpoint: 2026-03-20 - sec(pci-isolation): implement PCI-DSS tenant isolation rules in customer GCVE private cloud -->

<!-- Checkpoint: 2026-03-20 - refactor(perimeter-firewall): optimize egress gateway inspection policies for client workload -->

<!-- Checkpoint: 2026-03-23 - feat(bastion-iam): enforce context-aware IAP access to client GCVE management consoles -->

<!-- Checkpoint: 2026-03-31 - feat(bastion-iam): enforce context-aware IAP access to client GCVE management consoles -->
