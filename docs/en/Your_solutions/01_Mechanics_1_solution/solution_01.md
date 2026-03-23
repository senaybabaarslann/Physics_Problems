# Task 01 – Projectile Motion

## Problem Statement

A projectile is fired from the ground with an initial velocity of $v_0 = 100 \text{ m/s}$ at an angle of $\theta = 37^\circ$ above the horizontal. Assume no air resistance.

* Derive the differential equations of motion in the horizontal and vertical directions.
* Determine the time of flight.
* Determine the maximum height.
* Determine the range.

## Theory

Projectile motion is a form of two-dimensional motion under the sole influence of gravity. Neglecting air resistance, the acceleration is constant and directed downward.

According to Newton's Second Law:

$$
\vec{F} = m \vec{a}
$$

Since the only force is weight $\vec{W} = -mg \hat{j}$, the acceleration components are:

$$
\begin{align}
a_x &= 0 \\
a_y &= -g
\end{align}
$$

## Step-by-Step Solution

### 1. Differential Equations of Motion

The acceleration is the second derivative of position with respect to time. For the horizontal direction ($x$):

$$
\frac{d^2x}{dt^2} = 0
$$

Integrating once with initial condition $v_x(0) = v_0 \cos \theta$:

$$
v_x(t) = v_0 \cos \theta
$$

Integrating again with $x(0) = 0$:

$$
x(t) = v_0 t \cos \theta
$$

For the vertical direction ($y$):

$$
\frac{d^2y}{dt^2} = -g
$$

Integrating once with initial condition $v_y(0) = v_0 \sin \theta$:

$$
v_y(t) = v_0 \sin \theta - gt
$$

Integrating again with $y(0) = 0$:

$$
y(t) = (v_0 \sin \theta)t - \frac{1}{2}gt^2
$$

### 2. Time of Flight

The projectile hits the ground when $y(t) = 0$ (excluding $t=0$):

$$
(v_0 \sin \theta)t - \frac{1}{2}gt^2 = 0
$$

$$
t \left( v_0 \sin \theta - \frac{1}{2}gt \right) = 0
$$

The time of flight $t_f$ is:

$$
t_f = \frac{2 v_0 \sin \theta}{g}
$$

Using $v_0 = 100 \text{ m/s}$, $\theta = 37^\circ$, and $g \approx 9.81 \text{ m/s}^2$:

$$
t_f = \frac{2 \cdot 100 \cdot \sin(37^\circ)}{9.81} \approx \frac{200 \cdot 0.6018}{9.81} \approx 12.27 \text{ s}
$$

### 3. Maximum Height

Maximum height $H$ occurs when $v_y(t) = 0$:

$$
v_0 \sin \theta - gt_h = 0 \implies t_h = \frac{v_0 \sin \theta}{g}
$$

Substituting $t_h$ into $y(t)$:

$$
H = v_0 \sin \theta \left( \frac{v_0 \sin \theta}{g} \right) - \frac{1}{2}g \left( \frac{v_0 \sin \theta}{g} \right)^2
$$

$$
H = \frac{v_0^2 \sin^2 \theta}{2g}
$$

Calculation:

$$
H = \frac{100^2 \cdot \sin^2(37^\circ)}{2 \cdot 9.81} \approx \frac{10000 \cdot 0.3622}{19.62} \approx 184.61 \text{ m}
$$

### 4. Range

The range $R$ is the horizontal distance at $t = t_f$:

$$
R = x(t_f) = (v_0 \cos \theta) \left( \frac{2 v_0 \sin \theta}{g} \right)
$$

Using the identity $2 \sin \theta \cos \theta = \sin(2\theta)$:

$$
R = \frac{v_0^2 \sin(2\theta)}{g}
$$

Calculation:

$$
R = \frac{100^2 \cdot \sin(74^\circ)}{9.81} \approx \frac{10000 \cdot 0.9613}{9.81} \approx 979.92 \text{ m}
$$

## Final Result

* **Equations of Motion:** $x(t) = v_0 t \cos \theta$, $y(t) = v_0 t \sin \theta - \frac{1}{2}gt^2$
* **Time of Flight:** $t_f \approx 12.27 \text{ s}$
* **Maximum Height:** $H \approx 184.61 \text{ m}$
* **Range:** $R \approx 979.92 \text{ m}$

## Interpretation

The decoupling of horizontal and vertical motions allows for independent analysis. The horizontal velocity remains constant due to the absence of horizontal forces, while the vertical motion is a simple case of constant acceleration. The maximum height depends only on the vertical component of the initial velocity, whereas the range depends on both components.