# Temporal Stability and Persistence Analysis

## How Long Neural-State Patterns Persist

This directory contains figures and processed CSV outputs examining the temporal stability of cortical information dynamics between baseline and modulation conditions.

The purpose of this analysis is to move beyond instantaneous change. If cognitive state is a dynamic operating condition, then it matters not only what pattern appears, but how long that pattern is maintained before the system transitions again.

The figure set includes:

- Baseline persistence heatmaps for entropy and theta/alpha ratio measures.
- Modulation persistence heatmaps for entropy and theta/alpha ratio measures.
- Modulation-minus-baseline delta plots.
- Autocorrelation decay metrics.
- Mean dwell-time metrics above and below baseline anchors.
- Fraction-of-time-above-baseline metrics.
- Processed CSV tables for baseline, modulation, combined metrics, anchor medians, and deltas.

The persistence analysis uses several complementary measures:

- **ACF τ₁/e** estimates how long the autocorrelation structure persists before decaying toward 1/e.
- **ACF half-life** estimates the time required for autocorrelation to decay by half.
- **Mean dwell time above baseline** estimates how long a metric remains above its baseline anchor.
- **Mean dwell time below baseline** estimates how long a metric remains below its baseline anchor.
- **Fraction above baseline** estimates the proportion of time spent above the baseline reference.

Some ACF values are censored or plotted as bounds where the decay threshold was not fully crossed inside the search horizon. These should be read as bounded persistence estimates rather than exact decay times.

The outputs show selective persistence effects rather than uniform stabilisation across all bands and regions.

Entropy-derived persistence changes vary strongly by band and region. Some regional-frequency combinations show longer dwell times or longer autocorrelation persistence under modulation, while others show reductions. Across entropy rows, fraction-above-baseline tends to decrease on average, but dwell-time and decay metrics reveal that the temporal structure is more nuanced than a simple up-or-down shift.

Theta/alpha ratio and log theta/alpha ratio changes are comparatively modest. In the delta tables, fraction above baseline decreases slightly, mean dwell above baseline decreases by roughly a third of a second, and ACF decay changes remain small.

Temporal persistence describes the stability of a neural operating condition. A pattern that appears briefly may have different functional implications from a pattern that is sustained over time.

For the accompanying influence-warfare paper, this matters because cognitive state can influence the duration over which attention, salience, emotional weighting, and uncertainty processing remain biased toward a particular configuration. The persistence analyses illustrate that state organisation has temporal depth, not merely instantaneous structure.

Persistence metrics do not establish subjective experience, cognitive performance, or behavioural effect. They describe how long measured EEG-derived patterns remain above, below, or autocorrelated relative to baseline anchors.
