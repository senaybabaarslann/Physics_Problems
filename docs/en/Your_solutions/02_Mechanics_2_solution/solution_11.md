# Task 11 – Dynamics with a Time-Dependent Force

## Problem Statement

A mass $m = 3 \text{ kg}$ is subject to $\vec{F} = (15t, 3t - 12, -6t^2)$.
Initial conditions: $\vec{r}_0 = (5, 2, -3)$ and $\vec{v}_0 = (2, 0, 1)$. Find $\vec{r}(t)$ and $\vec{v}(t)$.

## Theory

From $\vec{F} = m\vec{a}$:

$$
\vec{a}(t) = \frac{\vec{F}(t)}{m}
$$

Integrating $\vec{a}(t)$ gives velocity, and integrating velocity gives position.

## Step-by-Step Solution

### 1. Acceleration

$$
\vec{a}(t) = \frac{1}{3}
\begin{pmatrix}
15t \\
3t - 12 \\
-6t^2
\end{pmatrix}
=
\begin{pmatrix}
5t \\
t - 4 \\
-2t^2
\end{pmatrix}
$$

### 2. Velocity

$$
\vec{v}(t) = \vec{v}_0 + \int_{0}^{t} \vec{a}(\tau) d\tau
$$

$$
\vec{v}(t) = 
\begin{pmatrix}
2 \\
0 \\
1
\end{pmatrix}
+
\begin{pmatrix}
2.5t^2 \\
0.5t^2 - 4t \\
-\frac{2}{3}t^3
\end{pmatrix}
=
\begin{pmatrix}
2.5t^2 + 2 \\
0.5t^2 - 4t \\
1 - \frac{2}{3}t^3
\end{pmatrix}
$$

### 3. Position

$$
\vec{r}(t) = \vec{r}_0 + \int_{0}^{t} \vec{v}(\tau) d\tau
$$

$$
\vec{r}(t) = 
\begin{pmatrix}
5 \\
2 \\
-3
\end{pmatrix}
+
\begin{pmatrix}
\frac{2.5}{3}t^3 + 2t \\
\frac{0.5}{3}t^3 - 2t^2 \\
t - \frac{2}{12}t^4
\end{pmatrix}
$$

## Final Result

* **Velocity:** $\vec{v}(t) = (2.5t^2+2, 0.5t^2-4t, 1-\frac{2}{3}t^3)$
* **Position:** $\vec{r}(t) = (\frac{5}{6}t^3+2t+5, \frac{1}{6}t^3-2t^2+2, - \frac{1}{6}t^4+t-3)$

## Interpretation

The particle's motion is highly non-linear because the force components vary with different powers of $t$. The $z$-component, in particular, shows a rapid downward acceleration as $t$ increases.