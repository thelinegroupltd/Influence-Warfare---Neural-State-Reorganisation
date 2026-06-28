# Spectral-Energy Fluctuation Coupling

## State-Space Dynamics and Spectral Reorganisation

This directory contains the complete state-space analysis supporting the exploratory spectral investigation presented in the accompanying paper. Included are all generated figures, source CSV files, and derived metrics describing how cortical spectral dynamics evolved under the modulation condition.

Rather than examining spectral power alone, these analyses treat successive EEG observations as trajectories through a multidimensional spectral state space. Together, the metrics characterise **how the brain moves through its own dynamical landscape**, quantifying the direction, magnitude, persistence and organisation of ongoing cortical state transitions.

## Contents

The directory includes analyses of:

* Global state-space flux (Cosine and L2)
* Bandwise state-space flux
* Flux distributions
* Burst statistics
* Entropy × Flux relationships
* Regional Entropy × Flux analyses
* Differential entropy and complexity comparisons
* Supporting CSV datasets for every figure

## Summary of Findings

Across independent analyses, a consistent systems-level pattern emerged.

Neuromodulation was associated with:

* increased large-scale functional coordination;
* subtle redistribution of informational complexity rather than wholesale loss of entropy;
* longer persistence of reorganised cortical states;
* substantially smaller state-space excursions;
* preservation of continuous adaptive state evolution.

Importantly, the modulation did **not** suppress neural dynamics. Instead, cortical activity continued to evolve continuously, but through smoother trajectories and smaller multidimensional adjustments.

Cosine-based flux demonstrated that successive cortical states maintained continuous directional evolution, while L2 flux showed that these trajectories travelled shorter distances through spectral state space. Distributional analyses further confirmed that modulation selectively reduced large state transitions while preserving frequent low-amplitude adjustments.

Joint entropy–flux analyses revealed that the underlying entropy–flux constraint remained largely unchanged between conditions. Rather than creating a fundamentally new dynamical regime, neuromodulation appeared to alter how the existing dynamical landscape was occupied. Both global and regional analyses demonstrated that trajectories became increasingly concentrated within stable, high-information, low-flux regions while preserving the overall geometry of the cortical attractor.

## Systems Interpretation

When considered alongside the coherence, entropy, complexity and temporal persistence analyses contained elsewhere in this repository, the state-space analyses support a unified interpretation.

Rather than increasing or decreasing neural activity in a simplistic sense, the modulation appears to recalibrate cortical dynamics toward a more constrained, efficient and dynamically stable operating regime. Large intermittent reorganisations become less common, while continuous fine-scale adaptation is preserved.

From a dynamical systems perspective, the intervention appears to modify the **navigation of cortical state space** rather than its underlying topology. The brain continues to adapt, but does so through smaller, more controlled adjustments that maintain trajectory continuity and reduce unnecessary large-scale fluctuations.

## Repository Structure

Every figure is accompanied by the corresponding processed CSV data to maximise transparency and reproducibility. The raw EEG recordings used to generate these analyses are intentionally not included within this repository.

These analyses are exploratory and are intended to provide a systems-level characterisation of neuromodulation by integrating spectral organisation, information dynamics, temporal persistence and cortical state-space evolution into a unified analytical framework.
