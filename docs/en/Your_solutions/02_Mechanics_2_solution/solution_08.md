# Task 08 – Work of a Variable Force

## Problem Statement

Given a one-dimensional force $F(x) = -kx$:

* Write down the equation of motion and solve it.
* Calculate the work done during the displacement from $0$ to $x_0$.
* Interpret the result as potential energy and verify $F = -dU/dx$.

## Theory

Newton's Second Law for this force is:

$$
m \frac{d^2x}{dt^2} = -kx
$$

Work done by a variable force is:

$$
W = \int_{x_1}^{x_2} F(x) dx
$$

Potential energy $U(x)$ is defined such that $W_{conservative} = -\Delta U$.

## Step-by-Step Solution

### 1. Equation of Motion

$$
\frac{d^2x}{dt^2} + \frac{k}{m}x = 0
$$

This is a second-order linear differential equation. The solution is:

$$
x(t) = A \cos(\omega t + \phi), \quad \text{where } \omega = \sqrt{\frac{k}{m}}
$$

### 2. Work Calculation

$$
W = \int_{0}^{x_0} (-kx) dx = \left[ -\frac{1}{2}kx^2 \right]_{0}^{x_0}
$$

$$
W = -\frac{1}{2}kx_0^2
$$

### 3. Potential Energy and Verification

Since $W = -\Delta U$ and $U(0) = 0$:

$$
-\frac{1}{2}kx_0^2 = -(U(x_0) - 0) \implies U(x) = \frac{1}{2}kx^2
$$

Verifying the relationship:

$$
-\frac{dU}{dx} = -\frac{d}{dx} \left( \frac{1}{2}kx^2 \right) = -kx
$$

This matches the original force $F(x)$.

## Final Result

* **Work:** $W = -\frac{1}{2}kx_0^2$
* **Potential Energy:** $U(x) = \frac{1}{2}kx^2$

## Interpretation

The negative work indicates that the force is acting against the displacement (restoring force). The energy is stored in the "field" (the spring) as potential energy, which is a quadratic function of displacement.