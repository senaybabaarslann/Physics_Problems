# Task 04 – Mixed Circuit (2)

## Problem Statement

Calculate the equivalent resistance for the circuit shown in the figure (image-r2.png). All resistors have a resistance of $10\,\Omega$.

## Theory

In more complex mixed circuits, we look for nodes to identify where the current splits (parallel) and where it stays the same (series).

## Step-by-Step Solution

1. **Inner Parallel Pair:** Looking at the diagram, two resistors are in parallel:

$$
R_{p1} = \frac{10 \cdot 10}{10 + 10} = 5\,\Omega
$$

2. **Series Connection:** This $5\,\Omega$ block is in series with another $10\,\Omega$ resistor:

$$
R_{s1} = 5 + 10 = 15\,\Omega
$$

3. **Outer Parallel:** This $15\,\Omega$ branch is in parallel with the remaining $10\,\Omega$ resistor:

$$
R_{eq} = \frac{15 \cdot 10}{15 + 10} = \frac{150}{25} = 6\,\Omega
$$

## Final Result

The equivalent resistance is $6\,\Omega$.

## Interpretation

Reducing the circuit from the innermost branches outward simplifies the calculation of the total resistance.