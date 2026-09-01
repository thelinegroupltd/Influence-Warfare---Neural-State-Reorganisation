# Spectral State Dynamics

## Functional Coordination Under Modulation

This directory contains figures examining large-scale cortical organisation through coherence, phase-locking, and band-power envelope coherence analyses.

These analyses compare a baseline eyes-closed resting condition with a modulation condition across canonical EEG frequency bands. The purpose is not to validate a particular modulation method. The purpose is to show that neural coordination can be measured as a dynamic property of cognitive state.

The figure set includes:

- Heuristic raw-input coherence retained for continuity with earlier outputs.
- Raw EEG band-limited coherence estimating frequency-specific channel-pair coordination.
- Raw EEG phase-locking value (PLV) estimating phase synchronisation between channel pairs.
- Band-power envelope coherence estimating slower coordination in amplitude-envelope dynamics.
- Modulation-versus-baseline delta maps showing where synchronisation metrics increased or decreased relative to baseline.

The summaries show that the modulation condition was generally associated with lower mean synchronisation values relative to baseline across the analysed bands.

Mean raw EEG band-limited coherence decreased across theta, alpha, beta-low, beta-high, and gamma bands. The largest mean decreases were observed in theta, beta-low, and gamma. PLV showed a similar broad reduction, again with theta, gamma, and beta-low showing larger mean shifts. Band-power envelope coherence also decreased on average, with the strongest aggregate reductions appearing in theta and beta-low, and a smaller reduction in gamma.

This should not be interpreted as the brain simply becoming “less connected.” The delta matrices show that changes are not uniformly distributed across all channel pairs. The more appropriate interpretation is functional reorganisation: the pattern of synchronisation changed, with some relationships weakening more than others and localised increases appearing in selected edges.

Coherence and PLV describe how distributed neural populations coordinate their activity. In this repository, they are used as systems-level indicators of how cortical communication patterns differ between operating states.

For the accompanying influence-warfare paper, the important point is conceptual: cognitive state is not merely an internal feeling. It has measurable correlates in how neural systems coordinate. If coordination patterns change, then the same external information signal may be processed through a different biological operating condition.

These figures do not establish cognitive performance, subjective experience, anatomical source localisation, or behavioural effect. They show differences in measured EEG coordination patterns between two conditions and should be read alongside the entropy, spatial reorganisation, persistence, and flux analyses.
