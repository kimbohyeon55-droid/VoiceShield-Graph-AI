# VoiceShield Graph AI

**An AI-assisted research project exploring Korean voice-phishing risk through conversation context, progression over time, and relationships between entities.**

Maintainer: [kimbohyeon55-droid](https://github.com/kimbohyeon55-droid)

This portfolio documents the project's architecture, data engineering, and research decisions. It is a documentation-only package: implementation files, datasets, model weights, and experiment outputs are excluded. There is no runnable application or hosted demo in this package.

## The problem

A suspicious word alone is a weak basis for identifying a fraudulent call. A legitimate customer can discuss a transfer, a compromised card, or identity verification. VoiceShield explores how a system could consider the surrounding conversation, the point at which a request becomes risky, and supporting relationships between entities.

The research question is whether those signals can support understandable, timely warnings. Real-world detection and intervention effectiveness remain unvalidated.

## What the project contains

| Area | Work observed in the local project | Evidence boundary |
|---|---|---|
| Data governance | Source discovery, provenance chains, license decisions, privacy review, and download checksums | Public availability is not treated as training or redistribution permission |
| Data engineering | Canonical conversation/turn/index tables, original-label preservation, duplicate grouping, and Parquet output | Single messages are distinguished from actual multi-turn conversations |
| Conversation modelling | TF-IDF and logistic-regression prototype scripts | Synthetic experiments; no validated Korean real-world performance claim |
| Temporal reasoning | Conversation prefixes, stage-based risk, and intervention-policy experiments | Prefix timing and synthetic stages require real-world validation |
| Graph reasoning | A separate synthetic entity-relation risk-propagation demonstration | No validated domestic voice-phishing relationship graph has been acquired |
| Explanations | Context-sensitive rule experiments for interpretable action cues | Explanations are not proof of fraud or model causality |

## My documented contribution

I defined the project scope, prioritized Korean transcripts and financial hard negatives, and set the requirements for source verification, privacy, and reproducibility. I required separate treatment of real data, synthetic experiments, and public statistics, and approved holding the real-data work when its eligibility conditions were not met.

Development was AI-assisted. Research, implementation, and validation tasks were carried out with Codex assistance; this portfolio does not claim that every implementation file was independently written by me. [Contribution and attribution details](docs/CONTRIBUTIONS.md) explain the evidence and its limits.

## Current status

The last documented data-harvest decision remains **STILL_BLOCKED** for the intended Korean real-data training task. Later local files show synthetic prototype and evaluation work, while the top-level status document still describes the earlier harvest milestone. This portfolio distinguishes those two tracks instead of presenting either as the complete project history.

No accuracy, F1, recall, deployment latency, or financial-loss-prevention result is claimed here. Synthetic results and the existence of a test artifact do not establish field performance.

## Explore the portfolio

- [Architecture](docs/ARCHITECTURE.md)
- [Development workflow](docs/DEVELOPMENT_WORKFLOW.md)
- [Data governance](docs/DATA_GOVERNANCE.md)
- [Contributions](docs/CONTRIBUTIONS.md)
- [AI assistance](docs/AI_ASSISTANCE.md)
- [Project status and limitations](docs/PROJECT_STATUS.md)
- [Publication scope](docs/PUBLICATION_SCOPE.md)
- [References](docs/REFERENCES.md)

The local implementation uses Python, pandas, NumPy, PyArrow, scikit-learn, NetworkX, Matplotlib, and joblib, with a PowerShell setup workflow. These are inspected implementation dependencies, not an installation requirement for reading this portfolio.

## Publication and licensing

This is a local publication proposal prepared on **17 October 2026**. No repository has been created or published by this preparation step. Source-code publication rights and applicable competition terms remain unresolved, so code is excluded. No open-source license has been assigned; no rights to third-party data, code, or research material are granted by this package.
