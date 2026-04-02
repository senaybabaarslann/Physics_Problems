# Task 02 – Harmonic Motion

## Problem Statement

A $10 \text{ kg}$ mass is attached to a spring and oscillates according to the equation $x(t) = 0.2 \cos(10\pi t)$ (in meters). 

* What is the spring constant $k$?
* What is the total mechanical energy of the system?

## Theory

The general equation for simple harmonic motion (SHM) is:

$$
x(t) = A \cos(\omega t + \phi)
$$

The angular frequency $\omega$ is related to the mass $m$ and spring constant $k$ by:

$$
\omega = \sqrt{\frac{k}{m}} \implies k = m \omega^2
$$

The total mechanical energy $E_{total}$ is conserved and given by:

$$
E_{total} = \frac{1}{2} k A^2
$$

## Step-by-Step Solution

### 1. Finding the Spring Constant

From the given equation $x(t) = 0.2 \cos(10\pi t)$:
* Amplitude $A = 0.2 \text{ m}$
* Angular frequency $\omega = 10\pi \text{ rad/s}$

Given $m = 10 \text{ kg}$:

$$
k = 10 \cdot (10\pi)^2 = 10 \cdot 100\pi^2 = 1000\pi^2
$$

Using $\pi^2 \approx 9.87$:

$$
k \approx 9869.6 \text{ N/m}
$$

### 2. Finding Total Mechanical Energy

$$
E_{total} = \frac{1}{2} (1000\pi^2) \cdot (0.2)^2
$$

$$
E_{total} = 500\pi^2 \cdot 0.04 = 20\pi^2
$$

Calculation:

$$
E_{total} \approx 20 \cdot 9.8696 \approx 197.39 \text{ J}
$$

## Final Result

* **Spring Constant:** $k = 1000\pi^2 \approx 9869.6 \text{ N/m}$
* **Total Energy:** $E_{total} = 20\pi^2 \approx 197.39 \text{ J}$

## Interpretation

The system possesses a high spring constant, indicating a very stiff spring. The total energy remains constant, oscillating between maximum elastic potential energy at the displacement peaks and maximum kinetic energy at the equilibrium position.
