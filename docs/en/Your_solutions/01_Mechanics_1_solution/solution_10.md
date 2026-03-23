# Task 10 – Kinematics in 3D

## Problem Statement

Point M moves according to the equation:

$$
\vec{r}(t) = (a \cos(\omega t), b \sin(\omega t), bt)
$$

where $a, b, \omega$ are positive constants.

a) Find the equation of the point's trajectory.
b) Compute the path length of the point from time $t=0$ to $t=t_0$.
c) Draw the trajectory (discussion).

## Theory

The trajectory is the curve traced in space.
The path length $s$ is the integral of the speed:

$$
s = \int_{0}^{t_0} |\vec{v}(t)| dt
$$

## Step-by-Step Solution

### a) Trajectory Equation

The components are:

$$
\begin{align}
x &= a \cos(\omega t) \implies \frac{x}{a} = \cos(\omega t) \\
y &= b \sin(\omega t) \implies \frac{y}{b} = \sin(\omega t) \\
z &= bt \implies t = \frac{z}{b}
\end{align}
$$

From the trigonometric identity $\cos^2 \theta + \sin^2 \theta = 1$:

$$
\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2 = 1
$$

This is the equation of an elliptical cylinder. The third component $z = bt$ indicates that the point also moves linearly along the z-axis.

### b) Path Length

Velocity $\vec{v}(t)$:

$$
\vec{v}(t) = \frac{d\vec{r}}{dt} = (-a\omega \sin(\omega t), b\omega \cos(\omega t), b)
$$

Speed $|\vec{v}(t)|$:

$$
|\vec{v}(t)| = \sqrt{(-a\omega \sin(\omega t))^2 + (b\omega \cos(\omega t))^2 + b^2}
$$

$$
|\vec{v}(t)| = \sqrt{a^2\omega^2 \sin^2(\omega t) + b^2\omega^2 \cos^2(\omega t) + b^2}
$$

Path length:

$$
s = \int_{0}^{t_0} \sqrt{a^2\omega^2 \sin^2(\omega t) + b^2\omega^2 \cos^2(\omega t) + b^2} dt
$$

Note: If $a=b$, then $|\vec{v}| = \sqrt{a^2\omega^2 + a^2}$, which is constant. If $a \neq b$, this is an elliptic integral.

### c) Trajectory Analysis

The trajectory is an **elliptical helix**.

* **Special Case $a=b$:** The trajectory is a circular helix. The path length becomes:
    $s = \int_{0}^{t_0} \sqrt{a^2\omega^2 + b^2} dt = t_0 \sqrt{a^2\omega^2 + b^2}$.
* **Special Case $\omega=0$:** The point stays at $(a, 0, bt)$, which is a straight line parallel to the z-axis.

## Final Result

* **Trajectory:** $\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2 = 1$ (Elliptical Cylinder)
* **Path Length:** $s = \int_{0}^{t_0} \sqrt{a^2\omega^2 \sin^2(\omega t) + b^2\omega^2 \cos^2(\omega t) + b^2} dt$

## Interpretation

The motion combines a periodic rotation in the $xy$-plane with a constant linear translation in the $z$-direction. If $a \neq b$, the speed is not constant throughout the motion, accelerating and decelerating as it orbits the elliptical cross-section.