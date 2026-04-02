# Task 01 – Gravitational Dependence of a Pendulum

## Problem Statement

A simple pendulum has a period of 4 seconds on Earth. 

* What would its period be on the Moon, where the gravitational acceleration is about 1/6th of Earth's?
* What is the required length of a simple pendulum to have a period of exactly 1 second on Earth?

## Theory

The period $T$ of a simple pendulum for small angles is given by:

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

where $L$ is the length of the pendulum and $g$ is the gravitational acceleration. From this, we can see that $T$ is inversely proportional to the square root of $g$:

$$
T \propto \frac{1}{\sqrt{g}}
$$

## Step-by-Step Solution

### 1. Period on the Moon

Let $T_E = 4 \text{ s}$ and $g_M = \frac{1}{6}g_E$. The ratio of the periods is:

$$
\frac{T_M}{T_E} = \frac{2\pi \sqrt{L/g_M}}{2\pi \sqrt{L/g_E}} = \sqrt{\frac{g_E}{g_M}}
$$

Substituting $g_M = g_E/6$:

$$
\frac{T_M}{4} = \sqrt{\frac{g_E}{g_E/6}} = \sqrt{6}
$$

$$
T_M = 4\sqrt{6} \approx 4 \times 2.449 \approx 9.80 \text{ s}
$$

### 2. Required Length on Earth

We solve the period formula for $L$:

$$
T^2 = 4\pi^2 \frac{L}{g} \implies L = \frac{g T^2}{4\pi^2}
$$

For $T = 1 \text{ s}$ and $g = 9.81 \text{ m/s}^2$:

$$
L = \frac{9.81 \cdot (1)^2}{4\pi^2} \approx \frac{9.81}{39.478} \approx 0.2485 \text{ m}
$$

## Final Result

* **Period on the Moon:** $T_M \approx 9.80 \text{ s}$
* **Required Length on Earth:** $L \approx 0.2485 \text{ m}$ (or $24.85 \text{ cm}$)

## Interpretation

The period increases on the Moon because the restoring force (gravity) is weaker, making the "swing" slower. To decrease the period to 1 second on Earth, the length must be shortened significantly, as the period is directly proportional to the square root of the length.