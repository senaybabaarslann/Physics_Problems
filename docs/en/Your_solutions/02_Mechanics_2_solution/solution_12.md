# Task 12 – Work and Energy with Constant Force

## Problem Statement

A constant force $\vec{F} = [6, 2] \text{ N}$ acts on $m = 2 \text{ kg}$. 
Initial state: $\vec{v}(0) = (1, -1) \text{ m/s}$ and $\vec{r}(0) = (0, 0)$.

* Determine $\vec{a}(t), \vec{v}(t), \vec{r}(t)$.
* Calculate the work done by the force at $t=3 \text{ s}$.
* Check consistency with the Work-Energy Theorem.

## Theory

For a constant force, acceleration is constant: $\vec{a} = \vec{F}/m$.
Work $W = \vec{F} \cdot \Delta \vec{r}$.
Work-Energy Theorem: $W = \Delta K = \frac{1}{2}m(v_f^2 - v_i^2)$.

## Step-by-Step Solution

### 1. Kinematics

$$
\vec{a} = \frac{1}{2}
\begin{pmatrix}
6 \\
2
\end{pmatrix}
=
\begin{pmatrix}
3 \\
1
\end{pmatrix} \text{ m/s}^2
$$

$$
\vec{v}(t) = \vec{v}_0 + \vec{a}t = 
\begin{pmatrix}
1 + 3t \\
-1 + t
\end{pmatrix}
$$

$$
\vec{r}(t) = \vec{v}_0 t + \frac{1}{2} \vec{a}t^2 = 
\begin{pmatrix}
t + 1.5t^2 \\
-t + 0.5t^2
\end{pmatrix}
$$

### 2. Work at $t=3$

First, find displacement $\Delta \vec{r}$ at $t=3$:

$$
\Delta x = 3 + 1.5(9) = 16.5 \text{ m}
$$

$$
\Delta y = -3 + 0.5(9) = 1.5 \text{ m}
$$

$$
W = F_x \Delta x + F_y \Delta y = 6(16.5) + 2(1.5) = 99 + 3 = 102 \text{ J}
$$

### 3. Work-Energy Theorem Verification

Initial speed $v_i^2 = 1^2 + (-1)^2 = 2$.
Final speed at $t=3$: $v_x = 10, v_y = 2 \implies v_f^2 = 100 + 4 = 104$.

$$
\Delta K = \frac{1}{2}(2)(104 - 2) = 102 \text{ J}
$$

Both values match.

## Final Result

* **Work:** $102 \text{ J}$
* **Theorem Check:** $W = \Delta K = 102 \text{ J}$ (Consistent)

## Interpretation

The constant force results in a parabolic trajectory. Since the work done by the force equals the change in the particle's kinetic energy, the calculation is verified.