# Christopher Mangun

**Agentic Systems Architect** | Verifiable execution · Governance · Evaluation · Regulated AI

[![Portfolio](https://img.shields.io/badge/Portfolio-healthcare--ai--consultant.com-blue?style=flat-square)](https://healthcare-ai-consultant.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-christophermangun-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/christophermangun)
[![Location](https://img.shields.io/badge/Location-Brooklyn,%20NY-green?style=flat-square)]()

---

## What I Do

I design agentic systems where execution is **verifiable**, policy is **non-bypassable**, and evidence is **portable**. My work defines the contracts, receipts, and evaluation boundaries that make AI agents deployable in regulated environments — not "can we ship it," but "can we prove what it did, why, and under which controls."

**15+ years** architecting AI and data platforms in healthcare, pharma, and regulated enterprise. Representative outcomes:

- Agentic RAG architecture deployed into clinical document intelligence at a top-5 pharma
- ML platform migration passed FDA audit with zero findings
- 510(k) validation frameworks shipped for an FDA-cleared AI medical device
- $51M AI/data portfolio delivered across 13 regulated brands

---

## Agentic Evidence Suite — Reference Architecture

A 6-repo specification and toolchain for verifiable agent execution.

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

- [healthcare-ai-consultant.com](https://healthcare-ai-consultant.com)
- [LinkedIn](https://linkedin.com/in/christophermangun)
- cmangun@gmail.com

**Open to:** Agentic Systems Architect · AI Platform Architect · Principal/Staff AI roles in regulated industries
