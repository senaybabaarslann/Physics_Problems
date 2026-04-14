# Task 02 – Electric Potential in a Square Configuration

## Problem Statement

Point charges of $+1\text{C}$, $-2\text{C}$, $+3\text{C}$, and $-4\text{C}$ are placed at the corners of a square with sides of $1.0\text{ m}$ (in order). Calculate the electric potential at the center of the square.

## Theory

The electric potential $V$ at a point due to a single point charge $q$ is a scalar quantity defined as:

$$
V = k_e \frac{q}{r}
$$

For a system of multiple charges, the total potential at a point is the algebraic sum of the potentials created by each charge:

$$
V_{total} = \sum_{i=1}^{n} k_e \frac{q_i}{r_i}
$$

Unlike force, potential is a scalar, so direction does not need to be considered—only the sign of the charges.

## Step-by-Step Solution

### 1. Determine the Distance
As established in the previous task, the distance $r$ from the center of a square with side $a=1.0\text{ m}$ to any corner is:

$$
r = \frac{a\sqrt{2}}{2} = \frac{1.0 \cdot \sqrt{2}}{2} = \frac{\sqrt{2}}{2}\text{ m}
$$

### 2. Summing the Potentials
The total potential $V_c$ at the center is:

$$
V_c = \frac{k_e}{r} (q_1 + q_2 + q_3 + q_4)
$$

Substitute the given charges $q_1 = 1, q_2 = -2, q_3 = 3, q_4 = -4$ (all in Coulombs):

$$
V_c = \frac{k_e}{\frac{\sqrt{2}}{2}} (1 - 2 + 3 - 4)
$$

$$
V_c = \frac{2k_e}{\sqrt{2}} (-2)
$$

$$
V_c = -\frac{4k_e}{\sqrt{2}} = -2\sqrt{2}k_e
$$

### 3. Numerical Calculation
Using $k_e \approx 8.99 \times 10^9\text{ V}\cdot\text{m}/\text{C}$:

$$
V_c \approx -2 \cdot 1.414 \cdot 8.99 \times 10^9
$$

$$
V_c \approx -2.54 \times 10^{10}\text{ V}