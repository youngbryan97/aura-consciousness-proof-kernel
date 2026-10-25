# Why the mechanisms matter, and where to compare them

The demonstration is useful because a small program makes it easier to see
whether a stored value affects a later decision. It is an example of component
behavior, not a substitute for the larger Aura experiment.

| Mechanism | Why an ordinary user might care | Evidence in this repo | Related work and limits |
|---|---|---|---|
| Attention | A new question needs to compete sensibly with old concerns | The workspace priority test | Cognitive architectures study selection and unresolved decisions; this example is only a small scored competition |
| Recent-event record | A conversation should retain relevant continuity | The narrative test and sample report | Memory systems such as [MemGPT](https://arxiv.org/abs/2310.08560) address broader context management; this demo does not reproduce that system |
| Prediction error | Unexpected outcomes should be detectable | The self-prediction test | A forecast-versus-outcome comparison is the relevant idea; a counter alone does not establish metacognition |
| Operating-condition values | Resource strain should influence appropriate priorities | The homeostasis test | The dashboard metaphor explains the control role without establishing a feeling |
| Perturbation measurement | Changing internal state can reveal something hidden from a simple output | The index-bound and state-shape test | [Theory-based consciousness indicators](https://arxiv.org/html/2308.08708v3) require a broader argument; the demo's opacity index is not their validated test |

The tests are [here](../tests/test_proof_kernel.py). The
[variables guide](VARIABLES.md) gives the calculations and the limits of the
labels.

## Scientific foundations and what transfers

[Dehaene, Kerszberg and Changeux (1998)](https://pmc.ncbi.nlm.nih.gov/articles/PMC24407/)
provide a computational-neuroscience precedent for a global workspace that
coordinates specialised processing. This demonstration's scored competition
is much smaller; its local attention test is the evidence for what it does.

[Rao and Ballard (1999)](https://www.nature.com/articles/nn0199_79) model
predictions and residual errors in a visual-processing hierarchy. The demo's
self-prediction component illustrates comparing a forecast with an outcome;
it does not reproduce their hierarchy or visual results.

[Sterling (2012)](https://pubmed.ncbi.nlm.nih.gov/21684297/) discusses
anticipatory biological regulation. This demo's homeostasis component updates
control values from supplied inputs. It should not be described as the larger
Aura resource forecaster, or as a biological result.

The [main scientific source map](https://github.com/youngbryan97/aura/blob/main/docs/SCIENCE_AND_SOURCES.md)
records the role and access limits of each reference, and links a reusable
bibliography for paper writing. Published findings about people or other
models motivate ideas; this repository's six tests support its own component
claims. Its opacity, causal-depth and phenomenal-criterion formulas are local
definitions, with no external scientific validation established here.

## Demos and larger Aura results

The committed sample is a small reproducible example, not footage of Aura's
current desktop. Published videos, historical scripts, fixture tests and
controlled experiments have different scopes. The main project's
[demos and related-work guide](https://github.com/youngbryan97/aura/blob/main/docs/DEMOS_AND_RELATED_WORK.md)
connects them without treating a planned demonstration as a witnessed result.

For an explanation you can use aloud, read [the demo explanation](EXPLAINED.md).
For the practical purpose of the larger project's mechanisms, read
[the plain-English tour](https://github.com/youngbryan97/aura/blob/main/docs/PLAIN_ENGLISH_GUIDE.md).

An addition in implementation scope is worth describing. A claim that Aura
outperforms a respected system needs an actual comparable evaluation. This
repository supplies no such head-to-head result.
