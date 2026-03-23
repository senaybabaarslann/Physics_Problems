# Task 07 – Elimination of Time and Acceleration Analysis

## Problem Statement

The path equation is given in parametric form:

$$
x(t)=2t^2, \qquad y(t)=3t^3
$$

* Eliminate the parameter $t$.
* Draw the trajectory (description).
* Calculate $\vec v(t)$, $|\vec v(t)|$, $\vec a(t)$ and $|\vec a(t)|$.
* Is the acceleration constant?

## Theory

To eliminate $t$, express $t$ in terms of one variable and substitute it into the other.
Velocity and acceleration vectors are derived by taking time derivatives of the components.

## Step-by-Step Solution

### 1. Elimination of Parameter $t$

From $x = 2t^2$, we find $t$:

$$
t = \left(\frac{x}{2}\right)^{1/2}
$$

Substitute into $y = 3t^3$:

$$
y = 3 \left(\left(\frac{x}{2}\right)^{1/2}\right)^3 = 3 \left(\frac{x}{2}\right)^{3/2}
$$

$$
y = \frac{3}{2\sqrt{2}} x^{3/2}
$$

### 2. Trajectory

The trajectory follows the curve $y \propto x^{1.5}$. This is a semi-cubical parabola, starting at the origin $(0,0)$ and curving upwards more steeply than a standard parabola ($y \propto x^2$) for large $x$, but less steeply for $x < 1$.

### 3. Kinematics Calculations

**Velocity:**

$$
\vec{v}(t) = \frac{d}{dt} 
\begin{pmatrix}
2t^2 \\
3t^3
\end{pmatrix}
=
\begin{pmatrix}
4t \\
9t^2
\end{pmatrix}
$$

Magnitude $|\vec v(t)|$:

$$
|\vec v(t)| = \sqrt{(4t)^2 + (9t^2)^2} = \sqrt{16t^2 + 81t^4} = t\sqrt{16 + 81t^2}
$$

**Acceleration:**

$$
\vec{a}(t) = \frac{d}{dt}
\begin{pmatrix}
4t \\
9t^2
\end{pmatrix}
=
\begin{pmatrix}
4 \\
18t
\end{pmatrix}
$$

Magnitude $|\vec a(t)|$:

$$
|\vec a(t)| = \sqrt{4^2 + (18t)^2} = \sqrt{16 + 324t^2}
$$

### 4. Is the acceleration constant?

No. The acceleration vector $\vec{a}(t) = (4, 18t)$ depends explicitly on time $t$ through its $y$-component.

## Final Result

* **Path Equation:** $y = \frac{3}{2\sqrt{2}} x^{3/2}$
* **Velocity:** $\vec{v}(t) = (4t, 9t^2)$, $|\vec{v}| = t\sqrt{16 + 81t^2}$
* **Acceleration:** $\vec{a}(t) = (4, 18t)$, $|\vec{a}| = \sqrt{16 + 324t^2}$
* **Constant Acceleration:** No.

## Interpretation

The changing acceleration indicates that the force acting on the object is not constant; specifically, the vertical force must be increasing linearly with time.