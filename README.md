# ADR-CML v10.0

Act, Diagnose, Repair: Active Relational Causal Mechanism Learning for Long-Horizon Agents.

## Public release

This repository provides the audited public release archive: [adr-cml-v10.0-public-release.zip](adr-cml-v10.0-public-release.zip). The archive contains the project source, configurations, tests, protocol documentation and the aggregate analysis materials in `paper_analysis/`.

The public archive deliberately excludes runtime `outputs/`, validation caches, checkpoints, replay buffers, virtual environments and other large binary artifacts. It does not claim that a completed run or a successful program exit establishes method effectiveness. The accompanying validation report records positive findings, null findings, counterexamples and evidence gaps.

No new training run, evaluation pipeline or hyperparameter search was launched for this release. The analysis materials were derived from existing records.

## Verification

SHA-256 of the release archive: `9f87a460739a3becfab769b91d48dfb33c492587d0e48a8b3924d85e2612ac82`.

For the experimental protocol and recovery instructions, see the files inside the archive, including `V10_VALIDATION_REPORT.txt`, `V10_LINUX_4090_RUN_GUIDE.txt` and `docs/V10_EXPERIMENT_PROTOCOL.md`.
