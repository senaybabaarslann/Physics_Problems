# Task 03 – Path Intersection

## Problem Statement

Alice is moving along a path described by $A(t) = (2+t, 8-3t)$ and Bob is moving along a path $B(t) = (2t-1, 2t+2)$. Determine if their paths intersect. If yes, determine when and where they will collide. If not, determine the minimum distance between them and when it occurs.

## Theory

A **collision** occurs if $A(t) = B(t)$ for the same time $t$. An **intersection** of paths occurs if $A(t_1) = B(t_2)$ for possibly different times $t_1$ and $t_2$.

The distance $D(t)$ between two objects at time $t$ is:

$$
D(t) = \sqrt{(x_A - x_B)^2 + (y_A - y_B)^2}
$$

## Step-by-Step Solution

### 1. Checking for Collision

Set $x_A(t) = x_B(t)$ and $y_A(t) = y_B(t)$:

$$
\begin{align}
2 + t &= 2t - 1 \\
8 - 3t &= 2t + 2
\end{align}
$$

From the first equation:
$t = 3$.

Check this value in the second equation:
$8 - 3(3) = 8 - 9 = -1$.
$2(3) + 2 = 8$.

Since $-1 \neq 8$, they do not collide at $t=3$.

### 2. Checking for Path Intersection

Set $A(t_1) = B(t_2)$:

$$
\begin{align}
2 + t_1 &= 2t_2 - 1 \implies t_1 = 2t_2 - 3 \\
8 - 3t_1 &= 2t_2 + 2
\end{align}
$$

Substitute $t_1$ into the second equation:

$$
8 - 3(2t_2 - 3) = 2t_2 + 2
$$

$$
8 - 6t_2 + 9 = 2t_2 + 2
$$

$$
17 - 6t_2 = 2t_2 + 2 \implies 8t_2 = 15 \implies t_2 = 1.875
$$

Then $t_1 = 2(1.875) - 3 = 3.75 - 3 = 0.75$.

The paths intersect at $t_1=0.75$ and $t_2=1.875$. The coordinates are:
$x = 2 + 0.75 = 2.75$.
$y = 8 - 3(0.75) = 8 - 2.25 = 5.75$.

### 3. Minimum Distance

Define the displacement vector $\vec{r}_{AB}(t) = A(t) - B(t)$:

$$
\vec{r}_{AB}(t) = ((2+t) - (2t-1), (8-3t) - (2t+2)) = (3-t, 6-5t)
$$

The squared distance $f(t) = D^2(t)$ is:

$$
f(t) = (3-t)^2 + (6-5t)^2
$$

$$
f(t) = 9 - 6t + t^2 + 36 - 60t + 25t^2 = 26t^2 - 66t + 45
$$

To find the minimum, set $f'(t) = 0$:

$$
f'(t) = 52t - 66 = 0 \implies t = \frac{66}{52} \approx 1.269 \text{ s}
$$

Minimum distance:

$$
D_{min} = \sqrt{26(1.269)^2 - 66(1.269) + 45} \approx \sqrt{41.86 - 83.75 + 45} \approx \sqrt{3.11} \approx 1.76 \text{ units}
$$

## Final Result

* **Collision:** No.
* **Path Intersection:** Yes, at $(2.75, 5.75)$.
* **Minimum Distance:** $D \approx 1.76$ at $t \approx 1.27 \text{ s}$.

## Interpretation

Although the geometric paths cross in space, the objects occupy the intersection point at different times, thus avoiding a collision. The minimum distance analysis shows that they are closest shortly after $t=1$.