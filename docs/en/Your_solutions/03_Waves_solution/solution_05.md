# Task 05 – Echo Ranging

## Problem Statement

A person shouts towards a cliff and hears the echo $1$ second later. How far away is the cliff? (Speed of sound in air is $343 \text{ m/s}$).

## Theory

The sound must travel to the cliff and back to the person. If $d$ is the distance to the cliff, the total distance traveled by the sound is:

$$
D = 2d
$$

Using the constant velocity formula $D = v \cdot t$:

$$
2d = v \cdot t \implies d = \frac{v \cdot t}{2}
$$

## Step-by-Step Solution

Given $v = 343 \text{ m/s}$ and $t = 1 \text{ s}$:

$$
d = \frac{343 \cdot 1}{2}
$$

$$
d = 171.5 \text{ m}
$$

## Final Result

The cliff is $171.5 \text{ meters}$ away.

## Interpretation

Echo ranging is the fundamental principle behind SONAR and LIDAR. The "round trip" time must always be halved to find the distance to the reflecting object.