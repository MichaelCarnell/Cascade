# Colocalisation

Colocalisation analysis helps determine whether two signals are spatially or intensity associated.

## Key Point

Colocalisation does not prove direct molecular interaction. It shows that signals are related according to the selected measurement.

## Metrics

### Linear Correlation: Pearson's R

Measures whether pixel intensities increase or decrease together.

### Rank Correlation: Spearman's Rank

Measures whether the relationship is monotonic, even if it is not linear.

### Signal Co-occurrence: Manders M1 and M2

Measures how much of one channel's signal occurs where the other channel is present.

### Area Overlap Fraction: Jaccard Index

Measures the fraction of segmented area shared by both channels.

## Common Problems

- Saturated pixels
- Poor background subtraction
- Bleed-through between channels
- Misregistration between channels
- Thresholds chosen without justification