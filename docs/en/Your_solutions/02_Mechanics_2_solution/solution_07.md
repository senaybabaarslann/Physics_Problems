# Task 07 – Dynamics with Friction

## Problem Statement

A $5 \text{ kg}$ block ($m_1$) is placed on a $10 \text{ kg}$ block ($m_2$). A horizontal force $F = 45 \text{ N}$ is applied to $m_2$, and $m_1$ is tied to the wall. The coefficient of kinetic friction $\mu_k$ between all moving surfaces is $0.2$. Find the acceleration of the $10 \text{ kg}$ block.

## Theory

The block $m_2$ experiences several forces:
1. The applied force $F$.
2. Kinetic friction from the ground ($f_{g}$).
3. Kinetic friction from block $m_1$ on top ($f_{top}$).

The normal forces are:
* $N_{top} = m_1 g$
* $N_{ground} = (m_1 + m_2)g$

Friction forces:
$$
f = \mu_k N
$$

## Step-by-Step Solution

### 1. Calculate Friction Forces

$$
f_{top} = \mu_k m_1 g = 0.2 \cdot 5 \cdot 9.81 = 9.81 \text{ N}
$$

$$
f_{ground} = \mu_k (m_1 + m_2)g = 0.2 \cdot (5 + 10) \cdot 9.81 = 0.2 \cdot 15 \cdot 9.81 = 29.43 \text{ N}
$$

### 2. Apply Newton's Second Law to $m_2$

$$
F_{net} = F - f_{top} - f_{ground} = m_2 a
$$

$$
45 - 9.81 - 29.43 = 10 \cdot a
$$

$$
45 - 39.24 = 10a
$$

$$
5.76 = 10a \implies a = 0.576 \text{ m/s}^2
$$

## Final Result

The acceleration of the $10 \text{ kg}$ block is $0.576 \text{ m/s}^2$.

## Interpretation

Even though $m_1$ is not moving, it exerts a "drag" on $m_2$ through the interface friction. The majority of the applied force ($39.24 \text{ N}$ out of $45 \text{ N}$) is consumed by overcoming friction, leaving only a small fraction for acceleration.