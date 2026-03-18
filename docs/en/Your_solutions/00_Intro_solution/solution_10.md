## 10. Infinite Series (The Ant's Final Position)
**Problem:** An ant moves 1m East, 1/2m North, 1/3m West, 1/4m South, and so on. Find the final $(x, y)$ position.

* **Step 1 (Analyze X-axis):** The ant moves East (+) and West (-). The series is:
  $x = 1 - 1/3 + 1/5 - 1/7 + \dots$
  This is the **Leibniz formula for $\pi$**, so $x = \pi/4 \approx 0.785\text{ m}$.
* **Step 2 (Analyze Y-axis):** The ant moves North (+) and South (-). The series is:
  $y = 1/2 - 1/4 + 1/6 - 1/8 + \dots$
  This is half of the **natural log series** $\ln(2)$, so $y = \frac{1}{2} \ln(2) \approx 0.347\text{ m}$.
* **Final Answer:** The ant's final coordinates are approximately **$(0.785, 0.347)$**.
