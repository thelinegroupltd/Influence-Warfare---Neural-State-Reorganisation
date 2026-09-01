# Differential Entropy and Regionalised Flux Difference Analysis

## Comparing Information Change With State-Space Movement

This directory contains a modulation-minus-baseline analysis comparing entropy change with regionalised L2 flux change.

Here, “differential” refers to the difference between conditions:

- **Δ entropy = MODULATION_DATASET − BASELINE_EC**
- **Δ regionalised L2 flux = MODULATION_DATASET − BASELINE_EC**

The purpose of this figure is to show how two different aspects of cognitive state can shift together or apart:

- **Entropy difference** captures change in information distribution relative to baseline.
- **Regionalised L2 flux difference** captures change in state-space movement velocity relative to baseline.

This analysis is useful because information organisation and state-transition velocity do not have to move in the same direction. A state can become more or less entropic while also moving more or less rapidly through regionalised state space.

The output includes:

- `Differential_Entropy_x_RegionalFlux_L2.png`
- `Differential_Entropy_x_RegionalFlux_L2.csv`

The CSV aligns BASELINE_EC and MODULATION_DATASET time series by progress through the recording and reports:

- baseline entropy;
- modulation entropy;
- modulation-minus-baseline entropy;
- baseline regionalised L2 flux;
- modulation regionalised L2 flux;
- modulation-minus-baseline regionalised L2 flux.

The analysis shows a mixed but slightly negative entropy shift and a clearer reduction in regionalised L2 flux.

Differential entropy ranges from negative to positive values, with a small negative median. Negative entropy differences are somewhat more frequent than positive differences. Differential regionalised L2 flux is more consistently negative, with more negative than positive flux differences and a negative median.

The quadrant structure is the key viewing aid. The analysis identifies moments where entropy and regionalised flux move together, as well as moments where they diverge. The largest quadrant by count is higher entropy with reduced regionalised flux, followed by lower entropy with increased regionalised flux. This supports the view that information distribution and state-space movement are related but not interchangeable.

This differential figure is a compact bridge between the entropy and flux analyses. It shows that neural-state reorganisation cannot be reduced to one axis.

For the accompanying influence-warfare paper, the conceptual value is straightforward: cognitive state is multidimensional. A change in the state of the receiver may involve shifts in information distribution, transition velocity, persistence, and coordination at the same time. Those dimensions can reinforce each other, oppose each other, or vary independently across time.

This analysis does not validate a modulation method or establish a behavioural outcome. It visualises how two EEG-derived state metrics differ from baseline and helps frame cognitive state as a measurable, multidimensional operating condition.
