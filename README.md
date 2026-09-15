# KoR Audits

KoR Audits documents a public methodology for structural audits of runtime systems, AI infrastructures, governance architectures, constraint interactions, provenance, observability, continuity, and drift.

The repository is intended as a public audit and assurance surface. Production audit engines, private instrumentation, proprietary workflows, private datasets, and operational tooling remain private.

---

## What this repository is

KoR Audits is a structural observability and audit methodology for evaluating complex systems under constraint.

It focuses on how systems preserve or lose:

- coherence
- provenance
- auditability
- admissibility boundaries
- runtime observability
- replay and memory continuity
- constraint stability
- drift control

The objective is not to infer hidden intent, ideology, consciousness, or private operational policy. The objective is structural cartography under constraint.

---

## What it evaluates

The public methodology can be applied to:

- AI governance architectures
- LLM and agentic system boundaries
- runtime orchestration systems
- recommendation and retrieval infrastructures
- provenance and evidence-chain systems
- human-in-the-loop workflows
- refusal and admissibility surfaces
- organizational AI control structures

The framework treats modern AI-enabled systems as coherence-preserving adaptive structures rather than isolated optimization engines.

---

## Audit methodology

The public methodology currently includes:

1. Structural Runtime Cartography
2. Constraint Surface Mapping
3. Runtime Observability Analysis
4. Coherence Surface Analysis
5. Continuity & Drift Evaluation

These layers are documented in [METHODOLOGY.md](METHODOLOGY.md).

---

## Evidence and reproducibility

Public audits should separate evidence levels clearly:

| Category | Meaning |
|---|---|
| Observed | directly visible public structures, documentation, outputs, or behaviors |
| Inferred | plausible architectural interpretation based on observable evidence |
| Speculative | higher-order implication requiring further validation |

Audit outputs should make their evidence chain explicit enough that another reviewer can understand what was observed, what was inferred, and where uncertainty remains.

---

## Public/private boundary

Production audit engines remain private. This repository documents the public methodology, structural model, reproducibility principles, and public examples.

This repository does not expose:

- proprietary audit-engine logic
- private instrumentation
- API keys or credentials
- private datasets or local corpora
- client or confidential material
- executable production audit pipelines
- internal scoring or automation workflows

Public material may include methodology, synthetic examples, public case studies, templates, evidence-chain concepts, and reproducibility principles.

---

## Example audit structure

```text
audits/
└── runtime-systems/
    ├── README.md
    └── reports/
        └── x-runtime-governance-stack/
            ├── README.md
            └── phase-1-runtime-cartography.md
```

A complete public audit should generally include:

- scope and boundary
- evidence sources
- observed structures
- inferred architectural model
- constraint surfaces
- continuity and drift analysis
- reproducibility notes
- limitations and uncertainty

---

## Professional applications

KoR Audits is relevant to work in:

- AI governance
- AI assurance
- AI risk and compliance
- Responsible AI
- LLM evaluation
- AI security and auditability
- runtime observability
- provenance and evidence-chain design
- human-in-the-loop governance workflows

---

## Repository structure

```text
README.md
METHODOLOGY.md
DISCLAIMER.md
audits/
└── runtime-systems/
```

---

## Current status

Public methodology and preliminary audit examples.

This repository should be read together with the broader KoR framework: https://resiliencekernel.org
