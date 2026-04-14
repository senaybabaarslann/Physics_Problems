# Task 03 – Electrostatic Equilibrium

## Problem Statement

Find the equilibrium position for a charge $q_3 = +1\text{C}$ placed on the line between a charge $q_1 = +4\text{C}$ and a charge $q_2 = +9\text{C}$, which are separated by a distance of $2\text{ m}$.

## Theory

Equilibrium occurs when the net force acting on a particle is zero. For a third charge $q_3$ placed between two charges of the same sign, the forces exerted by $q_1$ and $q_2$ will point in opposite directions.

The condition for equilibrium is:

$$
\vec{F}_{13} + \vec{F}_{23} = 0 \implies |\vec{F}_{13}| = |\vec{F}_{23}|
$$

## Step-by-Step Solution

### 1. Set up the Coordinates
Let $q_1$ be at $x = 0$ and $q_2$ be at $x = L$, where $L = 2\text{ m}$.
Let the position of $q_3$ be $x$. The distance from $q_1$ is $x$, and the distance from $q_2$ is $L - x$.

### 2. Formulate the Force Equation
Using Coulomb's Law:

$$
k_e \frac{q_1 q_3}{x^2} = k_e \frac{q_2 q_3}{(L - x)^2}
$$

Cancel $k_e$ and $q_3$:

$$
\frac{q_1}{x^2} = \frac{q_2}{(L - x)^2}
$$

### 3. Solve for $x$
Take the square root of both sides:

$$
\frac{\sqrt{q_1}}{x} = \frac{\sqrt{q_2}}{L - x}
$$

Substitute $q_1 = 4$ and $q_2 = 9$:

$$
\frac{2}{x} = \frac{3}{2 - x}
$$

Cross-multiply:

$$
2(2 - x) = 3x
$$

$$
4 - 2x = 3x \implies 5x = 4 \implies x = 0.8
$$

## Final Result

The equilibrium position for $q_3$ is $0.8\text{ m}$ from charge $q_1$ (the $+4\text{C}$ charge).

## Interpretation
Since $q_2$ is stronger than $q_1$, the equilibrium point must be closer to the weaker charge to balance the forces. The position is independent of the magnitude or sign of $q_3$.