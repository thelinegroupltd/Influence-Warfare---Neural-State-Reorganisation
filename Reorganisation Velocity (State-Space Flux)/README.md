# Reorganisation Velocity (State-Space Flux)

## State-Space Movement and Spectral Reorganisation

This directory contains figures and processed CSV outputs describing how EEG-derived spectral states move through a multidimensional state space over time.

The purpose of this analysis is to examine cognitive state as a trajectory rather than a static snapshot. Each time point can be treated as a position in spectral state space. Flux metrics then estimate how far, and in what direction, the system moves between successive states.

The figure set includes:

- Global L2 state-space flux.
- Global cosine flux.
- Bandwise flux summaries.
- Regionalised flux summaries.
- Standardised flux outputs using baseline-derived scaling.
- Flux burst and distribution analyses.
- Entropy × flux and regional entropy × flux relationships.
- Processed CSV outputs supporting each figure.

The outputs use several related flux measures:

- **L2 flux** estimates the magnitude of state displacement between successive observations.
- **Cosine flux** estimates directional change between successive state vectors.
- **Standardised L2 flux** estimates displacement after scaling features against the BASELINE_EC distribution.
- **Regionalised flux** estimates state movement after aggregating channels into broader regional groupings.

Together, these measures separate how far the system moves from whether its direction of movement remains broadly continuous.

The flux summaries compare **BASELINE_EC** with **MODULATION_DATASET**. Relative to BASELINE_EC, MODULATION_DATASET shows reduced state-space displacement.

Global native L2 flux decreases from approximately 62.09 to 44.11 units per second in the mean, a reduction of about 29%. Median native L2 flux decreases from approximately 52.71 to 38.87 units per second, a reduction of about 26%.

Standardised L2 flux shows a similar pattern. Mean standardised L2 flux decreases from approximately 22.85 in BASELINE_EC to 16.30 in MODULATION_DATASET, while median standardised L2 flux decreases from approximately 20.13 to 15.07.

Regionalised L2 flux also decreases. Mean regionalised L2 flux falls from approximately 25.15 in BASELINE_EC to 19.28 in MODULATION_DATASET. Standardised regionalised L2 flux falls from approximately 10.08 to 7.60.

Cosine flux changes much less than L2 flux. Global cosine flux is slightly lower in the mean during MODULATION_DATASET, but slightly higher in the median. Regional cosine flux shows the same pattern: a small mean reduction and a small median increase.

This distinction matters. L2 flux suggests that MODULATION_DATASET involves smaller state-space excursions than BASELINE_EC. Cosine flux suggests that this reduction in movement magnitude does not imply a collapse of directional state evolution. In simpler terms: the system continues to move through state space, but successive states tend to travel shorter distances.

The entropy × flux plots should be read as relationship plots, not as simple “increase” or “decrease” charts. The L2 hexbin figures show how entropy values are distributed against state-space movement magnitude within each condition. In these plots, BASELINE_EC and MODULATION_DATASET can occupy overlapping regions while still differing in density, spread, and flux range. The key interpretation is not that entropy directly causes flux, but that information distribution and state-transition velocity can be examined together as coupled features of neural-state organisation.

State-space flux adds a dynamical layer to the repository. Coherence examines coordination, entropy examines information distribution, temporal persistence examines duration, and flux examines movement.

For the accompanying influence-warfare paper, this is useful because cognitive state is not only a pattern of organisation. It is also a moving operating condition. If the state-transition landscape changes, then incoming information may be processed through a different rhythm of adaptation, stability, and responsiveness.

Flux metrics do not show that the brain became better, worse, faster, or more efficient in a behavioural sense. They describe changes in the magnitude and directionality of EEG-derived spectral state transitions.
