## 6. Variable Velocity
**Problem:** Find position and acceleration at $t=3$ for $v(t) = t^2 + 2t - 5$ with $x(0)=4$.

* **Step 1: Integration for Position**
  $x(t) = \int (t^2 + 2t - 5) dt = \frac{t^3}{3} + t^2 - 5t + C$
* **Step 2: Solving for Constant C**
  Given $x(0) = 4$, then $0 + 0 - 0 + C = 4 \Rightarrow C = 4$.
  $x(t) = \frac{t^3}{3} + t^2 - 5t + 4$
* **Step 3: Position at $t=3$**
  $x(3) = \frac{3^3}{3} + 3^2 - 5(3) + 4 = 9 + 9 - 15 + 4 = 7$
* **Step 4: Acceleration at $t=3$**
  $a(t) = \frac{dv}{dt} = 2t + 2$
  $a(3) = 2(3) + 2 = 8 \text{ m/s}^2$
