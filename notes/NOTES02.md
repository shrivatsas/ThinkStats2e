# Distributions

## Histograms

Used to represent frequencies a variable.
Terms to describe a histogram are,
* Central tendency - How clustered are values around a certain point
* Modes - Is there more than one cluster
* Spread - How much variability in values
* Tails - How quickly do probabilities drop off away from modes
* Outliers - Are there extreme values

## Terms

* Mode - The most common value.
* Mean - Describes the central tendency. The middle value.
* Variance - Describes variability or spread of a distribution. Mean squared deviation.
* Standard Deviation - Square root of variance.

Normal / Gaussian distribution - The bell shaped curve. Can be symmetric or asymmetric, based on left / right extensions.

A pandas `Series` type provides these metrics

## Outliers

Some values might be improbable given the context. These are mostly errors in data entry or very rare events. Needs some amount of domain knowledge to tackle these.

## Effect Size

Metric used to describe differences between 2 groups. Multiple ways are possible,
* Difference in Means
* Cohen's `d` - the difference of Means to the pooled standard deviation
