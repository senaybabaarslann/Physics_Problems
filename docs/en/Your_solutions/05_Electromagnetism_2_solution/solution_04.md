# Task 04 – Magnetic Torque on a Rectangular Loop

## Problem Statement

A rectangular loop of wire with dimensions $10 \text{ cm}$ by $5 \text{ cm}$ carries a current of $2 \text{ A}$. A uniform magnetic field of $B = 0.3 \text{ T}$ is applied parallel to the plane of the loop. What is the magnitude of the magnetic torque on the loop?

## Theory

The magnetic torque $\boldsymbol{\tau}$ exerted on a current-carrying loop in a uniform magnetic field is given by the cross product of the magnetic dipole moment $\mathbf{m}$ and the magnetic field $\mathbf{B}$:

$$
\boldsymbol{\tau} = \mathbf{m} \times \mathbf{B}
$$

The magnitude of the torque is:

$$
\tau = m B \sin\theta
$$

Where:
* $m = NIA$ is the magnetic moment ($N$ is the number of turns, $I$ is current, $A$ is area).
* $\theta$ is the angle between the normal to the loop's plane and the magnetic field.

If the magnetic field is parallel to the plane of the loop, the angle between the normal vector and the field is $\theta = 90^\circ$.

## Step-by-Step Solution

1. **Calculate the Area of the Loop**:

$$
A = 0.10 \text{ m} \times 0.05 \text{ m} = 0.005 \text{ m}^2
$$

2. **Calculate the Magnetic Moment**:
Assuming $N = 1$:

$$
m = I A = 2 \text{ A} \times 0.005 \text{ m}^2 = 0.01 \text{ A}\cdot\text{m}^2
$$

3. **Determine the Angle**:
Since the field is parallel to the plane, $\theta = 90^\circ$, thus $\sin(90^\circ) = 1$.

4. **Calculate the Torque**:

$$
\tau = m B \sin(90^\circ) = 0.01 \times 0.3 \times 1
$$

$$
\tau = 0.003 \text{ N}\cdot\text{m}
$$

## Final Result

The magnitude of the magnetic torque is:

$$
\tau = 3 \times 10^{-3} \text{ N}\cdot\text{m}
$$

## Interpretation

The torque is at its maximum value when the magnetic field is parallel to the plane of the loop. This torque will tend to rotate the loop until its normal vector is aligned with the magnetic field, at which point the torque becomes zero.