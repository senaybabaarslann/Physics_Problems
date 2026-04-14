# Task 09 – Vector Lorentz Force

## Problem Statement

A proton moves with a velocity $\vec{v} = (2\hat{i} - 4\hat{j} + \hat{k})\text{ m/s}$ in a region where the magnetic field is $\vec{B} = (\hat{i} + 2\hat{j} - \hat{k})\text{ T}$. What is the magnitude of the magnetic force?

## Theory

The magnetic force vector is given by the cross product:

$$
\vec{F} = q (\vec{v} \times \vec{B})
$$

The magnitude is $|\vec{F}| = q |\vec{v} \times \vec{B}|$.

## Step-by-Step Solution

### 1. Compute the Cross Product
$$
\vec{v} \times \vec{B} = \det \begin{pmatrix} \hat{i} & \hat{j} & \hat{k} \\ 2 & -4 & 1 \\ 1 & 2 & -1 \end{pmatrix}
$$

$$
\vec{v} \times \vec{B} = \hat{i}((-4)(-1) - (1)(2)) - \hat{j}((2)(-1) - (1)(1)) + \hat{k}((2)(2) - (-4)(1))
$$

$$
\vec{v} \times \vec{B} = 2\hat{i} + 3\hat{j} + 8\hat{k}
$$

### 2. Calculate Magnitude of Cross Product
$$
|\vec{v} \times \vec{B}| = \sqrt{2^2 + 3^2 + 8^2} = \sqrt{4 + 9 + 64} = \sqrt{77} \approx 8.775
$$

### 3. Calculate Force
Using $q = 1.6 \times 10^{-19}\text{ C}$:
$$
F = (1.6 \times 10^{-19})(8.775) \approx 1.40 \times 10^{-18}\text{ N}
$$

## Final Result

The magnitude of the magnetic force is $1.40 \times 10^{-18}\text{ N}$.

## Interpretation
The force is perpendicular to both the velocity and the magnetic field vectors, consistent with the right-hand rule.