# Task 06 – Field at a Point from a System of Charges

## Problem Statement

Two point charges are given:
* $+q$ at point $(-a, 0)$
* $+2q$ at point $(a, 0)$

1. Determine the field vector $\vec E(0, y)$, $\vec E(x, 0)$ and generally $\vec E(x, y)$.
2. Determine the condition for which the components $E_x = 0$, $E_y = 0$ and the zero field $\vec E = 0$.
3. Calculate the field for: $a = 0.2\,\mathrm{m}$, $y = 0.3\,\mathrm{m}$, $q = 2\,\mu\mathrm{C}$.
4. Investigate the limit $y \gg a$.

## Theory

The electric field $\vec{E}$ at a point $\vec{r}$ due to a point charge $q_i$ at $\vec{r}_i$ is:

$$
\vec{E}_i = \frac{k_e q_i}{|\vec{r} - \vec{r}_i|^3} (\vec{r} - \vec{r}_i)
$$

The total field is the vector sum $\vec{E} = \sum \vec{E}_i$.

## Step-by-Step Solution

### 1. General Field $\vec{E}(x, y)$
Let $\vec{r} = (x, y)$, $\vec{r}_1 = (-a, 0)$, and $\vec{r}_2 = (a, 0)$.

$$
\vec{E}(x, y) = k_e q \left[ \frac{(x+a, y)}{((x+a)^2 + y^2)^{3/2}} + \frac{2(x-a, y)}{((x-a)^2 + y^2)^{3/2}} \right]
$$

**Specific cases:**
* For $\vec{E}(0, y)$:
$$
\vec{E}(0, y) = k_e q \left[ \frac{(a, y)}{(a^2 + y^2)^{3/2}} + \frac{2(-a, y)}{(a^2 + y^2)^{3/2}} \right] = \frac{k_e q}{(a^2 + y^2)^{3/2}} (-a, 3y)
$$

* For $\vec{E}(x, 0)$:
$$
\vec{E}(x, 0) = k_e q \left[ \frac{x+a}{|x+a|^3} + \frac{2(x-a)}{|x-a|^3} \right] \hat{i}
$$

### 2. Zero Field Conditions
* $E_y = 0$: Occurs whenever $y=0$ (on the x-axis).
* $E_x = 0$: On the y-axis, this never occurs except at infinity because the $2q$ charge always pushes harder to the left than the $q$ charge pushes to the right.
* $\vec{E} = 0$: Must occur on the x-axis between the charges. Set $E_x(x,0) = 0$ for $-a < x < a$:
$$
\frac{1}{(x+a)^2} = \frac{2}{(a-x)^2} \implies \sqrt{2}(x+a) = a-x \implies x = a \frac{1-\sqrt{2}}{1+\sqrt{2}}
$$

### 3. Numerical Calculation
Given $a = 0.2, y = 0.3, q = 2\times 10^{-6}$. Using $\vec{E}(0, y)$:
$r = \sqrt{0.2^2 + 0.3^2} = \sqrt{0.13} \approx 0.361\text{ m}$.

$$
\vec{E}(0, 0.3) = \frac{(8.99\times 10^9)(2\times 10^{-6})}{(0.13)^{3/2}} \begin{pmatrix} -0.2 \\ 0.9 \end{pmatrix} \approx \begin{pmatrix} -7.67 \times 10^4 \\ 3.45 \times 10^5 \end{pmatrix} \text{ V/m}
$$

### 4. Limit $y \gg a$
When $y$ is large, the system behaves like a single charge of $Q = 3q$:

$$
\vec{E}(0, y) \approx \frac{k_e q}{(y^2)^{3/2}} (0, 3y) = \frac{3 k_e q}{y^2} \hat{j}
$$

## Final Result
The general field is defined by the superposition of two point-charge vectors. The equilibrium point ($\vec{E}=0$) lies at $x \approx -0.17a$ on the x-axis.

## Interpretation
At large distances, the details of charge placement become negligible, and the field approximates that of a single point charge equal to the sum of the constituents ($3q$).