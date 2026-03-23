# Task 02 – Range Optimization

## Problem Statement

For projectile motion, show analytically that the maximum range $R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$ for a given initial velocity is achieved at a launch angle of $45^\circ$.

## Theory

The range of a projectile launched from ground level is given by the formula:

$$
R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}
$$

To find the extreme values (maximum or minimum) of a function $f(\theta)$, we find the derivative with respect to $\theta$ and set it to zero:

$$
\frac{dR}{d\theta} = 0
$$

## Step-by-Step Solution

We differentiate $R(\theta)$ with respect to $\theta$:

$$
\frac{dR}{d\theta} = \frac{d}{d\theta} \left( \frac{v_0^2 \sin(2\theta)}{g} \right)
$$

Since $v_0$ and $g$ are constants:

$$
\frac{dR}{d\theta} = \frac{v_0^2}{g} \frac{d}{d\theta} (\sin(2\theta))
$$

Using the chain rule:

$$
\frac{dR}{d\theta} = \frac{v_0^2}{g} (2 \cos(2\theta))
$$

Setting the derivative to zero:

$$
\frac{2 v_0^2}{g} \cos(2\theta) = 0
$$

Assuming $v_0 \neq 0$:

$$
\cos(2\theta) = 0
$$

The first positive solution for $2\theta$ is:

$$
2\theta = 90^\circ
$$

$$
\theta = 45^\circ
$$

To confirm it is a maximum, we check the second derivative:

$$
\frac{d^2R}{d\theta^2} = -\frac{4 v_0^2}{g} \sin(2\theta)
$$

At $\theta = 45^\circ$:

$$
\frac{d^2R}{d\theta^2} = -\frac{4 v_0^2}{g} \sin(90^\circ) = -\frac{4 v_0^2}{g}
$$

Since the second derivative is negative, the point $\theta = 45^\circ$ is a maximum.

## Final Result

The maximum range is achieved at $\theta = 45^\circ$.

## Interpretation

The range depends on the product of the horizontal velocity ($v_0 \cos \theta$) and the time of flight (proportional to $v_0 \sin \theta$). The angle $45^\circ$ represents the optimal balance between these two components, as $\sin(2\theta)$ reaches its peak value of $1$ at $2\theta = 90^\circ$.