# Task 14 – RLC Circuit

## Problem Statement

Write the differential equation for a series RLC circuit and compare it to a damped harmonic oscillator.

## Theory

For a series RLC circuit, Kirchhoff’s Voltage Law states:

$$
L \frac{dI}{dt} + RI + V_C = V(t)
$$

Since $I = \frac{dq}{dt}$ and $V_C = \frac{q}{C}$:

$$
L \frac{d^2q}{dt^2} + R \frac{dq}{dt} + \frac{1}{C}q = V(t)
$$

## Comparison Table

The mechanical equivalent is the damped mass-spring system:

$$
m \frac{d^2x}{dt^2} + b \frac{dx}{dt} + kx = F(t)
$$

| Electrical Property | Mechanical Analogy |
| :--- | :--- |
| Charge ($q$) | Displacement ($x$) |
| Inductance ($L$) | Mass ($m$) |
| Resistance ($R$) | Damping coefficient ($b$) |
| Reciprocal Capacitance ($1/C$) | Spring constant ($k$) |
| Electromotive Force ($V$) | External Force ($F$) |

## Final Result

The RLC circuit is an electrical analog of a damped harmonic oscillator.

## Interpretation

The energy oscillates between the magnetic field (Inductor) and electric field (Capacitor), while the resistor dissipates energy as heat, similar to friction.