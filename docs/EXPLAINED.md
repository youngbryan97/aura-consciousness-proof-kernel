# The demonstration in ordinary language

This project is small enough to read without running the whole Aura system.
It combines a few mechanisms that a more complex agent might use.

## A short explanation you can say aloud

> This demo gives several concerns a chance to compete for attention. It keeps
> a short record of what happened, predicts some of its next state, and checks
> whether the prediction was right. Its operating-condition values also change
> with the example inputs. That shows how internal state can matter to a
> program. The larger Aura project tests how many such parts depend on one
> another; this small demo does not run that full experiment.

## Attention: which concern gets the floor

Think of a meeting where several people want to speak. The workspace scores
candidates and picks a winner. A focus boost can change which candidate wins.

Here the candidates are program-generated concerns such as investigating an
uncertainty or stabilising operating condition. The meeting comparison
illustrates selection; it does not imply that each candidate is a person.

## Recent events: what remains available

The temporal-binding component keeps recent events and refreshes a short
narrative. Think of a notebook open to the last few entries: what happened
earlier can still be read while the next thing happens.

A recent-event window is a software record. Its name, “autobiographical
present,” does not establish an experienced present or a continuing person.

## Prediction: noticing a mismatch

The predictor estimates later internal condition, drive and focus, then
compares those estimates with what actually follows. An unexpected change
increases its error.

It is like checking a weather forecast against the next day's weather. The
comparison explains prediction error; the demonstration predicts its own
program state, rather than outside weather.

## Operating condition: values that affect priorities

The example feeds in simulated resource strain, thermal load and error signals.
The homeostasis component updates values such as integrity and curiosity.
Those values affect the concerns proposed to the workspace.

A dashboard is a useful comparison: a warning reading can change what the
controller prioritises. Names such as “will to live” identify software
variables here; the example does not establish a desire or felt distress.

## Perturbation: change something and compare

A small numerical network receives a tiny change in its state. The monitor
compares the resulting internal change with a simple projected output change.

Imagine moving a fader inside a mixing desk and comparing the change in the
internal signal with the change on one output meter. The meter may show less
than changed internally. This illustrates the chosen calculation, rather than
proving that an outside observer cannot understand the system.

The [variables guide](VARIABLES.md) explains the actual arithmetic and why
“opacity,” “causal depth” and “exterior predictability” are narrower here than
their names might suggest.
