# Task 07 – Cyclotron Motion

## Problem Statement

An electron is accelerated from rest through a potential difference of $5000\text{ V}$. It then enters a region of uniform magnetic field $B = 0.1\text{ T}$, perpendicular to its velocity. What is the radius of the circular path it will follow?

## Theory

1. **Conservation of Energy**: The kinetic energy gained equals the electric potential energy lost:
$$
\frac{1}{2}mv^2 = eV
$$

2. **Magnetic Force**: A charge moving perpendicular to a magnetic field experiences a centripetal force:
$$
\frac{mv^2}{r} = evB \implies r = \frac{mv}{eB}
$$

## Step-by-Step Solution

### 1. Calculate Velocity
$$
v = \sqrt{\frac{2eV}{m}}
$$
Using $e = 1.6 \times 10^{-19}\text{ C}$, $V = 5000\text{ V}$, $m = 9.11 \times 10^{-31}\text{ kg}$:
$$
v = \sqrt{\frac{2 \cdot 1.6 \times 10^{-19} \cdot 5000}{9.11 \times 10^{-31}}} \approx 4.19 \times 10^7\text{ m/s}
$$

### 2. Calculate Radius
$$
r = \frac{(9.11 \times 10^{-31})(4.19 \times 10^7)}{(1.6 \times 10^{-19})(0.1)}
$$

$$
r \approx 0.00239\text{ m} = 2.39\text{ mm}
$$

## Final Result

The radius of the circular path is $r \approx 2.39\text{ mm}$.

## Interpretation
The small radius indicates that even moderate magnetic fields can significantly deflect high-speed electrons, a principle used in mass spectrometry and older CRT televisions.