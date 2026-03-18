# Section 0: Mathematical Foundations - Solutions

## 1. Vector Algebra
Given vectors: $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$

**a) Magnitude of each vector:**
* $|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14}$
* $|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21}$

**b) Dot product ($\vec{a} \cdot \vec{b}$):**
* $(2 \cdot 4) + (1 \cdot -2) + (-3 \cdot 1) = 8 - 2 - 3 = 3$

**c) Cross product ($\vec{a} \times \vec{b}$):**
* $[(1 \cdot 1 - (-3) \cdot (-2)), ((-3) \cdot 4 - 2 \cdot 1), (2 \cdot (-2) - 1 \cdot 4)]$
* Result: $[-5, -14, -8]$

**d) Angle between vectors:**
* $\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|} = \frac{3}{\sqrt{14} \cdot \sqrt{21}}$
* $\theta = \arccos\left(\frac{3}{\sqrt{294}}\right) \approx 79.9^\circ$

## 2. Systems of Equations
$2x + 3y = 12$ and $x - y = 1$
* From the second equation: $x = y + 1$
* Substitute into the first: $2(y+1) + 3y = 12 \Rightarrow 5y = 10 \Rightarrow y = 2$
* Then: $x = 2 + 1 = 3$
* **Answer:** $x = 3, y = 2$

## 3. Proportionality
$F = G \frac{m_1 m_2}{r^2}$
* If distance $r$ is doubled ($2r$), the denominator becomes $4r^2$ (Force decreases by factor of 4).
* If both masses are halved, the numerator becomes $1/4$ (Force decreases by factor of 4).
* **Total Change:** The force $F$ changes by a factor of $1/16$.

## 4. Rearranging Formulas
$T = 2\pi\sqrt{\frac{L}{g}}$
1. $T^2 = 4\pi^2 \frac{L}{g}$
2. $g \cdot T^2 = 4\pi^2 L$
3. **Result:** $g = \frac{4\pi^2 L}{T^2}$

## 5. Trigonometry
$A = 15, \theta = 60^\circ$
* **Horizontal component ($A_x$):** $15 \cdot \cos(60^\circ) = 15 \cdot 0.5 = 7.5$
* **Vertical component ($A_y$):** $15 \cdot \sin(60^\circ) = 15 \cdot \frac{\sqrt{3}}{2} \approx 12.99$

## 6. Function Analysis
$f(x) = 3x^2 - 12x + 7$
* First derivative: $f'(x) = 6x - 12$
* Set $f'(x) = 0 \Rightarrow 6x = 12 \Rightarrow x = 2$
* Since $f''(x) = 6 > 0$, there is a **local minimum** at $x = 2$.

## 7. Logic & Series (The Fly Problem)
* Time until collision: $t = \frac{\text{Distance}}{\text{Speed}} = \frac{10\text{ m}}{1\text{ m/s}} = 10\text{ seconds}$.
* The fly travels at a constant speed of 2 m/s for these 10 seconds.
* **Total Distance:** $2\text{ m/s} \cdot 10\text{ s} = 20\text{ meters}$.

## 8. Definite Integrals
$\int_0^\pi \sin(x) dx$
* Antiderivative: $[-\cos(x)]_0^\pi = -\cos(\pi) - (-\cos(0))$
* $-(-1) - (-1) = 1 + 1 = 2$
* **Area:** 2

## 9. Optimization Problem
$y = 3 - x^2$. Area $A = x \cdot y = x(3 - x^2) = 3x - x^3$
* $A' = 3 - 3x^2 = 0 \Rightarrow x = 1$
* Dimensions: $x = 1, y = 2$.

## 10. Infinite Series
* East-West (x): $1 - 1/3 + 1/5 - \dots = \pi/4 \approx 0.785\text{ m}$
* North-South (y): $1/2 - 1/4 + 1/6 - \dots = \frac{1}{2} \ln(2) \approx 0.347\text{ m}$
* **Final Position:** $(0.785, 0.347)$
