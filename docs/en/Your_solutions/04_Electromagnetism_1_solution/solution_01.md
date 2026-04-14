# Task 01 – Coulomb's Law in a Square Configuration

## Problem Statement

Four point charges of $+1.0\text{ C}$ each are placed at the corners of a square with sides of $1.0\text{ m}$. Calculate the magnitude and direction of the electric force on a charge of $-2.0\text{ C}$ placed at the center of the square.

## Theory

The electrostatic force between two point charges is governed by Coulomb's Law:

$$
\vec{F} = k_e \frac{q_1 q_2}{r^2} \hat{r}
$$

Where:
* $k_e \approx 8.99 \times 10^9\text{ N}\cdot\text{m}^2/\text{C}^2$ is Coulomb's constant.
* $q_1, q_2$ are the magnitudes of the charges.
* $r$ is the distance between the charges.
* $\hat{r}$ is the unit vector pointing from the source charge to the test charge.

According to the **Principle of Superposition**, the total force on a charge is the vector sum of the individual forces exerted by all other charges in the system:

$$
\vec{F}_{total} = \sum_{i=1}^{n} \vec{F}_i
$$

## Step-by-Step Solution

### 1. Geometry of the Square
Place the square in a coordinate system such that the center is at $(0,0)$. For a square with side $a = 1.0\text{ m}$, the distance from the center to any corner (the circumradius $R$) is calculated using the Pythagorean theorem:

$$
R = \frac{1}{2} \sqrt{a^2 + a^2} = \frac{a\sqrt{2}}{2}
$$

For $a = 1.0\text{ m}$:

$$
R = \frac{\sqrt{2}}{2} \approx 0.707\text{ m}
$$

### 2. Analysis of Force Vectors
Let the four corner charges be $q_1, q_2, q_3, q_4 = +1.0\text{ C}$ and the center charge be $Q = -2.0\text{ C}$.

Since all corner charges are identical in magnitude and sign, and the center charge is equidistant from all corners:
* The magnitude of the force from any single corner charge $i$ on $Q$ is:

$$
F_i = k_e \frac{|q_i Q|}{R^2}
$$

* Because $Q$ is negative and $q_i$ is positive, each force vector $\vec{F}_i$ points from the center toward the respective corner.

### 3. Vector Summation
In a symmetric arrangement where identical charges are placed at the corners of a regular polygon, the force vectors acting on a central charge will cancel out in pairs.

* The force from the top-left corner is equal in magnitude and opposite in direction to the force from the bottom-right corner.
* The force from the top-right corner is equal in magnitude and opposite in direction to the force from the bottom-left corner.

$$
\sum \vec{F} = \vec{F}_1 + \vec{F}_3 + \vec{F}_2 + \vec{F}_4 = 0
$$

## Final Result

The magnitude of the net electric force on the center charge is:

$$
F_{net} = 0\text{ N}
$$

The direction is undefined as the vector is null.

## Interpretation
Due to the perfect axial and central symmetry of the charge distribution, the electric field at the geometric center of the square is zero. Consequently, any charge placed at this point experiences no net electrostatic force, representing a point of electrostatic equilibrium.