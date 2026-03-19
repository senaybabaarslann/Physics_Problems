## Section 0: Mathematical Foundations

### 1. Vector Algebra
**Problem:** Given two vectors in 3D space: $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$.

---

#### **Step 1: Calculate the Magnitudes**
The magnitude (length) of a vector $\vec{v} = [x, y, z]$ is defined as $|\vec{v}| = \sqrt{x^2 + y^2 + z^2}$.

* **For Vector $\vec{a}$:**
    $$|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14} \approx 3.74$$
* **For Vector $\vec{b}$:**
    $$|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21} \approx 4.58$$

---

#### **Step 2: Calculate the Dot Product ($\vec{a} \cdot \vec{b}$)**
The dot product is the sum of the products of the corresponding components:
$$\vec{a} \cdot \vec{b} = (a_x \times b_x) + (a_y \times b_y) + (a_z \times b_z)$$
$$\vec{a} \cdot \vec{b} = (2 \times 4) + (1 \times -2) + (-3 \times 1)$$
$$\vec{a} \cdot \vec{b} = 8 - 2 - 3 = 3$$

---

#### **Step 3: Calculate the Cross Product ($\vec{a} \times \vec{b}$)**
Using the determinant of a $3 \times 3$ matrix with unit vectors $\mathbf{i, j, k}$:
$$\vec{a} \times \vec{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix}$$

* **$\mathbf{i}$ component:** $(1 \times 1) - (-3 \times -2) = 1 - 6 = -5$
* **$\mathbf{j}$ component:** $-[(2 \times 1) - (-3 \times 4)] = -(2 + 12) = -14$
* **$\mathbf{k}$ component:** $(2 \times -2) - (1 \times 4) = -4 - 4 = -8$

**Result Vector:** $\vec{a} \times \vec{b} = [-5, -14, -8]$

---

#### **Step 4: Find the Angle ($\theta$) Between Vectors**
Using the geometric definition: $\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos(\theta)$
$$\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \times |\vec{b}|} = \frac{3}{\sqrt{14} \times \sqrt{21}} \approx \frac{3}{17.15} \approx 0.175$$
$$\theta = \arccos(0.175) \approx 79.9^\circ$$
