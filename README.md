# Entropy and Complexity Metrics

## Information Distribution and Temporal Sequence Structure

This directory contains figures and processed CSV outputs examining cortical information dynamics through Shannon entropy and Lempel–Ziv complexity analyses.

In this analysis, Shannon entropy and Lempel–Ziv complexity measure related but distinct properties:

- **Shannon entropy** estimates how distributed or variable the spectral signal values are.
- **Lempel–Ziv complexity (LZ76)** estimates how diverse or compressible the signal sequence is over time.

In simple terms, entropy asks how spread out the spectral values are, while LZ complexity asks how repetitive or diverse the temporal sequence is.

The figure set includes:

- Band-level entropy and complexity plots for baseline and modulation.
- All-feature plots across channel, band, and feature combinations.
- Modulation-versus-baseline comparison figures.
- Entropy sensitivity checks across window lengths and bin counts.
- LZC window-length sensitivity checks.
- Surrogate-normalised LZC summaries for contextual interpretation.

In the outputs, band-level median Shannon entropy is lower during modulation across all five analysed bands. The largest median entropy reductions occur in gamma, theta, and beta-low, with additional reductions in beta-high and alpha. The aggregate entropy sensitivity checks show the same negative direction across the tested window lengths and bin counts, suggesting that the entropy reduction is not just an artefact of one parameter choice.

Lempel–Ziv complexity does not simply mirror entropy. Whole-record LZC increases in alpha, changes very little in beta-low and beta-high, and decreases in theta and gamma. Window-length sensitivity outputs show small non-negative median LZC shifts at longer windows, while feature-level summaries show mixed local effects.

This dissociation is important. Lower entropy does not automatically mean lower complexity, reduced cognition, or poorer function. Instead, these results suggest that spectral information distribution and temporal sequence organisation can be reconfigured in different ways during a change in cognitive state.

Entropy and complexity help describe the informational texture of neural activity. In the context of the accompanying paper, they support the view that cognitive state can be measured as an operating condition with observable structure.

The results are most consistent with a shift toward a more constrained or selectively reorganised spectral distribution, rather than a simple increase in randomness or activity. The LZC results add nuance by showing that temporal diversity remains frequency- and window-dependent.

For influence-warfare analysis, this matters because incoming narratives, cues, and signals are processed by systems already occupying a particular state. Changes in information distribution and sequence structure may therefore affect how salience, uncertainty, and attention are weighted before a message is consciously interpreted.

Entropy and LZC are not measures of intelligence, performance, truth detection, or subjective experience. They are descriptive metrics of signal organisation and should be interpreted alongside the coherence, spatial reorganisation, temporal persistence, and flux analyses.
