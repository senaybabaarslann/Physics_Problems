# Task 03 – Superposition Principle

## Problem Statement

Two waves are described by the equations $y_1(x,t) = A \sin(kx - \omega t)$ and $y_2(x,t) = A \sin(kx + \omega t)$. What is the equation of the resulting standing wave? Identify the positions of the nodes.

## Theory

The principle of superposition states that the resultant displacement is the algebraic sum of individual displacements:

$$
y_{res} = y_1 + y_2
$$

We use the trigonometric identity:

$$
\sin \alpha + \sin \beta = 2 \sin \left( \frac{\alpha + \beta}{2} \right) \cos \left( \frac{\alpha - \beta}{2} \right)
$$

## Step-by-Step Solution

### 1. Summation of Waves

Let $\alpha = kx - \omega t$ and $\beta = kx + \omega t$:

$$
y(x,t) = A [ \sin(kx - \omega t) + \sin(kx + \omega t) ]
$$

Applying the identity:

$$
\begin{align}
y(x,t) &= A \left[ 2 \sin \left( \frac{kx - \omega t + kx + \omega t}{2} \right) \cos \left( \frac{kx - \omega t - (kx + \omega t)}{2} \right) \right] \\
y(x,t) &= 2A \sin(kx) \cos(-\omega t)
\end{align}
$$

Since $\cos(-\theta) = \cos \theta$:

$$
y(x,t) = [2A \sin(kx)] \cos(\omega t)
$$

### 2. Identifying Nodes

Nodes are positions where the amplitude is always zero ($y = 0$ for all $t$):

$$
\sin(kx) = 0
$$

This occurs when:

$$
kx = n\pi, \quad n = 0, 1, 2, \dots
$$

Since $k = 2\pi / \lambda$:

$$
\frac{2\pi x}{\lambda} = n\pi \implies x = n \frac{\lambda}{2}
$$

## Final Result

* **Standing Wave Equation:** $y(x,t) = 2A \sin(kx) \cos(\omega t)$
* **Node Positions:** $x = 0, \frac{\lambda}{2}, \lambda, \frac{3\lambda}{2}, \dots$

## Interpretation

The resulting wave does not travel (the $x$ and $t$ terms are separated). The term $2A \sin(kx)$ represents the spatially varying amplitude, while $\cos(\omega t)$ represents the temporal oscillation.