# What the demonstration's numbers mean

A variable is a value the program keeps or computes. A name such as curiosity
or surprise tells you its intended role. To understand it, ask what writes the
value, what reads it, and what changes because of it.

## Attention and continuity

| Variable or label | Meaning here | Practical example |
|---|---|---|
| Cycle / tick | One pass through the demonstration | Twelve ticks means twelve rounds of the example, not twelve seconds of experience |
| Candidate | A proposed concern with a score | Investigate a simulated uncertainty |
| Priority | Part of the candidate's starting score | A high-priority concern has a stronger initial bid |
| Focus bias | An extra scoring contribution | A focused candidate can beat one with a slightly higher base priority |
| Winner | The candidate selected by the workspace | Its text becomes the recorded event |
| Ignition | A thresholded workspace event | A selection can occur without an ignition being counted |
| Event window | Recently retained events | Earlier selected concerns remain available for the summary |
| Valence | A positive/negative internal coordinate | The summary can describe its average as positive or negative |

Think of priority as a bid at an auction, and focus bias as an extra budget.
The comparison explains how selection can change; it does not describe an
independent bidder or a conscious decision.

## Prediction and operating condition

| Variable | Meaning here | What it changes or shows |
|---|---|---|
| Predicted state | The predictor's estimate of later condition, drive or focus | Supplies something to compare with the following cycle |
| Error | Difference between a prediction and the observed program state | Larger mismatches mean worse prediction on that comparison |
| Smoothed error | Error carried through a smoothing update | One unusual event need not replace the whole recent estimate |
| Surprise count | Events meeting the predictor's surprise condition | A counter of threshold crossings, not a direct measure of surprise being felt |
| Integrity | An internal operating-condition value | Supplied faults can lower it and alter maintenance priority |
| Curiosity | An internal drive value | Contributes to exploration bids in the example |
| Will to live | The control value with this name in the implementation | Read its update and consumers as software behavior; the label does not establish a desire |
| Thermal load / resource anxiety | Supplied example inputs representing strain | Influence homeostasis; the report program generates them rather than measuring the current Mac |

A forecast and a dashboard are the useful comparisons: one tracks prediction
error, the other supplies readings that influence priorities. Neither metaphor
adds evidence about experience.

## Hidden-state measurements

The report uses a small numerical network with 32 state values. Each
perturbation adds a small change and compares two one-step calculations.

| Name in the output | Actual calculation or role | Limit |
|---|---|---|
| Internal divergence | Mean absolute difference between the two next internal states | A one-step difference under this chosen network |
| Output change | Mean absolute change in a fixed, randomly chosen projection | This projection is not the whole externally visible behavior of Aura |
| Opacity index | Internal divergence divided by 100 times output change, capped at 1; a tiny-output special case returns 1 | A code-defined ratio, not a validated consciousness measure |
| Exterior predictability | 1 minus the opacity index | It is calculated from the index; an outside observer's prediction accuracy was not separately measured |
| Causal depth | Internal divergence multiplied by 10, capped at 1 | It does not count layers or prove a deep causal chain |
| Specious present | A weighted average of recent network states, favouring newer ones | A retained numerical summary, not proof of an experienced present |
| Phenomenal criterion met | The chosen opacity/depth/predictability thresholds passed often enough | A legacy program label for these thresholds, not a phenomenal verdict |

For an invented arithmetic example, internal divergence 0.02 and output change
0.01 produce opacity 0.02 / (100 × 0.01) = 0.02, exterior predictability 0.98,
and causal depth 0.20. These are values under the implemented definitions.
They do not mean the program is 2% conscious or that a real observer predicts
98% of its behavior.

Some of the perturbations use random draws and reports include timestamps.
Expect numeric variation. The tests check stated component behavior rather
than requiring every run to reproduce the sample file's exact values.

## The larger project's variables

The current ISC experiment has different measurements, including matched
unchanged copies, split-system comparisons, joint effects and uncertainty
bounds. Use the main project's
[worked variable guide](https://github.com/youngbryan97/aura/blob/main/docs/ISC_VARIABLES.md).
The demo's opacity index must not be substituted for those results.
