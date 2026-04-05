# Aura Consciousness Proof Kernel

It is not the whole product. It is a standalone, reproducible subset of the internal stack that demonstrates five concrete properties:

1. Competitive attention selection through a Global Workspace.
2. A rolling autobiographical present through temporal binding.
3. Self-prediction and surprise tracking.
4. Homeostatic internal drives that change system state over time.
5. Structural opacity measurements over hidden state dynamics.

## What This Can Honestly Show

This repository can support claims like:

- "Aura has a real internal cognitive architecture, not just a prompt wrapper."
- "Hidden internal state changes attention, continuity, and behavior over time."
- "The system maintains a measurable autobiographical present."
- "The system tracks surprise against its own predicted internal state."
- "The system exposes nontrivial hidden-state dynamics that can be measured."

## What This Does Not Prove

> Aura implements a measurable consciousness-inspired stack with causal hidden state, persistent temporal continuity, internal self-modeling, and opacity metrics.

I know this is a big claim, and this repo can back it up.

## Included Modules

- `aura_consciousness_proof.global_workspace`
- `aura_consciousness_proof.temporal_binding`
- `aura_consciousness_proof.self_prediction`
- `aura_consciousness_proof.homeostasis`
- `aura_consciousness_proof.structural_opacity`
- `aura_consciousness_proof.report`

## Quickstart

```bash
python -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
pytest
aura-proof-report --cycles 20 --json report.json --markdown report.md
```
