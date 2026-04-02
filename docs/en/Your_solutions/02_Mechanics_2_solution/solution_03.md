# Task 03 – Conservation of Energy

## Problem Statement

A pendulum with a length of $1.0$ meter is released from an initial angle of $15^\circ$. What is the speed of the pendulum bob at the bottom of its swing?

## Theory

In the absence of friction, mechanical energy is conserved:

$$
E_{initial} = E_{final}
$$

At the release point (height $h$), the energy is purely potential. At the bottom ($h=0$), it is purely kinetic:

$$
mgh = \frac{1}{2} mv^2
$$

The height $h$ relative to the bottom is determined by the geometry:

$$
h = L - L \cos \theta = L(1 - \cos \theta)
$$

## Step-by-Step Solution

### 1. Calculate Initial Height

Given $L = 1.0 \text{ m}$ and $\theta = 15^\circ$:

$$
h = 1.0 \cdot (1 - \cos 15^\circ)
$$

Using $\cos 15^\circ \approx 0.9659$:

$$
h \approx 1.0 \cdot (1 - 0.9659) = 0.0341 \text{ m}
$$

### 2. Calculate Velocity at the Bottom

From the energy balance $mgh = \frac{1}{2} mv^2$, we solve for $v$:

$$
v = \sqrt{2gh}
$$

Substituting the values:

$$
v = \sqrt{2 \cdot 9.81 \cdot 0.0341}
$$

$$
v \approx \sqrt{0.669} \approx 0.818 \text{ m/s}
$$

## Final Result

The speed at the bottom is approximately $0.818 \text{ m/s}$.

## Interpretation

The potential energy associated with the small vertical lift is converted entirely into kinetic energy. Even with a 1-meter arm, a $15^\circ$ release results in a relatively low speed due to the small vertical displacement.