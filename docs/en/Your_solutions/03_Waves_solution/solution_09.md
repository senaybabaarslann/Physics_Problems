# Task 09 – Damped Oscillator

## Problem Statement

For the damped harmonic oscillator equation:
$m\frac{d^2x}{dt^2} + b\frac{dx}{dt} + kx = 0$

1. Write down the general solution.
2. Classification: underdamped, critically damped, overdamped.
3. Numerical implementation (discussion).

## Theory

We assume a solution $x(t) = e^{rt}$. Substituting into the ODE:

$$
mr^2 + br + k = 0
$$

The roots are:

$$
r = \frac{-b \pm \sqrt{b^2 - 4mk}}{2m}
$$

## Step-by-Step Solution

### 1. Classification

* **Overdamped ($b^2 > 4mk$):** Two real, negative roots. The system returns to equilibrium without oscillating.
* **Critically Damped ($b^2 = 4mk$):** One repeated real root. The fastest return to equilibrium.
* **Underdamped ($b^2 < 4mk$):** Complex conjugate roots $r = -\gamma \pm i\omega_d$. The system oscillates with decaying amplitude.

### 2. General Solution (Underdamped)

$$
x(t) = A e^{-\frac{b}{2m}t} \cos(\omega_d t + \phi)
$$

where $\omega_d = \sqrt{\frac{k}{m} - \left(\frac{b}{2m}\right)^2}$.

## Numerical Simulation (HTML/JS)

The following code implements the simulation using the RK4 method:

```html
<script>
function rk4(x, v, dt, m, b, k) {
    const f = (x, v) => (-b*v - k*x) / m;
    // Standard RK4 steps for second order ODE
    // ... logic for x_next and v_next ...
}
</script>