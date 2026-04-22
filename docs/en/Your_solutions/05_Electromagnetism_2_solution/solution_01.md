# Task 01 – Gauss's Law for a Point Charge

## Problem Statement

A point charge of $+2 \text{ C}$ is located at the origin. Calculate the electric flux through a spherical surface of radius $1 \text{ m}$ centered at the origin.

## Theory

Gauss's Law relates the net electric flux $\Phi_E$ through a closed surface (Gaussian surface) to the net enclosed charge $Q_{enc}$. The law is expressed by the surface integral of the electric field $\mathbf{E}$ over a closed surface $S$:

$$
\Phi_E = \oint_S \mathbf{E} \cdot d\mathbf{A} = \frac{Q_{enc}}{\varepsilon_0}
$$

Where:
* $\Phi_E$ is the electric flux.
* $Q_{enc}$ is the total charge enclosed within the surface.
* $\varepsilon_0$ is the vacuum permittivity, approximately $8.854 \times 10^{-12} \text{ F/m}$.

Crucially, Gauss's Law states that the flux depends only on the enclosed charge and is independent of the radius of the spherical surface, provided the charge is contained within it.

## Step-by-Step Solution

1. **Identify the Enclosed Charge**:
The problem states a point charge is at the origin and the spherical surface is centered at the origin with $r = 1 \text{ m}$. Thus, the entire charge is enclosed.

$$
Q_{enc} = 2 \text{ C}
$$

2. **Apply Gauss's Law**:
Since we need to find the total flux $\Phi_E$, we use the direct relationship:

$$
\Phi_E = \frac{Q_{enc}}{\varepsilon_0}
$$

3. **Substitute Constants and Calculate**:

$$
\Phi_E = \frac{2}{8.854 \times 10^{-12}}
$$

$$
\Phi_E \approx 2.259 \times 10^{11} \text{ V} \cdot \text{m}
$$

## Final Result

The electric flux through the spherical surface is:

$$
\Phi_E \approx 2.26 \times 10^{11} \text{ N} \cdot \text{m}^2/\text{C}
$$

## Interpretation

The positive value of the flux indicates that the electric field lines are directed outward from the surface, which is consistent with a positive point charge. Although the radius was provided ($1 \text{ m}$), the result confirms that the flux through any closed surface surrounding this charge would be identical, regardless of the shape or size of that surface.