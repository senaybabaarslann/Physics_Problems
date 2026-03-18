## 1. Vector Algebra
**Given:** $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$

### a) Magnitude of Vector a
$$|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14}$$

### b) Magnitude of Vector b
$$|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21}$$

### c) Dot Product
$$\vec{a} \cdot \vec{b} = (2 \times 4) + (1 \times -2) + (-3 \times 1) = 8 - 2 - 3 = 3$$

### d) Cross Product
$$
\vec{a} \times \vec{b} = 
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
2 & 1 & -3 \\
4 & -2 & 1
\end{vmatrix}
$$

* **i component:** $(1 \times 1) - (-3 \times -2) = 1 - 6 = -5$
* **j component:** $-((2 \times 1) - (-3 \times 4)) = -(2 + 12) = -14$
* **k component:** $(2 \times -2) - (1 \times 4) = -4 - 4 = -8$

**Result Vector:** $[-5, -14, -8]$

### e) Angle Calculation ($\theta$)
$$\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|} = \frac{3}{\sqrt{14} \cdot \sqrt{21}} \approx 0.175$$
$$\theta = \arccos(0.175) \approx 79.9^\circ$$
