# Task 09 – Vertical Throw with Drag

## Problem Statement

Solve the equation of motion for a vertical throw with linear air drag:

$$
m \frac{dv}{dt} = -mg - kv
$$

Initial conditions: $v(0) = v_0$ and $x(0) = 10$.

## Theory

This is a first-order separable differential equation. As $v$ increases, the drag force $-kv$ increases until it potentially balances other forces.

## Step-by-Step Solution

### 1. Analytical Solution for Velocity

Separate the variables $v$ and $t$:

$$
\frac{m dv}{-mg - kv} = dt \implies \frac{dv}{g + \frac{k}{m}v} = -dt
$$

Let $\gamma = k/m$. Integrate both sides:

$$
\int \frac{dv}{g + \gamma v} = \int -dt
$$

$$
\frac{1}{\gamma} \ln(g + \gamma v) = -t + C
$$

Apply $v(0) = v_0$:

$$
C = \frac{1}{\gamma} \ln(g + \gamma v_0)
$$

$$
\ln\left( \frac{g + \gamma v}{g + \gamma v_0} \right) = -\gamma t
$$

$$
v(t) = \left( v_0 + \frac{g}{\gamma} \right) e^{-\gamma t} - \frac{g}{\gamma}
$$

### 2. Maximum Height

At maximum height, $v(t) = 0$:

$$
0 = \left( v_0 + \frac{g}{\gamma} \right) e^{-\gamma t_h} - \frac{g}{\gamma} \implies e^{-\gamma t_h} = \frac{g}{g + \gamma v_0}
$$

$$
t_h = \frac{1}{\gamma} \ln\left( 1 + \frac{\gamma v_0}{g} \right)
$$

The height $H$ is found by integrating $v(t)$ and adding $x(0) = 10$.

## Final Result

* **Velocity:** $v(t) = (v_0 + \frac{mg}{k})e^{-kt/m} - \frac{mg}{k}$
* **Max Height Time:** $t_h = \frac{m}{k} \ln(1 + \frac{kv_0}{mg})$

## Interpretation

Unlike the vacuum case where the velocity decreases linearly, here the velocity decreases exponentially towards a terminal velocity $-mg/k$. Drag reduces both the time to reach the peak and the maximum height reached compared to a frictionless environment.