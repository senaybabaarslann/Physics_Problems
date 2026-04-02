# Task 08 – Wave Equation Verification

## Problem Statement

Which of the following functions can describe a traveling wave? (Check if they satisfy the wave equation: $\frac{\partial^2y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2y}{\partial t^2}$)

a) $y(x,t) = A \cos(kx^2 - \omega t)$
b) $y(x,t) = A(x - vt)^2$
c) $y(x,t) = A \ln(x + vt)$

## Theory

Any function of the form $f(x \pm vt)$ is a solution to the wave equation.
If the variable depends on $(x \pm vt)$, the second derivatives will be related by a factor of $v^2$.

## Step-by-Step Solution

### Case (a)

$y = A \cos(kx^2 - \omega t)$. The argument is not a linear combination of $x$ and $t$ (due to $x^2$).

$$
\frac{\partial y}{\partial x} = -2Akx \sin(kx^2 - \omega t)
$$

The second derivative will include terms with $x^2$. This does **not** satisfy the wave equation.

### Case (b)

$y = A(x - vt)^2$. This is of the form $f(u)$ where $u = x - vt$.

$$
\frac{\partial^2 y}{\partial x^2} = 2A
$$

$$
\frac{\partial^2 y}{\partial t^2} = 2Av^2
$$

Substitute into the wave equation:

$$
2A = \frac{1}{v^2} (2Av^2) = 2A
$$

This **satisfies** the wave equation.

### Case (c)

$y = A \ln(x + vt)$. This is of the form $f(x + vt)$.

$$
\frac{\partial^2 y}{\partial x^2} = -\frac{A}{(x + vt)^2}
$$

$$
\frac{\partial^2 y}{\partial t^2} = -\frac{Av^2}{(x + vt)^2}
$$

This **satisfies** the wave equation.

## Final Result

Functions **(b)** and **(c)** can describe traveling waves. Function **(a)** cannot.

## Interpretation

For a wave to maintain its shape as it travels, the space and time components must be linearly linked. The $x^2$ term in (a) causes the shape to change as it moves, which is why it is not a valid traveling wave.