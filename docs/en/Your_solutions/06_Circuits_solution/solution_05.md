# Task 05 – Kirchhoff's Laws

## Problem Statement

Find the currents $I_1, I_2, I_3$ in a two-loop circuit.
- Loop 1: $R_1 = 20\,\Omega$, $\mathcal{E}_1 = 4.5\,\text{V}$, $r_{w1} = 1\,\Omega$.
- Loop 2: $\mathcal{E}_2 = 9\,\text{V}$, $r_{w2} = 1\,\Omega$.
- Shared: $R_2 = 10\,\Omega$.

## Theory

Kirchhoff's Current Law (KCL): $\sum I_{in} = \sum I_{out}$.
Kirchhoff's Voltage Law (KVL): $\sum \mathcal{E} = \sum I \cdot R$.

## Step-by-Step Solution

1. **KCL at top node:**
   $I_1 + I_3 = I_2$

2. **KVL Loop 1 (Left):**

$$
\mathcal{E}_1 = I_1(R_1 + r_{w1}) + I_2 R_2
$$

$$
4.5 = 21 I_1 + 10 I_2
$$

3. **KVL Loop 2 (Right):**

$$
\mathcal{E}_2 = I_3 r_{w2} + I_2 R_2
$$

$$
9 = 1 I_3 + 10 I_2
$$

4. **Solving the system:**
Substitute $I_3 = I_2 - I_1$ into the second equation:

$$
9 = (I_2 - I_1) + 10 I_2 \implies 9 = 11 I_2 - I_1
$$

From equation 1: $I_1 = 11 I_2 - 9$. Substitute into the first equation:

$$
4.5 = 21(11 I_2 - 9) + 10 I_2
$$

$$
4.5 = 231 I_2 - 189 + 10 I_2 \implies 193.5 = 241 I_2 \implies I_2 \approx 0.803\,\text{A}
$$

Find $I_1$ and $I_3$ accordingly.

## Final Result

$I_1 \approx -0.167\,\text{A}$, $I_2 \approx 0.803\,\text{A}$, $I_3 \approx 0.970\,\text{A}$.

## Interpretation

The negative sign for $I_1$ indicates the current flows in the opposite direction to the initially assumed arrow.