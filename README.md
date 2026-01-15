# [>] Flamehaven

Founder building **audit-first AI systems** — not demos.

I design **governed AI runtimes and reasoning infrastructure** where:
- Behavior is traceable
- Claims require evidence
- "Green CI" is not accepted without real execution paths

My work focuses on the gap between **research correctness** and **operational reality**.

---

## Core Philosophy

- **Executable > Described** — If it cannot run, it does not exist
- **Evidence > Claims** — Show execution traces, not promises
- **Deletion > Preservation** — Remove dead code, not comment it out
- **Audit > Opinion** — Deterministic verification beats subjective review
- **Undo > IQ** — Reversible systems beat irreversible genius moves

If a system cannot be executed, tested, and reasoned about in production, it is not real.

---

## [+] Featured Work

### [#] Production AI Infrastructure

**[Flamehaven-Filesearch](https://github.com/flamehaven01/Flamehaven-Filesearch)** — 89 [[*]]
Open-source semantic document search (RAG) engine. FastAPI backend, instant self-hosted deployment, production-ready.

**[AI-SLOP-Detector](https://github.com/flamehaven01/AI-SLOP-Detector)** — 9 [[*]]
Static analysis to detect *convincingly empty* AI-generated code. Focuses on implementation depth, not style. Detects hollow logic that passes lint but lacks real functionality.

### [T] Developer Infrastructure

**[Dir2md](https://github.com/flamehaven01/Dir2md)** — 4 [[*]]
Transform codebases into LLM-optimized markdown. Intelligent sampling, token budget control, perfect for AI-assisted code reviews.

**[FlashRecord](https://github.com/flamehaven01/FlashRecord)**
Python-first CLI screen recorder. Instant screenshots + lightweight GIF recording for developer workflows and automation.

**[FDS-Dev](https://github.com/flamehaven01/FDS-Dev)** — 23 [[*]]
Code-level internationalization with structure-aware linting and AI translation capabilities. Ship global products faster.

### [B] Scientific AI

**[RExSyn-Nexus-light](https://github.com/flamehaven01/RExSyn-Nexus-light)** — 4 [[*]]
Sovereign AI architecture for structural biology. Implements digital empathy and risk governance frameworks for medical AI systems.

---

## [#] Flamehaven Sovereign CI/CD Pack

Universal CI/CD workflow templates enforcing **S-Tier Quality Standards** with adaptive enforcement.

### Quality Gates

| Gate | Purpose | Enforcement |
|------|---------|-------------|
| **Sovereign Gate** | Style (Black/Isort) + Tests (pytest+coverage) + AI-Slop Detection | Hard on main/master |
| **Doc-Drift Guard** | Documentation integrity, broken link detection, hype language filter | Hard on main/master |
| **NHI Security Scanner** | TruffleHog + Trivy + JSD drift detection + audit hashing | Always Hard |
| **LOGOS Reasoning Integrity** | Assertion ratio, type hints, reasoning pattern validation | Soft on feature |
| **SIDRCE Omega-Score Gate** | Systemic integrity certification with HSTA metrics (Omega >= 0.95) | Hard on main/master |

**Adaptive Enforcement:**
- `main/master`: **Hard Mode** — Block merges on failure
- `feature/develop`: **Soft Mode** — Report issues, allow merge

---

## [B] REx Engine (Research Executable Engine)

**Transforming research papers into executable, verifiable code.**

REx Engine converts "read & interpret" research into "load & execute" systems — treating every scientific paper as a runnable software module.

### Key Capabilities

| Component | Function |
|-----------|----------|
| **Paper Parser** | NLP-based extraction of Methods, Results, Intents from publications |
| **SCL Modal Generator** | Semantic Code Language modal generation from research logic |
| **Operator Stub Generator** | Executable code stub creation with type signatures |
| **NNSL Knowledge Indexer** | Neural Network Semantic Layer integration for cross-paper linking |

### Active Pipelines

- **BioMedical Paper Harvester v1.1** — Automated crawling with quality gates
- **Missing Link Detection v3.2** — LOGOS-integrated hypothesis discovery
- **GLP-1 Drug Development Pipeline** — End-to-end biomedical research automation

**Versions:** v8.1 (Unified Manual + Governance) | v7.x (Helm + CI + Observability) | v6.2 OMEGA (Anti-Hallucination + Formal Proof)

---

## [*] LOGOS Reasoning Framework v1.1

**L**ogical **O**rchestration for **G**enerative **O**ntological **S**ynthesis

Multi-engine reasoning with explicit disagreement tracking and execution traces.

### Architecture

| Component | Role |
|-----------|------|
| **IRF Core** | Philosophical premise purification & logical verification (M-A-D-I-F-P dimensions) |
| **AATS Core** | Hypothesis generation & causal reasoning under uncertainty |
| **Drift Control** | JSD/L2 divergence detection between reasoning paths |
| **Calibration Gate** | Reference-based accuracy correction against ground truth |
| **Active Experiment** | Sandbox-based hypothesis validation with rollback |

### Validation Thresholds

```
JSD Critical: >= 0.06 (semantic drift warning)
L2 Critical: >= 0.04 (numerical divergence warning)
Calibration Correlation: >= 0.90 (accuracy requirement)
```

---

## [!] AI Slop Detector — Extended

**Static analysis to detect *convincingly empty* AI-generated code.**

Detects hollow implementations that pass lint and CI but lack real logic — focusing on *implementation depth*, not style.

### Core Metrics

| Metric | Description | Threshold |
|--------|-------------|-----------|
| **LDR** (Logic Density Ratio) | Actual logic vs boilerplate ratio | < 0.3 triggers warning |
| **BCR** (Buzzword-to-Code Ratio) | Marketing speak vs functional code | > 0.15 triggers warning |
| **DDC** (Deep Dependency Check) | Unused/hallucinated dependency detection | Any unused = fail |

### Detection Targets

- Placeholder functions with docstrings but no real implementation
- Excessive comments masking empty logic blocks
- Import statements for unused libraries (hallucinated dependencies)
- "Architectural mockups" pretending to be production code
- Pass-through functions that add no value

**Use Case:** Pre-commit hooks, CI/CD gates, code review automation.

---

## [L] ASDP (AI Sovereign Definition Protocol)

Compile-time governance layer for AI systems enforcing:

- **Traceability**: Every output linked to evidence chain (source → reasoning → result)
- **Evidence Requirements**: No claims without proof artifacts (logs, checksums, execution traces)
- **Deterministic Audit Artifacts**: Reproducible verification with SHA-256 hashing
- **Drift Detection**: Semantic and behavioral divergence monitoring with JSD/L2 metrics
- **Constitutional Gates**: Quality thresholds (Omega >= 0.95) before production deployment

---

## [=] Repository Structure

| Repository | Purpose | Status | Tech Stack |
|------------|---------|--------|-----------|
| [Flamehaven-Filesearch](https://github.com/flamehaven01/Flamehaven-Filesearch) | RAG semantic search engine | Production | Python, FastAPI, Vector DB |
| [AI-SLOP-Detector](https://github.com/flamehaven01/AI-SLOP-Detector) | Code quality validation | Active | Python, AST, Static Analysis |
| [Dir2md](https://github.com/flamehaven01/Dir2md) | LLM-optimized codebase export | Production | Python, Token Management |
| [FlashRecord](https://github.com/flamehaven01/FlashRecord) | Developer screen recorder | Active | Python, CLI, GIF encoding |
| [FDS-Dev](https://github.com/flamehaven01/FDS-Dev) | I18n with AI translation | Active | Python, NLP, Linting |
| [RExSyn-Nexus-light](https://github.com/flamehaven01/RExSyn-Nexus-light) | Scientific AI governance | Research | Python, Bio AI, Ethics |

**18 Public Repositories** | **8 Followers** | **Focus:** Governed AI Runtimes, Scientific AI, Developer Infrastructure

---

## [o] Tech Stack

```
Core:        Python | FastAPI | pytest | Black/Isort
AI/ML:       LLM Reasoning Engines | RAG Systems | NLP Pipelines
Governance:  SIDRCE | ASDP | Drift Detection (JSD/L2) | HSTA Metrics
CI/CD:       GitHub Actions | Pre-commit Hooks | Quality Gates
Security:    TruffleHog | Trivy | Audit Hashing | Evidence Chains
Scientific:  Structural Biology AI | Drug Development Pipelines | Research-to-Code
```

---

## [&] Connect

Building **production AI governance systems** that you can execute, audit, and trust.

Not interested in:
- Demos that cannot be deployed
- Research without reproducible artifacts
- "Green CI" without real execution paths

Interested in:
- Research-to-production pipelines with formal verification
- AI reasoning infrastructure with drift detection
- Governance tooling for LLM systems (traceability, evidence, audit)
- Scientific AI with executable models (biomedical, physics, chemistry)

**Collaboration:** Open to partnerships on audit-first AI systems, governed runtimes, and scientific AI infrastructure.

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=flamehaven01&color=blueviolet&style=flat-square)
[![GitHub followers](https://img.shields.io/github/followers/flamehaven01?style=social)](https://github.com/flamehaven01)
[![GitHub stars](https://img.shields.io/github/stars/flamehaven01?style=social)](https://github.com/flamehaven01)

</div>

---

<sub>Legend: [>]=Launch | [#]=Security | [B]=BioAI/Research | [*]=Core | [!]=Critical | [L]=Legal/Lock | [T]=Tools | [o]=Focus | [=]=Tech | [&]=Connect | [+]=Active</sub>
