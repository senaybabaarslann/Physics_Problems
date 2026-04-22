# Task 06 – EM Wave Analysis

## Problem Statement

An electromagnetic wave has its electric field component described by $E_y(x,t) = 100 \sin(10^7 x - \omega t) \text{ V/m}$.
1. What is the direction of propagation?
2. What is the wavelength $\lambda$?
3. What is the angular frequency $\omega$?
4. What is the equation for the magnetic field component?

## Theory

A plane EM wave in vacuum follows the general form $E = E_0 \sin(kx - \omega t)$.
* The propagation vector $\mathbf{k}$ indicates the direction.
* Wavelength: $\lambda = \frac{2\pi}{k}$
* Speed of light: $c = \frac{\omega}{k} = 3 \times 10^8 \text{ m/s}$
* Magnetic field amplitude: $B_0 = \frac{E_0}{c}$
* The $\mathbf{E}$ and $\mathbf{B}$ fields are perpendicular to each other and to the direction of propagation.

## Step-by-Step Solution

1. **Direction of Propagation**:
The argument $(kx - \omega t)$ implies the wave is moving in the **positive x-direction**.

2. **Wavelength**:
From the equation, $k = 10^7 \text{ rad/m}$.

$$
\lambda = \frac{2\pi}{k} = \frac{2\pi}{10^7} \approx 6.28 \times 10^{-7} \text{ m}
$$

3. **Angular Frequency**:

$$
\omega = c k = (3 \times 10^8) \times 10^7 = 3 \times 10^{15} \text{ rad/s}
$$

4. **Magnetic Field Component**:
Since $\mathbf{E}$ is in the $y$ direction and propagation is in $x$, $\mathbf{B}$ must be in the $z$ direction.

$$
B_0 = \frac{E_0}{c} = \frac{100}{3 \times 10^8} = 3.33 \times 10^{-7} \text{ T}
$$

$$
B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7 x - 3 \times 10^{15} t) \text{ T}
$$

## Final Result

* Direction: $+x$
* $\lambda \approx 628 \text{ nm}$
* $\omega = 3 \times 10^{15} \text{ rad/s}$
* $B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7 x - 3 \times 10^{15} t) \text{ T}$

## Interpretation

The wavelength ($628 \text{ nm}$) falls within the visible light spectrum (red light). The calculation confirms the phase and spatial relationship between the electric and magnetic components.