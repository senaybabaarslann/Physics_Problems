# Task 15 – Resistor Cube*

## Problem Statement

Find the equivalent resistance $R_{eq}$ between opposite corners of a cube made of 12 identical resistors $R$.

## Theory

Due to the symmetry of the cube, we can identify points of equal potential.

## Step-by-Step Solution

1. **Symmetry at Nodes:** Let current $I$ enter at corner A and leave at opposite corner B.
2. **Layer 1:** Current splits into 3 edges from A. By symmetry, $I/3$ flows through each.
3. **Layer 2:** Each of these 3 currents splits into 2 edges. So, $I/6$ flows through these 6 edges.
4. **Layer 3:** These 6 paths merge back into 3 edges leading to corner B. So, $I/3$ flows through each.

5. **Voltage Drop:**

$$
V_{total} = V_1 + V_2 + V_3 = \left( \frac{I}{3} \right)R + \left( \frac{I}{6} \right)R + \left( \frac{I}{3} \right)R
$$

$$
V_{total} = I \cdot R \left( \frac{2}{6} + \frac{1}{6} + \frac{2}{6} \right) = I \cdot R \left( \frac{5}{6} \right)
$$

6. **Equivalent Resistance:**

$$
R_{eq} = \frac{V_{total}}{I} = \frac{5}{6} R
$$

## Final Result

The equivalent resistance is $\frac{5}{6} R$.

## Interpretation

Symmetry allows us to treat complex 3D networks as simpler series-parallel combinations by grouping nodes with the same electrical potential.