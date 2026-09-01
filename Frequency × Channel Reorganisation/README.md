# Frequency × Channel Reorganisation

## Spatial Distribution of Spectral Change

This directory contains figures and processed CSV outputs examining how spectral power is distributed across EEG channels and frequency bands in the baseline and modulation conditions.

The purpose of this analysis is to add a spatial perspective to the wider neural-state framework. Rather than asking only whether activity changed overall, these figures ask where spectral organisation changed across the channel montage and which frequency bands contributed to that change.

The figure set includes:

- Absolute band × channel log10 power maps for baseline.
- Absolute band × channel log10 power maps for modulation.
- Baseline-normalised delta log10 maps.
- Channel-level reorganisation indices using Jensen–Shannon distance.
- Processed CSV tables for median power, fold change, delta log10, and channel reorganisation.

The comparison shows selective spectral redistribution rather than uniform change across scalp-recorded channels.

Mean delta log10 power is negative across all five analysed bands, with gamma and theta showing the largest average reductions. However, each band also contains channels with positive local changes. This is important: the modulation condition is not best described as a simple global power reduction. It is better described as an uneven redistribution across frequency bands and recording channels.

The channel-level reorganisation index identifies stronger spectral redistribution in a subset of channels, including posterior, temporal, and occipital sites. The highest Jensen–Shannon distance values include P8, FT9, O1, PO9, PO10, T7, Oz, and F7.

Frequency × channel analysis describes the spatial layout of state change. It complements the coherence analyses, which examine relationships between channels, and the entropy and flux analyses, which examine information structure and state-transition dynamics.

For the accompanying influence-warfare paper, the key point is that cognitive state is not a uniform global variable. It can involve distributed, frequency-specific, and regionally uneven changes in neural organisation. That systems-level framing is more useful than saying the brain is simply “more active” or “less active.”

These figures should not be treated as anatomical source localisation. EEG channel maps describe scalp-recorded patterns, not precise neural generators. The findings are best interpreted as channel-level evidence of spatially uneven spectral reorganisation.
