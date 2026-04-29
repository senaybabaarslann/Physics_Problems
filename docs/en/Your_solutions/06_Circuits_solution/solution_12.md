# Task 12 – Transformer Currents

## Problem Statement

$N_p=1000$, $N_s=200$, $V_p=120\,\text{V}$. Calculate $V_s$ and $I_p$ if $I_s=3\,\text{A}$.

## Theory

Transformer ratio:

$$
\frac{V_p}{V_s} = \frac{N_p}{N_s}
$$

Power conservation (ideal):

$$
V_p I_p = V_s I_s \implies \frac{I_s}{I_p} = \frac{N_p}{N_s}
$$

## Step-by-Step Solution

1. **Calculate $V_s$:**

$$
V_s = V_p \cdot \frac{N_s}{N_p} = 120 \cdot \frac{200}{1000} = 24\,\text{V}
$$

2. **Calculate $I_p$:**

$$
I_p = I_s \cdot \frac{N_s}{N_p} = 3 \cdot \frac{200}{1000} = 0.6\,\text{A}
$$

## Final Result

- Secondary Voltage: $24\,\text{V}$
- Primary Current: $0.6\,\text{A}$

## Interpretation

This is a step-down transformer. It reduces voltage but increases current on the secondary side.