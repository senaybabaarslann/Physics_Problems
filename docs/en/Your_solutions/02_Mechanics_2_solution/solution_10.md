# Task 10 – Force Field and Power

## Problem Statement

A particle with $m = 0.5 \text{ kg}$ has position:
$x = 5t^2 - t$, $y = 2t^3$, $z = -3t + 2$.

Find:
* Velocity $\vec{v}(t)$ and momentum $\vec{p}(t)$
* Acceleration $\vec{a}(t)$ and force $\vec{F}(t)$
* Power $P(t)$

## Theory

$$
\vec{v} = \frac{d\vec{r}}{dt}, \quad \vec{p} = m\vec{v}, \quad \vec{a} = \frac{d\vec{v}}{dt}, \quad \vec{F} = m\vec{a}, \quad P = \vec{F} \cdot \vec{v}
$$

## Step-by-Step Solution

### 1. Velocity and Momentum

$$
\vec{v}(t) = 
\begin{pmatrix}
10t - 1 \\
6t^2 \\
-3
\end{pmatrix}
$$

$$
\vec{p}(t) = 0.5 \cdot \vec{v}(t) = 
\begin{pmatrix}
5t - 0.5 \\
3t^2 \\
-1.5
\end{pmatrix}
$$

### 2. Acceleration and Force

$$
\vec{a}(t) = 
\begin{pmatrix}
10 \\
12t \\
0
\end{pmatrix}
$$

$$
\vec{F}(t) = 0.5 \cdot \vec{a}(t) = 
\begin{pmatrix}
5 \\
6t \\
0
\end{pmatrix}
$$

### 3. Power

$P = F_x v_x + F_y v_y + F_z v_z$:

$$
P(t) = 5(10t - 1) + 6t(6t^2) + 0(-3)
$$

$$
P(t) = 50t - 5 + 36t^3
$$

## Final Result

* **Momentum:** $\vec{p} = (5t-0.5, 3t^2, -1.5) \text{ kg m/s}$
* **Force:** $\vec{F} = (5, 6t, 0) \text{ N}$
* **Power:** $P(t) = 36t^3 + 50t - 5 \text{ W}$

## Interpretation

The force is time-dependent in the $y$-direction, leading to non-constant acceleration. The power is positive for $t > 0.1$, meaning the field is doing work on the particle and increasing its kinetic energy.