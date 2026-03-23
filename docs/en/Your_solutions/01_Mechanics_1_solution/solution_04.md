# Task 04 – Vector Calculus

## Problem Statement

The position of an object is given by $\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$. Find the object's velocity and acceleration vectors as a function of time.

## Theory

The velocity vector $\vec{v}(t)$ is the first derivative of the position vector with respect to time:

$$
\vec{v}(t) = \frac{d\vec{r}}{dt}
$$

The acceleration vector $\vec{a}(t)$ is the first derivative of the velocity vector (or second derivative of position):

$$
\vec{a}(t) = \frac{d\vec{v}}{dt} = \frac{d^2\vec{r}}{dt^2}
$$

## Step-by-Step Solution

### 1. Velocity Vector

Given:

$$
\vec{r}(t) = 
\begin{pmatrix}
3t^2 \\
5t - 8t^2
\end{pmatrix}
$$

Differentiating each component with respect to $t$:

$$
v_x(t) = \frac{d}{dt}(3t^2) = 6t
$$

$$
v_y(t) = \frac{d}{dt}(5t - 8t^2) = 5 - 16t
$$

Therefore:

$$
\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

### 2. Acceleration Vector

Differentiating the velocity components:

$$
a_x(t) = \frac{d}{dt}(6t) = 6
$$

$$
a_y(t) = \frac{d}{dt}(5 - 16t) = -16
$$

Therefore:

$$
\vec{a}(t) = 6\hat{i} - 16\hat{j}
$$

## Final Result

* **Velocity:** $\vec{v}(t) = 6t \hat{i} + (5 - 16t) \hat{j}$
* **Acceleration:** $\vec{a}(t) = 6 \hat{i} - 16 \hat{j}$

## Interpretation

The acceleration is constant in both magnitude and direction, which implies that the object is undergoing motion with constant acceleration. The trajectory is a parabola.