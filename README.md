# Christopher Mangun

Principal Technical Program Manager, AI Delivery

[![Portfolio](https://img.shields.io/badge/Portfolio-christophermangun-blue?style=flat-square)](https://cmangun.github.io/christopher-mangun-portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-christopher--mangun-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/christopher-mangun-5257265/)
[![Location](https://img.shields.io/badge/Location-New%20York,%20NY-green?style=flat-square)]()

---

## What I Do

Principal Technical Program Manager with 17+ years leading enterprise platforms, AI programs, and
complex technology delivery. Builds the operating models, governance, and release controls that move
programs from executive intent through production. Led portfolios up to $51M, scaled organizations to
60+ people, and launched cloud and AI platforms for enterprise users.

Representative outcomes:

- $51M AI and data portfolio delivered across 13 regulated brands, with the delivery organization
  scaled from five people to more than 60
- Enterprise RAG platform taken into governed production for 500+ users: source governance,
  retrieval, evaluation, access controls, and a named operational owner
- Diagnostics data ecosystem modernized across ~27,000 instruments — retrieval efficiency up 65%,
  a delivery cycle cut from roughly six months to three weeks
- Content operations redesigned to shorten review cycles 35% and raise approved-content reuse 2.3×,
  with human and MLR approval unchanged

The repositories below are reference implementations: the governance and evidence patterns those
programs relied on, written as working code rather than described in a deck.

---

## Agentic Evidence Suite

Six interoperating components for verifiable agent execution. The meta-repo **[agentic-evidence](https://github.com/cmangun/agentic-evidence)** (v0.1.0) carries the suite-level reference architecture, standards interop, glossary, roadmap, and versioning policy. The six components below implement it.

```
Spec ──→ Tooling ──→ Governance ──→ Evaluation ──→ Review
```

| Layer | Repository | Role |
|---|---|---|
| **Spec** | [agentic-receipts](https://github.com/cmangun/agentic-receipts) | Receipt schemas, canonicalization, hash-chain vectors |
| **Tooling** | [agentic-trace-cli](https://github.com/cmangun/agentic-trace-cli) | `init → append → sign → verify → redact → export` |
| **Governance** | [agentic-policy-engine](https://github.com/cmangun/agentic-policy-engine) | Deny-by-default evaluation with decision receipts |
| **Evaluation** | [agentic-eval-harness](https://github.com/cmangun/agentic-eval-harness) | PHI redaction, budget caps, bypass attempts |
| **Review** | [agentic-evidence-viewer](https://github.com/cmangun/agentic-evidence-viewer) | Client-side bundle verification |
| **Provenance** | [agentic-artifacts](https://github.com/cmangun/agentic-artifacts) | Artifact manifests with integrity hashing |

**Architectural invariants:**

- Hash-chained receipts (SHA-256) make tampering, reordering, and omission detectable
- Every allow/deny emits a decision receipt — auditors see exactly why
- Ed25519 signatures for non-repudiation across trust boundaries
- Redaction preserves integrity verification

---

## Regulated-AI Reference Architectures

| Repository | Domain |
|---|---|
| [healthcare-rag-platform](https://github.com/cmangun/healthcare-rag-platform) | HIPAA RAG: PHI detection, guardrails, audit logging |
| [mlops-healthcare-platform](https://github.com/cmangun/mlops-healthcare-platform) | FDA 21 CFR Part 11 model validation (IQ/OQ/PQ) |
| [enterprise-llm-integration](https://github.com/cmangun/enterprise-llm-integration) | Secure LLM adapter patterns with governance |
| [model-governance-framework](https://github.com/cmangun/model-governance-framework) | Bias/fairness, FDA-ready model cards |
| [clinical-nlp-pipeline](https://github.com/cmangun/clinical-nlp-pipeline) | Medical NER, UMLS linking, ICD-10 coding |

---

## Design Areas

**Verifiability** — receipts, canonicalization, hash chains, signatures
**Governance** — deny-by-default policy, decision receipts, bypass detection
**Evaluation** — scenario harnesses, red-team cases, regression gates
**Regulated AI** — HIPAA Safe Harbor, FDA 21 CFR Part 11, UMLS, ICD-10, HL7 FHIR
**Stack** — Python · Rust · TypeScript · FastAPI · Kubernetes · Azure ML · AWS SageMaker

---

## Connect

- [Portfolio](https://cmangun.github.io/christopher-mangun-portfolio/)
- [LinkedIn](https://www.linkedin.com/in/christopher-mangun-5257265/)
- cmangun@gmail.com

**Open to:** Principal Technical Program Manager and AI delivery leadership roles where platform
execution, governance, and organizational scale matter.
