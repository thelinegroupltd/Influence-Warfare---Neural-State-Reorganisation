# Differential Shannon Entropy × Lempel-Ziv Complexity × Flux Analysis

## Joint Changes in Information Structure and State-Space Movement

This directory contains figures and processed CSV outputs comparing modulation-minus-baseline changes across three EEG-derived state metrics: Shannon entropy, Lempel-Ziv complexity, and L2 flux.

Here, “differential” refers to the difference between conditions:

- **Δ Shannon entropy = MODULATION_DATASET − BASELINE_EC**
- **Δ Lempel-Ziv complexity = MODULATION_DATASET − BASELINE_EC**
- **Δ L2 flux = MODULATION_DATASET − BASELINE_EC**

The purpose of this analysis is to examine whether changes in information distribution, temporal sequence complexity, and state-space movement occur together or diverge from one another. It extends the entropy, complexity, and flux analyses by placing those measures into a shared differential frame.

- **Shannon entropy** estimates how distributed or variable the signal values are within the analysed window.
- **Lempel-Ziv complexity (LZ76)** estimates how diverse or compressible the temporal sequence is.
- **L2 flux** estimates the magnitude of movement between successive positions in EEG-derived spectral state space.

Positive values indicate higher values during MODULATION_DATASET relative to BASELINE_EC. Negative values indicate lower values during MODULATION_DATASET relative to BASELINE_EC.

The figure set includes:

- Aggregate differential hexbin plots comparing entropy × flux, entropy × LZC, and LZC × flux.
- Aggregate 3D and 2D projection plots for POW band-median and raw EEG channel-median tracks.
- Progress plots showing how differential trajectories evolve across the recording.
- POW band-level differential profiles and 3D plots.
- POW bandwise matching-flux hexbin and 3D plots.
- Raw EEG regional differential profiles and 3D plots.

The CSV outputs include:

- Aligned BASELINE_EC and MODULATION_DATASET time series.
- Differential tables for POW band-median, POW bands, POW features, raw EEG channel-median, raw EEG channels, and raw EEG regions.
- Matching-band flux tables for frequency-specific POW analyses.
- Baseline-standardised flux versions of the same differential analyses.
- Summary tables reporting medians, means, quartiles, correlations, and quadrant counts.
- Bootstrap audit tables testing the stability of pairwise relationships between differential metrics.

The baseline and modulation time series are aligned by normalised recording progress from 0 to 1.

The core aggregate, band, and regional tracks use 181 matched windows. The aggregate audit tables indicate that direct window positions were identical and interpolation was not required for the audited tracks. This means the differential values are comparing matched positions in the recording rather than arbitrary or unmatched time points.

Across the main POW band-median track, MODULATION_DATASET shows lower Shannon entropy than BASELINE_EC in most matched windows. The median Δ Shannon entropy is approximately −0.49, with 166 of 181 windows showing negative entropy differences.

Lempel-Ziv complexity behaves differently. In the POW band-median track, Δ LZC is mixed, with a median near zero and both positive and negative values present. In the raw EEG channel-median track, Δ LZC is slightly positive on average, while still remaining mixed across windows.

L2 flux is generally lower during MODULATION_DATASET relative to BASELINE_EC. In the native regionalised flux track, median Δ L2 flux is approximately −4.73. In the baseline-standardised version, median Δ L2 flux is approximately −2.06. This supports the interpretation that the modulation condition involved smaller state-space excursions relative to baseline.

The bandwise analyses show the same broad pattern with frequency-specific detail. Shannon entropy is mostly lower across theta, alpha, beta-low, beta-high, and gamma. Matching-band L2 flux is also negative in most windows across all bands. LZC remains more band-dependent, with beta-high showing the clearest positive median shift while several other bands remain closer to zero.

Raw EEG regional analyses also show mostly negative entropy differences across frontal, central, temporal, parietal, and occipital groupings. LZC is more mixed by region, with occipital values tending slightly negative and several other regions tending slightly positive.

The hexbin plots should be read as relationship and density plots, not as causal diagrams. They show how differential values cluster when two metrics are viewed together.

For example, an entropy × flux plot does not show that entropy causes flux or that flux causes entropy. It shows whether windows with higher or lower entropy differences tend to appear alongside higher or lower flux differences.

The 3D plots place Δ entropy, Δ LZC, and Δ flux into the same visual space. These figures are useful for seeing that the three metrics do not collapse onto a single axis. A window can show lower entropy, higher or unchanged LZC, and reduced flux at the same time.

The bootstrap audit tables provide a stability check for pairwise relationships between the differential metrics.

In the POW band-median native-flux track, Δ entropy and Δ flux show a positive association, while Δ entropy and Δ LZC are close to zero. In the baseline-standardised POW band-median track, the Δ entropy × Δ flux association is stronger. In the raw EEG channel-median track, Δ entropy and Δ LZC show a clearer negative association, while Δ LZC and Δ flux remain weak or inconsistent.

These bootstrap outputs should be interpreted as robustness checks on observed relationships, not as proof of causation.

This analysis supports the broader interpretation that neural-state reorganisation is multidimensional.

The key result is not simply that one metric increased or decreased. The more important result is that entropy, LZC, and flux do not behave as interchangeable measures. Entropy tends to shift downward, flux tends to show smaller state-space movement, and LZC remains more representation- and frequency-dependent.

For the accompanying influence-warfare paper, this matters because cognitive state is being treated as an operating condition of the receiver. If state organisation changes across multiple dimensions at once, then external information is not processed by a neutral system. It is processed through a changing biological landscape of information distribution, sequence structure, and state-transition dynamics.

These analyses do not validate a modulation method, establish a behavioural outcome, or provide clinical or diagnostic evidence. They visualise how EEG-derived state metrics differ between BASELINE_EC and MODULATION_DATASET and help frame cognitive state as a measurable, dynamic, multidimensional operating condition.
