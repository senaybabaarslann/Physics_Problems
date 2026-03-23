# Task 05 – Relative Velocity

## Problem Statement

A river flows east at $2 \text{ m/s}$. A boat that can travel at $5 \text{ m/s}$ in still water wants to go directly north across the river. In what direction (angle) should it head? How long will it take to cross the river if it's 200 meters wide?

## Theory

Let:
* $\vec{v}_{R}$ be the velocity of the river relative to the ground.
* $\vec{v}_{B/R}$ be the velocity of the boat relative to the river.
* $\vec{v}_{B}$ be the velocity of the boat relative to the ground.

The relationship is:

$$
\vec{v}_{B} = \vec{v}_{B/R} + \vec{v}_{R}
$$

For the boat to travel directly north, the eastward component of its velocity relative to the ground must be zero ($v_{Bx} = 0$).

## Step-by-Step Solution

### 1. Determining the Heading Angle

Let $\theta$ be the angle measured west of north.

$$
\begin{align}
\vec{v}_R &= 2 \hat{i} \\
\vec{v}_{B/R} &= -5 \sin \theta \hat{i} + 5 \cos \theta \hat{j}
\end{align}
$$

The resulting velocity is:

$$
\vec{v}_B = (2 - 5 \sin \theta) \hat{i} + (5 \cos \theta) \hat{j}
$$

For $\vec{v}_B$ to be purely in the $\hat{j}$ direction:

$$
2 - 5 \sin \theta = 0
$$

$$
\sin \theta = \frac{2}{5} = 0.4
$$

$$
\theta = \arcsin(0.4) \approx 23.58^\circ \text{ West of North}
$$

### 2. Time to Cross

The northward component of the velocity relative to the ground is:

$$
v_{By} = 5 \cos \theta
$$

Using $\cos \theta = \sqrt{1 - \sin^2 \theta} = \sqrt{1 - 0.16} = \sqrt{0.84} \approx 0.9165$:

$$
v_{By} \approx 5 \cdot 0.9165 \approx 4.5826 \text{ m/s}
$$

The time $t$ to cross width $W = 200 \text{ m}$ is:

$$
t = \frac{W}{v_{By}} = \frac{200}{4.5826} \approx 43.64 \text{ s}
$$

## Final Result

* **Heading Direction:** $23.58^\circ$ west of north.
* **Crossing Time:** $43.64 \text{ s}$.

## Interpretation

To compensate for the river's current pushing it east, the boat must steer "upstream" (west). The resulting speed across the river is lower than the boat's speed in still water because some of its effort is used to counteract the current.