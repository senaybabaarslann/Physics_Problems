# Task 06 – Variable Velocity

## Problem Statement

An object's velocity is given by $v(t) = t^2 + 2t - 5$. If the object was at $x=4$ at $t=0$, what is its position and acceleration at time $t=3$?

## Theory

Position $x(t)$ is found by integrating velocity:

$$
x(t) = x_0 + \int_{0}^{t} v(\tau) d\tau
$$

Acceleration $a(t)$ is the derivative of velocity:

$$
a(t) = \frac{dv}{dt}
$$

## Step-by-Step Solution

### 1. Position at $t=3$

First, find the general expression for $x(t)$:

$$
x(t) = 4 + \int_{0}^{t} (\tau^2 + 2\tau - 5) d\tau
$$

$$
x(t) = 4 + \left[ \frac{1}{3}\tau^3 + \tau^2 - 5\tau \right]_{0}^{t}
$$

$$
x(t) = \frac{1}{3}t^3 + t^2 - 5t + 4
$$

Evaluating at $t=3$:

$$
x(3) = \frac{1}{3}(3)^3 + (3)^2 - 5(3) + 4
$$

$$
x(3) = 9 + 9 - 15 + 4 = 7
$$

### 2. Acceleration at $t=3$

Differentiating $v(t)$:

$$
a(t) = \frac{d}{dt}(t^2 + 2t - 5) = 2t + 2
$$

Evaluating at $t=3$:

$$
a(3) = 2(3) + 2 = 8
$$

## Final Result

* **Position at $t=3$:** $x = 7$
* **Acceleration at $t=3$:** $a = 8$

## Interpretation

The velocity is a quadratic function of time, implying that the acceleration is not constant but increases linearly. By integrating, we found the cubic displacement function.