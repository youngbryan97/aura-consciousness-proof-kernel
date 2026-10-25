# Inspecting and running the component demo

Read [the explanation](EXPLAINED.md) for the idea and
[the variables guide](VARIABLES.md) for the output. This page provides the
implementation map and repeatable commands.

## Source map

| File | Role | Existing test |
|---|---|---|
| [global_workspace.py](../src/aura_consciousness_proof/global_workspace.py) | Candidate scoring, selection and ignition | Higher effective priority wins |
| [temporal_binding.py](../src/aura_consciousness_proof/temporal_binding.py) | Recent events and narrative | Recorded events reach the narrative |
| [self_prediction.py](../src/aura_consciousness_proof/self_prediction.py) | Predictions and mismatch tracking | Changed state produces error and surprise |
| [homeostasis.py](../src/aura_consciousness_proof/homeostasis.py) | Internal control-value updates | Supplied strain and faults change integrity |
| [structural_opacity.py](../src/aura_consciousness_proof/structural_opacity.py) | Perturbation ratio and recent-state average | Index bounds and retained-state shape |
| [report.py](../src/aura_consciousness_proof/report.py) | Synthetic input loop and report formatting | All report sections are present |

The tests are in [test_proof_kernel.py](../tests/test_proof_kernel.py). Their
scope is the component behavior just named. They do not implement the full
ISC null suite, 511 cuts, carrier search or bridge solver.

## Installed-package route

Use the commands in [the README](../README.md). Quote `'.[dev]'` so shells
such as zsh do not expand it as a filename pattern.

## Source-checkout route

With NumPy and pytest already available, installation is unnecessary:

```bash
PYTHONPATH=src python -m pytest -q
mkdir -p demo-output
PYTHONPATH=src python -m aura_consciousness_proof.report --cycles 20 \
  --json demo-output/report.json \
  --markdown demo-output/report.md
```

The input program generates simulated strain and candidate concerns. It does
not connect to Aura's live app, load a language model or measure the host for
these signals. Package requirements and the console entry point are declared
in [pyproject.toml](../pyproject.toml).

## Preserve the evidence boundary

The committed [report.md](../report.md) and [report.json](../report.json) remain
the original 12-cycle sample. Generate fresh output elsewhere. A report that
prints `phenomenal_criterion_met` reports the legacy code's three numerical
thresholds; interpret it through [the variable definitions](VARIABLES.md).

[The original README](history/README_2026-04-05.md) is preserved unchanged.
The documentation refresh does not replace modules, change public APIs or
promote this demonstration into the main Aura experiment.
