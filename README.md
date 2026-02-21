# Christopher Mangun

**Forward Deployed AI Engineer** | Production AI in regulated environments | Verifiable agent systems

[![Portfolio](https://img.shields.io/badge/Portfolio-healthcare--ai--consultant.com-blue?style=flat-square)](https://healthcare-ai-consultant.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-christophermangun-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/christophermangun)
[![Location](https://img.shields.io/badge/Location-Brooklyn,%20NY-green?style=flat-square)]()

---

## What I Do

I embed with customer teams to ship production AI systems — RAG pipelines, agentic workflows, and ML platforms — in regulated industries where compliance, reliability, and measurable outcomes matter.

**15+ years** in healthcare, pharma, and enterprise AI:
- **Pfizer** — Agentic RAG platform for clinical document intelligence
- **Abbott Labs** — ML pipeline migration with zero FDA audit findings
- **Medtronic** — GI Genius 510(k) validation frameworks
- **IPG Health** — $51M portfolio across 13 pharma brands

---

## Agentic Evidence Suite

A 6-repo specification and toolchain for **verifiable agent execution** — cryptographic receipts, non-bypassable policy enforcement, and portable evidence bundles.

```
Spec ──→ Tooling ──→ Governance ──→ Evaluation ──→ Review
```

| Repository | Lang | Description |
|------------|------|-------------|
| [**agentic-receipts**](https://github.com/cmangun/agentic-receipts) | JSON Schema | Receipt schemas, canonicalization spec, hash-chain vectors |
| [**agentic-trace-cli**](https://github.com/cmangun/agentic-trace-cli) | Rust | CLI: `init → append → sign → verify → redact → export` |
| [**agentic-policy-engine**](https://github.com/cmangun/agentic-policy-engine) | Python | Deny-by-default evaluation with decision receipts |
| [**agentic-eval-harness**](https://github.com/cmangun/agentic-eval-harness) | Python | 8 scenarios: PHI redaction, budget caps, bypass attempts |
| [**agentic-evidence-viewer**](https://github.com/cmangun/agentic-evidence-viewer) | TypeScript | Drag-drop bundle viewer with client-side verification |
| [**agentic-artifacts**](https://github.com/cmangun/agentic-artifacts) | Python | Artifact manifests with provenance and integrity hashing |

**Key design decisions:**
- Hash-chained receipts (SHA-256) make tampering, reordering, and omission detectable
- Policy engine emits receipts for every allow/deny — auditors see exactly why
- Ed25519 signatures for non-repudiation
- Redaction preserves integrity verification (original hash retained)

---

## Healthcare AI Systems

Production-ready implementations for regulated environments:

| Repository | Description | Demo |
|------------|-------------|------|
| [**healthcare-rag-platform**](https://github.com/cmangun/healthcare-rag-platform) | HIPAA-compliant RAG: PHI detection, guardrails, cost guard, audit logging | `docker compose up` |
| [**clinical-nlp-pipeline**](https://github.com/cmangun/clinical-nlp-pipeline) | Medical NER with UMLS linking and ICD-10 coding | |
| [**mlops-healthcare-platform**](https://github.com/cmangun/mlops-healthcare-platform) | FDA 21 CFR Part 11 model validation (IQ/OQ/PQ) with MLflow | |
| [**enterprise-llm-integration**](https://github.com/cmangun/enterprise-llm-integration) | Secure LLM adapters with governance guardrails | |

---

## Other Projects

| Repository | Description |
|------------|-------------|
| [**coco-ai**](https://github.com/cmangun/coco-ai) | AI project manager — Svelte 5 platform for autonomous agent orchestration |
| [**field-deployed-engineer-showcase**](https://github.com/cmangun/field-deployed-engineer-showcase) | Case studies from forward-deployed AI engagements |

---

## Tech Stack

**AI/ML:** RAG, Agentic AI, LLMs, LangChain, LlamaIndex, MLflow
**Healthcare:** HIPAA Safe Harbor, FDA 21 CFR Part 11, UMLS, ICD-10, HL7 FHIR
**Languages:** Python, Rust, TypeScript, SQL
**Platforms:** Azure ML, AWS SageMaker, Kubernetes, FastAPI
**Data:** PostgreSQL, Pinecone, Weaviate, Neo4j

---

## Connect

- [healthcare-ai-consultant.com](https://healthcare-ai-consultant.com)
- [LinkedIn](https://linkedin.com/in/christophermangun)
- cmangun@gmail.com

**Open to:** Forward Deployed Engineer, Solutions Architect, ML Platform roles
